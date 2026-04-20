---
title: Stealth und Verstecken
aliases: [ Stealth, Verstecken, Versteckt, Schleichen, Entdeckung ]
tags: [ rules, character, combat ]
---

# Stealth und Verstecken

Die meisten Operationen beginnen damit, dass jemand ungesehen bleibt. Stealth ist in diesem System ein Wettstreit zwischen dem DEX (Stealth) Check
einer aktiv-versteckenden Kreatur und der passiven (oder aktiven) Perception der beobachtenden Kreatur. Die Mechanik ist aus
klassischem 5E übernommen; die Homebrew-Schicht ist die Ausrüstung, die dich lauter macht (schwere Rüstung, bestimmte Rucksäcke) oder leiser (Covert
Training, bestimmte Optiken auf der Seite des Beobachters).

## When You Can Hide {#when-you-can-hide}

Du kannst dich nicht verstecken, während eine beobachtende Kreatur dich klar sehen kann. Um die [Hide Action](combat-turn.md#actions) zu versuchen,
musst du mindestens eines der folgenden relativ zu diesem Beobachter sein:

- **Stark verdeckt** von ihnen - Rauch, tiefe Dunkelheit, dichtes Unterholz, um eine Ecke.
  Siehe [Sicht und Licht](vision-and-light.md).
- **Hinter Deckung**, die ihre Sichtlinie vollständig bricht ([Drei-Viertel](cover.md)-Deckung oder besser, um vollständig
  dahinter zu verschwinden).

[Covert Training Level 3](../training/covert-programs.md) lockert das: Du kannst dich verstecken, während du nur **leicht verdeckt**
vom Ziel bist (Gedämpftes Licht, leichtes Laubwerk, leichter Nebel). Das ist es, was einem Scharfschützen-Beobachter-Paar erlaubt, in die Baumreihe
zu verschwinden, wo eine untrainierte Kreatur immer noch entdeckt würde.

## Making the Roll {#making-the-roll}

Die Hide Action ist ein `DEX (Stealth) Check`. Das Ergebnis wird von der **passiven Perception** jedes Beobachters contested, es sei denn,
der Beobachter würfelt aktiv. Siehe [Ability Checks](ability-checks.md#contested-checks).

- Ihre passive Perception übertreffen → du bist **Hidden** vor ihnen.
- Gleichstand oder niedriger → sie bemerken dich. Gleichstände gehen an den Verteidiger (den Beobachter).
- Ein Beobachter, der aktiv Perception würfelt, verwendet das gewürfelte Ergebnis anstelle seines passiven Werts.

Dein Versteckt-Status ist **pro Beobachter**: Du kannst vor einem Wachposten versteckt sein, während ein anderer mit einem
besseren Winkel dich klar sieht. Der GM verfolgt, wer weiß, dass du da bist.

## What Hidden Gets You {#what-hidden-gets-you}

Während du vor einer Kreatur versteckt bist:

- **Angriffe gegen diese Kreatur haben Advantage** (sie können ihren DEX-Bonus auf AC gegen einen Angriff, den sie nicht
  kommen sehen, abstrakt nicht anwenden; mechanisch verwendet das System Advantage als Sammelbegriff).
- **Sie haben Disadvantage, zurück anzugreifen** (sie wissen nicht genau, wo du bist).
- Du kannst dich aus der Deckung und zurück bewegen, ohne Stealth erneut zu würfeln, *es sei denn, du tust etwas, das dich enthüllen würde*.

Du hörst auf versteckt zu sein, wenn:

- Du einen Angriff machst (für alle enthüllt, die den Angriff wahrnehmen
  konnten). [Covert Training Level 2](../training/covert-programs.md) lässt dich versteckt bleiben, wenn dein Fernkampfangriff fehlschlägt.
- Du über einem Flüstern sprichst, eine nicht schallgedämpfte Waffe abfeuerst oder auf andere Weise ein klares Geräusch machst.
- Du dich in eine Position bewegst, in der ein Beobachter dich klar sehen kann.
- Der Beobachter aktiv dein Gebiet durchsucht und dein früheres Stealth-Ergebnis übertrifft.

## Modifiers To Stealth {#modifiers-to-stealth}

- **Rüstung mit dem Disadvantage Stealth Modifier** ([Armor](../armor.md)): Disadvantage auf jeden Stealth Check beim
  Tragen. Die meisten Medium- und alle Heavy-Träger tragen dieses Tag.
- **[Crouched](conditions.md) oder Liegend**: GM kann Advantage auf Stealth gewähren, wenn mit Deckung kombiniert.
- **Schnelle Gangart** beim Patrouillieren: GM kann Disadvantage auf Stealth auferlegen (du bewegst dich schneller als deine Schritte
  es dir erlauben, leise zu sein).
- **Suppressed Feuerwaffen**: besiegen die Entdeckung nicht automatisch, reduzieren aber stark den Radius, in dem ein Schuss dich enthüllt - GM
  Entscheidung.
- **Operator mit [Covert Training Level 1](../training/covert-programs.md)**: trainiert in Stealth, addiert Proficiency
  Bonus.

## Group Stealth {#group-stealth}

Wenn sich das ganze Element zusammen bewegt, kann der GM einen **Group Stealth Check** (
siehe [Ability Checks](ability-checks.md#group-checks)) verlangen.
Wenn die Hälfte oder mehr der Squad die passive Perception des Beobachters übertrifft, ist das ganze Element versteckt. Das laute
Mitglied der Squad kann von seinen leisen Teamkollegen mitgetragen werden, aber nur soweit - ein klappernder Kit auf einer Vier-Mann-Patrouille ist
handhabbar; zwei sind ein Tell.

## Surprise {#surprise}

Wenn deine ganze Seite versteckt ist, wenn der Kampf beginnt, ist die unwissende Seite in der ersten Runde **Surprised** - sie können sich nicht
bewegen, keine Aktion ausführen oder eine Reaction nehmen. Siehe [Combat Turn - Surprise](combat-turn.md#surprise). Mehrere
[Covert Training](../training/covert-programs.md) Features richten sich an die Surprise-Runde aus, einschließlich Auto-Crits auf
den ersten Treffer.

## Examples {#examples}

> **Beispiel - Basis-Hide:** Falke (DEX +3, trainiert in Stealth, Proficiency +2) duckt sich hinter eine Ziegelmauer und würfelt
> einen DEX (Stealth) Check: **1d20 → 12**, +3 +2 = **17**. Der patrouillierende Wachposten hat passive Perception 13. 17 vs 13 →
> Falke ist vor diesem Wachposten versteckt. Er bewegt sich 20 ft entlang der Mauer zu einer neuen Feuerposition; die Sichtlinie des Wachpostens
> kreuzt ihn nie, also bleibt er versteckt.

> **Beispiel - durch einen Angriff enthüllt:** Aus dem Versteck macht Falke einen Einzelschuss auf den Wachposten. Er hat Advantage vom
> Verstecktsein. Er würfelt **2d20 → 9 und 16**, nimmt die 16, +3 +2 = **21** vs AC 13 → Treffer. Er ist nun jeder
> Kreatur enthüllt, die den Schuss wahrnehmen konnte. (Hätte er Covert Training Level 2 *und* verfehlt, wäre er versteckt geblieben.)

> **Beispiel - Heavy Armor Stealth:** Ein Teamkollege in einer Medium Flak mit Shoulders (Disadvantage on Stealth) versucht den
> gleichen Hide-Versuch gegen den gleichen DC 13 Wachposten. Er hat DEX +1, untrainiert in Stealth. Er würfelt **2d20 → 14 und 6**,
> nimmt die 6 (Disadvantage), +1 = **7** vs 13 → entdeckt. Er hätte nicht als Erster gehen sollen.

## Compared to Classic D&D 5E {#compared-to-classic-dd-5e}

- Der DEX (Stealth) vs passive Perception Wettstreit, der Pro-Beobachter-Versteckt-Zustand und die "Angriff enthüllt dich"-Regel sind
  alle klassisches 5E.
- Surprise übernimmt die *2024 5E* Version (verliert die erste Runde komplett), passend zu [Combat Turn](combat-turn.md#surprise).
- Das Compendium hat keinen Pass Without Trace Zauber; die entsprechende Rolle wird von Covert Training Programs und
  Nachtzyklus-Ausrüstung (Rauch, NVG-Asymmetrie, Schalldämpfer) ausgefüllt.
- Heavy-Armor-Stealth-Strafen sind härter als im klassischen 5E: Viele Medium-Träger auferlegen ebenfalls Disadvantage, nicht nur
  Heavy.
