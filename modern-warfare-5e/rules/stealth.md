---
title: Stealth and Hiding
aliases: [ Stealth, Hide, Hidden, Sneaking, Detection ]
tags: [ rules, character, combat ]
---

# Stealth and Hiding

Most operations open with someone unseen. Stealth in this system is a contest between an actively-hiding creature's
DEX (Stealth) check and the watching creature's passive (or active) Perception. The mechanics are inherited from
classic 5E; the homebrew layer is the kit that makes you noisier (heavy armor, certain rucks) or quieter (Covert
training, certain optics on the watcher's side).

## When You Can Hide

You cannot hide while a watching creature can clearly see you. To attempt the [Hide action](combat-turn.md#actions),
you must be at least one of the following relative to that watcher:

- **Heavily obscured** from them - smoke, deep darkness, dense undergrowth, around a corner.
  See [Vision and Light](vision-and-light.md).
- **Behind cover** that fully breaks their line of sight ([three-quarters](cover.md) cover or better, used to drop
  completely behind it).

[Covert Training Level 3](../training/covert-programs.md) loosens this: you can hide while only **lightly obscured**
from the target (dim light, light foliage, light fog). This is what lets a sniper-spotter pair fade into the treeline
where an untrained creature would still be spotted.

## Making the Roll

The Hide action is a `DEX (Stealth) check`. The result is contested by every watcher's **passive Perception** unless
the watcher actively rolls. See [Ability Checks](ability-checks.md#contested-checks).

- Beat their passive Perception → you are **Hidden** from them.
- Tie or lower → they notice you. Ties go to the defender (the watcher).
- A watcher who actively rolls Perception uses the rolled result instead of their passive score.

Your hidden status is **per-watcher**: you can be hidden from one sentry while plainly visible to a different one with
a better angle. The GM tracks who knows you're there.

## What Hidden Gets You

While hidden from a creature:

- **Attacks against that creature have advantage** (they cannot apply their DEX bonus to AC against an attack they don't
  see coming, in the abstract; mechanically, the system uses advantage as the catch-all).
- **They have disadvantage attacking back** (they don't know exactly where you are).
- You can move out of cover and back without rerolling Stealth, *unless you do something that would reveal you*.

You stop being hidden when:

- You make an attack (revealed to all who could perceive the
  attack). [Covert Training Level 2](../training/covert-programs.md) lets you stay hidden if your ranged attack misses.
- You speak above a whisper, fire an unsuppressed weapon, or otherwise produce a clear sound.
- You move into a position where a watcher can plainly see you.
- The watcher actively searches your area and beats your earlier Stealth result.

## Modifiers To Stealth

- **Armor with the Disadvantage Stealth modifier** ([Armor](../armor.md)): disadvantage on every Stealth check while
  wearing it. Most medium and all heavy carriers carry this tag.
- **[Crouched](conditions.md) or Prone**: GM may grant advantage on Stealth when combined with cover.
- **Fast pace movement** while patrolling: GM may impose disadvantage on Stealth (you are moving faster than your steps
  allow you to silence).
- **Suppressed firearms**: do not auto-defeat detection but greatly reduce the radius at which a shot reveals you - GM
  ruling.
- **Operator with [Covert Training Level 1](../training/covert-programs.md)**: trained in Stealth, adds Proficiency
  Bonus.

## Group Stealth

When the whole element moves together, the GM may call a **group Stealth check** (
see [Ability Checks](ability-checks.md#group-checks)).
If half or more of the squad clear the watcher's passive Perception, the whole element is hidden. The squad's
loud member can still be carried by their quiet teammates, but only so far - one rattling kit on a four-man patrol is
manageable; two is a tell.

## Surprise

If your whole side is hidden when combat begins, the unaware side is **Surprised** for the first round - they cannot
move, take an action, or take a reaction. See [Combat Turn - Surprise](combat-turn.md#surprise). Several
[Covert Training](../training/covert-programs.md) features key off the surprise round, including auto-crits on the
first hit.

## Examples

> **Example - basic Hide:** Falke (DEX +3, trained in Stealth, Proficiency +2) ducks behind a brick wall and rolls
> a DEX (Stealth) check: **1d20 → 12**, +3 +2 = **17**. The patrolling sentry has passive Perception 13. 17 vs 13 →
> Falke is hidden from that sentry. He moves to a new firing position 20 ft along the wall; the sentry's eyeline never
> intercepts him, so he stays hidden.

> **Example - revealed by an attack:** From hiding, Falke takes a single-shot at the sentry. He has advantage from
> being hidden. He rolls **2d20 → 9 and 16**, takes the 16, +3 +2 = **21** vs AC 13 → hit. He is now revealed to every
> creature that could perceive the shot. (If he had Covert Training Level 2 *and* missed, he would have stayed hidden.)

> **Example - heavy armor stealth:** A teammate in a Medium Flak with Shoulders (Disadvantage on Stealth) tries the
> same Hide attempt against the same DC 13 sentry. He has DEX +1, untrained in Stealth. He rolls **2d20 → 14 and 6**,
> takes the 6 (disadvantage), +1 = **7** vs 13 → spotted. He should not have been the one going first.

## Compared to Classic D&D 5E

- The DEX (Stealth) vs passive Perception contest, the per-watcher hidden state, and the "attack reveals you" rule are
  all classic 5E.
- Surprise lifts the *2024 5E* version (loses the first turn entirely), matching [Combat Turn](combat-turn.md#surprise).
- The compendium does not have a Pass Without Trace spell; the equivalent role is filled by Covert Training Programs and
  night-cycle gear (smoke, NVG asymmetry, suppressors).
- Heavy-armor stealth penalties are harder than classic 5E: many medium carriers also impose disadvantage, not just
  heavy.
