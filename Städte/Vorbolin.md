---
title: Vorbolin
NoteIcon: 
tags:
Alignment: neutral
type: Handels- und Zollvorposten von Salbolin
politics: Vorranging von der Handelsgilde geführt
region: [[Exigonia]]
size: mid-large
leader: "[[Baptiste Colbert]]"
guildsgroups: ["[[Handelsgilde]]"]
population: 5000
commonraces: human
religion: [[]]
exportLinks: ["[[-]]"]
importLinks: ["[[Gewürze]]","[[Kunst]]","[[Rohstoffe]]"]
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
Zollstadt von [[Exegonia]]

Jede Ware die nach [[Salbolin]] eingeführt werden soll, muss zunächst [[Exegonia]] passieren und durch den Zoll verzollt und geprüft werden.

Verschiedene Handelshäuser haben das Zollprivileg erworben und dürfen die Verzollung durchführen. Dabei geht ein kleiner Teil der eingenommenen Beträge in die Kassen des Handelshauses und der Rest in die Staatskasse.

Möchte man Vorbolin in Richtung Salbolin passieren, muss man sich zunächst am Nordtor ein Zollhaus zuweisen lassen. Angehörige eines Handelshauses dürfen dabei nicht in eines der eigenen Zollhäuser geschickt werden. Unter der Hand bevorteilen sich die großen Häuser aber dennoch gegenseitig.

Nach der Verzollung erhält man einen Zollschein und darf dann mit seinen Waren das Südtor in Richtung Salbolin passieren.

Es wird nach selbst geschätztem Preis der mitgeführten Waren sortiert.

Bei Einbruch der Dunkelheit werden die Tore geschlossen.
Es gab eine kleine Vorstadt außerhalb der Mauern, um Händlern auch nach Torschluss Schutz gewähren zu können. Diese ist aber vor einiger Zeit aus bisher unbekannten Gründen abgebrant.

Seitdem ist jeder für seinen eigenen Schutz verantwortlich und es hat sich eine kleine Wirtschaft um das Angebot temporärer Siegelkreise und selbstgebauter Schutzhäuser entwickelt. (teils zwielichtig und nicht von der [[Siegelgilde]] bewilligt)
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

### Ankunft
Beim Eintreffen an der Stadt, sieht die Gruppe die Überreste der alten Außenstadt.

Zusätzlich sieht sie die verbrannten Überreste einer Karavane die scheinbar in der Nacht zuvor durch Dämonen getötet wurde. Um sie herum liegen ein paar Pfeile im Boden.

Vor dem Stadttor ist auf der Straße auch noch frisch getrocknetes Blut zu erkennen.


### Aufenthalt
Bevor die Gruppe in die Stadt gelassen wird, müssen sie sich vorstellen / ausweisen

durch die Anwesenheit von Trador werden sie an das Zollhause der Familie [[Haus Silberquell]] weitergeleitet. Als mächtiges Handelshaus haben liegt ihr Zollhaus im Herzen der Stadt. Dort werden sie professionell abgefertigt.

Nachdem sie verzollt wurden, erhalten sie ihren Zollbrief und können ihre Reise fortsetzen.

Auf dem Weg aus der Stadt werden sie von den Dächern beschossen. Der Attentäter hat auf den Dächern gelauert und tritt den Rückzug an, nachdem sein Attentat fehlgeschlagen ist.

**Sollte die Gruppe ihm folgen**:
* Verfolgung über die Dächer bis zu einem verlassenen Haus 
* Dort Überfall
* Weiterer Überfall auf die Kutsche

**Sollte die Gruppe nicht folgen**:
* Werden nach kurzer Zeit von Stadtwache (verkleidete Attentäter) angehalten
* Weisen die Gruppe an ihnen zu folgen --> Sackgasse --> Überfall mit Fokus auf Trador


### Abfahrt/Reise



## Points of Interest
[[Orte/Vorbolin/Außenstadt]]

[[Orte/Vorbolin/Zollallee]]

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


