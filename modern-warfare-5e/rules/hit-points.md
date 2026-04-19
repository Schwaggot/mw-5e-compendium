---
title: Hit Points
aliases: [ HP, Triage, Triage Code, Downed, Dying, Death Saves, Hit Dice ]
tags: [ rules, combat, character ]
---

# Hit Points

Hit Points (HP) measure how much fight an Operator has left in them. They are not a literal count of wounds - a high
HP total is the abstraction for armor that took the hit, body armor that bruised but didn't break, the round that
clipped a magazine instead of an artery, and the will to keep moving anyway. When HP runs out, real damage starts.

Where you sit on your HP track puts you in one of five **Triage Codes**, the in-universe label medics use over comms to
describe a casualty's state. Triage Code drives natural healing, exhaustion penalties, and which medical features can be
applied to you.

## Calculating Hit Points

From the [Operator Class](../operator-class.md#hit-points):

- **1st level:** `10 + your full Constitution score` (the score, not the modifier).
- **Each level after 1st:** `1d10 (or 6) + Constitution modifier`.
- **Hit Dice:** `1d10 per Operator level`. Used to recover HP on a [short rest](rest.md#short-rest).

> **Example:** Falke (CON 11) starts at 21 HP. He levels to 2nd and rolls a 7 on his Hit Die, so he gains 7 + 0 = 7 HP,
> putting him at 28 max. At 3rd level he takes the average instead, gaining 6 + 0 = 6 HP, for 34 max.

## Taking Damage

When you are hit, the attacker deals a damage roll. Subtract the result from your current HP. Two things modify the
incoming number before it lands:

- **Armor / cover** absorbs damage according to the [Armor](../armor.md) rules and
  any [Damage Reduction (DR)](damage-types.md#damage-reduction) granted by gear.
- **Damage type** can trigger side effects in addition to the HP loss - bleed, slowed, stunned, deafened, etc.
  See [Damage Types](damage-types.md).

If the hit is on Red or Orange triage, [piercing](damage-types.md#damage-types) and slashing damage can also start
[Bleed or Major Bleed](conditions.md), which keeps draining HP between turns until stopped.

## Triage Code

Every character always has exactly one Triage Code, derived from their current HP as a percentage of maximum.

| Code                       | % Health | Natural Healing                                                    | Exhaustion |
|----------------------------|----------|--------------------------------------------------------------------|------------|
| 5: Black, Deceased         | 0%       | None                                                               | 5          |
| 4: Red, Critically Wounded | 1%-25%   | Must get medical help; Hit Dice no longer heal; 10 HP per 1 healed | 2          |
| 3: Orange, Wounded         | 26%-50%  | 5 HP per 1 healed                                                  | 1          |
| 2: Yellow, Injured         | 51%-75%  | 2 HP per 1 gained                                                  | -          |
| 1: Green, Healthy          | 76%-100% | Normal rate                                                        | -          |

The right-hand columns drive a few important downstream rules:

- **Natural Healing** scales the value of every HP point you would recover from rest, Hit Dice, or non-medical sources.
  At Yellow you only get 1 HP for every 2 the source rolled; at Red you get 1 HP for every 10 *and* you can no longer
  spend Hit Dice. Field medics ([Combat Medic](../designations/combat-medic.md), Stim Pack, Quick Clot, etc.) bypass
  this divisor.
- **Exhaustion** is added to your standing exhaustion total while you remain at that Code. Drop back up the track and
  the bonus exhaustion lifts.
- **Second Wind, Stim Pack, several Unit Leader features**, and any other ability that lists a Triage requirement only
  fires inside its named Codes. See each feature.

> **Example:** Falke is at 34 max HP and currently sits at 12 HP - that is 35%, putting him at Orange. He spends a Hit
> Die on a short rest and rolls 7. Orange's natural-healing column says "5 HP per 1 healed," so the 7 becomes 1 HP
> healed (7 ÷ 5, rounded down). He's still at 13 HP and still Orange. If a medic hits him with a Stim Pack instead, the
> divisor doesn't apply.

## Going Down at 0 HP

When damage drops your current HP to 0 (and not to deceased outright), you are **Downed**. Mechanically:

- You fall **Unconscious** and **Prone**. You drop whatever you were holding.
- Your HP stays at 0; further damage triggers death saves, not subtraction.
- At the start of every one of your turns while Downed, roll a **death saving throw**.

### Death Saving Throws

A death save is a `1d20` roll with no modifier. It is *not* a [saving throw](saving-throws.md) for the purposes of
features that modify saves, unless a feature explicitly says so.

- **10 or higher → success.** Track the count.
- **9 or lower → failure.** Track the count.
- **Natural 20 → you regain 1 HP** and stand back up at Yellow's lower bound (still Wounded, but conscious).
- **Natural 1 → counts as two failures.**

Reaching **3 successes** before 3 failures: you are **stable**. You stop rolling, but you are still at 0 HP and still
unconscious. After 1d4 hours you regain 1 HP and wake up at Triage Red. Any healing during the stable window also wakes
you immediately at the new HP value.

Reaching **3 failures** before 3 successes: you die. Triage Code drops to Black.

### Damage While Downed

Taking any damage while at 0 HP costs you a death-save failure - 1 failure for a normal hit, **2 failures for a hit
within 5 ft** (point-blank execution shot) or for any hit that crits. If the single hit's damage equals or exceeds your
HP maximum, you die outright (instant Black) with no further saves.

### Stabilizing a Casualty

A nearby ally can stop the bleed without restoring HP:

- **Wisdom (Medicine) check, DC 10** as an action. Success = the casualty is stable. Failure = no progress, try again.
- A medical item with the `stops-bleed` tag (see [Gear](../gear.md)) auto-stabilizes a Bleeding casualty.
- A medical item with the `revives` tag (e.g. Smelling Salts, certain Stims) can bring an unconscious target back to
  Yellow at GM discretion.
- Several [Combat Medic](../designations/combat-medic.md) features stabilize and heal in the same action.

A stable casualty is still at 0 HP and Triage Code Red - they are not back in the fight, just not actively dying. Get
them to a medic.

> **Example:** Falke takes a burst that drops him from 4 HP to -7. He's at 0 HP, Downed, Unconscious, Prone. On his
> next turn he rolls a death save: **8** → 1 failure. The medic crawls over and rolls a Wisdom (Medicine) check
> against DC 10: **14** → success, Falke is stable. He stays at 0 HP / Triage Red until he gets healing or 1d4 hours
> pass. A teammate's Stim Pack ten seconds later puts 12 HP back on him - he wakes up immediately at Triage Yellow.

## Healing

HP comes back from a few sources. The Triage Code natural-healing divisor applies to non-medical sources only.

| Source                                                                 | Amount                                    | Cost / Cooldown                                                     |
|------------------------------------------------------------------------|-------------------------------------------|---------------------------------------------------------------------|
| **[Second Wind](../operator-class.md#second-wind)**                    | `1d10 + Operator level`                   | Bonus action; once per short or long rest. Triage Orange or better. |
| **Hit Dice on a [short rest](rest.md#short-rest)**                     | Per die: `1d10 + CON mod`                 | Each die spent. Cannot spend dice at Triage Red.                    |
| **[Long rest](rest.md#long-rest)**                                     | Full HP; recover up to half your Hit Dice | 8 hours.                                                            |
| **Medical gear (IFAK, Stims, Quick Clot, Liquid Skin Patch)**          | Item-specific                             | Action; consumes the item. Bypasses divisor.                        |
| **[Combat Medic](../designations/combat-medic.md) features**           | Feature-specific                          | Per feature; many bypass the Triage divisor.                        |
| **[Unit Leader](../designations/unit-leader.md) Get In The Fight die** | `1d10 + Unit Leader level`                | Action; only on targets at Triage Yellow or Green.                  |

## Compared to Classic D&D 5E

- HP is mechanically the same number, but the system layers Triage Code on top to model that taking serious damage
  actually slows your recovery and stacks exhaustion.
- Hit Dice work as in classic 5E (1d10 here, like a Fighter), but the Triage divisor can shrink what each die actually
  delivers if you're already hurt.
- Death saving throws work exactly as in classic 5E - 3/3, nat 20 stands you up, nat 1 counts double, hits at 0 HP cost
  a failure (or two if within 5 ft or critical).
- The "stable" state lasts 1d4 hours before you wake at 1 HP, same as classic 5E.
- Bleed (added by piercing/slashing on Red or Orange) replaces classic 5E's "you don't bleed out unless you fail
  saves" - here you can be both stable on death saves and still actively losing HP from a Bleed condition until someone
  stops it.
