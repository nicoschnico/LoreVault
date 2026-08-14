Händlerdynastie, mit großem Einfluss in der [[Handelsgilde]]

Stehen in wirtschaftlicher Konkurrenz zur [[Joésa-Händlerdynastie]]


Wappen: Berg aus dessen Spitze ein silberner Fluss entspringt




``` dataview
TABLE location_tag as "Location", Alignment
FROM "NPCs"
WHERE contains(associatedGroup, this.file.name)
SORT file.name, location_tag, Alignment
```