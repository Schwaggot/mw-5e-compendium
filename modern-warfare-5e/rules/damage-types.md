---
title: Damage Types
aliases: [Damage, DR, Stress, Subdual, Target Zones]
tags: [rules, damage]
---

# Damage Types

## Damage Reduction

Some gear grants Damage Reduction (DR). Reduce the damage of a single hit by the listed amount. DR may be typed.

## Damage Types

- **Acid:** -
- **Bludgeoning:** Can be declared Subdual before attack.
- **Cold:** DC for CON save or Slowed 1d4 rounds.
- **Electrical:** DC for CON save or Paralyzed 1d4 rounds.
- **Fire:** Ignites flammables; action to extinguish.
- **Flash:** DC for CON save or Blinded 1d4 rounds.
- **Force:** Always counts as Subdual too.
- **Piercing:** On Red/Orange triage, roll d100: 01-25 Major Bleed, 26-75 Bleed.
- **Poison:** DC for CON save or Poisoned.
- **Radiation:** DC for CON save or Poisoned.
- **Slashing:** Like Piercing, roll for Bleed.
- **Sound:** DC for CON save or Deafened 1d4 rounds.
- **Stun:** DC for CON save or Stunned 1d4 rounds.
- **Stress:** Separate accumulated damage; see below.

## Stress Damage

- Stress damage per hit = damage dealt minus target's Wisdom score (min 1).
- Stress does not reduce HP; it accumulates.
- Each time total stress crosses a multiple of the Wisdom score, the target makes a Wisdom save. DC and condition depend on the multiple reached.

| WIS Multiple | DC | Condition | Short Rest Heal | Long Rest Heal |
|--------------|----|-----------|-----------------|----------------|
| 1× WIS       | 12 | Shaken 1  | 1d6 + WIS       | 1d12 + WIS     |
| 2× WIS       | 15 | Shaken 2  | 1d4 + WIS       | 1d8 + WIS      |
| 3× WIS       | 20 | Shaken 3  | 1               | 1d4 + WIS      |
| 4× WIS       | 25 | Shaken 4  | Medical help    | 1 + WIS        |
| 5× WIS       | 30 | Broken    | Medical help    | Medical help   |

See [Shaken](conditions.md#shaken) for the condition effects.

## Subdual (Non-Lethal)

- Does not apply to HP.
- If subdual damage exceeds the target's CON modifier, that value is the DC for a Constitution save or fall unconscious.
- If unconscious, retest each round at the failed DC.

## Target Zones

A single shot, burst, or controlled burst may target a specific body part (declared before rolling). If not declared, it is a torso shot.

| Target | To-Hit Penalty | Effect                                                                                                                                     |
|--------|----------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Head   | -10            | Counts as critical. On natural 20 that still hits, triple damage dice.                                                                     |
| Torso  | -              | Normal hit, default zone.                                                                                                                  |
| Arms   | -6             | If target is bladed (far arm), double penalty. On hit, CON save (DC = damage) or drop item and cannot use the arm for 1d4 rounds.          |
| Hands  | -8             | Same bladed rule. On hit, CON save or drop item and cannot use hand for 1d4 rounds.                                                        |
| Pelvis | -4             | CON save or fall prone and cannot stand for 1d4 rounds.                                                                                    |
| Legs   | -5             | Bladed rule. CON save or Slowed 1d4 rounds. Both legs hit = speed 5 ft while effect lasts.                                                 |
| Feet   | -7             | Bladed rule. CON save or cannot apply DEX bonus to skill rolls/saves for 1d4 rounds. Both feet = also disadvantage on all DEX tests/saves. |
