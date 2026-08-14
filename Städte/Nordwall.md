---
NoteIcon: 
tags:
Alignment: neutral
type: Militärischer Außenposten
politics: Wird von General geführt
region: [[Exigonia]]
size: medium
leader: "[[NPCs/Nordwall/Dagult Immerglut]]"
guildsgroups: ["[[Heer]]","[[Handelsgilde]]","[[Schmiedegilde]]"]
population: 2000
commonraces: Human
religion: [[Tempus]]
exportLinks: ["[[-]]"]
importLinks: ["[[Materialien]]","[[Rohstoffe]]","[[Nahrung]]"]
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


# `=this.title`
## Overview
Stadt die sich aus einer Militärgarnision entwickelt hat
zu jeder Zeit sind mindestens 1000 Soldaten stationiert.

Sie dienen als Reserve für die Verteidigung von Salbolin und Beschützen den Zugang aus Norden in die Kronregion Exigonia.

Außerdem dient die Stadt als Ausbildungstelle neuer Soldaten.

Um die Stadt herum wurden verschiedene Traningszonen errichtet.

Die Stadt ist vollkommen auf Importe angewiesen.

Es wohnen zusätzlich ca 1000 Zivilisten, die sich um die Belange der Soldaten kümmern und einen Großteil der Logistik durchführen.

## Notable NPCs
[[Lesley Handwald]]

```dataview
table regexreplace(file.folder, "^NPCs/", "") as "Status"
from "NPCs" 
where location = this.file.name
sort regexreplace(file.folder, "^NPCs/", "") asc, file.name asc
```

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

## Quests
```dataview
table regexreplace(file.folder, "^Quests/", "") as "Status"
from "Quests" 
where location = this.file.name 
sort regexreplace(file.folder, "^Quests/", "") asc, file.name asc
```


