---
title: Kampfzug
aliases: [ Initiative, Action Economy, Round, Turn, Surprise, Reaction, Bonus Action ]
tags: [ rules, combat ]
---

# Kampfzug

Kampf wird in **Runden** unterteilt. Eine Runde repräsentiert etwa 6 Sekunden In-Fiction-Zeit und gibt jeder Kreatur
einen Zug. Innerhalb einer Runde handeln Charaktere in **Initiative**-Reihenfolge. In ihrem Zug hat jeder Charakter
ein Budget aus Bewegung plus einer kleinen Auswahl an Action-Typen. Diese Seite behandelt die Struktur; spezifische
Feuermodus-Actions leben in [Combat Actions](combat-actions.md).

## Initiative würfeln {#rolling-initiative}

Initiative ist ein [DEX Check](ability-checks.md): `1d20 + DEX-Modifier + situative Boni`. Höhere Ergebnisse handeln
zuerst. Gleichstände zwischen zwei Kreaturen werden durch den höheren DEX Score, dann durch Spielerentscheidung
aufgelöst.

- **Born to Fight** (Personality Trait): +5 auf Initiative.
- **Advanced Awareness Training Level 1**: Advantage auf Initiative-Rolls.
- Der GM kann **Disadvantage** anwenden, wenn jemand schläft, betäubt oder anderweitig beeinträchtigt ist, wenn der
  Kampf beginnt.

> **Beispiel:** Falke (DEX +3) und ein Kämpfer (DEX +1) würfeln beide Initiative. Falke würfelt **1d20 → 14**,
> +3 = **17**. Der Kämpfer würfelt **1d20 → 18**, +1 = **19**. Der Kämpfer kommt in dieser Runde zuerst dran, dann
> Falke, dann alle anderen in der Reihenfolge.

## Surprise {#surprise}

Wenn eine Seite den Kampf beginnt, ohne dass die andere etwas davon weiß - ein erfolgreicher Hinterhalt, ein
lautloser Breach, ein Sniper, der ohne Vorwarnung eröffnet -, sind die ahnungslosen Kreaturen **Surprised**.
Surprised-Kreaturen können sich in der ersten Runde des Kampfes nicht bewegen und keine Action oder Reaction
ausführen. Sie würfeln Initiative wie gewohnt, werden aber in ihrem ersten Zug übersprungen. Ab Runde zwei handeln
sie normal.

Der GM bestimmt Awareness über passive Perception (siehe [Ability Checks](ability-checks.md#passive-checks)) gegen
die Stealth des Angreifers.

## Was es in deinem Zug gibt {#whats-on-your-turn}

Jeden Zug bekommst du:

- **Movement** bis zu deiner Speed, aufteilbar wie du willst (siehe [Movement](movement.md)).
- **Eine Action**.
- **Eine Bonus Action**, *nur* wenn du ein Feature oder eine Fähigkeit hast, die eine gewährt.
- **Eine freie Object Interaction** - ein Magazin fallen lassen, eine Pistole ziehen, eine unverschlossene Tür öffnen,
  einen Knopf drücken. Eine zweite Interaction im selben Zug kostet deine Action (Use an Object).

Du hast außerdem **eine Reaction** pro Runde, die außerhalb deines Zuges genutzt wird.

Du kannst Bewegung um deine Action herum aufteilen: 15 ft bewegen, feuern, weitere 15 ft bewegen. Du kannst deine
Bonus Action vor oder nach deiner Action ausführen. Du kannst ungenutzte Bewegung oder Actions nicht für später
aufsparen.

## Actions {#actions}

Das Standard-Menü der Actions ist:

| Action               | Wirkung                                                                                                                       |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------|
| **Attack**           | Mache einen Waffenangriff (oder mehr, mit Extra Attack). Siehe [Combat Actions](combat-actions.md).                           |
| **Aim**              | +2 auf Ranged-Attack-Rolls gegen ein gewähltes Ziel, bis die Line of Sight bricht. Siehe [Combat Actions](combat-actions.md#aim). |
| **Dash**             | Bewege dich in diesem Zug erneut bis zu deiner Speed (insgesamt also 2× Speed).                                               |
| **Disengage**        | Bewegung provoziert für den Rest des Zuges keine Opportunity Attacks mehr.                                                    |
| **Dodge**            | Bis zu deinem nächsten Zug: Angriffe gegen dich haben Disadvantage; du hast Advantage auf DEX Saves.                          |
| **Help**             | Gewähre einem Verbündeten Advantage auf seinen nächsten Ability Check oder Angriff gegen eine Kreatur innerhalb 5 ft von dir. |
| **Hide**             | Mache einen DEX (Stealth) Check, kontrastiert durch die passive Perception der Beobachter. Siehe [Cover](cover.md).           |
| **Ready**            | Wähle einen Auslöser und eine einzelne Action; die Action feuert als Reaction, wenn der Auslöser eintritt.                    |
| **Search**           | Mache einen WIS (Perception) oder INT (Investigation) Check.                                                                  |
| **Use an Object**    | Eine zweite Object Interaction in diesem Zug, oder benutze ein Ausrüstungsstück, das dies erfordert.                          |
| **Suppressive Fire** | Siehe [Combat Actions](combat-actions.md#suppressive-fire). Schließt Attack im selben Zug gegenseitig aus.                    |
| **Use a Feature**    | Aktiviere eine Class-, Designation- oder Training-Program-Fähigkeit, die mit "as an action" aufgeführt ist.                   |

[Combat Actions](combat-actions.md) fügt Feuermodus-Actions (Spray, Riddle, Controlled Burst, Burst Fire) oben drauf
zu diesem Menü hinzu.

## Bonus Actions {#bonus-actions}

Bonus Actions kommen nie aus dem Nichts - sie werden ausdrücklich durch ein Feature, eine Weapon Property oder eine
Fähigkeit gewährt. Du kannst eine ungenutzte Action nicht in eine Bonus Action umwandeln. Häufige Quellen:

- **[Second Wind](../operator-class.md#second-wind)** - HP regenerieren.
- **[Machine Gunner](../designations/machine-gunner.md) Suppressive Fire** - hebt Suppression auf eine Bonus Action an.
- **[Combat Medic](../designations/combat-medic.md) Dash** - Bonus-Action Dash, wenn du deine Action zum Heilen
  genutzt hast.
- Reloads bei bestimmten Waffen, Off-Hand-Angriffe unter Two-Weapon Fighting und diverse Designation Features.

Du kannst mehrere Bonus-Action-Optionen verfügbar haben, aber du kannst pro Zug höchstens eine nutzen.

## Reactions {#reactions}

Eine Reaction ist eine Off-Turn-Antwort pro Runde, die zu Beginn deines nächsten Zuges auffrischt. Sie muss durch ein
Ereignis ausgelöst werden, das du wahrnehmen kannst. Häufige Reactions:

- **Opportunity Attack** - wenn ein Feind deine Reichweite verlässt, ohne zu disengagen, darfst du einen Melee Attack
  machen.
- **Ranged Opportunity Attack** - wenn eine Kreatur, auf die du gezielt hast (Aim), sich mehr als 5 ft bewegt,
  siehe [Combat Actions](combat-actions.md#ranged-opportunity-attack).
- **Dirty Fighting** (Basic Training) - zwinge einem benachbarten Angreifer Disadvantage auf.
- **Get Your Head Down** ([Unit Leader](../designations/unit-leader.md)) - gib einen Leadership Die aus, um einem
  nahen Verbündeten Deckung zu gewähren.
- **Indomitable** ([Operator Class](../operator-class.md#indomitable)) - würfle einen gescheiterten Save neu (nach
  dem Ergebnis).
- Eine ausgelöste Readied Action.

Eine Kreatur mit mehreren verfügbaren Reactions bekommt trotzdem nur eine pro Runde.

## Action Surge {#action-surge}

Einmal pro Short oder Long Rest gewährt [Action Surge](../operator-class.md#action-surge) eine einzelne zusätzliche
Action in deinem Zug. Sie gewährt keine zweite Bonus Action und keine zweite Reaction. Mehrere Anwendungen werden bei
höheren Operator-Levels freigeschaltet.

## Ende des Zuges {#end-of-turn}

Eine Handvoll Effekte lösen sich am Ende des Zuges der handelnden Kreatur auf, statt am Anfang: bestimmte Conditions
ticken, laufender Schaden wird angewendet, ein paar Designation Features zählen runter. Der GM behält den Überblick.

## Vergleich mit klassischem D&D 5E {#compared-to-classic-dd-5e}

- Initiative, das Action-Menü, Bonus-Action/Reaction-Struktur und Free Object Interaction sind alles klassische
  5E-Mechaniken, direkt übernommen.
- Surprised-Kreaturen, die den ersten Zug verlieren, entsprechen den *2024*-5E-Surprise-Regeln, nicht der
  Legacy-Version "keine Actions und keine Reactions in Zug eins, dann Advantage auf Angriffe gegen dich" - dieses
  Kompendium verwendet die saubere Version.
- Die Custom-Actions (Aim, Suppressive Fire, Feuermodi, Ranged Opportunity Attack) sind spezifisch für dieses System;
  der Slot, den sie verbrauchen, ist derselbe.
- Action Surge funktioniert genauso (zusätzliche Action, keine zusätzliche Bonus Action).
