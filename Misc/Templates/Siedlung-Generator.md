<%*
let title = await tp.system.prompt("Name der Siedlung");
await tp.file.move("/Städte/" + title)

let communitySize = await tp.system.prompt("Enter Community Size") ?? "-";
let alignment = await tp.system.prompt("Enter Alignment") ?? "-";
let type = await tp.system.prompt("Enter Type") ?? "-";
let politics = await tp.system.prompt("Enter Politics Description") ?? "-";
let leader = await tp.system.prompt("Enter Leader Name") ?? "-";
let guildsgroups = await tp.system.prompt("Enter Guilds/Groups") ?? ["-"];
let guildItems = []

guildsgroups = guildsgroups.split(",").map(item => item.trim());
guildsgroups.forEach(item => {
	guildItems.push(`"[[${item}]]"`); 
});

let region = await tp.system.prompt("Enter Region") ?? "-";
let size = await tp.system.prompt("Enter Size") ?? "-";
let population = await tp.system.prompt("Enter Population") ?? "-";
let commonraces = await tp.system.prompt("Enter Common Races (comma-separated)") ?? "-";
let religion = await tp.system.prompt("Enter Religion") ?? "-";


let exports = await tp.system.prompt("Enter Exports");
exports = exports.split(",").map(item => item.trim());
let exportItems = []
exports.forEach(item => {
	exportItems.push(`"[[${item}]]"`); 
});

let imports = await tp.system.prompt("Enter Imports");
imports = imports.split(",").map(item => item.trim());
let importItems = [];
imports.forEach(item => {
	importItems.push(`"[[${item}]]"`); 
});


tR += `---
NoteIcon: 
tags:
Alignment: ${alignment}
type: ${type}
politics: ${politics}
region: [[${region}]]
size: ${size}
leader: [[${leader}]]
guildsgroups: [${guildItems}]
population: ${population}
commonraces: ${commonraces}
religion: [[${religion}]]
exportLinks: [${exportItems}]
importLinks: [${importItems}]
---
`;
_%>

> [!infobox]
> # `=this.file.name`
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Politics
> Type |  Stat |
> ---|---|
> Regierung | `=this.government` |
> Govt Type | `=this.politics` |
> Ruler | `=this.leader` |
> Defense | `=this.defences` |
> ###### Organizations
> Type |  Stat |
> ---|---|
> Guilds & Groups | `=this.guildsgroups` |
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `=this.population` |
> Races | `=this.commonraces` |
> Temples | `=this.religion`  |
> ###### Commerce
> Type |  Stat |
> ---|---|
> Exports | `=this.exports` |
> Imports | `=this.imports` |


# `=this.title`
## Overview
Placeholder
## Notable NPCs
Placeholder

## Profile
Placeholder

## Story
Placeholder

## Points of Interest
Placeholder

## Valuables
Placeholder

## Internal Relationships
Placeholder

## Outward Relationships
Placeholder

## Background
Placeholder

## Additional Details
Placeholder




