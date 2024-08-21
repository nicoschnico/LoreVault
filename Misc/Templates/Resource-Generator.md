<%*
let price, usage, unit, title

// Prompt for each property
title = await tp.system.prompt("Name");
price = await tp.system.prompt("Preis pro Einheit:");
unit = await tp.system.prompt("Einheit:");
usage = await tp.system.prompt("Verwendungszweck:");

// Move the file to the new location with the NPC's name
await tp.file.move("/Resourcen/" + title);

// Write the frontmatter properties
tR += `---
price : ${price}
usage: ${usage}
unit: ${unit}
---
`;
_%>
> [!infobox]
> # `=this.file.name`
> ###### Basic Information
> Preis:  `=this.price` 
> Einheit: `=this.unit` 
> Verwendung: `=this.usage` 