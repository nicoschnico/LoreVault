#Myzelzirkel

Eine kleine Druidenenklave im [[Orte/Underdark/Pilzbiom|Pilzbiom]].

Der Zirkel lebt in Symbiose mit den Großpilzen, hütet die Mycelknoten und lenkt Sporenströme, um Eindringlinge fernzuhalten.

Sie stehen dem [[Fraktionen/Druidenzirkel des Landes|Druidenzirkel des Landes]] nahe, gelten jedoch als abgeschottet und deutlich kompromissloser.

## Aufbau
- Der Zirkel besteht aus fünf Druiden.
- Kein Mitglied ist höher als Stufe 8; der erfahrenste Druide führt den Zirkel an.
- Die Druiden wohnen in Höhlen in den Außenwänden des Bioms.
- Vor den Eingängen hängen Vorhänge aus Pilzhaut, die das Eindringen von Pollen und Sporen in die Wohnhöhlen verhindern.
- Die Pilzhaut wird vorsichtig von den Stämmen besonders großer Pilzbäume abgezogen und anschließend getrocknet und geglättet.

## Die fünf Druiden
- **Maelis Wurzelhauch (Stufe 8):** Anführerin des Zirkels, ruhig und unbeirrbar. Sie kennt die Lage jedes zentralen Mycelknotens und entscheidet, wann Fremde als Gefahr gelten.
- **Tharok Sporenhand (Stufe 7):** Heiler und Bewahrer der Brutgleichgewichte. Er ist einer der beiden vermissten Druiden und glaubt, dass selbst verdorbene Kreaturen noch gerettet werden können.
- **Nimu Pilzlicht (Stufe 6):** Kundschafterin und Sammlerin. Sie wird seit dem Aufbruch vermisst und hat die Spuren des Overlords zuerst entdeckt.
- **Odran Tiefenbart (Stufe 5):** Wächter der Wohnhöhlen, schweigsam und misstrauisch gegenüber Fremden. Er hält die verbliebenen Mycelknoten stabil, während die anderen fehlen.
- **Sivra Tauhaut (Stufe 3):** Jüngstes Mitglied des Zirkels und Spezialistin für Pilzhaut und Pilzfäden. Sie versorgt die Höhlen mit Vorhängen, Schuhen und repariertem Reisegeflecht.

## Pilzfadenschuhe
Die Druiden tragen Schuhe, die aus stabilen Pilzfäden gewoben sind. Das Material passt sich dem lebenden Mycel an und verhindert, dass die Druiden im Pilzbiom festgesetzt werden. Dadurch können sie sich ungehindert durch den Pilzwald, über den Mycelteppich und zwischen den Großpilzen bewegen.

## Pilzkreise
Tief im Pilzbiom wachsen seltene Pilzkreise, deren Mycel nicht nur mit dem Underdark, sondern auch mit dem [[Länder/Feywild|Feywild]] verbunden ist. Wer einen solchen Kreis unter den richtigen Bedingungen betritt, kann in das Feywild gelangen.

Die Pilzkreise öffnen sich nicht jederzeit. Mondlicht, Sporenströme und die Pflege durch den Myzelzirkel müssen in Einklang stehen. Der Zirkel kennt die Standorte der Kreise und entscheidet, wer sie benutzen darf. Ein falsch geöffneter Kreis kann Reisende an einen unbekannten Ort im Feywild führen oder den Übergang für gefährliche Wesen offenlassen.

## Belohnung für Helfer
Wer den Myzelzirkel in einer ernsten Gefahr unterstützt, erhält ein **Mycelzeichen** aus gehärtetem Pilzgeflecht. Es weist die Gruppe als geduldete Verbündete aus: Parasects und die meisten Bewohner des Pilzbioms greifen sie nicht ohne Anlass an, und die Druiden gewähren ihnen Schutz und Unterkunft.

Als besondere Belohnung kann der Zirkel einmalig einen sicheren Pilzkreis öffnen. Die Gruppe erhält dadurch eine kontrollierte Reise ins [[Länder/Feywild|Feywild]] oder eine sichere Rückkehr aus der Feenwildnis. Der Kreis wird nur für die Gruppe geöffnet und bleibt danach wieder verschlossen.

## Ziele
- Das Pilzbiom vor Ausbeutung schützen
- Die Ausbreitung dämonischer Fäulnis eindämmen
- Parasects nicht ausrotten, sondern kontrolliert im Gleichgewicht halten
- [[Die Fäulnis unter dem Pilzbiom]]

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
