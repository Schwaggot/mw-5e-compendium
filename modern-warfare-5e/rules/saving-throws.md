---
title: Saving Throws
aliases: [ Saves, Save, Save DC ]
tags: [ rules, combat ]
---

# Saving Throws

A **saving throw** (or "save") is a d20 roll your Operator makes to *avoid or reduce* something bad happening *to*
them - a flashbang going off in the room, a door blowing inward, gas filling the corridor, an interrogator getting in
your head. Unlike an attack roll or a skill check, you don't choose to make a save; the GM tells you to roll one because
something is being done to you.

In classic D&D 5E, saves get rolled against spells. Here they get rolled against blasts, gas, falls, suppression, fear,
and coercion. The mechanics are the same.

## How a Save Works

1. The GM names the save: "Make a DEX save" or "CON save against the gas."
2. The GM names a **Save DC** - usually 10 (easy), 12-13 (moderate), 15-16 (hard), 18+ (brutal). Hazards from gear and
   abilities list their DC explicitly.
3. You roll `1d20 + the relevant attribute modifier`. If you are trained in that save, also add
   your [Proficiency Bonus](proficiency.md).
4. Total ≥ DC = success. Total < DC = failure. Many effects also have a "half on a successful save" clause; the GM will
   say so.

> **Example:** Falke (Operator level 3, Proficiency Bonus +2, DEX 17 → mod +3, Save Training in DEX) is leaning out of
> a market-stall doorway when a frag grenade bounces in beside him. The GM calls a DC 14 DEX save - full damage on
> fail, half on success.
>
> - Rolls **1d20** → **12**.
> - Adds DEX modifier: 12 + 3 = 15.
> - Trained in DEX saves, adds Proficiency Bonus: 15 + 2 = **17**.
> - Total 17 vs DC 14 → **save**, takes half damage.
>
> A teammate diving for the same doorway, also DEX +3 but with no Save Training in DEX, would have rolled the same 12
> for a total of **15** - still a save, but only by 1. A militant in the stall (DEX +1, untrained) would roll 12 + 1 =
> **13**, just under the DC, and eat full damage.

## The Six Saves

Each of the six [Attributes](attributes.md) has a save. The attribute the save uses is the attribute that *would help
you avoid the effect*, not the attribute of whoever is causing it.

| Save    | What it covers                                                                                                 | Examples                                                                                                       |
|---------|----------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| **STR** | Resisting being moved, grappled, shoved, or physically pinned.                                                 | A breaching charge knocks you off the catwalk; an opponent tries to throw you from cover.                      |
| **DEX** | Dodging a sudden area effect, getting low, twisting out of the way.                                            | Frag grenade lands at your feet; a vehicle clips your position; a flashbang detonates in the room.             |
| **CON** | Enduring damage to the body itself - poison, disease, shock, suppression at close range, the worst of a blast. | Tear gas fills the room; a stim pushes you past safe limits; you take a heavy blast wave.                      |
| **INT** | Resisting confusion, deception, illusion, disorientation, or technical compromise.                             | A loud disorientation device scrambles your read of the room; a hostile network probe targets your kit.        |
| **WIS** | Holding your nerve and your read on the situation. The fear save.                                              | The Shaken track ([Conditions](conditions.md#shaken)); an interrogator works on your resolve; a horror moment. |
| **CHA** | Resisting attacks on your sense of self - long-form coercion, breaking cover, deep manipulation.               | An interrogator tries to break your cover identity over hours; coerced narrative under duress.                 |

## Save Training

Like all proficiencies in this compendium, save proficiency comes from a [Training Program](../training-programs.md) -
specifically, the **Save Training** track. At 1st level,
the [Operator Class](../operator-class.md#starter-training-programs)
grants Save Training Level 1 in **Strength** and **Dexterity** for free, mirroring the classic-5E Fighter chassis.

Each Save Training level you have in a given save adds your Proficiency Bonus to that save. Stacking the higher levels
of the track (or relevant Armor / Mental Fitness programs) can grant Expertise, which doubles the Proficiency Bonus -
see [Proficiency](proficiency.md#expertise).

> **Example:** Same firefight, ten minutes later. Falke (CON 11 → mod +0, **not** trained in CON saves) is clearing a
> back room when a CS-gas canister cooks off. The GM calls a DC 13 CON save against the gas - fail means a level of
> disadvantage on his next action and a round of coughing.
>
> - Rolls **1d20** → **11**.
> - Adds CON modifier: 11 + 0 = **11**. No Proficiency Bonus to add.
> - Total 11 vs DC 13 → **fail**. Eyes streaming, he stumbles back to the doorway.
>
> If Falke had picked up Save Training Level 1 in CON during a later operator-training pick, the same roll would have
> totaled 11 + 0 + 2 = **13** - exactly the DC, save. The single Proficiency Bonus is the difference between holding
> the room and giving it back.

## Save DC of Effects You Impose

When something *you* do forces another creature to save (a flashbang you threw, a takedown maneuver, a designation
feature), the DC the target rolls against is:

`Save DC = 8 + your Proficiency Bonus + the relevant ability modifier`

The "relevant ability" is named by the source of the effect - usually DEX for thrown ordnance, CHA for command and
intimidation effects, INT for technical attacks.

> **Example:** Falke (Proficiency Bonus +2, DEX +3) cooks off a flashbang and tosses it through the doorway of a small
> room. The flashbang's save is keyed to the thrower's DEX, so the DC is:
>
> `8 + 2 (Falke's Proficiency Bonus) + 3 (Falke's DEX modifier) = DC 13`
>
> Two militants are inside.
>
> - Militant A (CON +1, untrained): rolls **1d20** → **9**. 9 + 1 = **10** vs DC 13 → **fail**, stunned for one round.
> - Militant B (CON +2, untrained): rolls **1d20** → **15**. 15 + 2 = **17** vs DC 13 → **save**, no effect.
>
> If Falke levels up to 5 (Proficiency Bonus +3), the same flashbang would impose a DC 14 save - and Militant A's 10
> would still fail by the same margin, while Militant B's 17 would still clear it. Higher proficiency widens the gap
> on the marginal rolls, not the obvious ones.

## Compared to Classic D&D 5E

- The d20 + attribute mod (+ proficiency if trained) ≥ DC formula is identical.
- Six saves, one per attribute - same as classic 5E.
- Where classic 5E uses saves mostly against spells, this game uses them against modern hazards: explosives, gas,
  suppression, interrogation, and disorientation.
- Class-locked save proficiencies become Save Training Programs. Every Operator starts with STR and DEX trained, and can
  pick up the others as they level.
- Death saves work as in classic 5E (see [Conditions - Triage Code](conditions.md#triage-code) for how dying is handled
  in this compendium).
