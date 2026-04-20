---
title: Saving Throws
aliases: [ Saves, Save, Save DC ]
tags: [ rules, combat ]
---

# Saving Throws

Ein **Saving Throw** (oder "Save") ist ein d20-Wurf, den dein Operator macht, um *zu vermeiden oder zu reduzieren*, dass etwas Schlimmes mit
*ihm* passiert - ein Flashbang, der im Raum zündet, eine Tür, die nach innen gesprengt wird, Gas, das den Korridor füllt, ein Verhörer, der dich
bricht. Anders als ein Angriffswurf oder ein Skill Check entscheidest du nicht selbst, einen Save zu machen; der GM sagt dir, du sollst einen würfeln, weil
dir etwas angetan wird.

Im klassischen D&D 5E werden Saves gegen Zauber gewürfelt. Hier werden sie gegen Sprengungen, Gas, Stürze, Suppression, Furcht
und Nötigung gewürfelt. Die Mechanik ist die gleiche.

## How a Save Works {#how-a-save-works}

1. Der GM nennt den Save: "Mach einen DEX Save" oder "CON Save gegen das Gas."
2. Der GM nennt einen **Save DC** - meist 10 (einfach), 12-13 (moderat), 15-16 (schwer), 18+ (brutal). Gefahren aus Ausrüstung und
   Fähigkeiten listen ihren DC explizit auf.
3. Du würfelst `1d20 + den relevanten Attribut-Modifikator`. Wenn du in diesem Save trainiert bist, addiere zusätzlich
   deinen [Proficiency Bonus](proficiency.md).
4. Gesamt ≥ DC = Erfolg. Gesamt < DC = Fehlschlag. Viele Effekte haben auch eine "halb bei erfolgreichem Save"-Klausel; der GM wird
   das sagen.

> **Beispiel:** Falke (Operator Stufe 3, Proficiency Bonus +2, DEX 17 → Mod +3, Save Training in DEX) lehnt sich aus
> einer Marktstand-Tür, als eine Splittergranate neben ihn rollt. Der GM ruft einen DC 14 DEX Save aus - voller Schaden bei
> Fehlschlag, halber bei Erfolg.
>
> - Würfelt **1d20** → **12**.
> - Addiert DEX-Modifikator: 12 + 3 = 15.
> - Trainiert in DEX Saves, addiert Proficiency Bonus: 15 + 2 = **17**.
> - Insgesamt 17 vs DC 14 → **Save**, nimmt halben Schaden.
>
> Ein Teamkollege, der in dieselbe Tür springt, auch DEX +3 aber ohne Save Training in DEX, hätte die gleiche 12
> gewürfelt für eine Gesamtsumme von **15** - immer noch ein Save, aber nur um 1. Ein Militanter im Stand (DEX +1, untrainiert) würfelt 12 + 1 =
> **13**, knapp unter dem DC, und kassiert vollen Schaden.

## The Six Saves {#the-six-saves}

Jedes der sechs [Attributes](attributes.md) hat einen Save. Das Attribut, das der Save verwendet, ist das Attribut, das *dir helfen würde,
den Effekt zu vermeiden*, nicht das Attribut dessen, der ihn verursacht.

| Save    | Was er abdeckt                                                                                                 | Beispiele                                                                                                        |
|---------|----------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| **STR** | Bewegung, Griff, Stoß oder körperlichem Festhalten widerstehen.                                                | Eine Sprengladung wirft dich vom Laufsteg; ein Gegner versucht, dich aus der Deckung zu werfen.                  |
| **DEX** | Einem plötzlichen Flächeneffekt ausweichen, sich ducken, aus dem Weg drehen.                                   | Splittergranate landet zu deinen Füßen; ein Fahrzeug streift deine Position; ein Flashbang zündet im Raum.       |
| **CON** | Schaden am Körper selbst aushalten - Gift, Krankheit, Schock, Suppression aus der Nähe, das Schlimmste einer Explosion. | Tränengas füllt den Raum; ein Stim treibt dich über sichere Grenzen; du nimmst eine schwere Druckwelle.  |
| **INT** | Verwirrung, Täuschung, Illusion, Desorientierung oder technischer Kompromittierung widerstehen.                | Ein lautes Desorientierungsgerät bringt deinen Raumüberblick durcheinander; ein feindlicher Netzwerk-Probe zielt auf deine Ausrüstung. |
| **WIS** | Nerven und Situationsbewusstsein behalten. Der Furcht-Save.                                                    | Die Shaken-Skala ([Conditions](conditions.md#shaken)); ein Verhörer arbeitet an deiner Entschlossenheit; ein Horror-Moment. |
| **CHA** | Angriffen auf dein Selbstbild widerstehen - Langform-Nötigung, Cover brechen, tiefe Manipulation.              | Ein Verhörer versucht über Stunden deine Cover-Identität zu brechen; erzwungene Narrative unter Druck.           |

## Save Training {#save-training}

Wie alle Proficiencies in diesem Compendium kommt Save Proficiency aus einem [Training Program](../training-programs.md) -
speziell dem **Save Training** Track. Auf 1. Stufe gewährt die
[Operator Class](../operator-class.md#starter-training-programs)
Save Training Level 1 in **Strength** und **Dexterity** kostenlos, analog zum klassischen 5E Fighter-Chassis.

Jede Save Training Stufe, die du in einem gegebenen Save hast, addiert deinen Proficiency Bonus zu diesem Save. Höhere Stufen des Tracks stapeln (oder
relevante Armor / Mental Fitness Programme) können Expertise gewähren, was den Proficiency Bonus verdoppelt -
siehe [Proficiency](proficiency.md#expertise).

> **Beispiel:** Gleiches Feuergefecht, zehn Minuten später. Falke (CON 11 → Mod +0, **nicht** in CON Saves trainiert) räumt einen
> Hinterraum, als ein CS-Gas-Kanister abbrennt. Der GM ruft einen DC 13 CON Save gegen das Gas aus - Fehlschlag bedeutet eine Stufe
> Disadvantage auf seine nächste Aktion und eine Runde Husten.
>
> - Würfelt **1d20** → **11**.
> - Addiert CON-Modifikator: 11 + 0 = **11**. Kein Proficiency Bonus zu addieren.
> - Insgesamt 11 vs DC 13 → **Fehlschlag**. Mit tränenden Augen stolpert er zurück zur Tür.
>
> Hätte Falke Save Training Level 1 in CON bei einer späteren Operator-Training-Wahl genommen, hätte der gleiche Wurf
> 11 + 0 + 2 = **13** ergeben - genau den DC, Save. Der einzelne Proficiency Bonus ist der Unterschied zwischen den Raum zu halten
> und ihn wieder aufzugeben.

## Save DC of Effects You Impose {#save-dc-of-effects-you-impose}

Wenn etwas *das du* tust eine andere Kreatur zu einem Save zwingt (ein Flashbang den du geworfen hast, ein Takedown-Manöver, ein Designation-
Feature), ist der DC, gegen den das Ziel würfelt:

`Save DC = 8 + dein Proficiency Bonus + der relevante Attribut-Modifikator`

Das "relevante Attribut" wird von der Quelle des Effekts benannt - meist DEX für geworfene Munition, CHA für Befehls- und
Einschüchterungseffekte, INT für technische Angriffe.

> **Beispiel:** Falke (Proficiency Bonus +2, DEX +3) entsichert einen Flashbang und wirft ihn durch die Tür eines kleinen
> Raumes. Der Save des Flashbangs ist an die DEX des Werfers gekoppelt, also ist der DC:
>
> `8 + 2 (Falkes Proficiency Bonus) + 3 (Falkes DEX-Modifikator) = DC 13`
>
> Zwei Militante sind drinnen.
>
> - Militanter A (CON +1, untrainiert): würfelt **1d20** → **9**. 9 + 1 = **10** vs DC 13 → **Fehlschlag**, betäubt für eine Runde.
> - Militanter B (CON +2, untrainiert): würfelt **1d20** → **15**. 15 + 2 = **17** vs DC 13 → **Save**, kein Effekt.
>
> Wenn Falke auf Stufe 5 aufsteigt (Proficiency Bonus +3), würde der gleiche Flashbang einen DC 14 Save auferlegen - und Militanter As 10
> würde immer noch mit dem gleichen Abstand fehlschlagen, während Militanter Bs 17 immer noch bestehen würde. Höhere Proficiency weitet den Abstand
> auf den Grenzwürfen, nicht auf den offensichtlichen.

## Compared to Classic D&D 5E {#compared-to-classic-dd-5e}

- Die Formel d20 + Attribut-Mod (+ Proficiency wenn trainiert) ≥ DC ist identisch.
- Sechs Saves, einer pro Attribut - gleich wie im klassischen 5E.
- Wo klassisches 5E Saves meistens gegen Zauber nutzt, nutzt dieses Spiel sie gegen moderne Gefahren: Sprengstoffe, Gas,
  Suppression, Verhör und Desorientierung.
- Klassengebundene Save-Proficiencies werden zu Save Training Programs. Jeder Operator startet mit trainiertem STR und DEX und kann
  die anderen beim Aufstieg erwerben.
- Death Saves funktionieren wie im klassischen 5E (siehe [Hit Points - Going Down at 0 HP](hit-points.md#going-down-at-0-hp) dafür wie
  das Sterben in diesem Compendium gehandhabt wird).
