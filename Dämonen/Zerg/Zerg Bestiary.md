---
faction: Zerg
source: Zerg Bestiary
system: D&D 5e
type: Bestiary
---

# The Zerg

## Lore

Living in massive hives and dotting the landscape with underground hatcheries, the zerg are nearly innumerable and embody the most savage and twisted aspects of nature. They live to consume and assimilate. Amid the chaos of the swarm there is a distinct and terrifying order, centered on the [[Queen of Blades]], the abyssal war-regent and right hand woman of [[Dämonen/Prinzen/Graz'zt|Graz'zt]]. Her will drives the zerg onward to kill, expand, and assimilate in the Dark Prince's name.

### Assimilation

Each zerg creature is an amalgamation of the essence of different beasts
and monsters. Claws, scales, legs, and other traits have been stolen and
repurposed. The endless expansion of the zerg into new territories feeds
this process: creatures that once lived there are assimilated into the
swarm, and their raw essence is stored inside zerg larva and various
zerg structures.

When a creature's essence is added to the swarm, it is used to iterate
on both new and old designs. These designs are tested against one
another, with weaker forms dying and only the strongest contributing
their essence back to the swarm. This brutal process allows the zerg to
adapt to almost any environment.

### Endless Numbers

The zerg swarm appears nearly endless. They breed in hatcheries beneath the ground or in labyrinthine cave systems. When populations become too large, they form hives.

### Meaning in Servitude

The zerg are given intelligence and direction by the [[Queen of Blades]]. Through her, the influence of [[Dämonen/Prinzen/Graz'zt|Graz'zt]] spreads into hive, tunnel, and brood. When a zerg creature loses this connection, it becomes feral. Broodmothers (see [[Queen]]) can perform complex strategy and command hatcheries in the queen's absence.

## Hive Mind Template

Feral zerg (as presented) have no hive mind. Connected zerg gain telepathy 60 ft. (zerg only).

**Hive Mind.** As an action, the zerg creature can see through the senses of any other zerg creature within range of its telepathy.

---

## Monster Index

```dataview
TABLE WITHOUT ID
	file.link AS Name,
	cr AS CR,
	size AS Size,
	zerg_type AS Type
FROM "Dämonen/Zerg"
WHERE file.name != "Zerg Bestiary" AND faction = "Zerg" AND zerg_type AND size
FLATTEN string(cr) AS cr_text
FLATTEN replace(replace(replace(cr_text, "1/8", "0.125"), "1/4", "0.25"), "1/2", "0.5") AS cr_num_text
FLATTEN number(cr_num_text) AS cr_sort
SORT cr_sort ASC, file.name ASC
```
