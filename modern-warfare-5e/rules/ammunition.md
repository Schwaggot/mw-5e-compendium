---
title: Ammunition
aliases: [ Magazines, Mags, Ammo, Spare Mags, Resupply ]
tags: [ rules, weapon, combat ]
---

# Ammunition

Firearms in Modern Warfare 5E carry a finite supply. A weapon's magazine holds a fixed number of rounds (the `Ammo N`
property on every weapon stat block). When it runs dry, you reload by swapping in one of the spare magazines you carry
in your rig. This page defines how many mags you start with, what they weigh, and how you get more.

## Loaded Magazine

Each magazine in your carried pool tracks its own round count. At character creation and after a full resupply, every
mag is full to the weapon's `Ammo N` capacity; mid-mission they may be partially loaded (see [Reloading](#reloading)
below).

- When you fire, subtract rounds from the loaded magazine per the firing-mode rules in
  [Combat Actions](combat-actions.md). Single Shot costs 1 round, Burst Fire costs 3, Spray / Riddle / Controlled Burst
  cost 1d4+2, Suppressive Fire costs 3 / 1d4+2 / 1 burst per target.
- A weapon at 0 rounds is empty and cannot fire until reloaded.

> **Example (ammo burn-through):** Falke's assault rifle is Select Fire S/B/A with a full 30/30 mag. He uses Spray
> against three militants in a corridor - 1d4+2 rounds per target. He rolls 5, 4, and 6 = **15 rounds consumed in one
> action**. The loaded mag drops to 15/30. Another volley like that and he's swapping to a fresh mag.

## Reloading

A reload (action or one attack, per [Weapon Properties](weapon-properties.md) and the
[Reload action](combat-turn.md#actions)) swaps the loaded magazine for any one from your carried pool. By default you
grab a full mag, but you can pick a specific partial on purpose if the situation calls for it.

The mag you just took out is **not destroyed**. What happens to it depends on how you reload:

- **Stowed reload** (default): the swapped-out mag goes into your dump pouch or back on the rig. It keeps whatever
  rounds remained and stays in your pool as a partial. This is the normal tactical reload.
- **Speed reload** (narrative): you fling the old mag away to save the heartbeat it takes to pouch it. The mag is lost
  unless you pick it back up as a free object interaction. GM call - most operators only speed-reload when it actually
  matters.

> **Example (tactical reload):** Falke has 5 rounds left in his 30-round rifle mag after a hallway fight. Before the
> next room he spends his action to reload, pocketing the partial. His pool now holds **3 full mags + 1 partial at
> 5/30**. The partial sits in his dump pouch until he consolidates later.

> **Example (speed reload under fire):** Falke is pinned, rifle dry, a militant stacking on his door. He speed-reloads,
> slinging the empty mag off into the hallway to save the beat. Later, if he survives the breach, the GM rules he
> could crawl out and recover it - but right now it is **gone from his inventory**.

## Consolidating Partials

Out of combat, you may pour rounds from one partially-filled magazine into another as a **1-minute** activity. Rounds
move between mags; no rounds are created or destroyed. Empty, discarded mags are not recovered automatically - pick
them up off the ground if you want them back.

> **Example (consolidation):** Falke ends a patrol with three partials - 22/30, 11/30, and 5/30 (38 rounds total
> across three mags). He spends 1 minute consolidating: 22 + 8 from the 11-mag tops one mag to 30/30, leaving 3
> rounds; those 3 combine with the other 5 into a second partial at 8/30. His pool is now **1 full (30/30), 1 partial
> (8/30), and 1 empty**.

## Starting Loadout

Each weapon you bring to character creation comes with a baseline pool of magazines at no additional Requisition cost.
The count below *includes* the one already loaded in the weapon:

| Weapon class                                   | Magazines / rounds included |
|------------------------------------------------|-----------------------------|
| Pistol, Revolver                               | 3 magazines                 |
| SMG, Shotgun                                   | 4 magazines                 |
| Assault Rifle, Semi-Auto Rifle, Bolt-Action    | 6 magazines                 |
| Machine Gun (SAW / GPMG / HMG)                 | 3 belts                     |
| Rocket Launcher                                | 2 rounds                    |
| Grenade Launcher (standalone)                  | 4 rounds                    |
| Grenade Launcher (underbarrel, e.g. M203)      | 6 rounds                    |

You may purchase additional magazines during character creation or downtime at **0.5 Req per spare mag** (pistol, SMG,
shotgun, rifle) or **1 Req per belt, rocket round, or grenade round**. Extras add to your carried weight - see below.

## Magazine Weight

Loaded magazines and belts weigh as follows. Add these to your carried total in [Encumbrance](encumbrance.md).

| Magazine type                        | Loaded weight |
|--------------------------------------|---------------|
| Pistol / revolver (6-17 rd)          | 0.2 kg        |
| SMG (20-30 rd)                       | 0.3 kg        |
| Shotgun (5-8 shells, boxed)          | 0.2 kg        |
| 5.56 / 5.45 rifle (20-30 rd)         | 0.4 kg        |
| 7.62 rifle (10-20 rd)                | 0.5 kg        |
| .50 / anti-materiel (5-10 rd)        | 0.8 kg        |
| SAW belt (100-200 rd, drum / box)    | 2.5 kg        |
| GPMG belt (100-200 rd)               | 3.0 kg        |
| 40mm grenade (single round)          | 0.2 kg        |
| Rocket / AT round (single)           | 2.5 kg        |

An empty magazine weighs roughly half the loaded value; round to the loaded figure unless the GM wants finer precision.

## Magazine Modifications

The [Weapon Modifications](weapon-modifications.md#magazines) list has three magazine-related options:

- **Extended Magazine.** Increases per-mag capacity (+10 to +20 rounds by weapon class). Every magazine in your
  starting pool uses the upgraded capacity at no extra cost beyond the mod's Req price. Weight scales proportionally
  with the new round count.
- **Drum Magazine.** Same rule, larger increase (+30 to +70 rounds). Drums are visibly bulky; GM may impose
  disadvantage on Stealth (Sleight of Hand to conceal) for silhouette.
- **Quick Mag.** Reloads become a **free action**. No change to capacity or weight.

**Scaling weight.** Modified-mag loaded weight is the base weight (from the table above) times the ratio of new
capacity to base capacity. A 5.56 Extended mag (30 → 50 rd) weighs `0.4 × 50/30 ≈ 0.65 kg`. A 5.56 Drum (30 → 100 rd)
weighs `0.4 × 100/30 ≈ 1.3 kg`. Round to one decimal.

> **Example (Extended Mag):** Falke's Beretta AR70/90 (baseline Ammo 30) has the Extended Magazine mod (+20 rounds).
> His starting pool is still 6 magazines, but each now holds **50/50 rounds** and weighs ~0.65 kg. Total mag weight
> climbs from 2.4 kg to 3.9 kg - worth a check against his [Encumbrance](encumbrance.md) band before ruck-up.

## Resupply

- **Long rest at a secure, resupplied location** (base, FOB, established cache): all magazines refilled to the starting
  loadout amount. This is the default way ammo gets back into the rig.
- **Long rest in the field without supply access**: rounds remain as-is. You may still consolidate partials during the
  rest.
- **Short rest with a supply cache present**: top off the loaded mag from spares; consolidate partials. No net gain in
  rounds, just redistribution.
- **Scavenging**: compatible enemy mags (same weapon or caliber) can be taken and used directly at the GM's discretion.
  Rounds from incompatible magazines or bulk crates can be stripped at **1 minute per 10 rounds**.

> **Example (base resupply):** Falke rolls back to the FOB after a three-day patrol. His rifle pool is down to 1 full,
> 2 partials (14/30 and 7/30), and 1 empty - the sixth mag he speed-reloaded during the breach on day two and never
> recovered. After his long rest at the FOB, his pool returns to **6 full magazines**. The lost mag is replaced from
> stores; the partials top back up.

## Compared to Classic D&D 5E

- Classic 5E tracks ammunition one arrow or bolt at a time. This compendium tracks **magazines as the unit**, with
  per-round counting only inside the currently-loaded mag - much less bookkeeping for the same tactical pressure.
- The carry cap is the standard [Encumbrance](encumbrance.md) calculation, not a dedicated slot system. Every extra mag
  costs kilograms, not a special slot.
- Resupply on a long rest at base is the modern analogue to "restock in town." Field ops without resupply access keep
  the ammo pressure on until extract.
