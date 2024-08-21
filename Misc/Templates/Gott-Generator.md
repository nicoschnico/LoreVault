<%*
let price, usage, unit, title, amountDom

// Prompt for each property
title = await tp.system.prompt("Titel");
name = await tp.system.prompt("Name");
amountDom = await tp.system.prompt("Wie viele Domains / Avatare)? ");
domains = await tp.system.prompt("Domänen:");
avatars = await tp.system.prompt("Avatare");

// Move the file to the new location with the NPC's name
await tp.file.move("/Götter/" + title);

// Write the frontmatter properties
tR += `---
name : ${name}
domains: [${domains}]
avatars: [${avatars}]
---
`;

// Start building the infobox
let output = "> [!infobox]\n";
output += `> # ${name} - ${tp.file.title}\n`;

// Add each domain and its corresponding avatar
for (let i = 0; i < amountDom; i++) {
    output += `> **\`= this.domains[${i}]\`**\n`;
    output += `> _Avatar_ : \`= this.avatars[${i}]\`\n`;
}

// Output the generated content
tR += output;

_%>