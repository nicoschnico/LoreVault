<%*
let title, associatedGroup, gender, race, age, charClass, alignment, charRole, location, condition;

// Prompt for each property
title = await tp.system.prompt("Enter NPC Name");
associatedGroup = await tp.system.prompt("Enter Associated Group");
gender = await tp.system.prompt("Enter Gender");
race = await tp.system.prompt("Enter Race");
age = await tp.system.prompt("Enter Age");
charClass = await tp.system.prompt("Enter Class");
alignment = await tp.system.prompt("Enter Alignment");
charRole = await tp.system.prompt("Enter Character Role");
location = await tp.system.prompt("Enter Location");
condition = await tp.system.prompt("Enter Condition");

// Move the file to the new location with the NPC's name
await tp.file.move("/NPCs/" + title);

// Write the frontmatter properties
tR += `---
Gender: "#${gender}"
associatedGroup: ${associatedGroup}
associatedGroup_tag: "[[Fraktionen/${associatedGroup}]]"
Race: "#${race}"
Age: ${age}
Class: ${charClass}
Alignment: "#${alignment}"
Character-Role: ${charRole}
location: ${location}
location_tag: "[[${location}]]"

NoteIcon:
Condition: ${condition}
---
`;
_%>



> [!infobox]
> # `=this.file.name`
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Home | `=this.location_tag` |
> Group | `=this.associatedGroup_tag` |
> Sex | `=this.gender` |
> Race | `=this.race` |
> Age | `=this.age` |
> Condition | Healthy |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Alignment | `=this.alignment` |
> Class | `=this.class` |
> Character Role | `=this.character-role` |

## Infos

<% tp.file.cursor() %>

## Aufträge
