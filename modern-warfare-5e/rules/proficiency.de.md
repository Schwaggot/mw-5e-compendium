---
title: Proficiency
aliases: [ Proficiency Bonus, Expertise, Trained ]
tags: [ rules, character ]
---

# Proficiency

"Proficient" bedeutet, du wurdest formell an der Sache ausgebildet - einer Waffe, einem Rüstungsteil, einem Skill, einem Save, einem Werkzeug.
Wenn du einen d20 für etwas würfelst, für das du Proficient bist, addierst du deinen **Proficiency Bonus** auf den relevanten
Attribut-Modifikator. Fehlende Proficiency ist kein Fail-State; es bedeutet nur, dass du ohne den Bonus würfelst, und bei
spezialisierter Ausrüstung kann es Disadvantage bedeuten.

Im klassischen D&D 5E kommen Proficiencies gebündelt mit Rasse, Klasse und Background. In diesem Compendium kommen fast alle
Proficiencies aus [Training Programs](../training-programs.md) - formalen Lehrgängen, die ein Operator absolviert hat. Ein paar
werden im Voraus durch die [Operator Class](../operator-class.md#starter-training-programs) und durch deinen
[Personality Trait](../personality-traits.md) gewährt.

## Proficiency Bonus {#proficiency-bonus}

Eine feste Zahl, die mit der Operator-Stufe skaliert. Sie stammt aus der
[Operator Class](../operator-class.md#operator-class-table) Tabelle:

| Operator-Stufe | Proficiency Bonus |
|----------------|-------------------|
| 1-4            | +2                |
| 5-8            | +3                |
| 9-12           | +4                |
| 13-16          | +5                |
| 17-20          | +6                |

Identische Skalierung wie im klassischen 5E.

## Where the Bonus Applies {#where-the-bonus-applies}

Du addierst deinen Proficiency Bonus einmal - niemals zweimal (außer bei Expertise, unten) - zu einem d20-Wurf, wenn du in der
Sache, die gewürfelt wird, Proficient bist. Häufige Fälle:

- **Waffenangriffswürfe** mit einer Waffenklasse, in der du Weapons Training hast.
- **Skill Checks** für einen Skill, in dem du Skills Training hast (Perception, Athletics, Stealth usw.).
- **Saving Throws** für ein Attribut, in dem du Save Training hast (siehe [Saving Throws](saving-throws.md)).
- **Tool Checks** für einen Satz, für den du trainiert wurdest (Medic's Kit, Demolitions Kit, Thieves' Tools usw.).
- **Save DCs die du auferlegst**: Wenn eine Fähigkeit von dir eine andere Kreatur zu einem Save zwingt, ist der DC
  `8 + dein Proficiency Bonus + der relevante Attribut-Modifikator`.

Du addierst den Proficiency Bonus **nicht** zur Basis der passiven Perception; du addierst ihn nur, wenn du in Perception trainiert bist. Die
allgemeine Regel "wenn du trainiert bist, taucht der Bonus auf" gilt im gesamten System.

> **Beispiel:** Falke (Operator Stufe 3, Proficiency Bonus +2, DEX 17 → Mod +3) schießt mit seiner M4 auf einen Militanten 60 m die
> Gasse hinunter. Die AC des Militanten ist 14. Falke hat Weapons Training in Assault Rifles, also ist die Rechnung:
>
> - Würfelt **1d20** → **11**.
> - Addiert DEX-Modifikator: 11 + 3 = 14.
> - Addiert Proficiency Bonus: 14 + 2 = **16**.
> - Insgesamt 16 vs AC 14 → **Treffer**.
>
> Der Grenadier der Gruppe (auch DEX +3, aber nur in Pistols und Grenade Launchers trainiert), der die gleiche M4 auf das
> gleiche Ziel abfeuert, hätte die gleiche 11 gewürfelt, +3 addiert und 14 bekommen - knapp mit der AC gleichauf und den Treffer verpasst,
> den Falke gelandet hat.

## Trained vs Untrained {#trained-vs-untrained}

Du kannst trotzdem fast alles untrainiert versuchen - ein unbekanntes Gewehr aufheben, ein Fahrzeug fahren, das du nie gesehen hast, versuchen
ein fremdsprachiges Straßenschild zu lesen.

- **Trained:** Attribut-Modifikator + Proficiency Bonus. Spezialisierte Ausrüstung funktioniert wie vorgesehen.
- **Untrained:** Nur Attribut-Modifikator. Bei spezialisierter Ausrüstung (schwere Waffen, chirurgische Instrumente, Demolitions, bestimmte
  Rüstungen) kann der GM auch Disadvantage auferlegen, den Vorgang verlangsamen oder entscheiden, dass die Aktion ohne Aufsicht
  unmöglich ist.

Spezifische Training Program Tracks entfernen als erste Stufe den Disadvantage - das ist der häufigste Effekt auf Stufe 1
im [Training Programs](../training-programs.md)-Abschnitt.

> **Beispiel:** Gleiches Feuergefecht. Der Militante, den Falke gerade erledigt hat, trug ein russisches PKM, und jetzt will Falke
> den Gurtzuführer nehmen und das Dach unter Feuer nehmen (AC 13 für den Dachschützen in Teildeckung). Er hat kein Weapons
> Training in Heavy Machine Guns, also entscheidet der GM Disadvantage auf den ersten Burst, während er sich an Rückstoß
> und Schussfrequenz gewöhnt.
>
> - Würfelt **2d20, nimmt den niedrigeren** (Disadvantage) → 14 und **6**, nimmt die 6.
> - Addiert DEX-Modifikator: 6 + 3 = **9**. Kein Proficiency Bonus zu addieren.
> - Insgesamt 9 vs AC 13 → **daneben**.
>
> Wäre Falke in Heavy Machine Guns trainiert gewesen, hätte er einen einzelnen d20 gewürfelt (sagen wir eine 14), +3 + 2 = **19** addiert, und
> der Burst hätte das Ziel vom Dach gewischt. Untrainiert kostet ihn sowohl den Bonus als auch den besseren Würfel.

## Expertise {#expertise}

Eine Handvoll fortgeschrittener Training Tracks gewähren **Expertise**. Solange Expertise wirkt, addierst du **das Doppelte deines
Proficiency Bonus** anstelle des normalen einzelnen Bonus. Beispiele:

- Einige [Armor Proficiency](../training/armor-proficiency-programs.md) Stufen gewähren Expertise auf einen bestimmten Save, während
  man diese Rüstungsklasse trägt.
- Höhere Stufen des [Physical Skills Training](../training/physical-fitness-programs.md) können eine bestehende Skill
  Proficiency auf Expertise aufwerten.

Expertise stapelt sich niemals mit sich selbst - wenn zwei Quellen beide Expertise auf den gleichen Wurf gewähren, verdoppelst du trotzdem nur einmal.

> **Beispiel:** Doc (Operator Stufe 5, Proficiency Bonus +3, CON 14 → Mod +2) trägt einen schweren Plattenträger und hat Heavy
> Armor Training auf einer Stufe, die Expertise auf CON Saves gewährt, während man Heavy Armor trägt. Eine Sprengladung geht
> im Nebenraum los - der GM ruft einen DC 14 CON Save gegen die Druckwelle aus (voller Schaden bei Fehlschlag, halber bei Erfolg).
>
> - Würfelt **1d20** → **8**.
> - Addiert CON-Modifikator: 8 + 2 = 10.
> - Addiert **doppelten** Proficiency Bonus (Expertise): 10 + 6 = **16**.
> - Insgesamt 16 vs DC 14 → **Save**, nimmt halben Schaden.
>
> Ohne Expertise (einzelner Proficiency Bonus) hätte der gleiche Wurf 13 ergeben - einen unter dem DC, voller Schaden.
> Ohne irgendein Save Training in CON wäre es eine 10 flat gewesen, weit darunter.

## How To Read Your Sheet {#how-to-read-your-sheet}

Für jeden d20-Wurf gehe ihn in dieser Reihenfolge durch:

1. Identifiziere das Attribut (der GM sagt "mach einen DEX Save", "WIS Check" usw.).
2. Addiere den Attribut-Modifikator aus [Attributes](attributes.md).
3. Bist du in der spezifischen Sache trainiert? Wenn ja, addiere Proficiency Bonus. Wenn Expertise gilt, verdopple ihn.
4. Addiere alle situativen Boni (Aim, Deckung, Training-Programm-Vorteile, Gear-Tags).
5. Vergleiche mit dem DC oder AC, den der GM nennt.

> **Beispiel:** Falke (Stufe 3, Proficiency Bonus +2, STR 11 → Mod +0) klettert unter Feuer einen Maschendrahtzaun hoch, um
> sich vom Feind zu lösen. Der GM ruft einen DC 13 STR (Athletics) Check aus.
>
> 1. Attribut: STR.
> 2. STR-Modifikator: +0.
> 3. Trainiert in Athletics, also addiere Proficiency Bonus +2.
> 4. Er trägt einen vollen Assault-Rucksack - der GM entscheidet Disadvantage.
> 5. Würfelt **2d20, nimmt den niedrigeren**: 17 und **9**, nimmt die 9.
> 6. 9 + 0 (STR) + 2 (Proficiency) = **11**. Vs DC 13 → **Fehlschlag** um 2. Er bleibt am Draht hängen und der GM lässt ihn
     > den Rucksack fallen lassen oder einen Zug damit verbringen, sich zu befreien.
>
> Hätte er Physical Skills Training hoch genug, um Expertise in Athletics zu bekommen, wäre Schritt 3 +4 statt
> +2: 9 + 0 + 4 = **13**, genau der DC, und er überwindet den Zaun sauber. Der gleiche Würfelwurf, zwei verschiedene Ergebnisse,
> getrennt durch eine Training-Stufe.

## Compared to Classic D&D 5E {#compared-to-classic-dd-5e}

- Die Zahl des Proficiency Bonus und die Skalierung sind identisch.
- Die Quelle der Proficiencies ist anders: Training Programs ersetzen "Klasse gewährt dir diese Proficiencies".
- "Proficient" wird in diesem Compendium manchmal "trained" genannt - gleiche Bedeutung.
- Expertise funktioniert gleich (doppelter Bonus), ist aber seltener und situativer - meist an das Tragen der richtigen
  Rüstung oder das Abschließen eines fortgeschrittenen Tracks gebunden.
