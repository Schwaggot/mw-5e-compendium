---
title: Proficiency
aliases: [ Proficiency Bonus, Expertise, Trained ]
tags: [ rules, character ]
---

# Proficiency

"Proficient" means you have been formally trained on the thing - a weapon, a piece of armor, a skill, a save, a tool.
When you roll a d20 for something you are proficient in, you add your **Proficiency Bonus** on top of the relevant
attribute modifier. Lacking proficiency is not a fail-state; it just means you roll without the bonus, and on
specialized gear it can mean disadvantage.

In classic D&D 5E proficiencies come bundled with race, class, and background. In this compendium almost all
proficiencies come from [Training Programs](../training-programs.md) - formal courses an Operator has completed. A few
are granted up front by the [Operator Class](../operator-class.md#starter-training-programs) and by your
[Personality Trait](../personality-traits.md).

## Proficiency Bonus

A flat number that scales with Operator level. It comes off
the [Operator Class](../operator-class.md#operator-class-table) table:

| Operator Level | Proficiency Bonus |
|----------------|-------------------|
| 1-4            | +2                |
| 5-8            | +3                |
| 9-12           | +4                |
| 13-16          | +5                |
| 17-20          | +6                |

Identical scaling to classic 5E.

## Where the Bonus Applies

You add your Proficiency Bonus once - never twice (except Expertise, below) - to a d20 roll when you are proficient in
the thing being rolled. Common cases:

- **Weapon attack rolls** with a weapon class you have Weapons Training in.
- **Skill checks** for a skill you have Skills Training in (Perception, Athletics, Stealth, etc.).
- **Saving throws** for an attribute you have Save Training in (see [Saving Throws](saving-throws.md)).
- **Tool checks** for a kit you have been trained on (medic's kit, demolitions kit, thieves' tools, etc.).
- **Save DCs you impose**: when an ability of yours forces another creature to save, the DC is
  `8 + your proficiency bonus + the relevant ability modifier`.

You do **not** add Proficiency Bonus to passive Perception's base; you add it only if you are trained in Perception. The
general rule "if you are trained, the bonus shows up" holds across the system.

> **Example:** Falke (Operator level 3, Proficiency Bonus +2, DEX 17 → mod +3) snaps a shot at a militant 60 m down
> the alley with his M4. The militant's AC is 14. Falke has Weapons Training in Assault Rifles, so the math is:
>
> - Rolls **1d20** → **11**.
> - Adds DEX modifier: 11 + 3 = 14.
> - Adds Proficiency Bonus: 14 + 2 = **16**.
> - Total 16 vs AC 14 → **hit**.
>
> The squad's grenadier (also DEX +3, but trained only in Pistols and Grenade Launchers) firing the same M4 at the
> same target would have rolled the same 11, added +3, and gotten 14 - just barely tied to the AC, missing the hit
> Falke landed.

## Trained vs Untrained

You can still attempt almost anything untrained - pick up an unfamiliar rifle, drive a vehicle you've never seen, try to
read a foreign road sign.

- **Trained:** Attribute modifier + Proficiency Bonus. Specialized gear works as designed.
- **Untrained:** Attribute modifier only. For specialized gear (heavy weapons, surgical tools, demolitions, certain
  armor), the GM may also impose disadvantage, slow operation, or rule that the action is impossible without
  supervision.

Specific Training Program tracks remove disadvantage as their first level - that is the most common Level 1 effect
across the [Training Programs](../training-programs.md) section.

> **Example:** Same firefight. The militant Falke just dropped was carrying a Russian PKM, and now Falke wants to
> grab the belt-fed and suppress the rooftop (AC 13 for the rooftop shooter behind partial cover). He has no Weapons
> Training in Heavy Machine Guns, so the GM rules disadvantage on the first burst while he gets a feel for the recoil
> and cyclic rate.
>
> - Rolls **2d20, takes the lower** (disadvantage) → 14 and **6**, takes the 6.
> - Adds DEX modifier: 6 + 3 = **9**. No Proficiency Bonus to add.
> - Total 9 vs AC 13 → **miss**.
>
> Had Falke been trained in Heavy Machine Guns, he would have rolled a single d20 (say a 14), added +3 + 2 = **19**, and
> the burst would have walked the target off the roof. Untrained costs him both the bonus and the better die.

## Expertise

A handful of advanced training tracks grant **Expertise**. While Expertise is in effect, you add **double your
Proficiency Bonus** instead of the normal single bonus. Examples:

- Some [Armor Proficiency](../training/armor-proficiency-programs.md) levels grant Expertise on a specific save while
  wearing that armor class.
- Higher levels of [Physical Skills Training](../training/physical-fitness-programs.md) can upgrade an existing skill
  proficiency to Expertise.

Expertise never stacks with itself - if two sources both grant Expertise on the same roll, you still only double once.

> **Example:** Doc (Operator level 5, Proficiency Bonus +3, CON 14 → mod +2) is in a heavy plate carrier and has Heavy
> Armor Training to a level that grants Expertise on CON saves while wearing heavy armor. A breaching charge goes off
> in the next room - the GM calls a DC 14 CON save against the blast wave (full damage on fail, half on success).
>
> - Rolls **1d20** → **8**.
> - Adds CON modifier: 8 + 2 = 10.
> - Adds **double** Proficiency Bonus (Expertise): 10 + 6 = **16**.
> - Total 16 vs DC 14 → **save**, takes half damage.
>
> Without Expertise (single Proficiency Bonus) the same roll would have totaled 13 - one short of the DC, full damage.
> Without any Save Training in CON it would have been 10 flat, well below.

## How To Read Your Sheet

For any d20 roll, walk it in this order:

1. Identify the attribute (the GM will say "make a DEX save," "WIS check," etc.).
2. Add the attribute modifier from [Attributes](attributes.md).
3. Are you trained in the specific thing? If yes, add Proficiency Bonus. If Expertise applies, double it.
4. Add any situational bonuses (Aim, cover, training-program perks, gear tags).
5. Compare to the DC or AC the GM names.

> **Example:** Falke (level 3, Proficiency Bonus +2, STR 11 → mod +0) is climbing a chain-link fence under fire to
> break contact. The GM calls a DC 13 STR (Athletics) check.
>
> 1. Attribute: STR.
> 2. STR modifier: +0.
> 3. Trained in Athletics, so add Proficiency Bonus +2.
> 4. He's wearing a full assault ruck - the GM rules disadvantage.
> 5. Rolls **2d20, takes the lower**: 17 and **9**, takes the 9.
> 6. 9 + 0 (STR) + 2 (Proficiency) = **11**. Vs DC 13 → **fail** by 2. He gets caught on the wire and the GM has him
     > drop the ruck or take a turn untangling.
>
> If he had picked up Physical Skills Training high enough to get Expertise in Athletics, step 3 would be +4 instead of
> +2: 9 + 0 + 4 = **13**, exactly the DC, and he clears the fence cleanly. The same die roll, two different outcomes,
> separated by one training level.

## Compared to Classic D&D 5E

- The Proficiency Bonus number and scaling are identical.
- The source of proficiencies is different: Training Programs replace "class grants you these proficiencies."
- "Proficient" is sometimes called "trained" in this compendium - same meaning.
- Expertise works the same way (double the bonus) but is rarer and more situational - usually keyed to wearing the right
  armor or finishing an advanced track.
