---
title: Cover
aliases: [ Half Cover, Three-Quarters Cover, Full Cover, Concealment, Soft Cover ]
tags: [ rules, combat ]
---

# Cover

Modern combat is built around cover. An Operator behind a concrete wall is a different fight than an Operator in the
open street - and the system treats them that way. Cover gives a flat AC bonus and a matching bonus to DEX
[saving throws](saving-throws.md) against effects that originate on the other side of it.

There are three grades.

## The Three Grades

| Grade              | Threshold                               | AC Bonus | DEX Save Bonus | Notes                                                                         |
|--------------------|-----------------------------------------|----------|----------------|-------------------------------------------------------------------------------|
| **Half**           | About half the body is obscured/blocked | +2       | +2             | Low wall, doorframe, vehicle hood, partner standing between you and threat.   |
| **Three-quarters** | Most of the body is obscured/blocked    | +5       | +5             | Murder hole, sandbag with firing slit, corner of a building, half-open hatch. |
| **Full**           | Body is entirely obscured/blocked       | -        | -              | Cannot be targeted directly by attacks or effects requiring line of sight.    |

A target in **full cover** cannot be the *direct* target of an attack or single-target ability. They can still be hit
indirectly: area effects (frags, blast), suppressing fire that walks past the cover, or attacks against the cover
itself.

## Cover vs Concealment

The two are different and easy to confuse. **Cover stops the round; concealment just hides you.**

- **Cover** (this page): rounds physically don't reach you - concrete, steel, earth berm, stack of hard sandbags.
- **Concealment**: line of sight is broken or degraded but the material wouldn't stop a bullet - smoke, foliage,
  darkness, fog. Concealment grants disadvantage on attacks against you (see [Advantage and Disadvantage](advantage.md))
  but no AC or save bonus.

A burst into concealment can still hit you; a burst into cover physically cannot, unless the cover is destroyed or
defeated (an AP rifle round through a car door, an HMG through cinder block, a rocket through a wall).

A creature standing between an attacker and your position counts as **soft cover** - half cover for game purposes -
which is why "do not stand in front of friendlies" is a brief item, not a suggestion.

## Determining the Grade

The GM calls it from the situation. Useful rules of thumb:

- Crouched behind a low wall or in a doorframe: half cover.
- Prone behind the same low wall: three-quarters cover.
- Around a corner with only weapon and one eye showing: three-quarters cover.
- Fully behind a wall: full cover.
- A pickup truck side, hood, or door: half cover (most rounds will defeat it; see *Defeating Cover* below).
- A vehicle's engine block: three-quarters cover.

[Crouched](conditions.md) by itself does not grant cover - it gives an attacker -2 at range past 5 ft, separately - but
it makes claiming three-quarters cover easier behind a low obstacle.

## Cover and Target Zones

When a target is in cover, only the *exposed* body parts can be attacked
with [Target Zone](damage-types.md#target-zones)
shots. A shooter behind three-quarters cover that exposes only their head and weapon-hand can be shot in the head or
hand - everything else is blocked.

## Defeating Cover

Several abilities and weapons reduce or ignore cover:

- **[Ranged Weapons Training Level 4](../training/ranged-weapon-programs.md)**: treat enemies as having one grade less
  of cover (full → three-quarters, three-quarters → half, half → none).
- **[Demolitions Specialist](../designations/demolitions-specialist.md) anti-tank weapons**: rocket launchers and
  similar ignore all cover short of full.
- **High-grade ammunition** (.50 BMG, AP rounds, etc.): may shoot *through* the cover at GM discretion, with the cover
  acting as Damage Reduction equal to its hardness rather than a binary block.
- **Suppressive fire and area effects**: don't care about half or three-quarters cover; only full cover negates them,
  and even full cover does not block a frag whose blast wraps around the obstacle.

## Granting Cover

A few ways to make your own cover where there isn't any:

- **Ballistic Blanket** (see [Armor](../armor.md)): deployed as an action over a prone teammate, grants half or full
  cover at GM discretion.
- **[Demolitions Specialist field fortifications](../designations/demolitions-specialist.md)**: build three-quarters
  cover squares in a 20-ft line.
- **[Ballistic Shield](../armor.md)**: grants half cover to the carrier and to one adjacent ally on the covered side.
- **Smoke**: not cover - it grants concealment (disadvantage on attacks against creatures inside or beyond it) but does
  not stop rounds.

## Examples

> **Example - half cover:** Falke (AC 14 from his medium flak) is firing over the hood of a sedan at a militant 20 m
> away. The militant returns fire. The GM rules Falke is in half cover behind the hood: AC becomes **16**. Militant
> rolls **1d20 → 13**, +3 = **16** vs AC 16 → tied, ties miss the attacker, **miss**. Without the hood, that 16 would
> have hit.

> **Example - three-quarters cover and target zones:** Falke is stacked on the corner of a stairwell, leaning out only
> his head and rifle. The GM rules three-quarters cover. A militant on the landing tries to take an arm shot - but
> Falke's arm is behind the wall. The militant must take a head shot (-10 to hit) or a hand shot (-8) or hold fire.

> **Example - full cover defeated:** Falke ducks fully behind a brick pillar (full cover) for a reload. The militant
> cannot directly target him - so the militant lobs a frag past the pillar instead. Falke takes a DEX save against the
> blast; full cover does not protect against an area effect that wraps around it.

## Compared to Classic D&D 5E

- Half (+2), three-quarters (+5), and full cover are identical to classic 5E grades and bonuses.
- Cover grants the same bonus to DEX saves as to AC, same as classic 5E.
- Cover vs concealment is the same distinction; concealment is mechanically "disadvantage on attacks," same as classic
  5E's "lightly obscured" / "heavily obscured" treatment.
- The big difference is how *common* and *targetable* cover is - cover is the default state of every gunfight, not the
  exception, and the system gives you tools to deploy, ignore, or defeat it.
