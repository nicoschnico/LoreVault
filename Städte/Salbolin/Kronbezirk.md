---
NoteIcon: 
tags: v 
Alignment: neutral good
type: Bezirk
politics: Wohnort von König Malbor
region: [[]]
size: 
leader: [[ Marlon Malbor]]
guildsgroups: ["[[]]"]
population: 1000
commonraces: Human
religion: [[]]
exportLinks: ["[[]]"]
importLinks: ["[[]]"]
---
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


## Regierungshügel
Unterteilt sich in Regierungshügel und Adelsviertel
Hof & Verwaltung: Palast, Kanzlei, Audienzhalle, „Straße der Bittsteller“

- natürlicher Hügel
    
- terrassiert bebaut
    
- sichtbar von fast überall
    

**Aufteilung**

- oben: Palast & höchste Verwaltung
    
- mittig: Kanzlei, Archive, Gerichte
    
- unten: Kasernen, Kontrollpunkte
    

**Siegelzustand**

- dichtestes Netz der Stadt
    
- mehrfach überlagert
    
- praktisch undurchdringlich

## Adelsviertel

- breite Straßen
    
- gepflegte Fassaden
    
- private Zusatzsiegel
    
- Nachtwachen auf eigene Kosten
    

**Spielgefühl**  
👉 Sicherheit, Kontrolle, Arroganz  
👉 Dämonen sind hier _theoretisch_ – bis sie es nicht mehr sind.



## Points of Interest

![[Die Morgenglocke#Die Morgenglocke]]


![[Die Abendglocke#Die AbendGlocke]]


![[Palast#Palast]]


![[Adligenhäuser#Adligenhäuser]]


![[Königliche Bibliothek#Königliche Bibliothek]]


![[Das Kronjuwel#Das Kronjuwel]]


Magische Konfluenz --> Magischer Laden geführt von Magier 
Benedikt Hochzinn (Halbling, Langer Bart)

## Notable NPCs
```dataview
table regexreplace(file.folder, "^NPCs/", "") as "Status"
from "NPCs" 
where location = this.file.name
sort regexreplace(file.folder, "^NPCs/", "") asc, file.name asc
```



