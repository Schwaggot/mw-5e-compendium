---
title: Critical Hits
aliases: [ Crit, Critical Hit, Crit Range, Auto-Crit, Critical Shot ]
tags: [ rules, combat ]
---

# Critical Hits

A **critical hit** rolls extra damage and represents a shot that landed where it really mattered: through the eye port
of a helmet, between plates, into the femoral artery. The base mechanic is classic 5E (a natural 20 doubles your
damage dice), but each weapon in the compendium publishes its own **Crit range** that can extend the trigger window.
Several training programs and designation features let you skip the dice and just declare a hit a crit outright.

## How Crits Trigger

Look at the **Misfire/Crit** column of the weapon's table entry (e.g. an AI AW lists `1/19-20`). The right-hand value
is the **Crit range**:

- A natural attack roll **at or above** the Crit range is a critical hit, *if the attack also clears the target's AC
  after modifiers*. A natural 20 always hits regardless of AC, but other crit-range numbers do not - they only crit on
  hits.
- Most precision weapons crit on **19-20**; magnum/anti-materiel weapons (e.g. .50 BMG bolt rifles) crit on **18-20**;
  some pistols crit on **20** only. Read the table.

The other property to know is **Misfire**, on the *left* of the slash. A natural roll at or below the Misfire value
auto-fails and triggers the misfire chart in [Weapon Properties](weapon-properties.md). Crit range and Misfire range
are independent: a single weapon has both windows.

## What a Crit Does

On a critical hit, **roll all damage dice twice** and add them together. **Then add modifiers once.** Static bonuses
(STR/DEX, Accurate, ammunition bonuses) are not doubled.

> **Example:** Falke's M4 deals `2d8` damage. He rolls a hit and the natural die was a 19 (Crit range 19-20). He rolls
> the damage dice **twice**: `2d8 → 11`, second `2d8 → 9`. Total dice = 20, plus his +3 DEX modifier = **23 damage**.
> A normal hit on the same roll would have been `2d8 + 3 → 11 + 3 = 14`.

The doubling applies only to the dice of the *attack* that crit. Side-effect damage from the same hit (Bleed it
caused, ongoing Ignite ticks, etc.) is not doubled.

## Headshots Always Crit

When you call a [Target Zone](damage-types.md#target-zones) head shot (-10 to hit), the hit is treated as a critical -
no Crit range needed. If the natural die was *also* a 20, the damage dice are **tripled** instead of doubled. This is
the only "triple dice" trigger in the system without a feature granting it.

> **Example:** Falke calls a head shot with the same M4. He rolls **1d20 → 17**, +3 (DEX) +2 (Prof) -10 (head zone) =
> **12** vs AC 13 → miss. Different shot: he rolls a **natural 20**, which always hits. Head shot + nat 20 = triple
> damage dice. `2d8 × 3 → 5+7+3+1+8+6 = 30`, +3 DEX = **33 damage**. Whatever was wearing the helmet is no longer a
> problem.

## Crits Under Advantage and Disadvantage

- A natural number in the Crit range on **either die** under [advantage](advantage.md) triggers the crit.
- A natural number in the Crit range on the chosen die under disadvantage triggers the crit. The unchosen high die does
  not count - it isn't the result.

This means advantage roughly doubles your crit chance; disadvantage roughly halves it.

## Auto-Crits and Other Sources

Several features bypass the dice and crit on contact. The most common:

- **[Marksman - Critical Shot](../designations/marksman.md)** (3rd-level Combat Designation feature): as an action, fire
  one bolt-action or single-shot rifle round. If it hits, it is automatically a critical hit. If the underlying roll
  *also* fell in the Crit range, the dice triple instead of double.
- **[Covert Training Level 3 (Ambush)](../training/covert-programs.md)**: your first hit on a Surprised creature is
  automatically a critical hit. A normal-rolled crit on top of this becomes maximum damage dice instead of doubled.
- **Precision strike on a downed target**: a hit within 5 ft of an unconscious creature, by a melee or single-shot
  weapon, is treated as a crit at GM discretion.

When two auto-crit sources stack on the same attack (rare), the attack is a single crit, not "double crit" - the
upgrades only kick in if the source explicitly says so (Critical Shot's "triple if naturally crit" or Ambush's
"max damage if naturally crit").

## Crits While Downed

Any crit landed on a creature at 0 HP costs them **2 death-save failures** instead of 1. A close-range crit can take a
casualty from "still rolling saves" to dead in a single hit. See [Hit Points](hit-points.md#damage-while-downed).

## Compared to Classic D&D 5E

- The "natural 20 → crit, double the dice, add modifiers once" core is identical to classic 5E.
- The configurable Crit range per weapon (e.g. 18-20 on heavy magnums, 20 on small pistols) is homebrew - classic 5E
  only widens this through class features (Champion fighter).
- Auto-crit-on-headshot is homebrew, paired with the target-zone -10 penalty.
- Triple damage dice exists but is rare: nat-20 head shot, or a feature explicitly stacking onto a natural crit (
  Critical Shot, Ambush).
- Crits at 0 HP costing 2 death-save failures matches classic 5E.
