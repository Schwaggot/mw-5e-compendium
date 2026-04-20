---
title: Rüstung und Schutzausrüstung
aliases: [ Rüstung ]
tags: [ armor, equipment ]
---

# Rüstung und Schutzausrüstung

Für Schutzhandschuhe und -stiefel siehe [Kleidung - Handschuhe](gear/clothing.md#gloves)
und [Kleidung - Schuhwerk](gear/clothing.md#footwear).

## Stoppwirkung (NIJ-Stufen) {#stopping-power-nij-levels}

Rüstungen in diesem Kompendium werden nach dem NIJ-Standard eingestuft. Die Spalte **Stops** in jeder Tabelle unten
bezieht sich auf die Einstufung des weichen Panels; die Stoppwirkung von Gewehrplatten ist separat unter [Platten](#plates) aufgeführt.

| Level | Stops                                                                            |
|-------|----------------------------------------------------------------------------------|
| IIA   | 9mm, .40 S&W (Subsonic-Pistole).                                                 |
| II    | 9mm +P, .357 Magnum (Standardpistole).                                           |
| IIIA  | .357 SIG, .44 Magnum, die meisten Handfeuerwaffen und Schrotflinten-Slugs.       |
| III   | 7.62×51 FMJ und die meisten Standard-Gewehrmunitionen.                           |
| III+  | + 5.56 M855 und 7.62×39 MSC "Green Tip" mit Stahlkern.                           |
| IV    | .30-06 AP und die meisten panzerbrechenden Gewehrmunitionen.                     |

AC-Bonus und [DR](rules/damage-types.md#damage-reduction) von Rüstung/Platten gelten nur für die Seite/den Slot, die sie abdecken. Der
GM entscheidet, welches Teil einen bestimmten Treffer abfängt.

## Oberkörperrüstung {#torso-armor}

### Verdeckt (Tragbar unter Kleidung) {#covert-concealable}

Wird unter Zivilkleidung für Grayman-Einsätze, Personenschutz und Undercover-Operationen getragen. Keine Plattentaschen.

| Weste                   | AC       | Stops | Modifikatoren | Resistenzen        | Abdeckung      | Gewicht | Req |
|-------------------------|----------|-------|---------------|--------------------|----------------|---------|-----|
| Concealable Vest (IIA)  | 11 + DEX | IIA   | -             | Piercing           | Brust, Rücken  | 1.5 kg  | 3   |
| Concealable Vest (IIIA) | 12 + DEX | IIIA  | -             | Piercing, Slashing | Brust, Rücken  | 2.5 kg  | 5   |
| Safariland SX01 Elite   | 12 + DEX | IIIA  | -             | Piercing, Slashing | Brust, Rücken  | 2.2 kg  | 8   |
| Point Blank Vision      | 12 + DEX | IIIA  | -             | Piercing, Slashing | Brust, Rücken  | 2.3 kg  | 8   |

### Plattenträger {#plate-carriers}

Modulare Hüllen, die Gewehrplatten aufnehmen. **Stops** bezieht sich auf optionale Weichrüstungs-Einsätze; die Stoppwirkung der Platten
stammt von den Platten selbst (siehe [Platten](#plates)).

| Carrier               | AC               | Stops | Modifikatoren | Stealth | Resistenzen        | Abdeckung         | Plattentaschen        | Gewicht | Req |
|-----------------------|------------------|-------|---------------|---------|--------------------|-------------------|-----------------------|---------|-----|
| Plate Carrier (Light) | 12 + DEX         | -     | -             | -       | Piercing, Slashing | Torso             | Front/Back            | 5.5 kg  | 5   |
| Crye JPC              | 12 + DEX         | -     | -             | -       | Piercing, Slashing | Torso             | Front/Back            | 5.0 kg  | 10  |
| Crye AVS              | 13 + DEX (max 3) | IIIA  | -             | -       | Piercing, Slashing | Torso + Flanken   | Front/Back + Side × 2 | 7.0 kg  | 15  |
| LBT-6094              | 13 + DEX (max 3) | IIIA  | -             | -       | Piercing, Slashing | Torso + Flanken   | Front/Back + Side × 2 | 7.5 kg  | 15  |
| Eagle CIRAS           | 13 + DEX (max 3) | IIIA  | -             | -       | Piercing, Slashing | Torso + Flanken   | Front/Back + Side × 2 | 8.0 kg  | 15  |

### Splitterschutzwesten und Körperpanzer {#flak-vests-and-body-armor}

Weichrüstung mit integriertem Splitterschutz und Plattentaschen.

| Weste                           | AC               | Stops   | Modifikatoren                                                    | Stealth      | Resistenzen                            | Abdeckung                          | Plattentaschen        | Gewicht | Req |
|---------------------------------|------------------|---------|------------------------------------------------------------------|--------------|----------------------------------------|------------------------------------|-----------------------|---------|-----|
| Flak Jacket (Light)             | 13 + DEX (max 3) | IIIA    | -                                                                | -            | Piercing, Slashing                     | Brust, Rücken, Leiste              | Torso + Seite         | 7.5 kg  | 10  |
| Medium Flak / IBA               | 14 + DEX (max 2) | IIIA    | -                                                                | Disadvantage | Piercing, Slashing                     | Brust, Rücken, Leiste              | Torso F/B, Seite × 2  | 12 kg   | 15  |
| Medium Flak w/ Shoulders        | 15 + DEX (max 2) | IIIA    | -                                                                | Disadvantage | Piercing, Slashing                     | Brust, Rücken, Arme, Leiste        | Torso F/B, Seite × 2  | 14.5 kg | 20  |
| Medium Flak w/ Shoulders & Legs | 16               | IIIA    | Disadvantage auf DEX Saving Throws                               | Disadvantage | Piercing, Slashing                     | Brust, Rücken, Arme, Beine, Leiste | Torso F/B, Seite × 2  | 14.5 kg | 25  |
| Bomb Suit (EOD)                 | 18               | Frag/IV | -10 ft Bewegung, Disadvantage auf DEX Saving Throws und Checks   | Disadvantage | Bludgeoning, Piercing, Slashing, Force | Brust, Rücken, Arme, Beine, Leiste | Torso F/B, Seite      | 40 kg   | 40  |

## Platten {#plates}

Gewehrplatten werden in Carrier- und Westentaschen eingesetzt. Eine Platte schützt nur die Seite, auf der sie installiert ist.

### Oberkörperplatten {#torso-plates}

| Platte              | Level | Stops                                      | Vorteil                                    | Gewicht (jew.) | Req |
|---------------------|-------|--------------------------------------------|--------------------------------------------|----------------|-----|
| Steel Plate (III)   | III   | 7.62×51 FMJ und Standard-Gewehrmunition    | 2 DR gegen Schüsse auf die abgedeckte Seite| 4.0 kg         | 5   |
| Steel Plate (III+)  | III+  | + 5.56 M855, 7.62×39 MSC Green Tip         | 2 DR gegen Schüsse auf die abgedeckte Seite| 4.5 kg         | 8   |
| Ceramic SAPI (III)  | III   | 7.62×51 FMJ und Standard-Gewehrmunition    | 2 DR gegen Schüsse auf die abgedeckte Seite| 2.5 kg         | 10  |
| Ceramic ESAPI (IV)  | IV    | .30-06 AP und die meisten Gewehrmunitionen | 3 DR gegen Schüsse auf die abgedeckte Seite| 2.8 kg         | 15  |
| Polyethylene (III)  | III   | 7.62×51 FMJ und Standard-Gewehrmunition    | 2 DR gegen Schüsse auf die abgedeckte Seite| 1.5 kg         | 20  |
| Polyethylene (III+) | III+  | + 5.56 M855, 7.62×39 MSC Green Tip         | 2 DR gegen Schüsse auf die abgedeckte Seite| 1.8 kg         | 25  |

### Positionsplatten {#positional-plates}

Kleinere Platten für Flanken, Schultern, Kehle, Leiste und Beine. Die Werte gelten standardmäßig für Ceramic SAPI (III);
äquivalente Materialsubstitutionen folgen denselben Gewichts-/Req-Deltas wie bei Oberkörperplatten.

| Platte             | Abdeckung                 | Vorteil                                        | Gewicht (jew.) | Req |
|--------------------|---------------------------|------------------------------------------------|----------------|-----|
| Side Plate         | Flanke (unter dem Arm)    | 2 DR gegen Schüsse auf die abgedeckte Flanke   | 1.5 kg         | 10  |
| Shoulder Plate     | Hinterer Torso / Schultern| 2 DR gegen Angriffe auf den hinteren Torso     | 0.5 kg         | 10  |
| Leg Plates (pair)  | Oberschenkel / Leiste     | 2 DR beider Platten gegen Torso-/Leistenschüsse| 3.0 kg         | 10  |
| Throat Plate       | Hals / Kehle              | 2 DR gegen Halsangriffe                        | 0.3 kg         | 8   |
| Groin Plate (hard) | Leiste                    | 2 DR gegen Leistenangriffe                     | 0.5 kg         | 8   |

## Helme {#helmets}

| Helm                       | AC | Stops | Modifikatoren | Resistenzen                            | Gewicht | Req |
|----------------------------|----|-------|---------------|----------------------------------------|---------|-----|
| Bump Helmet (Ops-Core)     | +1 | -     | -             | Bludgeoning, Slashing                  | 0.6 kg  | 3   |
| Tactical Helmet            | +1 | -     | -             | Bludgeoning, Slashing                  | 0.9 kg  | 5   |
| PASGT                      | +1 | IIIA  | -2 Perception | Piercing, Slashing, Bludgeoning        | 1.6 kg  | 8   |
| MICH / ACH                 | +1 | IIIA  | -1 Perception | Piercing, Slashing, Bludgeoning        | 1.5 kg  | 10  |
| Ops-Core FAST Ballistic    | +1 | IIIA  | -             | Piercing, Slashing, Bludgeoning        | 1.3 kg  | 15  |
| Team Wendy Exfil Ballistic | +1 | IIIA  | -             | Piercing, Slashing, Bludgeoning        | 1.3 kg  | 15  |
| Crye AirFrame              | +1 | IIIA  | -             | Piercing, Slashing, Bludgeoning        | 1.2 kg  | 18  |
| Bomb Suit Helm             | +2 | -     | -5 Perception | Force, Piercing, Slashing, Bludgeoning | 1.8 kg  | 20  |

### Helm-Zusätze {#helmet-add-ons}

| Zusatz                         | Effekt                                                                                  | Gewicht | Req |
|--------------------------------|-----------------------------------------------------------------------------------------|---------|-----|
| Mandible (Ops-Core)            | +1 AC gegen Gesichtsschüsse; -1 Perception                                              | 0.3 kg  | 8   |
| Face Shield (Ballistic Visor)  | +1 AC gegen Gesichtsschüsse; Resistenz gegen Piercing und Slashing am Gesicht (Stops IIIA) | 0.5 kg  | 10  |
| Helmet Cover (Camo)            | Verleiht einen `camo-<terrain>` Tag passend zur Tarnung                                 | 0.1 kg  | 1   |

## Weichrüstungs-Zusätze {#add-on-soft-armor}

Zusätzliche Weichrüstungsteile, die an einem Carrier oder einer Weste befestigt werden.

| Teil                    | Stops | Effekt                                                                                | Abdeckung            | Gewicht | Req |
|-------------------------|-------|---------------------------------------------------------------------------------------|----------------------|---------|-----|
| DAPS (Deltoid/Axillary) | IIIA  | Resistenz gegen Piercing und Slashing an Armen/Achseln                                | Schultern, Achseln   | 1.5 kg  | 8   |
| Throat Protector (soft) | IIIA  | +1 AC gegen Halsangriffe                                                              | Hals                 | 0.3 kg  | 5   |
| Groin Protector (soft)  | IIIA  | +1 AC gegen Leistenangriffe                                                           | Leiste               | 0.5 kg  | 5   |
| Cummerbund (soft)       | IIIA  | Resistenz gegen Piercing und Slashing an den Flanken, wenn mit Plattenträger getragen | Flanken              | 0.5 kg  | 3   |

## Ballistische Schilde {#ballistic-shields}

Handgeführte Schilde für Breaching und Personenschutz. Ein Schild gewährt seinen AC-Bonus nur gegen Angriffe von der
abgedeckten Seite und belegt eine Hand - du kannst keine zweihändige Waffe führen, während du ihn trägst.
Siehe [Deckung](rules/cover.md#granting-cover) dafür, wie Schilde und ballistische Decken Deckung für Verbündete schaffen.

| Schild                             | AC | Stops | Modifikatoren                                                                                                             | Gewicht | Req |
|------------------------------------|----|-------|---------------------------------------------------------------------------------------------------------------------------|---------|-----|
| Ballistic Shield (IIIA)            | +3 | IIIA  | Nur einhändige Waffen beim Tragen                                                                                         | 6 kg    | 10  |
| Ballistic Shield (III+)            | +4 | III+  | Nur einhändige Waffen; -10 ft Bewegung                                                                                    | 10 kg   | 15  |
| Breacher Shield (viewport + light) | +4 | III+  | Wie III+ Schild; integriertes Weißlicht und gepanzertes Sichtfenster                                                      | 11 kg   | 18  |
| Ballistic Blanket                  | -  | IIIA  | Wird als Action ausgebreitet, um einem benachbarten liegenden Ziel halbe/volle Deckung zu geben (GM); kein AC für Träger | 7 kg    | 8   |
