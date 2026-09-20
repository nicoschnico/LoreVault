#Myzelzirkel

Eine kleine Druidenenklave im [[Orte/Underdark/Pilzbiom|Pilzbiom]].

Der Zirkel lebt in Symbiose mit den Großpilzen, hütet die Mycelknoten und lenkt Sporenströme, um Eindringlinge fernzuhalten.

Sie stehen dem [[Fraktionen/Druidenzirkel des Landes|Druidenzirkel des Landes]] nahe, gelten jedoch als abgeschottet und deutlich kompromissloser.

## Ziele
- Das Pilzbiom vor Ausbeutung schützen
- Die Ausbreitung dämonischer Fäulnis eindämmen
- Parasects nicht ausrotten, sondern kontrolliert im Gleichgewicht halten

## Haltung zu Fremden
- Vorsichtig und misstrauisch beim ersten Kontakt
- Hilfsbereit, wenn jemand das Biom respektiert
- Feindselig gegen Feuer, Raubbau und dämonische Rituale


``` dataview
TABLE location_tag as "Location", Alignment
FROM "NPCs"
WHERE contains(associatedGroup, this.file.name)
SORT file.name, location_tag, Alignment
```
