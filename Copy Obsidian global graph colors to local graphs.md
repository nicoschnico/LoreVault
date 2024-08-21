[[Obsidian]] local graphs don't inherit global graph settings as of [[2021-06-28]], which can make for an inconsistent experience. Relevant feature request: [Colour group settings apply to both global and local graphs Obsidian Forum](https://forum.obsidian.md/t/colour-group-settings-apply-to-both-global-and-local-graphs/12709)

[[JSON]] local graph config is stored in `.obsidian/workspace`, and global graph config is stored in `.obsidian/graph.json`, so we can sync settings by editing the configuration directly.

First, open a local graph view and close Obsidian (it seems like Obsidian prefers its own configuration to whatever is on disk when it is running). Then, either [[#Sync all graph settings]] or [[#Sync specific graph settings]]. Once done, open Obsidian and your local graph should look the same as your global graph!

### Sync all graph settings

We rewrite configuration using [[Comby]].

```bash
# First, save our graph settings
GRAPHOPTIONS="$(cat .obsidian/graph.json)"

# Generate and review new configuration for our workspace 
comby -review -l .json '"type": "localgraph", "state": { :[state] "options": :[options] } ' "\"type\": \"localgraph\", \"state\": { :[state] \"options\": $GRAPHOPTIONS }" .obsidian/workspace 
```

###  Sync specific graph settings 

This uses [[jq]] for selecting JSON elements. Unfortunately it turns out that [[jq]] is awful for in-place editing, so we do the actual fenangling with [[Comby]] instead.

Example that syncs the `colorGroups` setting - to change other settings, explore `.obsidian/graph.json` to see what you want and replace `colorGroups` below with your desired setting.

```bash
# First, save our color settings
COLORGROUPS="$(jq .colorGroups .obsidian/graph.json)"

# Generate and review new configuration for our workspace
comby -review -l .json '"colorGroups": [:[groups]]' "\"colorGroups\": $COLORGROUPS" .obsidian/workspace
```
