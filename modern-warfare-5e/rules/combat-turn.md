---
title: Combat Turn
aliases: [ Initiative, Action Economy, Round, Turn, Surprise, Reaction, Bonus Action ]
tags: [ rules, combat ]
---

# Combat Turn

Combat is broken into **rounds**. A round represents about 6 seconds of in-fiction time and gives every creature one
turn. Within a round, characters act in **initiative** order. On their turn, each character has a budget of movement
plus a small set of action types. This page covers the structure; specific firing-mode actions live in
[Combat Actions](combat-actions.md).

## Rolling Initiative

Initiative is a [DEX check](ability-checks.md): `1d20 + DEX modifier + situational bonuses`. Higher results act first.
Ties between two creatures are broken by higher DEX score, then by player decision.

- **Born to Fight** (Personality Trait): +5 to initiative.
- **Advanced Awareness Training Level 1**: advantage on initiative rolls.
- The GM may apply **disadvantage** for being asleep, drugged, or otherwise impaired at the moment combat starts.

> **Example:** Falke (DEX +3) and a militant (DEX +1) both roll initiative. Falke rolls **1d20 → 14**, +3 = **17**.
> The militant rolls **1d20 → 18**, +1 = **19**. Militant goes first this round, then Falke, then everyone else in
> order.

## Surprise

If one side starts combat without the other being aware - a successful ambush, a silent breach, a sniper opening
without warning - the unaware creatures are **Surprised**. Surprised creatures cannot move or take any action or
reaction during the first round of combat. They roll initiative as normal but are skipped on their first turn. From
round two onward they act normally.

The GM determines awareness via passive Perception (see [Ability Checks](ability-checks.md#passive-checks)) versus the
attacker's Stealth.

## What's On Your Turn

Each turn you get:

- **Movement** up to your speed, broken however you like (see [Movement](movement.md)).
- **One Action**.
- **One Bonus Action**, *only* if you have a feature or ability that grants one this turn.
- **One Free Object Interaction** - drop a mag, draw a pistol, open an unlocked door, push a button. A second
  interaction in the same turn costs your action (Use an Object).

You also have **one Reaction** per round, used outside your turn.

You can split movement around your action: move 15 ft, fire, move another 15 ft. You can take your bonus action before
or after your action. You cannot bank unused movement or actions for later.

## Actions

The standard menu of actions is:

| Action               | Effect                                                                                                                       |
|----------------------|------------------------------------------------------------------------------------------------------------------------------|
| **Attack**           | Make one weapon attack (or more, with Extra Attack). See [Combat Actions](combat-actions.md).                                |
| **Aim**              | +2 to ranged attack rolls against one chosen target until line of sight breaks. See [Combat Actions](combat-actions.md#aim). |
| **Dash**             | Move up to your speed again this turn (so total movement = 2× speed).                                                        |
| **Disengage**        | Movement no longer provokes opportunity attacks for the rest of the turn.                                                    |
| **Dodge**            | Until your next turn: attacks against you have disadvantage; you have advantage on DEX saves.                                |
| **Help**             | Grant an ally advantage on their next ability check or attack against a creature within 5 ft of you.                         |
| **Hide**             | Make a DEX (Stealth) check, contested by the watchers' passive Perception. See [Cover](cover.md).                            |
| **Ready**            | Choose a trigger and a single action; the action fires as a reaction when the trigger occurs.                                |
| **Search**           | Make a WIS (Perception) or INT (Investigation) check.                                                                        |
| **Use an Object**    | A second object interaction this turn, or use a piece of gear that requires it.                                              |
| **Suppressive Fire** | See [Combat Actions](combat-actions.md#suppressive-fire). Mutually exclusive with Attack on the same turn.                   |
| **Use a Feature**    | Activate any class, designation, or training-program ability that lists "as an action."                                      |

[Combat Actions](combat-actions.md) adds firing-mode actions (Spray, Riddle, Controlled Burst, Burst Fire) on top of
this menu.

## Bonus Actions

Bonus actions never come from nowhere - they are explicitly granted by a feature, weapon property, or ability. You
cannot turn an unused action into a bonus action. Common sources:

- **[Second Wind](../operator-class.md#second-wind)** - regain HP.
- **[Machine Gunner](../designations/machine-gunner.md) Suppressive Fire** - upgrades suppression to a bonus action.
- **[Combat Medic](../designations/combat-medic.md) Dash** - bonus-action Dash if you used your action to heal.
- Reloads on certain weapons, off-hand attacks under Two-Weapon Fighting, and assorted designation features.

You can have multiple bonus-action options available, but you can use at most one per turn.

## Reactions

A reaction is one off-turn response per round, refreshing at the start of your next turn. It must be triggered by an
event you can perceive. Common reactions:

- **Opportunity Attack** - when a hostile leaves your reach without Disengaging, you may make one melee attack.
- **Ranged Opportunity Attack** - when a creature you've Aimed at moves more than 5 ft,
  see [Combat Actions](combat-actions.md#ranged-opportunity-attack).
- **Dirty Fighting** (Basic Training) - impose disadvantage on an adjacent attacker.
- **Get Your Head Down** ([Unit Leader](../designations/unit-leader.md)) - spend a Leadership Die to grant a nearby ally
  cover.
- **Indomitable** ([Operator Class](../operator-class.md#indomitable)) - reroll a failed save (after seeing the result).
- A Readied action triggering.

A creature with multiple available reactions still gets only one per round.

## Action Surge

Once per short or long rest, [Action Surge](../operator-class.md#action-surge) grants a single extra action on your
turn. It does not grant a second bonus action or a second reaction. Multiple uses unlock at higher Operator levels.

## End of Turn

A handful of effects resolve at the end of the acting creature's turn rather than the start: certain conditions tick,
ongoing damage applies, a few designation features count down. The GM tracks these.

## Compared to Classic D&D 5E

- Initiative, the action menu, bonus action / reaction structure, and Free Object Interaction are all classic-5E
  mechanics, lifted directly.
- Surprised creatures losing the first turn matches the *2024* 5E surprise rules, not the legacy "no actions and no
  reactions on turn one then advantage on attacks against you" version - this compendium uses the cleaner version.
- The custom actions (Aim, Suppressive Fire, firing modes, ranged opportunity attack) are specific to this system; the
  slot they consume is the same.
- Action Surge works the same way (extra action, not extra bonus action).
