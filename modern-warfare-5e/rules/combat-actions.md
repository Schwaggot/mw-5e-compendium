---
title: Combat Actions
aliases: [ Homebrew Rules, Firing Modes ]
tags: [ rules, combat ]
---

# Combat Actions

Homebrew rules, mods, and actions in combat. The default firing mode for any ranged attack is Single Shot. The modes
below extend or replace that default and are gated by weapon properties (Burst, Automatic, Manual Action) listed
in [Weapon Properties](weapon-properties.md).

**Firing into Melee:** Disadvantage on the attack. Natural 1 = no misfire; you hit a random target in the melee
instead (GM randomizes).

## Single Shot

The baseline firing mode, available to any functional firearm.

- **Action economy:** one attack from your Attack action.
- **Targets:** one.
- **Ammo cost:** 1 round.
- **Penalties:** standard [Range](weapon-properties.md#range) penalties only.

> **Example (Single Shot):** Falke fires his pistol (Range 30 ft) at a militant 50 ft away. 50 ft falls in the x2 band (
> 31-60 ft), so he attacks at **Disadvantage**. He spends **1 round** from the magazine.

## Aim

Action: aim at one target. +2 to ranged attack rolls against that target. Only one target at a time; breaks when line of
sight breaks.

## Burst Fire

For weapons with the **Burst** property. A short, mechanically fixed 3-round volley.

- **Action economy:** one Burst per attack from your Attack action.
- **Targets:** one.
- **Ammo cost:** 3 rounds.
- **Penalties:** standard [Range](weapon-properties.md#range) penalties **plus an additional -5 per Range Multiple
  beyond x1** (so -5 at x2, -10 at x3, -15 at x4).
- **Extra hits:** see [Extra-Hit Rule](#extra-hit-rule).

> **Example (Burst Fire):** Falke's PDW (Range 60 ft, Burst) targets a militant at 70 ft. 70 ft falls in the x2 band (
> 61-120 ft). Standard range table at x2 = Disadvantage; Burst adds -5 per Multiple beyond x1, which at x2 is another -5.
> Total: **Disadvantage and -5**. He spends **3 rounds**.

## Automatic Firing Modes

For weapons with the **Automatic** property, you may use Controlled Burst, Spray, or Riddle in place of a Single Shot or
Burst.

### Controlled Burst

A short auto-fire burst of variable length; the auto-fire equivalent of Burst Fire.

- **Action economy:** one Controlled Burst per attack from your Attack action.
- **Targets:** one.
- **Ammo cost:** 1d4+2 rounds (rolled per Burst).
- **Penalties:** standard [Range](weapon-properties.md#range) penalties **plus -5 per Range Multiple beyond x1**.
- **Extra hits:** see [Extra-Hit Rule](#extra-hit-rule).

### Spray

Sweep auto-fire across multiple adjacent targets ("horizontal" auto-fire).

- **Action economy:** Action (replaces your Attack action).
- **Targets:** up to your DEX modifier; targets must be adjacent to one another (each within 5 ft of the next).
- **Ammo cost:** 1d4+2 rounds **per target** (rolled separately per target).
- **Penalties:** **-5 per target beyond the first** (cumulative: -0 / -5 / -10 / ...).
  Standard [Range](weapon-properties.md#range) penalties also apply normally to each attack roll.
- **Extra hits:** see [Extra-Hit Rule](#extra-hit-rule); cap is the rounds fired in *that* target's volley.

### Riddle

Pour auto-fire into a single target across multiple volleys ("vertical" auto-fire).

- **Action economy:** Action.
- **Targets:** exactly one.
- **Volleys:** choose a number of volleys up to your DEX modifier; each volley is one separate attack roll.
- **Ammo cost:** 1d4+2 rounds **per volley** (rolled separately per volley).
- **Penalties:** **-5 per volley beyond the first** (cumulative). Standard [Range](weapon-properties.md#range) penalties
  apply.
- **Extra hits:** see [Extra-Hit Rule](#extra-hit-rule); applied per volley.

> **Example (Spray vs Riddle):** Falke (DEX 16, +3) corners three militants in a doorway, all within 5 ft of each other.
>
> - Going **Spray**, he targets all three. Attack penalties stack: target 1 at -0, target 2 at -5, target 3 at -10. Ammo
    cost is rolled separately per target: e.g. 4 + 6 + 5 = **15 rounds**.
> - Going **Riddle** instead, he ignores the other two and stacks **3 volleys** into the lead militant. Attack
    penalties: volley 1 at -0, volley 2 at -5, volley 3 at -10. Ammo cost is rolled per volley: e.g. 5 + 3 + 6 = **14
    rounds**.

## Extra-Hit Rule

Burst, Controlled Burst, Spray, and Riddle can land additional rounds on the same target when the attack lands well
above AC. **For every full 5 points by which your attack roll exceeded the target's AC, score one additional hit** (each
adds the weapon's damage dice). The maximum number of extra hits is capped at the number of rounds fired in that volley.

> **Example (extra hits):** Falke fires a Controlled Burst at a militant (AC 14) and rolls **24** to hit - 10 over AC.
> That's two full chunks of 5, so he scores the original hit **+ 2 extra hits = 3x weapon damage dice**. He rolled 5
> rounds for the burst, so the 5-hit cap is not reached.

## Suppressive Fire

Action; pin enemies down without aiming for kills. Mutually exclusive with the Attack action on the same turn.

- **Targets:** creatures within 10 ft of each other, up to your DEX modifier.
- **Ammo cost per target:** 3 rounds (Burst weapons), 1d4+2 (Automatic weapons), or 1 burst as defined by the weapon.
- **Effect:** suppressed targets have Disadvantage on ranged attacks and on WIS (Perception) checks until the end of
  their next turn.
- **Restriction:** cannot be used with Manual Action weapons.

> **Example (suppression):** Falke's squad is taking fire from two riflemen 8 ft apart in a window line. Falke uses
> Suppressive Fire with his Automatic carbine. Both targets are within 10 ft of each other and within his DEX modifier (
> 3). He spends **2 x 1d4+2 = 9 rounds**. Both riflemen are at Disadvantage on ranged attacks against the squad and on
> Perception checks until the end of their next turn, letting his team reposition.

## Ranged Opportunity Attack

If a creature you're aimed at moves more than 5 ft during its turn, you may use your reaction to make one ranged attack
against it (within range and line of sight).
