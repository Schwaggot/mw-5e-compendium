---
title: Weapon Properties
aliases: [ ]
tags: [ rules, weapon ]
---

# Weapon Properties

**1H / 2H:** Whether the weapon is wielded one-handed or two-handed. A 2H weapon cannot be fired with one hand without
the appropriate training.

**Ammunition ( - / - ):** Two numbers - rounds per magazine / round type. You can only fire when loaded.

**Accurate (-):** +N to all attack rolls with this weapon.

**Deviation (-):** Nominate a point within range. Roll an attack vs AC 10 (+5 per range increment beyond first). On a
miss, roll the scatter die and a deviation die (subtract DEX bonus, min 1); result = 5 ft increments deviated in scatter
direction. At long range, targets have advantage on saves and deviation dice doubled.

<a id="range"></a>**Range:** Each weapon's listed range in feet is its **Normal** (x1) range. Beyond that, distance
scales into Range Multiples (x2, x3, x4) with cumulative penalties. Beyond x4 the target is out of range and cannot be
hit.

| Distance band             | Range Multiple | Penalty              |
|---------------------------|----------------|----------------------|
| 0 to listed range         | x1 (Normal)    | None                 |
| listed range, up to 2x    | x2             | Disadvantage         |
| 2x listed range, up to 3x | x3             | Disadvantage and -5  |
| 3x listed range, up to 4x | x4             | Disadvantage and -10 |
| beyond 4x                 | -              | Out of range         |

At long range (x3 and beyond) targets have advantage on saves caused by the attack and any deviation dice are doubled.
Burst, Controlled Burst, Spray, and Riddle suffer **an additional -5 per Range Multiple beyond x1** (so -5 at x2, -10 at
x3, -15 at x4), stacking on top of the table above. See [Combat Actions](combat-actions.md) for full firing-mode rules.

> **Example (Pistol, Range 30 ft):** Bands are 0-30 (x1), 31-60 (x2), 61-90 (x3), 91-120 (x4). A target at 70 ft is *
*x3 = Disadvantage and -5**. A Controlled Burst at the same range adds another **-10** (Burst/Auto: -5 per Multiple
> beyond x1, summed across x2 and x3) for a total of **Disadvantage and -15**.
>
> **Example (Assault Rifle, Range 120 ft):** Bands are 0-120 (x1), 121-240 (x2), 241-360 (x3), 361-480 (x4). A target at
> 300 ft is **x3 = Disadvantage and -5** for a Single Shot. A Controlled Burst at 300 ft adds another **-10** for a total
> of **Disadvantage and -15**. A target at 500 ft is out of range entirely.

**Reloading:** Spend an action or one attack to reload when empty. A reload consumes one spare magazine from your
carried pool; see [Ammunition](ammunition.md).

**Recoil (-):** If Strength is less than the Recoil value, -1 to Single-Shot attack rolls; for Burst/Auto, attack
penalty = Recoil - Strength.

**Critical Success/Failure:** Natural rolls at or below the critical-failure range auto-fail; natural rolls at or above
the critical range score a critical (double damage dice).

**Close Quarter Combat (CQC):** No disadvantage firing within 5 ft of an enemy.

**Covert:** Advantage on Sleight of Hand to conceal.

**Manual Action:** After firing, spend an action or sacrifice an attack to chamber the next round.

**Blast (-ft):** Creatures within the radius make a DEX save DC 8 + proficiency + DEX mod (if proficient). Fail = full
damage; pass = half.

**Braced:** Disadvantage on attack rolls unless braced (bipod, wall, sandbags, etc.).

**Dependable:** On a misfire, roll two d100 and use the higher.

**Ignite:** On damage to a creature wearing cloth, ignites for 1d6 fire damage per round until extinguished (action).

**Inaccurate (-):** -N penalty to attack rolls with this weapon.

**Lite:** Compact, lightweight, and easy to carry concealed. Allows off-hand bonus-action attacks without dual-wielding
training, and grants advantage on Sleight of Hand to draw quickly. (Distinct from the "Light" armor weight class.)

**Mounted:** Cannot be fired without a tripod, bipod, or vehicle mount. Setting up the mount costs an action.

**Select Fire (S/B/A):** The weapon offers more than one firing mode - any combination of Single-shot, Burst, and Auto.
Switch modes as a free action on your turn.

**Engulf (-ft):** Cone; targets make DEX save DC 8 + DEX + Prof; pass = half damage.

**Misfire:** Natural roll at or below misfire = attack misses; roll d100 on the misfire chart.

| d100   | Result                                                                                                                                 |
|--------|----------------------------------------------------------------------------------------------------------------------------------------|
| 1      | FUBAR - destroyed; full replacement cost                                                                                               |
| 2-5    | Requires replacement parts (% of full cost d100), then day of work + DC 15 Weapon Maintenance and Armorer's Tools checks. Fail = FUBAR |
| 6-10   | Broken. Long rest + DC 15 Armorer's Tools. Fail = treat as 4-10%                                                                       |
| 11-15  | Broken. Short rest + DC 10 Weapon Maintenance. Fail = treat as 11-20%                                                                  |
| 16-60  | Jammed. Action + DC 10 DEX check. Fail = treat as 21-45%                                                                               |
| 61-100 | Weapon fine; you just missed                                                                                                           |

**Takedown:** On damage, target CON save (DC = damage). Fail = Prone.

**Quirky:** Non-proficient users fire at disadvantage.

**Imprecise:** Disadvantage when firing into a melee.

**Unreliable:** On a misfire, roll two d100 and use the lower.
