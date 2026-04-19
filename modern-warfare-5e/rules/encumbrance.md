---
title: Encumbrance
aliases: [ Carry Capacity, Carry Weight, Load, Encumbered, Heavily Encumbered ]
tags: [ rules, character ]
---

# Encumbrance

Every piece of [Gear](../gear.md), [Armor](../armor.md), and [Weapon](../weapons.md) in the compendium lists a weight
in kilograms. Encumbrance is the bookkeeping that turns those weights into a carry limit. An Operator who is
overloaded moves slower and rolls worse on anything physical.

## Carry Limits

Carry capacity scales off your **Strength score** (the score, not the modifier).

| Threshold              | Limit                       | Effect                                                                                                                          |
|------------------------|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| **Light load**         | up to `2.5 × STR` kg        | No penalty.                                                                                                                     |
| **Encumbered**         | `2.5 × STR` to `5 × STR` kg | Speed -10 ft.                                                                                                                   |
| **Heavily encumbered** | `5 × STR` to `7 × STR` kg   | Speed -20 ft (min 5 ft); disadvantage on STR, DEX, and CON [checks](ability-checks.md), attacks, and [saves](saving-throws.md). |
| **Over max**           | above `7 × STR` kg          | Cannot carry. May drag at half speed (see *Push, Drag, Lift* below).                                                            |

> **Example:** Falke has STR 11 (his pre-trait score; the Agile trait dropped him from 13 to 11). His carry brackets
> are: light load up to 27.5 kg, encumbered 27.5-55 kg, heavily encumbered 55-77 kg, over max past 77 kg. With a full
> assault loadout (rifle + ammo + plate carrier + assault pack ~ 22 kg), he is in light load and pays no penalty. Add a
> 10-kg breaching kit for an op and he tips into Encumbered: -10 ft speed for the duration.

## Push, Drag, Lift

You can move heavier loads if you're not trying to carry them on you the whole turn:

- **Push, drag, or lift** up to twice your max carry (`14 × STR` kg). Speed is halved while doing so.
- A casualty drag is the canonical use: a 75-kg casualty is well over Falke's 77-kg ceiling, so he can drag but not
  carry. He moves at half speed and his hands are full.

## What Counts as Carried

Add up everything on your person: armor worn, weapons slung or holstered, ammo in mags and on the rig, the contents of
your pack, and any consumables. Items dropped at your feet, set on a table, or stashed in a vehicle do not count
against carry weight until you pick them up.

A few common loadouts for reference:

| Loadout                   | Approx Weight | What's In It                                                                         |
|---------------------------|---------------|--------------------------------------------------------------------------------------|
| **Patrol minimum**        | ~10 kg        | Rifle + 4 mags + IFAK + canteen + admin pouch.                                       |
| **Assault loadout**       | ~22-25 kg     | Plate carrier with plates + rifle + 8 mags + IFAK + grenades + radio + assault pack. |
| **Long-range patrol**     | ~30-35 kg     | Assault loadout + full ruck (rations, sleeping kit, batteries, sat radio).           |
| **Demo / breach loadout** | ~35-40 kg     | Assault loadout + breaching charges + crowbar + extra ammo + spare batteries.        |
| **Bomb suit on the man**  | ~50+ kg       | EOD work; speed already capped by the suit itself.                                   |

## Reducing Load

Common ways to stay out of the encumbered band:

- **Cache it.** Drop the ruck at the ORP before the assault; pick it back up on exfil.
- **Distribute.** A SAW gunner's belt-fed ammo gets parceled out across the squad.
- **Right-size the kit.** A reconnaissance op does not need the breaching kit. Match the loadout to
  the [Mission Kit](../gear.md#mission-kits).
- **Stronger Operator.** Higher STR shifts every threshold up linearly. Two more STR points = +5 kg of light-load room.

## Vehicles and Carry Capacity

Vehicles have their own load limits set by the GM. An Operator in a vehicle does not count personally-carried weight
against personal encumbrance for the purposes of speed and check penalties - they do, however, have to *get out of*
the vehicle still wearing it.

## Compared to Classic D&D 5E

- The mechanic mirrors the classic 5E **variant encumbrance rule** (the standard 5E rule is "you have a flat carry max
  and otherwise no penalty," which this game finds too forgiving for modern combat).
- Classic 5E uses pounds and `5 × STR` / `10 × STR` / `15 × STR` thresholds. This compendium uses kilograms and the
  rounded `2.5 × STR` / `5 × STR` / `7 × STR` thresholds, which works out to roughly the same in absolute terms once you
  convert.
- Push/drag/lift at 2× max carry, half speed, is unchanged.
- The compendium adds a fourth band (over max → drag only); classic 5E just rules it impossible.
