---
title: Schadensarten
aliases: [Damage, DR, Stress, Subdual, Target Zones]
tags: [rules, damage]
---

# Schadensarten

## Damage Reduction {#damage-reduction}

Einige Ausrüstungen gewähren Damage Reduction (DR). Reduziert den Schaden eines einzelnen Treffers um den angegebenen Betrag. DR kann typisiert sein.

## Schadensarten {#damage-types}

- **Acid (Säure):** -
- **Bludgeoning (Wucht):** Kann vor dem Angriff als Subdual deklariert werden.
- **Cold (Kälte):** DC für CON Save oder Slowed 1d4 Runden.
- **Electrical (Elektrisch):** DC für CON Save oder Paralyzed 1d4 Runden.
- **Fire (Feuer):** Entzündet Brennbares; Action zum Löschen.
- **Flash:** DC für CON Save oder Blinded 1d4 Runden.
- **Force (Energie):** Zählt immer zusätzlich als Subdual.
- **Piercing (Stich):** Bei Red/Orange Triage würfle d100: 01-25 Major Bleed, 26-75 Bleed.
- **Poison (Gift):** DC für CON Save oder Poisoned.
- **Radiation:** DC für CON Save oder Poisoned.
- **Slashing (Hieb):** Wie Piercing, würfle für Bleed.
- **Sound:** DC für CON Save oder Deafened 1d4 Runden.
- **Stun:** DC für CON Save oder Stunned 1d4 Runden.
- **Stress:** Separat akkumulierter Schaden; siehe unten.

## Stressschaden {#stress-damage}

- Stressschaden pro Treffer = zugefügter Schaden minus Wisdom Score des Ziels (min 1).
- Stress reduziert HP nicht; er akkumuliert.
- Jedes Mal, wenn der Gesamt-Stress ein Vielfaches des Wisdom Score überschreitet, macht das Ziel einen Wisdom Save.
  DC und Condition hängen vom erreichten Vielfachen ab.

| WIS Multiple | DC | Condition | Short Rest Heilung | Long Rest Heilung |
|--------------|----|-----------|--------------------|-------------------|
| 1× WIS       | 12 | Shaken 1  | 1d6 + WIS          | 1d12 + WIS        |
| 2× WIS       | 15 | Shaken 2  | 1d4 + WIS          | 1d8 + WIS         |
| 3× WIS       | 20 | Shaken 3  | 1                  | 1d4 + WIS         |
| 4× WIS       | 25 | Shaken 4  | Medizinische Hilfe | 1 + WIS           |
| 5× WIS       | 30 | Broken    | Medizinische Hilfe | Medizinische Hilfe |

Siehe [Shaken](conditions.md#shaken) für die Condition-Effekte.

## Subdual (Nicht-Tödlich) {#subdual-non-lethal}

- Wirkt sich nicht auf HP aus.
- Wenn Subdual-Schaden den CON-Modifier des Ziels übersteigt, ist dieser Wert die DC für einen Constitution Save oder das Ziel fällt in Bewusstlosigkeit.
- Wenn bewusstlos, erneuter Test in jeder Runde mit der gescheiterten DC.

## Target Zones {#target-zones}

Ein einzelner Schuss, Burst oder Controlled Burst kann auf ein bestimmtes Körperteil zielen (vor dem Würfeln angesagt). Wenn nicht angesagt, ist es ein Torsoschuss.

| Ziel   | To-Hit-Malus | Effekt                                                                                                                                    |
|--------|--------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Kopf   | -10          | Zählt als Critical. Bei natürlicher 20, die noch trifft, dreifache Schadenswürfel.                                                        |
| Torso  | -            | Normaler Treffer, Standardzone.                                                                                                           |
| Arme   | -6           | Wenn Ziel bladed (ferner Arm), Malus verdoppeln. Bei Treffer, CON Save (DC = Schaden) oder Gegenstand fallen lassen und Arm 1d4 Runden unbenutzbar. |
| Hände  | -8           | Gleiche Bladed-Regel. Bei Treffer, CON Save oder Gegenstand fallen lassen und Hand 1d4 Runden unbenutzbar.                                |
| Becken | -4           | CON Save oder Prone fallen und 1d4 Runden nicht aufstehen können.                                                                         |
| Beine  | -5           | Bladed-Regel. CON Save oder Slowed 1d4 Runden. Beide Beine getroffen = Speed 5 ft während der Effekt anhält.                              |
| Füße   | -7           | Bladed-Regel. CON Save oder DEX-Bonus 1d4 Runden nicht auf Skill Rolls/Saves anwendbar. Beide Füße = zusätzlich Disadvantage auf alle DEX-Tests/Saves. |
