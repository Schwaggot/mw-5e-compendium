---
title: Sicht und Licht
aliases: [ Licht, Dunkelheit, Gedämpftes Licht, Helles Licht, Verdeckt, Rauch, NVG, Nachtsicht, Thermal ]
tags: [ rules, combat ]
---

# Sicht und Licht

Ob du dein Ziel sehen kannst - und wie klar - prägt jeden Wurf in einem Feuergefecht. Das System verwendet drei
Lichtstufen und zwei Grade der Verdeckung, aus klassischem 5E übernommen und erweitert mit Optik- und Signalausrüstung, die sie
selektiv überwindet. Diese Seite deckt die Baseline ab; die [Optics](../gear/optics.md) und
[Electronics](../gear/electronics.md) Seiten decken die Ausrüstung ab, die sie verbiegt.

## Light Levels {#light-levels}

| Stufe                 | Wie es aussieht                                         | Auswirkung auf Sicht                                                                                   |
|-----------------------|---------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| **Helles Licht**      | Tageslicht, gut beleuchteter Raum, Fahrzeugscheinwerfer auf dir. | Normale Sicht. Keine Strafe.                                                                   |
| **Gedämpftes Licht**  | Dämmerung, Mondlicht, Straße mit beleuchteten Fenstern. | Bereich ist **leicht verdeckt**: Disadvantage auf WIS (Perception) Checks, die auf Sicht beruhen.      |
| **Dunkelheit**        | Kein Mond, Innenraum mit Licht aus, tiefer Keller.      | Bereich ist **stark verdeckt**: sichtbasierte Perception versagt; Kreaturen darin sind effektiv Geblendet. |

Eine Fackel oder Waffenlampe macht einen Radius von 20 ft hell und weitere 20 ft Radius gedämpft. Fahrzeugscheinwerfer, Gebäude-
Flutlichter und Fallschirmleuchten sind größer, aber immer noch endliche Kegel. Außerhalb des Kegels gilt die natürliche Lichtstufe.

## Obscurement {#obscurement}

Verdeckung und Lichtstufe interagieren - Licht sagt dir, was möglich ist, Verdeckung sagt dir, was im Moment tatsächlich die Sicht
blockiert.

- **Leicht verdeckt** (Gedämpftes Licht, leichter Nebel, Laubwerk, leichter Rauch): Disadvantage auf WIS (Perception) Checks per
  Sicht.
- **Stark verdeckt** (Dunkelheit, dichter Rauch, dichter Nebel, tiefes Unterholz): Eine Kreatur im Bereich wird als
  **Geblendet** behandelt, wenn sie versucht, irgendetwas darin oder dahinter zu sehen.

Eine Kreatur in einem stark verdeckten Bereich hat totale Tarnung vor Kreaturen außerhalb: Angreifer haben Disadvantage,
das Ziel hat Advantage auf Angriffe (weil der Angreifer nicht sehen kann). Dies ist **Concealment**, keine [Deckung](cover.md) - es
versteckt dich, aber es stoppt keine Kugeln.

## Signature Gear {#signature-gear}

Drei Gear-Tag-Familien existieren speziell, um die oben genannten Regeln zu biegen. Jeder relevante Gegenstand listet eine oder mehrere davon; siehe
[Gear Tags](../gear.md#gear-tags).

### Night-Vision (NVG) {#night-vision-nvg}

Gegenstände mit dem Tag `night-vision` (PVS-14 Monokular, GPNVG-18 Quads usw.) behandeln **Dunkelheit und Gedämpftes Licht als Helles Licht**
bis zur Reichweite des Geräts (typischerweise 100 ft). Einschränkungen:

- NVGs flachen die Tiefenwahrnehmung ab und verengen das Sichtfeld; der GM kann Disadvantage auf Perception im Nahbereich
  oder schnelles Kopfverfolgen beim Tragen auferlegen.
- Eine helle Lichtquelle (Mündungsfeuer, Fahrzeugscheinwerfer, Flashbang) innerhalb des Sichtfelds des Geräts kann es für 1
  Runde überstrahlen.
- NVGs durchdringen keinen Rauch, Nebel oder feste Hindernisse.

### Thermal {#thermal}

Gegenstände mit dem Tag `thermal` zeigen Wärmesignaturen anstelle von sichtbarem Licht.

- Sehen durch Rauch, leichtes Laubwerk und die meiste Tarnung.
- Sehen warme Körper in Dunkelheit unabhängig von der Lichtstufe.
- Können keinen Text, Schilder oder Details lesen; ein Gesicht allein anhand von Wärme zu identifizieren ist unmöglich.
- Können nicht durch feste Wände sehen, Glas blockiert IR, und sehr kalte Ziele (kürzlich tot, tief hypotherm, in schwerer
  Isolation) können nur schwach oder gar nicht registrieren.

### IR Strobe / IR Marker {#ir-strobe-ir-marker}

Gegenstände in [Electronics](../gear/electronics.md) wie IR-Strobes und IR-Chemlights sind für das bloße Auge unsichtbar, blitzen aber
hell unter NVG.

- Werden verwendet, um Freunde, LZs, gefallene Verwundete und IR-geräumte Korridore zu markieren.
- Eine Kreatur ohne NVG kann sie gar nicht sehen.
- Ein Feind mit NVG kann sie absolut sehen - deshalb ist IR-Disziplin Teil des Briefings.

## Magnified Optics {#magnified-optics}

Gegenstände mit dem Tag `magnified` (Zielfernrohre, Spektive, Ferngläser):

- **Advantage** auf WIS (Perception) Checks auf lange Distanz.
- **Disadvantage** um Bewegungen im Nahbereich zu erspähen (enges Sichtfeld).

Dies ist der einzige häufige Fall im System, in dem du *sowohl* mit Advantage als auch Disadvantage auf verschiedene
verwandte Checks innerhalb derselben Szene würfeln kannst; laut [Advantage and Disadvantage](advantage.md) gelten sie jeweils für ihren eigenen
Wurf, nicht gegeneinander.

## Smoke and Concealment {#smoke-and-concealment}

Rauchgranaten und Schlachtfeldrauch sind stark verdeckt für alle außer `thermal`-Nutzer.

- Ein Operator im Rauch ist getarnt (Angreifer haben Disadvantage; sie haben Advantage heraus zu attackieren, können aber
  nicht über die Wolke hinaus sehen).
- Rauch stoppt keine Kugeln. Suppressive Fire durch Rauch trifft immer noch jeden, der unglücklicherweise in der Linie ist.
- Thermal-Optiken sehen durch die meisten Rauche; NVGs nicht.

## Examples {#examples}

> **Beispiel - Gedämpftes Licht:** Falke bewegt sich durch eine schlecht beleuchtete Gasse (Gedämpftes Licht). Der Militante am anderen Ende ist auch
> im Gedämpften Licht. Falke macht einen passiven Perception Check, um nach Bedrohungen zu scannen - er leidet -5 vom Disadvantage des
> Gedämpften Lichts auf Sichtchecks (Awareness Training Level 1 würde das entfernen; Falke hat es, also ist das -5 weg). Der
> Militante, dem Awareness Training fehlt, ist bei -5 auf *seine* passive Perception. Falke erspäht den Militanten; der Militante
> erspäht Falke nicht. Falke bekommt den ersten Zug.

> **Beispiel - NVG:** Gleiche Gasse, diesmal keine Straßenlichter (Dunkelheit). Falke trägt PVS-14 Monokulare (`night-vision`,
> 100 ft Reichweite). Die Gasse wird für ihn effektiv Helles Licht bis zu 100 ft, also sind seine Angriffe und Perception
> normal. Der Militante hat kein NVG und ist nach Dunkelheitsregeln - stark verdeckt, effektiv Geblendet. Angriffe gegen
> Falke haben Disadvantage; Falkes Angriffe haben Advantage. Der Kampf ist eine Schlachtung.

> **Beispiel - Rauch und Thermal:** Falke zündet eine Rauchgranate im Korridor und bewegt sich hindurch. Ein Militanter auf der
> anderen Seite hat ein Thermal-Monokular (`thermal`). Der Rauch beeinträchtigt seine Sicht nicht - er sieht Falkes Wärmesignatur
> klar und schießt normal. Falke, der mit bloßem Auge durch die Wolke zurückschaut, sieht nichts. Der Militante
> attackiert ohne Strafe; Falkes Rückfeuer ist mit Disadvantage.

## Compared to Classic D&D 5E {#compared-to-classic-dd-5e}

- Drei Lichtstufen (hell / gedämpft / Dunkelheit) und zwei Grade der Verdeckung (leicht / stark) sind direkt aus
  klassischem 5E übernommen.
- Leicht verdeckt = Disadvantage auf Sicht-Perception; stark verdeckt = effektiv Geblendet - gleich wie klassisches 5E.
- Dieses Compendium ersetzt das rassische Darkvision-Merkmal durch einen Ausrüstungsslot: NVGs sind Ausrüstung, keine Biologie, und sie können
  verloren, kaputt oder durch Licht gestört werden.
- Thermal, IR-Strobes und vergrößerte Optiken sind Homebrew-Gear-Tags, aber jedes ist ein sauberer Regeltext-Override einer
  spezifischen Verdeckungsklausel.
