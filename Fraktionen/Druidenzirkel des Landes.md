Sammeln Wissen überall auf [[Summonia]]

Ältester Zirkel liegt im [[Länder/Shekia]]

Können die Gruppe mit Hinweisen nach neuen Kammern versorgen



``` dataview
TABLE location_tag as "Location", Alignment
FROM "NPCs"
WHERE contains(associatedGroup, this.file.name)
SORT file.name, location_tag, Alignment
```
