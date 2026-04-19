---
title: Ability Checks
aliases: [ Skill Checks, Ability Check, Check, DC, Contested Check, Passive Check ]
tags: [ rules, character ]
---

# Ability Checks

An **ability check** is a d20 roll the GM asks for when an Operator tries something whose outcome is uncertain - kicking
in a door, picking a lock, reading a map in low light, talking down a checkpoint guard. Together with attack rolls and
[saving throws](saving-throws.md), checks are the third of the three core d20 pillars in the system.

If the GM doesn't ask, you don't roll. Routine, no-stakes actions just succeed (or just fail, if the situation is
hopeless). Checks come out when there's both a chance of success and a meaningful consequence for failure.

## The Basic Formula

`1d20 + ability modifier + Proficiency Bonus (if trained) + situational modifiers`

The GM names a **Difficulty Class (DC)**. Roll ≥ DC = success; roll < DC = failure. The ability and any training are
named together: a "DEX (Stealth) check" is `1d20 + DEX mod`, plus your Proficiency Bonus if you have Skills Training in
Stealth (see [Proficiency](proficiency.md)).

| DC | Difficulty                                |
|----|-------------------------------------------|
| 5  | Very easy (an untrained civilian usually) |
| 10 | Easy (a trained operator usually)         |
| 13 | Moderate                                  |
| 15 | Hard                                      |
| 18 | Very hard                                 |
| 20 | Heroic                                    |
| 25 | Nearly impossible                         |
| 30 | The stuff of after-action legend          |

The GM picks the DC from the situation, not from the character's stats.

## Choosing the Attribute

Most checks are named by attribute and skill together: STR (Athletics), DEX (Sleight of Hand), WIS (Perception), CHA
(Intimidation), and so on. The skill names what kind of action it is; the attribute names what kind of effort it
takes. The GM may call for an unusual pairing when the situation warrants - a STR (Intimidation) check to physically
loom over a captive, a CHA (Performance) check to carry a cover identity at a function. The attribute follows the
*nature of the effort*, not a fixed list. See [Attributes](attributes.md) for what each one covers.

## Contested Checks

When two characters oppose each other directly - one sneaking, one watching; one hiding a weapon, one frisking; an
arm-wrestle - both make a check. Higher total wins. **Ties go to the defender** (the one not actively trying to change
the situation). If neither is the defender, ties result in no change.

> **Example:** Falke (DEX +3, trained in Stealth, Proficiency +2) is moving past a roving sentry (WIS +1, untrained in
> Perception). Falke rolls a DEX (Stealth) check: **1d20 → 12**, total 12 + 3 + 2 = **17**. The sentry rolls a WIS
> (Perception) check: **1d20 → 18**, total 18 + 1 = **19**. The sentry's 19 beats the 17. Falke is spotted.

## Passive Checks

A **passive check** is a check the GM rolls in your head with the assumption that the die came up 10. Used for ongoing
activity or for things you would do whether or not you knew you were doing them - noticing a trip wire, hearing a
footstep, reading a stranger's mood.

`Passive score = 10 + ability modifier + Proficiency Bonus (if trained) + situational modifiers`

- **Advantage on the relevant roll**: +5 to the passive score.
- **Disadvantage**: -5 to the passive score.

The compendium leans hardest on **passive Perception**, used by the GM to set ambush, stealth, and "do you notice"
thresholds. Awareness Training boosts it directly; see [Awareness Programs](../training/awareness-programs.md).

## Group Checks

When the whole squad is doing the same thing - patrolling silently, slogging through a swamp, breaking and entering -
the GM may call a **group check**. Everyone rolls; if **half or more** succeed, the group succeeds. Strong members
carry weak ones, but only so far.

## Help, Tools, and Working Together

- **Help action**: An ally adjacent to you can use their action to grant you advantage on your next ability check,
  provided they could plausibly help (a sniper spotter helping the shooter; a teammate boosting you over a wall). One
  helper per check.
- **Tools and kits**: When you have the right kit and Tools Training for it, add Proficiency Bonus to the check. Without
  the kit, the GM may rule the check is impossible or apply disadvantage.
- **Repeat attempts**: For non-time-pressured actions, the GM may allow a retry after a short delay. For time-pressured
  actions, you usually get one roll.

## When Not To Roll

The GM should not call a check when:

- The action would obviously succeed (turning a doorknob, walking up a staircase).
- The action is impossible regardless of the roll (lifting a vehicle bare-handed).
- The information would not change the player's choice (rolling Insight on a known ally giving an honest brief).

## Examples

> **Example:** Falke is reading a sniper's range card written in Pashto. The GM calls a DC 13 INT check, but Falke has
> Language Training in German and English only - no Pashto. He rolls **1d20 → 14**, +1 INT = **15**. He'd clear the
> DC, but the GM rules the language barrier means he can read the *numbers* and the *grid* but not the marginalia, so
> he gets partial intel.

> **Example - contested with disadvantage:** A militant tries to wrestle Falke's rifle out of his hands. Both make
> contested STR (Athletics) checks. Falke is one-handed (he was reloading) so the GM gives him disadvantage. Falke
> rolls **2d20 → 16 and 4**, takes the 4, +0 STR +2 Proficiency = **6**. Militant rolls **1d20 → 11**, +2 STR (no
> training) = **13**. Falke loses the rifle.

## Compared to Classic D&D 5E

- The d20 + mod + proficiency formula and the DC ladder are identical.
- Skill list is trimmed (no Arcana, Religion, Performance is rare) and reflavored (Investigation is scene-reading,
  Nature is terrain/weather).
- Passive checks work exactly the same; advantage/disadvantage adjust ±5 as in classic 5E.
- Contested checks tie to defender, same as classic 5E.
- Help, group checks, and tool proficiencies all work the same; the source of training is just different.
