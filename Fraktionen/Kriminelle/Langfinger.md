Diebesgilde

Besteht aus 5 Untergruppen.
Daumen - Kämpferische Abteilung (Daumen hoch / runter --> Tod / Leben)
Zeigefinger - Diebstähle (Langfinger)
Mittelfinger - Schmähungen, Erpressung
Ringfinger - Bündnisse, Bestechungen
Kleiner Finger - Geld  verleihen




``` dataview
TABLE location_tag as "Location", Alignment
FROM "NPCs"
WHERE contains(associatedGroup, this.file.name)
SORT file.name, location_tag, Alignment
```