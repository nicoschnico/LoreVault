Die Gruppe wurde von [[Iremeriest]] zusammengesucht, um aus ihnen Helden zu machen und so dieser Existenzebene eine bessere Chance gegen den Aufstieg des Bösen zu geben. 

Basis in [[Spiglia]]






aktuelle Aufträge:
``` dataview
table
from "Quests/active"
sort file.name asc
```

``` dataview
TABLE location_tag as "Location", Alignment
FROM "NPCs"
WHERE contains(associatedGroup, this.file.name)
SORT file.name, location_tag, Alignment
```