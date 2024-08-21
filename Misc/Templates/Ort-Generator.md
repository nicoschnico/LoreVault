<%*
let type, associatedGroup, treasures, shortDescription

// Prompt for each property
title = await tp.system.prompt("Name des Orts");
type = await tp.system.prompt("Typ des Orts");
associatedGroup = await tp.system.prompt("Kontrolliert von:");
shortDescription = await tp.system.prompt("Kurze Beschreibung");
treasures = await tp.system.prompt("Schätze/Ressourcen:");

// Move the file to the new location with the NPC's name
await tp.file.move("/Orte/" + title);

// Write the frontmatter properties
tR += `---
type : ${type}
associatedGroup: ${associatedGroup}
shortDescription: ${shortDescription}
treasures: ${treasures}
NoteIcon:
---
`;
_%>
> [!infobox]
> # `=this.file.name`
> ###### Basic Information
> Typ:  `=this.type` 
> Gruppe: `=this.associatedGroup` 
> Schätze: `=this.treasures` 
> ##### Kurzbeschreibung
> `=this.shortDescription`

# Beschreibung
<% tp.file.cursor() %>