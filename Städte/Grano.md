---
NoteIcon: 
tags: 
Alignment: good
Government: Provinzhauptstadt
type: Stadt
politics: Wohnsitz von Voigt Bolum
leader: "[[NPCs/Siglaz Bolum II]]"
guildsgroups:
  - "[[Gilden/Schmiedegilde]]"
  - "[[Siegelgilde]]"
  - "[[Gilden/Steinmetzgilde]]"
  - "[[Gilden/Handelsgilde]]"
  - "[[Söldnergilde]]"
region: "[[Bolumia]]"
size: large
population: large
commonraces: Mensch, Zwerg
religion: "[[]]"
exportLinks:
  - "[[Salz]]"
  - "[[Eisen]]"
  - "[[Stahl]]"
  - "[[Silber]]"
  - "[[Gold]]"
  - "[[Kupfer]]"
  - "[[Minerale]]"
importLinks:
  - "[[Holz]]"
  - "[[Nahrung]]"
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
> Exports | `=this.exportLinks` |
> Imports | `=this.importLinks` |


# `=this.title`
## Overview
* Häuser mit 2-3 Etagen. EG i.d.R aus Stein, Rest ist Fachwerk
* Palastbezirk ist von Stadtmauer umgeben 
	--> Eintritt nur für Adlige, wichtige Leute aus dem Volk


## Notable NPCs
[[NPCs/Felix von Ferrum]] (Lokaler Anführer der Schmiedegilde) (Wappen ist Ambos mit Flammen dahinter)
[[NPCs/Salem Salerim]] (Lokaler Anführer der [[Handelsgilde]])
[[NPCs/Marim Malbor]] (Bruder vom König) (Siegelgilde:Goldsiegel)
[[Glimmer Sonnenstrahl]]
[[Siglaz Bolum II]]
### Adelsgeschlechter
* Sonnenstrahl
* Malbor 
* Salerim
* Bolum
* Ferrum
* Blaag (Erudio (Doktorant/Historiker))

## Profile


## Story
Placeholder

## Points of Interest
Marktplatz
Bibliothek
Palast
Lagerhäuser

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

## Quests
```dataview
table regexreplace(file.folder, "^Quests/", "") as "Status"
from "Quests" 
where location = this.file.name 
sort regexreplace(file.folder, "^Quests/", "") asc, file.name asc
```
