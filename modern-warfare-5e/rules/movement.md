---
title: Movement
aliases: [ Speed, Difficult Terrain, Dash, Disengage, Sprint, Climbing, Swimming, Jumping, Prone ]
tags: [ rules, combat, character ]
---

# Movement

An Operator's **speed** is the number of feet they can cover on their turn under normal conditions. Movement is the
single most-used resource in a firefight - getting to cover, breaking contact, repositioning for an angle. It is
spent freely throughout the turn and can be split around the action and bonus action.

## Base Speed

Default Operator speed is **30 ft per turn**. A few sources modify it:

- **[Agile](../personality-traits.md)** Personality Trait: +5 ft.
- **[Mobility](../operator-class.md#basic-training)** Basic Training: +5 ft.
- **[Bomb Suit (EOD)](../armor.md)**: -10 ft.
- **[Ballistic Shield](../armor.md)** carrier: -10 ft.
- **[Crouched](conditions.md)**: 1/2 speed (round down).
- **[Slowed](conditions.md)**: 1/2 speed (rounded down, min 5 ft).
- **Encumbrance**: GM may halve speed if you exceed your safe carry weight.

You may move up to your speed, broken however you like across the turn. You may move 10 ft, take an action, then move
the remaining 20 ft. You cannot save unused movement for next turn.

## Movement Costs

Most ground costs **1 foot per foot moved**. The following multiply the cost:

| Terrain or Condition                               | Cost per Foot                                |
|----------------------------------------------------|----------------------------------------------|
| Open ground, paved street, hard floor              | 1                                            |
| Difficult terrain (rubble, dense brush, mud, snow) | 2                                            |
| Climbing (rope, ladder, drainpipe, fence)          | 2                                            |
| Swimming                                           | 2                                            |
| Crawling (prone movement)                          | 2                                            |
| Standing up from prone                             | 1/2 your speed (one-shot cost, not per-foot) |
| Dropping prone                                     | Free                                         |

A 30-ft Operator slogging through difficult terrain effectively moves 15 ft per turn. A 30-ft Operator standing from
prone spends 15 ft of movement just to get up, leaving 15 ft for the rest of the turn.

## Prone, Crouched, Standing

- **Standing** is the default posture. Full speed, normal AC, normal targeting.
- **Crouched** ([condition](conditions.md)): half speed, attackers beyond 5 ft suffer -2 to ranged attacks against you,
  standing back to full posture costs 5 ft of movement.
- **Prone**: dropping is free; movement on the ground costs 2 ft per ft (crawling). Melee attacks against you are at
  advantage; ranged attacks against you (beyond 5 ft) are at disadvantage. Standing up costs half your speed.

Operators frequently bounce between standing and crouched within a single turn - crouch behind a low wall to break the
shooter's line, pop up to fire, drop back. The crouched/standing flip costs are the price you pay.

## Dash

The [Dash](combat-turn.md#actions) action lets you spend your *action* to move up to your speed again. Total movement
on a Dash turn is 2 × speed (or 4 × speed if you also have a bonus-action Dash from a feature). A Dashing Operator
running across open ground covers a lot of distance, but they cannot also fire that turn.

> **Example:** Falke has 35 ft speed (30 base + 5 Agile). On a clean street he moves 35 ft, takes the Dash action, and
> moves another 35 ft - total 70 ft this turn. He cannot also shoot, since Dash consumed his action.

## Disengage

The [Disengage](combat-turn.md#actions) action lets you leave melee reach without provoking an opportunity attack for
the rest of that turn. Use it when an enemy is adjacent and you need to fall back to a longer-range firing position.

## Climbing, Swimming, Crawling

Each costs 2 ft per ft, as above. The GM may also call for a STR (Athletics) [check](ability-checks.md) on rough or
slick surfaces, in heavy current, or when carrying weight near your limit. Failing the check usually means no progress
that turn; failing badly may mean falling, dropping the load, or losing grip.

## Jumping

| Jump Type                | Distance                                    | Notes                                                                               |
|--------------------------|---------------------------------------------|-------------------------------------------------------------------------------------|
| **Long jump (run-up)**   | Feet equal to your STR score                | Need at least 10 ft of run-up.                                                      |
| **Long jump (standing)** | Half STR score in feet                      | No run-up.                                                                          |
| **High jump (run-up)**   | 3 + STR modifier feet of vertical clearance | Need at least 10 ft of run-up. Reach an extra 1.5 × your height with arms extended. |
| **High jump (standing)** | Half the run-up distance                    | No run-up.                                                                          |

Jump distance counts against your movement (1 ft per ft jumped). A failed jump may end with you Prone, in difficult
terrain, or worse depending on what was below.

## Breaking Contact

To get out of a bad fight cleanly:

- **Disengage** (action) so you are not chased by an opportunity attack.
- **Dash** (action) for distance. You cannot do both in the same turn unless you also have Action Surge or a
  bonus-action Dash.
- Pop **smoke** ([gear](../gear.md)) to grant concealment to your withdrawal.
  See [Cover](cover.md#cover-vs-concealment).
- Drop **suppressive fire** with another element to keep the enemy's heads down while you move.

## Vehicle Movement

When mounted in a vehicle, you use the vehicle's speed instead of your own. Most ground vehicles move at multiples of
foot speed; helicopters and aircraft are entirely off the per-turn grid and operate by GM narration. Detailed vehicle
combat rules are GM discretion.

## Compared to Classic D&D 5E

- 30 ft default speed, free split of movement around the action, and free Object Interaction are unchanged.
- Difficult terrain at 2 ft per foot, climbing/swimming at 2 ft per foot, crawling at 2 ft per foot - all classic 5E.
- Dropping prone is free; standing costs half your speed - same as classic 5E.
- Jumping numbers (STR score for long jump, 3 + STR mod for high jump, halve without run-up) are lifted directly from
  classic 5E.
- The homebrew layer is **Crouched** as a posture between standing and prone, and the bigger menu of speed-modifying
  gear (bomb suit, ballistic shield, IFV).
