---
title: Rest
aliases: [ Short Rest, Long Rest, Resting, Recovery ]
tags: [ rules, character ]
---

# Rest

A rest is a stretch of downtime long enough for an Operator to recover - patch wounds, top off mags, eat, drink, and
sleep off the worst of the day. The system recognizes two flavors: a **short rest** (about an hour, in cover, weapons
hot) and a **long rest** (eight hours, secure perimeter, sleep). Most class and designation features that recharge use
one of these two clocks.

## Short Rest

A short rest is **at least 1 hour** of low-effort activity: weapon maintenance, eating an MRE, redressing a tourniquet,
running comms checks. You can be alert and armed; you cannot be in active combat or sustained heavy exertion.

During a short rest:

- **Spend Hit Dice.** You may spend any number of your Hit Dice. For each die, roll the die and add your Constitution
  modifier - that is the HP regained from that die. Your current [Triage Code](hit-points.md#triage-code) still divides
  the result. **Triage Red blocks Hit Dice spending entirely.**
- **Recover features.** Anything that recharges "per short rest" or "per short or long rest" comes back. This
  includes [Second Wind](../operator-class.md#second-wind), [Action Surge](../operator-class.md#action-surge), [Unit Leader Leadership Dice](../designations/unit-leader.md),
  and several other designation abilities.
- **Heal stress.** Stress damage heals on a short rest at the rate listed in
  the [Stress Damage](damage-types.md#stress-damage) table.
- **Craft field expedients.** A [Combat Medic](../designations/combat-medic.md) can craft an improvised stim or antidote
  during a short rest. Tech and demolitions specialists also use short rests for small fixes.
- **Top off magazines.** With a supply cache on hand, top off the loaded mag from spares and consolidate partials. No
  net gain in ammo - redistribution only. See [Ammunition](ammunition.md#resupply).

You can take **up to two short rests** between long rests at most tables - the GM may rule otherwise based on the
operational tempo.

> **Example:** Falke (3 Hit Dice, CON +0) finishes an objective at 12 / 34 HP (Orange). He calls a short rest in a
> cleared building. He spends 2 Hit Dice: rolls 7 and 4, +0 each = 7 and 4 HP healed before the divisor. Orange's
> divisor is "5 per 1," so the 7 becomes 1 HP and the 4 becomes 0. He's at 13 HP, still Orange. Second Wind, on the
> other hand, recharged - and bypasses the divisor when he uses it next turn.

## Long Rest

A long rest is a period of **at least 8 hours**, of which at least 6 are sleep. The Operator can stand up to two
hours of light watch in the middle without breaking the rest. A long rest requires safety and shelter - a hide site, a
FOB, a safehouse, a hotel room. You cannot long rest in active contact, on a moving exfil aircraft, or while taking
fire.

After a long rest:

- **HP fully restored.** You wake at maximum HP and Triage Green, regardless of where you started (provided you survived
  the night).
- **Hit Dice recovered.** You regain spent Hit Dice up to **half your total** (minimum 1).
- **All "per long rest" features reset.
  ** [Indomitable](../operator-class.md#indomitable), [Resourceful](../operator-class.md#resourceful), and most
  designation features key off this clock.
- **Stress damage heals** at the long-rest rate from the [Stress Damage](damage-types.md#stress-damage) table.
- **Exhaustion drops by 1 level.** Unless held by a persistent cause (Triage Red still adds 2 while you remain there).
- **Resupply ammunition.** At a secure, supplied location (base, FOB, established cache), all magazines refill to the
  starting loadout. In the field without supply access, no refill - only consolidation. See
  [Ammunition](ammunition.md#resupply).

A long rest's HP-restore step is a healing source for the purposes of the Triage divisor - but it bypasses the divisor
because it's set to "full HP" rather than a roll. You always wake fresh, even if you slept Red.

> **Example:** Falke ends the day at 13 / 34 HP, Orange, Exhaustion 2 (1 from Orange, 1 from a previous fail). The
> squad makes the safehouse and racks out. He long rests: HP back to 34, Triage Green, Hit Dice back from 0 → 1 (half
> of 3, rounded down, minimum 1), Exhaustion drops from 2 to 1. He's combat-effective again by morning.

## Interrupted Rests

If a rest is broken before its minimum time has elapsed - contact, alarm, casualty - it grants no benefit. Restart the
clock from zero once the threat is handled.

A short rest of less than 1 hour gives nothing. A long rest of less than 8 hours counts as a short rest if it ran at
least 1 hour, otherwise nothing.

## Compared to Classic D&D 5E

- 1 hour short / 8 hour long is the same baseline as classic 5E.
- Hit Dice spending on short rests works the same way; the Triage Code divisor is the homebrew layer on top.
- Long rest fully heals and refunds half of spent Hit Dice - same as classic 5E.
- Exhaustion drops by 1 per long rest, same as classic 5E.
- The big change is **operational realism**: you cannot long rest in active operations, and the Triage Code can throttle
  Hit Dice value or block them entirely. This is why field medics and stims matter so much.
