---
title: Bewegung
aliases: [ Geschwindigkeit, Schwieriges Gelände, Dash, Disengage, Sprint, Klettern, Schwimmen, Springen, Liegend ]
tags: [ rules, combat, character ]
---

# Bewegung

Die **Geschwindigkeit** eines Operators ist die Anzahl Fuß, die er unter normalen Bedingungen in seinem Zug zurücklegen kann. Bewegung ist die
meistgenutzte Ressource in einem Feuergefecht - in Deckung kommen, sich vom Feind lösen, für einen Winkel umpositionieren. Sie wird
während des Zuges frei ausgegeben und kann rund um Action und Bonus Action aufgeteilt werden.

## Base Speed {#base-speed}

Standard-Operator-Geschwindigkeit beträgt **30 ft pro Zug**. Einige Quellen modifizieren sie:

- **[Agile](../personality-traits.md)** Personality Trait: +5 ft.
- **[Mobility](../operator-class.md#basic-training)** Basic Training: +5 ft.
- **[Bomb Suit (EOD)](../armor.md)**: -10 ft.
- **[Ballistic Shield](../armor.md)** Träger: -10 ft.
- **[Crouched](conditions.md)**: 1/2 Geschwindigkeit (abgerundet).
- **[Slowed](conditions.md)**: 1/2 Geschwindigkeit (abgerundet, min 5 ft).
- **Encumbrance**: GM kann die Geschwindigkeit halbieren, wenn du dein sicheres Traggewicht überschreitest.

Du kannst dich bis zu deiner Geschwindigkeit bewegen, beliebig über den Zug aufgeteilt. Du kannst 10 ft bewegen, eine Action ausführen und dann
die verbleibenden 20 ft bewegen. Du kannst keine unbenutzte Bewegung für den nächsten Zug aufsparen.

## Movement Costs {#movement-costs}

Der meiste Boden kostet **1 Fuß pro bewegtem Fuß**. Folgendes multipliziert die Kosten:

| Gelände oder Zustand                                | Kosten pro Fuß                               |
|-----------------------------------------------------|-----------------------------------------------|
| Offener Boden, gepflasterte Straße, harter Boden    | 1                                             |
| Schwieriges Gelände (Trümmer, dichtes Gestrüpp, Schlamm, Schnee) | 2                                |
| Klettern (Seil, Leiter, Regenrohr, Zaun)            | 2                                             |
| Schwimmen                                           | 2                                             |
| Kriechen (Bewegung liegend)                         | 2                                             |
| Aus liegender Position aufstehen                    | 1/2 deiner Geschwindigkeit (Einmalkosten, nicht pro Fuß) |
| Sich hinlegen                                       | Frei                                          |

Ein 30-ft-Operator, der sich durch schwieriges Gelände schleppt, bewegt sich effektiv 15 ft pro Zug. Ein 30-ft-Operator, der aus liegender Position aufsteht,
gibt 15 ft Bewegung nur zum Aufstehen aus und hat noch 15 ft für den Rest des Zuges.

## Prone, Crouched, Standing {#prone-crouched-standing}

- **Stehend** ist die Standardhaltung. Volle Geschwindigkeit, normale AC, normales Zielen.
- **Crouched** ([Condition](conditions.md)): halbe Geschwindigkeit, Angreifer jenseits von 5 ft erleiden -2 auf Fernkampfangriffe gegen dich,
  zurück zu voller Haltung aufstehen kostet 5 ft Bewegung.
- **Liegend**: Hinlegen ist frei; Bewegung auf dem Boden kostet 2 ft pro ft (Kriechen). Nahkampfangriffe gegen dich sind mit
  Advantage; Fernkampfangriffe gegen dich (jenseits von 5 ft) sind mit Disadvantage. Aufstehen kostet die Hälfte deiner Geschwindigkeit.

Operator wechseln häufig innerhalb eines einzigen Zuges zwischen Stehend und Crouched - hinter einer niedrigen Mauer ducken, um die
Schusslinie des Schützen zu brechen, hochkommen um zu schießen, zurückfallen. Die Crouched/Stehend-Wechselkosten sind der Preis, den du zahlst.

## Dash {#dash}

Die [Dash](combat-turn.md#actions) Action lässt dich deine *Action* ausgeben, um dich erneut bis zu deiner Geschwindigkeit zu bewegen. Gesamtbewegung
in einem Dash-Zug ist 2 × Geschwindigkeit (oder 4 × Geschwindigkeit, wenn du auch einen Bonus-Action-Dash durch ein Feature hast). Ein Dash-Operator,
der über offenen Boden rennt, legt eine große Distanz zurück, kann aber in diesem Zug nicht auch schießen.

> **Beispiel:** Falke hat 35 ft Geschwindigkeit (30 Basis + 5 Agile). Auf einer sauberen Straße bewegt er sich 35 ft, führt die Dash Action aus und
> bewegt sich weitere 35 ft - insgesamt 70 ft in diesem Zug. Er kann nicht auch schießen, da Dash seine Action verbraucht hat.

## Disengage {#disengage}

Die [Disengage](combat-turn.md#actions) Action lässt dich die Nahkampfreichweite verlassen, ohne für
den Rest des Zuges einen Opportunity Attack auszulösen. Nutze sie, wenn ein Feind in Reichweite ist und du dich auf eine weitergehende Feuerposition zurückziehen musst.

## Climbing, Swimming, Crawling {#climbing-swimming-crawling}

Jedes kostet 2 ft pro ft, wie oben. Der GM kann außerdem auf rauen oder
rutschigen Oberflächen, bei starker Strömung oder beim Tragen nahe deiner Belastungsgrenze einen STR (Athletics) [Check](ability-checks.md) fordern. Ein Fehlschlag bedeutet meist keinen Fortschritt
in diesem Zug; ein starker Fehlschlag kann Fallen, Last fallen lassen oder Griff verlieren bedeuten.

## Jumping {#jumping}

| Sprungart                      | Distanz                                     | Hinweise                                                                            |
|--------------------------------|---------------------------------------------|-------------------------------------------------------------------------------------|
| **Weitsprung (mit Anlauf)**    | Fuß gleich deinem STR-Wert                  | Braucht mindestens 10 ft Anlauf.                                                    |
| **Weitsprung (stehend)**       | Halber STR-Wert in Fuß                      | Kein Anlauf.                                                                        |
| **Hochsprung (mit Anlauf)**    | 3 + STR-Modifikator Fuß vertikale Höhe      | Braucht mindestens 10 ft Anlauf. Reiche mit ausgestreckten Armen extra 1.5 × deiner Höhe. |
| **Hochsprung (stehend)**       | Halbe Anlaufdistanz                         | Kein Anlauf.                                                                        |

Sprungweite zählt gegen deine Bewegung (1 ft pro gesprungenem ft). Ein misslungener Sprung kann damit enden, dass du Liegend, in schwierigem
Gelände oder schlimmer landest, abhängig davon was darunter war.

## Breaking Contact {#breaking-contact}

Um sauber aus einem schlechten Kampf herauszukommen:

- **Disengage** (Action), damit du nicht von einem Opportunity Attack verfolgt wirst.
- **Dash** (Action) für Distanz. Du kannst nicht beides im selben Zug, es sei denn du hast auch Action Surge oder einen
  Bonus-Action-Dash.
- Zünde **Rauch** ([Gear](../gear.md)), um deinem Rückzug Tarnung zu gewähren.
  Siehe [Cover](cover.md#cover-vs-concealment).
- Setze **Suppressive Fire** mit einem anderen Element, um die Köpfe des Feindes unten zu halten, während du dich bewegst.

## Vehicle Movement {#vehicle-movement}

Wenn du in einem Fahrzeug bist, verwendest du die Geschwindigkeit des Fahrzeugs anstelle deiner eigenen. Die meisten Bodenfahrzeuge bewegen sich mit Vielfachen der
Fußgeschwindigkeit; Hubschrauber und Flugzeuge sind völlig außerhalb des Pro-Zug-Rasters und operieren nach GM-Erzählung. Detaillierte Fahrzeug-
Kampfregeln liegen im GM-Ermessen.

## Compared to Classic D&D 5E {#compared-to-classic-dd-5e}

- 30 ft Standardgeschwindigkeit, freie Aufteilung der Bewegung um die Action und freie Object Interaction sind unverändert.
- Schwieriges Gelände zu 2 ft pro Fuß, Klettern/Schwimmen zu 2 ft pro Fuß, Kriechen zu 2 ft pro Fuß - alles klassisches 5E.
- Sich hinlegen ist frei; Aufstehen kostet die Hälfte deiner Geschwindigkeit - gleich wie im klassischen 5E.
- Sprungzahlen (STR-Wert für Weitsprung, 3 + STR Mod für Hochsprung, halbieren ohne Anlauf) sind direkt aus
  klassischem 5E übernommen.
- Die Homebrew-Schicht ist **Crouched** als Haltung zwischen Stehend und Liegend, und das größere Menü an geschwindigkeits-
  modifizierender Ausrüstung (Bomb Suit, Ballistic Shield, IFV).
