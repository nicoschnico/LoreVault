Ehemaliger Anführer: [[Darian]]


Die Truppe verlor einen Großteil ihrer Leute, darunter auch ihren Hauptmann [[Darian]] bei dem Versuch das Dorf [[Altenwald]] zu verteidigen.




``` dataview
TABLE location_tag as "Location", Alignment
FROM "NPCs"
WHERE contains(associatedGroup, this.file.name)
SORT file.name, location_tag, Alignment
```