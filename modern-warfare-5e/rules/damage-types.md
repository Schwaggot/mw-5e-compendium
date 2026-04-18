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
- **Cold:** DC for Con save or Slowed 1d4 rounds.
- **Electrical:** DC for Con save or Paralyzed 1d4 rounds.
- **Fire:** Ignites flammables; action to extinguish.
- **Flash:** DC for Con save or Blinded 1d4 rounds.
- **Force:** Always counts as Subdual too.
- **Piercing:** On Red/Orange triage, roll d100: 01-25 Major Bleed, 26-75 Bleed.
- **Poison:** DC for Con save or Poisoned.
- **Radiation:** DC for Con save or Poisoned.
- **Slashing:** Like Piercing, roll for Bleed.
- **Sound:** DC for Con save or Deafened 1d4 rounds.
- **Stun:** DC for Con save or Stunned 1d4 rounds.
- **Stress:** Separate accumulated damage; see below.

## Stress Damage

- Stress damage per hit = damage dealt minus target's Wisdom score (min 1).
- Stress does not reduce HP; it accumulates.
- Each time total stress crosses a multiple of Wisdom score, target makes a Wisdom save. DC and condition depend on multiple reached.

| Wis Multiple | DC | Condition | Short Rest Heal | Long Rest Heal |
|--------------|----|-----------|-----------------|----------------|
| 1× Wis       | 12 | Shaken 1  | 1d6 + Wis       | 1d12 + Wis     |
| 2× Wis       | 15 | Shaken 2  | 1d4 + Wis       | 1d8 + Wis      |
| 3× Wis       | 20 | Shaken 3  | 1               | 1d4 + Wis      |
| 4× Wis       | 25 | Shaken 4  | Medical help    | 1 + Wis        |
| 5× Wis       | 30 | Broken    | Medical help    | Medical help   |

See [Shaken](conditions.md#shaken) for the condition effects.

## Subdual (Non-Lethal)

- Does not apply to HP.
- If subdual damage exceeds target's Con modifier, that value is the DC for a Constitution save or fall unconscious.
- If unconscious, retest each round at the failed DC.

## Target Zones

A single shot, burst, or controlled burst may target a specific body part (declared before rolling). If not declared, it is a torso shot.

| Target | To-Hit Penalty | Effect                                                                                                                                     |
|--------|----------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Head   | -10            | Counts as critical. On natural 20 that still hits, triple damage dice.                                                                     |
| Torso  | -              | Normal hit, default zone.                                                                                                                  |
| Arms   | -6             | If target is bladed (far arm), double penalty. On hit, Con save (DC = damage) or drop item and cannot use the arm for 1d4 rounds.          |
| Hands  | -8             | Same bladed rule. On hit, Con save or drop item and cannot use hand for 1d4 rounds.                                                        |
| Pelvis | -4             | Con save or fall prone and cannot stand for 1d4 rounds.                                                                                    |
| Legs   | -5             | Bladed rule. Con save or Slowed 1d4 rounds. Both legs hit = speed 5 ft while effect lasts.                                                 |
| Feet   | -7             | Bladed rule. Con save or cannot apply Dex bonus to skill rolls/saves for 1d4 rounds. Both feet = also disadvantage on all Dex tests/saves. |
