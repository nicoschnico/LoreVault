---
title : <%await tp.system.prompt("Name der Quest", tp.file.title)%>
state : <%await tp.system.prompt("Status", tp.file.folder(false)) ?? "inactive"%>
types : [persönlich, fraktion, gruppe, siedlung]
location:  <%await tp.system.prompt("Location der Quest (Stadt, Person, Ort)") ?? ""%>
x : <%tp.frontmatter["state"]%>
--- 

<%*
await tp.file.move("/Quests/" + tp.frontmatter["state"] + "/" + tp.file.title);
%>



### Questgeber:

### Zustand
#inaktiv 
### Art
#dorf
### Beschreibung

### Mögliche Belohnung
