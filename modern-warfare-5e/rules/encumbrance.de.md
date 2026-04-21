---
title: Belastung
aliases: [ Tragekapazität, Traglast, Last, Belastet, Schwer belastet ]
tags: [ rules, character ]
---

# Belastung

Jedes [Gear](../gear.md), jede [Armor](../armor.md) und jede [Weapon](../weapons.md) im Kompendium listet ein Gewicht
in Kilogramm. Belastung ist die Buchhaltung, die diese Gewichte in eine Traglimite umrechnet. Ein Operator, der
überladen ist, bewegt sich langsamer und würfelt schlechter bei allem Körperlichen.

## Tragelimits {#carry-limits}

Die Tragekapazität skaliert mit deinem **Strength Score** (dem Score, nicht dem Modifier).

| Schwelle               | Limit                        | Effekt                                                                                                                           |
|------------------------|------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| **Light Load**         | bis zu `2.5 × STR` kg        | Keine Strafe.                                                                                                                    |
| **Encumbered**         | `2.5 × STR` bis `5 × STR` kg | Speed -10 ft.                                                                                                                    |
| **Heavily Encumbered** | `5 × STR` bis `7 × STR` kg   | Speed -20 ft (min 5 ft); Disadvantage auf STR-, DEX- und CON-[Checks](ability-checks.md), Attacks und [Saves](saving-throws.md). |
| **Über Max**           | über `7 × STR` kg            | Kann nicht getragen werden. Kann mit halber Speed gezogen werden (siehe *Schieben, Ziehen, Heben* unten).                        |

> **Beispiel:** Falke hat STR 11 (sein Pre-Trait-Score; der Agile Trait hat ihn von 13 auf 11 gesenkt). Seine
> Tragebereiche sind: Light Load bis 27,5 kg, Encumbered 27,5-55 kg, Heavily Encumbered 55-77 kg, über Max ab 77 kg.
> Mit einer vollen Assault-Loadout (Gewehr + Munition + Plate Carrier + Assault Pack ~ 22 kg) ist er in Light Load
> und zahlt keine Strafe. Füge ein 10-kg-Breaching-Kit für eine Operation hinzu und er rutscht in Encumbered: -10 ft
> Speed für die Dauer.

## Schieben, Ziehen, Heben {#push-drag-lift}

Du kannst schwerere Lasten bewegen, wenn du nicht versuchst, sie die ganze Zeit auf dir zu tragen:

- **Schieben, Ziehen oder Heben** bis zum Doppelten deiner maximalen Trageleistung (`14 × STR` kg). Speed halbiert
  sich dabei.
- Ein Casualty Drag ist die kanonische Verwendung: ein 75-kg-Verwundeter liegt weit über Falkes 77-kg-Grenze, also
  kann er ziehen, aber nicht tragen. Er bewegt sich mit halber Speed und seine Hände sind voll.

## Was als getragen zählt {#what-counts-as-carried}

Zähle alles zusammen, was du bei dir trägst: getragene Rüstung, geschulterte oder holsterte Waffen, Munition in
Magazinen und am Rig, den Inhalt deines Packs und jegliche Verbrauchsgegenstände. Gegenstände, die zu deinen Füßen
abgelegt, auf einen Tisch gelegt oder in einem Fahrzeug verstaut sind, zählen nicht gegen das Tragegewicht, bis du
sie aufhebst.

Gewichte pro Magazin stehen unter [Munition](ammunition.md#magazine-weight).

Ein paar gängige Loadouts zur Referenz:

| Loadout                   | Ungefähres Gewicht | Was darin ist                                                                            |
|---------------------------|--------------------|------------------------------------------------------------------------------------------|
| **Patrol Minimum**        | ~10 kg             | Gewehr + 4 Magazine + IFAK + Feldflasche + Admin Pouch.                                  |
| **Assault Loadout**       | ~22-25 kg          | Plate Carrier mit Platten + Gewehr + 8 Magazine + IFAK + Granaten + Funk + Assault Pack. |
| **Long-Range Patrol**     | ~30-35 kg          | Assault Loadout + voller Ruck (Verpflegung, Schlafzeug, Batterien, Sat-Funk).            |
| **Demo / Breach Loadout** | ~35-40 kg          | Assault Loadout + Breaching Charges + Brecheisen + Extra-Munition + Ersatzbatterien.     |
| **Bomb Suit am Mann**     | ~50+ kg            | EOD-Arbeit; Speed ist bereits durch den Anzug selbst gedeckelt.                          |

## Last reduzieren {#reducing-load}

Gängige Wege, um aus dem Encumbered-Bereich herauszubleiben:

- **Cache it.** Lass den Rucksack am ORP vor dem Angriff; hol ihn beim Exfil wieder ab.
- **Verteilen.** Die Gurtmunition eines SAW-Schützen wird auf die Squad verteilt.
- **Kit richtig dimensionieren.** Eine Reconnaissance-Operation braucht kein Breaching-Kit. Passe die Loadout zum
  [Mission Kit](../gear.md#mission-kits).
- **Stärkerer Operator.** Höheres STR schiebt jede Schwelle linear nach oben. Zwei weitere STR-Punkte = +5 kg mehr
  Light-Load-Raum.

## Fahrzeuge und Tragekapazität {#vehicles-and-carry-capacity}

Fahrzeuge haben ihre eigenen Laderaumlimits, vom GM festgelegt. Ein Operator in einem Fahrzeug rechnet persönlich
getragenes Gewicht nicht gegen die persönliche Belastung für Speed- und Check-Strafen - er muss allerdings noch *aus
dem Fahrzeug aussteigen*, während er es trägt.

## Vergleich mit klassischem D&D 5E {#compared-to-classic-dd-5e}

- Die Mechanik spiegelt die klassische 5E **Variant-Encumbrance-Regel** wider (die Standard-5E-Regel ist "du hast ein
  flaches Tragemaximum und ansonsten keine Strafe", was dieses Spiel für modernen Kampf als zu nachsichtig empfindet).
- Klassisches 5E benutzt Pfund und `5 × STR` / `10 × STR` / `15 × STR` Schwellen. Dieses Kompendium verwendet
  Kilogramm und die gerundeten `2.5 × STR` / `5 × STR` / `7 × STR` Schwellen, was umgerechnet etwa dem gleichen
  absoluten Wert entspricht.
- Push/Drag/Lift bei 2× max Carry, halbe Speed, unverändert.
- Das Kompendium fügt ein viertes Band hinzu (über Max → nur Ziehen); klassisches 5E erklärt es einfach für unmöglich.
