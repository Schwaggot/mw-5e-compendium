---
title: Advantage und Disadvantage
aliases: [ Advantage, Disadvantage, Adv, Disadv ]
tags: [ rules, character ]
---

# Advantage und Disadvantage

Manche Situationen sind so günstig - oder so ungünstig -, dass das System die Würfel entsprechend sprechen lässt.
**Advantage** bedeutet, du würfelst **2d20 und nimmst den höheren**. **Disadvantage** bedeutet, du würfelst **2d20
und nimmst den niedrigeren**. Der Mechanismus taucht bei Angriffswürfen, [Ability Checks](ability-checks.md) und
[Saving Throws](saving-throws.md) auf - überall dort, wo ein einzelner d20 zählt.

Dies ist der am häufigsten verwendete "situative" Mechanismus im Kompendium. Die meisten Trainingsprogramme gewähren
oder entfernen ihn. Die meisten Ausrüstungsstücke ohne flachen Zahlenbonus erzeugen oder kontern ihn. Die meisten
Conditions verleihen ihn Angreifern oder zwingen ihn der betroffenen Kreatur auf.

## Wie man würfelt {#how-to-roll}

- **Advantage:** Würfle 2d20. Nimm den höheren Würfel. Addiere Modifikatoren wie gewohnt.
- **Disadvantage:** Würfle 2d20. Nimm den niedrigeren Würfel. Addiere Modifikatoren wie gewohnt.

Du addierst Modifikatoren (Ability-Mod, Proficiency Bonus, situative Boni) **nach** der Auswahl des Würfels, nicht zu
beiden Würfeln.

## Stacking-Regel {#stacking-rule}

Advantage und Disadvantage **stapeln sich nie mit sich selbst**. Eine Quelle von Advantage ist genauso wie fünf
Quellen von Advantage - du würfelst immer 2d20 und nimmst den höheren, nicht mehr. Dasselbe gilt für Disadvantage.

Wenn du **mindestens eine Quelle Advantage und mindestens eine Quelle Disadvantage** zur gleichen Zeit hast, heben
sie sich komplett auf - du würfelst einen normalen 1d20, egal wie viele von jedem du gestapelt hattest. Es gibt kein
"Netto-Advantage" oder "leichtes Disadvantage". Es ist binär: Advantage, normal oder Disadvantage.

> **Beispiel:** Falke (DEX +3, ausgebildet in Assault Rifles, Proficiency +2) schießt auf einen Kämpfer (AC 14), der
> durch einen Beinschuss [Slowed](conditions.md) ist - das gibt Falke Advantage auf den Angriff. Aber der Kämpfer ist
> mit einem freundlichen Schützen gepackt, also feuert Falke auch [firing into melee](combat-actions.md) -
> Disadvantage. Je eine Quelle: sie heben sich komplett auf. Er würfelt einen flachen **1d20 → 13**, +3 +2 = **18**
> gegen AC 14 → Treffer. Drei weitere Advantage-Quellen oben drauf hätten den Wurf nicht geändert - jedes Disadvantage
> neutralisiert jedes Advantage.

## Interaktion mit Crits {#interaction-with-crits}

Eine natürliche 20 auf einem der Würfel unter Advantage löst weiterhin einen Critical Hit aus. Eine natürliche 1 auf
einem der Würfel unter Disadvantage löst weiterhin jeden "Fumble"- oder Natural-1-Effekt aus (z.B. Feuer ins Handgemenge,
bestimmte Weapon Properties).

Unter Advantage ist die Wahrscheinlichkeit, eine 20 zu würfeln, etwa doppelt so hoch; unter Disadvantage ist die
Wahrscheinlichkeit, eine 1 zu würfeln, etwa doppelt so hoch.

## Interaktion mit Passive Checks {#interaction-with-passive-checks}

Bei Passive Checks (passive Perception, passive Investigation) **addiert Advantage +5** auf den Wert und
**Disadvantage zieht 5 ab**. Sie stapeln sich ebenfalls nicht: die Spanne beträgt maximal ±5.

## Häufige Quellen {#common-sources}

Es gibt keine Masterliste - die Regel lautet "der GM benennt es" - aber die wiederkehrenden Muster sind:

**Advantage auf dich (gut für dich)**

- Ein benachbarter Verbündeter gewährt [Help](ability-checks.md#help-tools-and-working-together).
- Ein Ziel ist [Slowed](conditions.md), Restrained oder anderweitig gegen deine Angriffe beeinträchtigt.
- Mehrere Trainingsprogramme (Awareness, bestimmte Tactical, Combat Designation Features).
- Der `magnified` Optic-Tag auf Long-Range Perception Checks.
- Surprise-Runde, Angriff aus Concealment oder andere Szenarien mit Positionsvorteil.

**Disadvantage auf dich (schlecht für dich)**

- Du benutzt Ausrüstung, in der du kein Training hast.
- Du bist [Crouched](conditions.md) und zielst auf lange Distanz, [Shaken](conditions.md), Frightened oder Poisoned.
- Du greifst durch teilweise Verdunkelung, Rauch an oder hast [Suppressive Fire](combat-actions.md#suppressive-fire)
  auf dir.
- Du feuerst ins Handgemenge.
- Du trägst Rüstung mit dem "Disadvantage"-Stealth-Modifier und versuchst, leise zu sein.
- Du bist Off-Hand im Two-Weapon Fighting ohne das entsprechende Basic Training.

**Disadvantage, das mit dem richtigen Training Program verschwindet**

- Der Level-1-Effekt der meisten Training Programs ist "entferne Disadvantage auf X". Dies ist der häufigste einzelne
  Level-1-Perk im System. Siehe [Training Programs](../training-programs.md).

## Vergleich mit klassischem D&D 5E {#compared-to-classic-dd-5e}

- Die Mechanik ist identisch: 2d20 höheren/niedrigeren nehmen, kein Stacking, jedes Disadvantage neutralisiert jedes
  Advantage zu einem flachen d20.
- ±5 auf Passive Checks funktioniert gleich.
- Die Quellen sind im Flavor anders - viele Optic-Tags, Suppression, Training-Program-Toggles - aber die Mathematik
  ist unverändert.
