---
title: Vision and Light
aliases: [ Light, Darkness, Dim Light, Bright Light, Obscured, Smoke, NVG, Night Vision, Thermal ]
tags: [ rules, combat ]
---

# Vision and Light

Whether you can see your target - and how clearly - shapes every roll in a firefight. The system uses three light
levels and two grades of obscurement, lifted from classic 5E and extended with optic and signaling gear that
selectively defeat them. This page covers the baseline; the [Optics](../gear/optics.md) and
[Electronics](../gear/electronics.md) pages cover the gear that bends it.

## Light Levels

| Level            | What It Looks Like                                  | Effect on Sight                                                                                        |
|------------------|-----------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| **Bright light** | Daylight, well-lit room, vehicle headlights on you. | Normal vision. No penalty.                                                                             |
| **Dim light**    | Twilight, moonlight, street with lit windows.       | Area is **lightly obscured**: disadvantage on WIS (Perception) checks relying on sight.                |
| **Darkness**     | No moon, interior with lights off, deep cellar.     | Area is **heavily obscured**: vision-based perception fails; creatures inside are effectively Blinded. |

A torch or weapon-light makes a 20-ft radius bright and another 20-ft radius dim. Vehicle headlights, building
floodlights, and parachute flares are larger but still finite cones. Outside the cone, the natural light level applies.

## Obscurement

Obscurement and light level interact - light tells you what's possible, obscurement tells you what's actually blocking
sight in the moment.

- **Lightly obscured** (dim light, light fog, foliage, light smoke): disadvantage on WIS (Perception) checks made by
  sight.
- **Heavily obscured** (darkness, thick smoke, dense fog, deep undergrowth): a creature in the area is treated as *
  *Blinded** when trying to see anything in or beyond it.

A creature inside a heavily obscured area has total concealment from creatures outside it: attackers have disadvantage,
target has advantage on attacks (because the attacker can't see). This is **concealment**, not [cover](cover.md) - it
hides you, but it does not stop rounds.

## Signature Gear

Three gear-tag families exist specifically to bend the rules above. Every relevant item lists one or more of them; see
[Gear Tags](../gear.md#gear-tags).

### Night-Vision (NVG)

Items tagged `night-vision` (PVS-14 monocular, GPNVG-18 quads, etc.) treat **darkness and dim light as bright light**
out to the device's range (typically 100 ft). Restrictions:

- NVGs flatten depth perception and narrow the field of view; the GM may impose disadvantage on close-range Perception
  or fast head-tracking while wearing them.
- A bright light source (muzzle flash, vehicle headlight, flashbang) inside the device's field can wash it out for 1
  round.
- NVGs do not penetrate smoke, fog, or solid obstacles.

### Thermal

Items tagged `thermal` show heat signatures rather than visible light.

- See through smoke, light foliage, and most concealment.
- See warm bodies in darkness regardless of light level.
- Cannot read text, signs, or detail; identifying a face from heat alone is impossible.
- Cannot see through solid walls, glass blocks IR, and very cold targets (recently dead, deeply hypothermic, in heavy
  insulation) may register dimly or not at all.

### IR Strobe / IR Marker

Items in [Electronics](../gear/electronics.md) like IR strobes and IR chemlights are invisible to the naked eye but
flash brightly under NVG.

- Used to mark friendlies, LZs, downed casualties, and IR-cleared corridors.
- A creature without NVG cannot see them at all.
- An enemy with NVG can absolutely see them - which is why IR discipline is part of the brief.

## Magnified Optics

Items tagged `magnified` (scopes, spotting scopes, binoculars):

- **Advantage** on WIS (Perception) checks at long range.
- **Disadvantage** to spot close movement (narrow field of view).

This is the only common case in the system where you can roll *both* with advantage and disadvantage on different
related checks within the same scene; per [Advantage and Disadvantage](advantage.md), they each apply to their own
roll, not to each other.

## Smoke and Concealment

Smoke grenades and battlefield smoke are heavily obscured for everyone except `thermal` users.

- An Operator inside the smoke is concealed (attackers have disadvantage; they have advantage attacking out, but cannot
  see beyond the cloud either).
- Smoke does not stop rounds. Suppressive fire walked through smoke still hits anyone unlucky enough to be in the line.
- Thermal optics see through most smoke; NVGs do not.

## Examples

> **Example - dim light:** Falke is moving down a poorly-lit alley (dim light). The militant at the far end is also
> in dim light. Falke makes a passive Perception check to scan for threats - it suffers -5 from the disadvantage of
> dim light on sight checks (Awareness Training Level 1 would remove this; Falke has it, so the -5 is gone). The
> militant, who lacks Awareness Training, is at -5 to *his* passive Perception. Falke spots the militant; the militant
> doesn't spot Falke. Falke gets the first move.

> **Example - NVG:** Same alley, no streetlights this time (darkness). Falke wears PVS-14 monoculars (`night-vision`,
> 100 ft range). The alley becomes effectively bright light for him out to 100 ft, so his attacks and Perception are
> normal. The militant has no NVG and is at darkness rules - heavily obscured, effectively Blinded. Attacks against
> Falke have disadvantage; Falke's attacks have advantage. The fight is a rout.

> **Example - smoke and thermal:** Falke pops a smoke grenade in the corridor and moves through it. A militant on the
> far side has a thermal monocular (`thermal`). The smoke does not affect his sight - he sees Falke's heat signature
> clearly and shoots normally. Falke, looking back through the cloud with his eyes only, sees nothing. The militant
> attacks at no penalty; Falke's return fire is at disadvantage.

## Compared to Classic D&D 5E

- Three light levels (bright / dim / darkness) and two grades of obscurement (lightly / heavily) are lifted directly
  from classic 5E.
- Lightly obscured = disadvantage on sight Perception; heavily obscured = effectively Blinded - same as classic 5E.
- This compendium replaces the racial darkvision trait with a kit slot: NVGs are gear, not biology, and they can be
  lost, broken, or jammed by light.
- Thermal, IR strobes, and magnified optics are homebrew gear tags, but each is a clean rules-text override of one
  specific obscurement clause.
