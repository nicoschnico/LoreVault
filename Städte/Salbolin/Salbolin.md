---
NoteIcon: 🏰
tags: [Ort, Stadt, Hauptstadt, Malboria, Salbolin]
title: Salbolin
Alignment: neutral
type: Hauptstadt
politics: Hauptstadt von Malboria
government: Monarchie (königlicher Hof mit Kanzlei & Stadtrat der Zünfte)
region: [[Exigonia County]]
size: large
leader: ["[[Marlon Malbor IV]]"]
defences: Stadtmauer (Altwall), Königsgarde, Hafenwacht, Siegelamt-Wächter, Alarmglocken & Signalfeuer
guildsgroups: ["[[Siegelgilde]]","[[Schmiedegilde]]","[[Handelsgilde]]","[[Religionsgilde]]","[[Schiffahrtsgilde]]","[[Bergbaugilde]]", "[[Söldnergilde]]", "[[Steinmetzgilde]]"]
population: 10000
commonraces: Human, Halfling, Dwarf
religion: ["[[Tempel der Ordnung]]","[[Hauskapelle der Malbor]]","[[Schrein der Reisenden]]"]
exports: ["[[Resourcen/Schmiedewaren]]","[[Resourcen/Siegelutensilien]]","[[Resourcen/Möbel]]","[[Resourcen/Kunst]]","[[Resourcen/Bücher]]","[[Resourcen/Gebrannter Alkohol]]"]
imports: ["[[Resourcen/Getreide]]","[[Resourcen/Salz]]","[[Resourcen/Wolle]]","[[Resourcen/Exotische Gewürze]]","[[Resourcen/Papierrohstoffe]]"]
exportLinks: ["[[Resourcen/Schmiedewaren]]","[[Resourcen/Siegelutensilien]]","[[Resourcen/Möbel]]","[[Resourcen/Kunst]]","[[Resourcen/Bücher]]","[[Resourcen/Gebrannter Alkohol]]"]
importLinks: ["[[Resourcen/Getreide]]","[[Resourcen/Salz]]","[[Resourcen/Wolle]]","[[Exotische Gewürze]]","[[Resourcen/Papierrohstoffe]]"]
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
Salbolin ist die Hauptstadt Malborias – für Summonia-Verhältnisse eine „riesige“ Stadt: rund **100.000 Einwohner**

## Notable NPCs
```dataview
table regexreplace(file.folder, "^NPCs/", "") as "Status" from "NPCs" where location = this.file.name sort regexreplace(file.folder,"NPCs/", "") asc, file.name asc
```

## Profile

### Erster Eindruck
[[Struktur von Salbolin]]
**Geruch**: Kohlefeuer, Lack, Papierstaub, Branntwein – je nach Viertel.
    
- **Geräusch**: Hämmer im Schmiedeviertel, Glocken vom Altwall, Marktschreier auf den Plätzen.
    
- **Bild**: Fahnen der Malbor über dem Palastbezirk, Siegelwachs in jedem Amt, überall Zunftzeichen.
### Nacht in Salbolin

- Stadttore werden geschlossen.
    
- Laternen bleiben an.
    
- Die Stadtwache patrouilliert bevorzugt an bekannten Schwachstellen.
    
- Die meisten Bürger schlafen ruhig – _bis auf jene_, die nahe alter oder beschädigter Siegel wohnen.
    

Es heißt:
> „Wenn ein Dämon durchkommt, merkt man es erst, wenn es zu spät ist.“
### Stadtgliederung (Viertel)

- **[[Kronbezirk]]** (Hof & Verwaltung): Palast, Kanzlei, Audienzhalle, „Straße der Bittsteller“.
    
- **[[Siegelhain]]** (Amt & Archive): Siegelamt, Registerhäuser, Notare, Schreibstuben, Papiermagazine.
    
- **Schmiedekamm** (Handwerk): Hochöfen, Werkzeugmacher, Rüstschmieden, Karrenbauer.
    
- **[[Salzhalle]]** (Kunst & Bürgertum): Galerien, Mäzenenhäuser, Musikstuben, Buchläden.
    
- **Handelsviertel** (Handel & Schatten): Lagerhäuser, Branntweinschenken, Heuerbüros, Hehlerkontakte.
    
- **Altwall** (ärmer, alt, zäh): ursprüngliche Mauer, enge Gassen, Veteranen, Kleinkirchen.
### Die Siegel von Salbolin

- Siegel sind **keine Magie im klassischen Sinn**, sondern eine alte Schutztechnik.
    
- Sie wirken **abschreckend, schwächend oder umleitend** auf Dämonen.
    
- Das Stadtsiegelnetz besteht aus:
    
    - Mauer- und Tor-Siegeln
        
    - Gebäudesiegeln (öffentlich & privat)
        
    - Überlagernden Mustern in dicht bebauten Vierteln
    - 
### Wartung & soziale Unterschiede

- **Wohlhabende Viertel**
    
    - frisch nachgezogene Linien
        
    - klare Kanten, gereinigte Fassungen
        
    - zusätzliche private Siegel
        
- **Ärmere Viertel (v. a. Altwall)**
    
    - verwitterte, übermalte oder beschädigte Siegel
        
    - Lücken im Muster
        
    - notdürftig reparierte Zeichen
        

Ein Siegel schützt – **aber ein gepflegtes Siegel schützt besser**.

## Gesetze

**Siegelpflicht (bauliche Mindestnorm)**  
Jedes dauerhaft bewohnte Gebäude **muss** mindestens ein anerkanntes Schutzsiegel tragen.

- Neubauten: Pflicht vor Bezug
    
- Verstöße: Geldstrafe oder Zwangsversiegelung
    
- In armen Vierteln wird oft „geduldet“, was eigentlich unzulässig ist
    

**Haftung bei Durchbruch**  
Kommt es zu einem Dämonenvorfall, wird geprüft:

- War das Siegel ordnungsgemäß gewartet?
    
- Wurde eine Reparatur gemeldet, aber nicht durchgeführt?
    

Je nach Ergebnis haftet:

- der Hauseigner
    
- der Siegelhandwerker
    
- oder (selten) die Stadt
    

**Nachtruhe & Bannzeiten**  
Zwischen Sonnenuntergang und -aufgang sind verboten:

- bauliche Veränderungen an Siegeln
    
- das Übermalen oder „Auffrischen“ alter Zeichen  
    (Begründung: instabile Resonanzen ziehen Dämonen an)
    

**Siegelbruch**  
Das mutwillige Zerstören eines Siegels gilt nicht als Sakrileg, sondern als **grobe Fahrlässigkeit** – mit harten Strafen, da es andere gefährdet.

## Bräuche

**Der Abendblick**  
Viele Bürger berühren vor dem Schlafengehen kurz das Haussiegel oder werfen einen prüfenden Blick darauf. Nicht religiös – eher wie Türen abschließen.

**Kreidestriche**  
In ärmeren Vierteln markieren Bewohner kleine Risse oder Abplatzungen mit Kreide, damit Nachbarn wissen: _Hier stimmt etwas nicht._

**Stillhalten bei Vorfällen**  
Wenn nachts etwas „Ungewöhnliches“ passiert, bleiben Fenster geschlossen.  
Helfen kommt **nach** dem Läuten der Alarmglocke – nie vorher.

**Siegelgeschenke**  
Zum Einzug schenkt man oft:

- kleine Schutzplaketten
    
- Werkzeug zur Reinigung
    
- oder einen Gutschein für Wartung  
    Luxusviertel machen daraus Statussymbole.
    

### Quest-Ideen

- **Die Lücke im Netz** – mehrere Einbrüche deuten auf ein Muster.
    
- **Das tote Siegel** – ein Zeichen ist noch da, wirkt aber nicht mehr.
    
- **Nächtlicher Durchbruch** – ein Dämon hat es bis in ein Wohnhaus geschafft.
    
- **Billige Reparaturen** – ein Viertel spart an der falschen Stelle.

## Points of Interest

### Der Altwall – „Die Alte Linie“

Der älteste Mauerabschnitt der Stadt.

- Siegel hier sind **unregelmäßig**, teils kaum noch erkennbar
    
- Einige wirken stärker, andere gar nicht mehr
    
- Die Wache patrouilliert hier häufiger – offiziell wegen Einsturzgefahr
    

**Gerücht:**  
Ein Abschnitt reagiert _aktiv_, wenn Dämonen sich nähern.

---


### Die Morgenglocke
![[Die Morgenglocke]]
### Die Abendglocke
[[Die Abendglocke]]


### Das Siegelamt – Warteschalter & Register

Kein mystischer Ort, sondern:

- Akten
    
- Prüfsteine
    
- Warteschlangen
    

Hier wird entschieden:

- welches Siegel „anerkannt“ ist
    
- welche Reparatur gilt
    
- und welches Haus offiziell „sicher genug“ ist
    

**Spannung:**  
Das Amt ersetzt keine Siegel – es **bestätigt** nur deren Zustand.


### Die Südgassen

Dicht bebaute Wohngegend mit vielen kleinen Häusern.

- Siegel überlagern sich chaotisch
    
- viele wurden mehrfach ausgebessert
    
- bekannte Schwachstelle bei Nacht
    

Die Stadtwache kennt jede Gasse – aber nie alle Türen.

### Irena Feldwacht – Siegelprüferin (überarbeitet, ehrlich)

- Mittleren Alters, müde, präzise
    
- Prüft Siegel streng, aber fair
    
- Weiß genau, wo die Stadt _wegguckt_
    

**Konflikt:**  
Sie kennt mehrere gefährliche Lücken – aber es fehlt Geld für Reparaturen.

---

### Torben Grau – Hausbesitzer im Altwall

- Besitzer von drei alten Mietshäusern
    
- Spart an Wartung, aber nicht aus Bosheit – aus Angst vor Ruin
    
- Hat „private Lösungen“ ausprobiert
    

**Plot-Haken:**  
Eines seiner Siegel ist verändert – absichtlich oder aus Versehen?

---

### Lysa Kreidefinger – inoffizielle Siegelmelderin

- Läuft nachts durch Viertel
    
- Markiert beschädigte Siegel mit Kreide
    
- Kennt jede Schwachstelle der Stadt
    

**Gerücht:**  
Sie hat einmal einen Dämon gesehen – und überlebt.

---

### Hauptmann Relgor Brenn – Nachtwache

- Veteran, pragmatisch
    
- Glaubt nicht an absolute Sicherheit
    
- Setzt Patrouillen bewusst **nicht** gleichmäßig ein
    

**Geheimnis:**  
Er opfert Randgassen, um Kernviertel sicherer zu halten.

---

### Meister Ovan Silcher – Siegelhandwerker

- Arbeitet für Reiche _und_ Arme
    
- Unterschiedliche Qualität, je nach Bezahlung
    
- Hasst es, aber lebt davon
    

**Dilemma:**  
Soll er ein schlechtes Siegel melden – oder den Auftrag behalten?

## Quests
```dataview
table regexreplace(file.folder, "^Quests/", "") as "Status"
from "Quests" 
where location = this.file.name 
sort regexreplace(file.folder, "^Quests/", "") asc, file.name asc
```


