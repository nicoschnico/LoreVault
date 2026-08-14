<%*
let name = await tp.system.prompt("Name der Gilde", tp.file.title);
let home = await tp.system.prompt("Hauptsitz");
let leader = await tp.system.prompt("Anführer:");
let services = await tp.system.prompt("Dienste:");
let shortDescription = await tp.system.prompt("Kurze Beschreibung");

// Move the file to the new location with the NPC's name
await tp.file.move("/Gilden/" + name);

// Write the frontmatter properties
tR += `---
name : ${name}
home: "[[${home}]]"
services: "${services}"
leader: "[[${leader}]]"
shortDescription: ${shortDescription}
NoteIcon:
---
`;
_%>
> [!infobox]
> # `=this.file.name`
> Hauptsitz:  `=this.home` 
> Dienste: `=this.services` 
> Anführer: `=this.leader`
> Kurzbeschreibung: `=this.shortDescription` 

# Beschreibung
# Wichtige Personen
# Notizen
