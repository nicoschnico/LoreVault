---
type: Region
tags: [Ort, Unterwelt, Höhlen, Gefährlich]
---

# Underdark

Der Underdark ist ein großes Tunnelsystem, das weite Teile des Kontinents unter sich verbirgt. Es ist eine gefährliche, finstere Welt, in der Sonnenlicht niemals eindringt.

## Allgemeine Informationen

### Charakteristiken
- Riesiges, miteinander verbundenes Höhlen- und Tunnelsystem
- Spannt über weite Teile des Kontinents
- Ewige Dunkelheit – Sonnenlicht dringt niemals durch
- Unberechenbar und tückisch
- Ständig bewohnt von gefährlichen Kreaturen

### Bewohner
- **Dämonen** – omnipräsent, zu jeder Zeit
- **Andere Kreaturen** – diverse unterirdische Wesen
- **Völker und Kulturen** – einige sind ganz oder teilweise in den Höhlen angesiedelt
- **Unbekannte Wesen** – manche Regionen sind kaum erforscht

### Gefahren
- Dämonische Angriffe
- Einsturz von Höhlendecken
- Vergiftete Gewässer und Gase
- Verlaufen in Labyrinthen
- Unbekannte, unvorhergesehene Bedrohungen

## Bekannte Höhlen und Regionen

### Landkarte
- [[Landkarte - Underdark (Salbolin-Region)]]

### Schnellüberblick
- [[Steinwald]]: Versteinerter Urwald aus Säulen, Tierformen und Ruinen; Jagdgebiet einer Zerg-Kolonie.
- [[Erste Ebene des Abgrunds]]: Tiefe Grenzregion mit dämonischer Verseuchung und instabilen Übergängen.

```dataview
TABLE
  file.link AS "Name",
  description AS "Kurzbeschreibung",
  ursprung AS "Ursprung",
  zugang AS "Zugang",
  merkmale AS "Kernmerkmale",
  begegnungen AS "Typische Begegnungen",
  gefährlichkeit AS "Gefahrenstufe"
FROM "Orte/Underdark"
WHERE contains(tags, "Underdark") AND file.name != this.file.name
SORT file.name
```

## Geschichte
Die genaue Entstehung des Underdark ist unbekannt. Alte Aufzeichnungen deuten darauf hin, dass es von antiken Zivilisationen erforscht und teilweise genutzt wurde.

## Lore-Verbindungen
- [[Elowen Voss]] – Forscherin, die viel über den Underdark weiß
- [[16_08_26 - Höhlen unter Salbolin|Expedition in die Höhlen]]
