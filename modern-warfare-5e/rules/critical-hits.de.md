---
title: Critical Hits
aliases: [ Crit, Critical Hit, Crit Range, Auto-Crit, Critical Shot ]
tags: [ rules, combat ]
---

# Critical Hits

Ein **Critical Hit** würfelt zusätzlichen Schaden und repräsentiert einen Schuss, der wirklich dort gelandet ist, wo
es zählt: durch den Sehschlitz eines Helms, zwischen Platten, in die Oberschenkelarterie. Die Grundmechanik ist
klassisches 5E (eine natürliche 20 verdoppelt deine Schadenswürfel), aber jede Waffe im Kompendium gibt ihre eigene
**Crit Range** an, die das Trigger-Fenster erweitern kann. Mehrere Training Programs und Designation Features
erlauben es dir, die Würfel zu überspringen und einen Treffer einfach direkt als Crit zu deklarieren.

## Wie Crits ausgelöst werden {#how-crits-trigger}

Schau in die Spalte **Misfire/Crit** im Tabelleneintrag der Waffe (z.B. eine AI AW listet `1/19-20`). Der rechte Wert
ist die **Crit Range**:

- Ein natürlicher Angriffswurf **gleich oder über** der Crit Range ist ein Critical Hit, *sofern der Angriff auch die
  AC des Ziels nach Modifikatoren übertrifft*. Eine natürliche 20 trifft immer unabhängig von der AC, aber andere
  Crit-Range-Zahlen nicht - sie kritten nur auf Treffern.
- Die meisten Präzisionswaffen kritten auf **19-20**; Magnum-/Anti-Materiel-Waffen (z.B. .50-BMG-Bolzengewehre)
  kritten auf **18-20**; manche Pistolen kritten nur auf **20**. Lies die Tabelle.

Die andere Eigenschaft, die du kennen solltest, ist **Misfire**, *links* vom Schrägstrich. Ein natürlicher Wurf gleich
oder unter dem Misfire-Wert scheitert automatisch und löst die Misfire-Tabelle in
[Weapon Properties](weapon-properties.md) aus. Crit Range und Misfire Range sind unabhängig: eine einzelne Waffe hat
beide Fenster.

## Was ein Crit bewirkt {#what-a-crit-does}

Bei einem Critical Hit **würfelst du alle Schadenswürfel zweimal** und addierst sie zusammen. **Dann addierst du die
Modifikatoren einmal.** Statische Boni (STR/DEX, Accurate, Munitionsboni) werden nicht verdoppelt.

> **Beispiel:** Falkes M4 macht `2d8` Schaden. Er würfelt einen Treffer und der natürliche Würfel war eine 19
> (Crit Range 19-20). Er würfelt die Schadenswürfel **zweimal**: `2d8 → 11`, zweites `2d8 → 9`. Würfel gesamt = 20,
> plus seinen +3 DEX-Modifier = **23 damage**. Ein normaler Treffer auf demselben Wurf wäre `2d8 + 3 → 11 + 3 = 14`
> gewesen.

Die Verdopplung gilt nur für die Würfel des *Angriffs*, der gekrittet hat. Seiteneffekt-Schaden vom selben Treffer
(Blutung, die er verursacht, laufende Ignite-Ticks, etc.) wird nicht verdoppelt.

## Kopfschüsse kritten immer {#headshots-always-crit}

Wenn du einen [Target Zone](damage-types.md#target-zones) Kopfschuss ansagst (-10 zum Treffen), wird der Treffer als
Critical behandelt - keine Crit Range erforderlich. Wenn der natürliche Würfel *zusätzlich* eine 20 war, werden die
Schadenswürfel **verdreifacht** statt verdoppelt. Dies ist der einzige "dreifache Würfel"-Trigger im System ohne ein
Feature, das ihn gewährt.

> **Beispiel:** Falke sagt einen Kopfschuss mit derselben M4 an. Er würfelt **1d20 → 17**, +3 (DEX) +2 (Prof) -10
> (Head Zone) = **12** gegen AC 13 → Fehlschlag. Anderer Schuss: er würfelt eine **natürliche 20**, die immer trifft.
> Kopfschuss + Nat 20 = dreifache Schadenswürfel. `2d8 × 3 → 5+7+3+1+8+6 = 30`, +3 DEX = **33 damage**. Was auch
> immer den Helm trug, ist kein Problem mehr.

## Crits unter Advantage und Disadvantage {#crits-under-advantage-and-disadvantage}

- Eine natürliche Zahl in der Crit Range auf **einem der Würfel** unter [Advantage](advantage.md) löst den Crit aus.
- Eine natürliche Zahl in der Crit Range auf dem gewählten Würfel unter Disadvantage löst den Crit aus. Der nicht
  gewählte hohe Würfel zählt nicht - er ist nicht das Ergebnis.

Das bedeutet, Advantage verdoppelt deine Crit-Chance ungefähr; Disadvantage halbiert sie ungefähr.

## Auto-Crits und andere Quellen {#auto-crits-and-other-sources}

Mehrere Features umgehen die Würfel und kritten bei Kontakt. Die häufigsten:

- **[Marksman - Critical Shot](../designations/marksman.md)** (3rd-Level Combat Designation Feature): als Action,
  feuere einen Bolzengewehr- oder Einzelschussgewehr-Schuss. Wenn er trifft, ist er automatisch ein Critical Hit.
  Wenn der darunterliegende Wurf *ebenfalls* in die Crit Range fiel, werden die Würfel verdreifacht statt verdoppelt.
- **[Covert Training Level 3 (Ambush)](../training/covert-programs.md)**: dein erster Treffer auf eine Surprised
  Kreatur ist automatisch ein Critical Hit. Ein normal gewürfelter Crit darauf wird zu maximalem Schadenswürfel statt
  verdoppelt.
- **Präzisionsschlag auf ein am Boden liegendes Ziel**: ein Treffer innerhalb 5 ft einer bewusstlosen Kreatur durch
  eine Melee- oder Einzelschusswaffe wird nach GM-Ermessen als Crit behandelt.

Wenn zwei Auto-Crit-Quellen auf demselben Angriff stapeln (selten), ist der Angriff ein einzelner Crit, nicht
"Doppel-Crit" - die Upgrades greifen nur, wenn die Quelle es explizit sagt (Critical Shots "dreifach, wenn
natürlicher Crit" oder Ambushs "max Schaden, wenn natürlicher Crit").

## Crits bei am Boden Liegenden {#crits-while-downed}

Jeder Crit, der auf einer Kreatur bei 0 HP landet, kostet sie **2 Death Save Failures** statt 1. Ein Crit aus kurzer
Distanz kann einen Verwundeten von "noch am Saven" zu tot in einem einzigen Treffer bringen.
Siehe [Hit Points](hit-points.md#damage-while-downed).

## Vergleich mit klassischem D&D 5E {#compared-to-classic-dd-5e}

- Der Kern "natürliche 20 → Crit, Würfel verdoppeln, Modifikatoren einmal addieren" ist identisch mit klassischem 5E.
- Die konfigurierbare Crit Range pro Waffe (z.B. 18-20 auf schweren Magnums, 20 auf kleinen Pistolen) ist Homebrew -
  klassisches 5E erweitert dies nur über Class Features (Champion Fighter).
- Auto-Crit-on-Headshot ist Homebrew, kombiniert mit dem Target-Zone -10 Malus.
- Dreifache Schadenswürfel existieren, sind aber selten: Nat-20-Kopfschuss oder ein Feature, das explizit auf einen
  natürlichen Crit stapelt (Critical Shot, Ambush).
- Crits bei 0 HP, die 2 Death Save Failures kosten, entspricht klassischem 5E.
