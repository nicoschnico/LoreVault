---
NoteIcon: 
tags:
Alignment: 
type: 
politics: 
region: [[]]
size: 
leader: [[]]
guildsgroups: ["[[]]"]
population: 
commonraces: 
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


# `=this.title`
## Overview
Placeholder
## Notable NPCs
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


