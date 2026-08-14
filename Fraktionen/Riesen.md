


``` dataview
TABLE location_tag as "Location", Alignment
FROM "NPCs"
WHERE contains(associatedGroup, this.file.name)
SORT file.name, location_tag, Alignment
```

