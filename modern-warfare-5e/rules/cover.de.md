---
title: Deckung
aliases: [ Halbe Deckung, Dreiviertel-Deckung, Volle Deckung, Concealment, Soft Cover ]
tags: [ rules, combat ]
---

# Deckung

Moderner Kampf ist auf Deckung aufgebaut. Ein Operator hinter einer Betonmauer ist ein anderer Kampf als ein Operator
auf offener Straße - und das System behandelt sie entsprechend. Deckung gibt einen flachen AC-Bonus und einen
entsprechenden Bonus auf DEX [Saving Throws](saving-throws.md) gegen Effekte, die von der anderen Seite kommen.

Es gibt drei Stufen.

## Die drei Stufen {#the-three-grades}

| Stufe               | Schwelle                                | AC-Bonus | DEX-Save-Bonus | Hinweise                                                                          |
|---------------------|-----------------------------------------|----------|----------------|-----------------------------------------------------------------------------------|
| **Halb**            | Etwa die Hälfte des Körpers verdeckt    | +2       | +2             | Niedrige Mauer, Türrahmen, Motorhaube, Partner zwischen dir und Bedrohung.        |
| **Dreiviertel**     | Der größte Teil des Körpers verdeckt    | +5       | +5             | Murder Hole, Sandsack mit Schießschlitz, Gebäudeecke, halb geöffnete Luke.        |
| **Voll**            | Körper vollständig verdeckt             | -        | -              | Kann nicht direkt von Angriffen oder Effekten mit Line of Sight anvisiert werden. |

Ein Ziel in **voller Deckung** kann nicht das *direkte* Ziel eines Angriffs oder einer Single-Target-Fähigkeit sein.
Es kann trotzdem indirekt getroffen werden: Flächeneffekte (Frags, Blast), Suppressing Fire, das an der Deckung
vorbeigeht, oder Angriffe auf die Deckung selbst.

## Deckung vs. Concealment {#cover-vs-concealment}

Die beiden sind verschieden und leicht zu verwechseln. **Deckung stoppt den Schuss; Concealment versteckt dich nur.**

- **Deckung** (diese Seite): Schüsse erreichen dich physisch nicht - Beton, Stahl, Erdwall, Stapel harter Sandsäcke.
- **Concealment**: Line of Sight ist unterbrochen oder beeinträchtigt, aber das Material würde eine Kugel nicht
  stoppen - Rauch, Laub, Dunkelheit, Nebel. Concealment gewährt Disadvantage auf Angriffe gegen dich
  (siehe [Advantage and Disadvantage](advantage.md)), aber keinen AC- oder Save-Bonus.

Ein Burst in Concealment kann dich trotzdem treffen; ein Burst in Deckung kann es physisch nicht, es sei denn, die
Deckung wird zerstört oder überwunden (eine AP-Gewehrkugel durch eine Autotür, eine HMG durch Hohlblockstein, eine
Rakete durch eine Wand).

Eine Kreatur, die zwischen einem Angreifer und deiner Position steht, zählt als **Soft Cover** - halbe Deckung für
Spielzwecke - weshalb "nicht vor Freundlichen stehen" ein Briefing-Punkt ist, kein Vorschlag.

## Die Stufe bestimmen {#determining-the-grade}

Der GM entscheidet es anhand der Situation. Nützliche Faustregeln:

- Geduckt hinter einer niedrigen Mauer oder in einem Türrahmen: halbe Deckung.
- Liegend hinter derselben niedrigen Mauer: Dreiviertel-Deckung.
- Um eine Ecke, nur Waffe und ein Auge sichtbar: Dreiviertel-Deckung.
- Vollständig hinter einer Mauer: volle Deckung.
- Flanke, Motorhaube oder Tür eines Pickups: halbe Deckung (die meisten Schüsse überwinden sie; siehe *Deckung überwinden* unten).
- Der Motorblock eines Fahrzeugs: Dreiviertel-Deckung.

[Geduckt](conditions.md) allein gewährt keine Deckung - es gibt einem Angreifer -2 auf Range jenseits 5 ft, separat -
aber es macht es einfacher, hinter einem niedrigen Hindernis Dreiviertel-Deckung zu beanspruchen.

## Deckung und Target Zones {#cover-and-target-zones}

Wenn ein Ziel in Deckung ist, können nur die *freiliegenden* Körperteile mit [Target Zone](damage-types.md#target-zones)
Schüssen angegriffen werden. Ein Schütze hinter Dreiviertel-Deckung, der nur seinen Kopf und die Waffenhand zeigt, kann
in Kopf oder Hand geschossen werden - alles andere ist blockiert.

## Deckung überwinden {#defeating-cover}

Mehrere Fähigkeiten und Waffen reduzieren oder ignorieren Deckung:

- **[Ranged Weapons Training Level 4](../training/ranged-weapon-programs.md)**: behandle Feinde so, als hätten sie
  eine Stufe weniger Deckung (voll → dreiviertel, dreiviertel → halb, halb → keine).
- **[Demolitions Specialist](../designations/demolitions-specialist.md) Panzerabwehrwaffen**: Raketenwerfer und
  ähnliche ignorieren jede Deckung außer voller.
- **Hochgradige Munition** (.50 BMG, AP Rounds, etc.): kann nach GM-Ermessen *durch* die Deckung schießen, wobei die
  Deckung als Damage Reduction in Höhe ihrer Härte fungiert statt als binärer Block.
- **Suppressive Fire und Flächeneffekte**: kümmern sich nicht um halbe oder Dreiviertel-Deckung; nur volle Deckung
  neutralisiert sie, und selbst volle Deckung blockiert keine Frag-Explosion, deren Blast um das Hindernis herumgeht.

## Deckung gewähren {#granting-cover}

Ein paar Möglichkeiten, sich Deckung zu verschaffen, wo keine ist:

- **Ballistic Blanket** (siehe [Armor](../armor.md)): als Action über einen liegenden Teamkollegen ausgebreitet,
  gewährt halbe oder volle Deckung nach GM-Ermessen.
- **[Demolitions Specialist Feldbefestigungen](../designations/demolitions-specialist.md)**: baue
  Dreiviertel-Deckungsquadrate in einer 20-ft-Linie.
- **[Ballistic Shield](../armor.md)**: gewährt dem Träger und einem benachbarten Verbündeten auf der gedeckten Seite
  halbe Deckung.
- **Rauch**: keine Deckung - er gewährt Concealment (Disadvantage auf Angriffe gegen Kreaturen darin oder dahinter),
  aber stoppt keine Schüsse.

## Beispiele {#examples}

> **Beispiel - halbe Deckung:** Falke (AC 14 durch seine Medium Flak) feuert über die Motorhaube einer Limousine auf
> einen Kämpfer 20 m entfernt. Der Kämpfer erwidert das Feuer. Der GM entscheidet, dass Falke in halber Deckung hinter
> der Motorhaube ist: AC wird **16**. Kämpfer würfelt **1d20 → 13**, +3 = **16** gegen AC 16 → Gleichstand,
> Gleichstände verfehlen den Angreifer, **Fehlschlag**. Ohne die Motorhaube hätte die 16 getroffen.

> **Beispiel - Dreiviertel-Deckung und Target Zones:** Falke steht an der Ecke eines Treppenhauses und lehnt sich nur
> mit Kopf und Gewehr hinaus. Der GM entscheidet Dreiviertel-Deckung. Ein Kämpfer auf dem Treppenabsatz versucht einen
> Armschuss - aber Falkes Arm ist hinter der Wand. Der Kämpfer muss einen Kopfschuss (-10 zum Treffen) oder einen
> Handschuss (-8) versuchen oder das Feuer einstellen.

> **Beispiel - volle Deckung überwunden:** Falke duckt sich für ein Reload vollständig hinter einen Ziegelpfeiler
> (volle Deckung). Der Kämpfer kann ihn nicht direkt anvisieren - also wirft der Kämpfer stattdessen eine Frag am
> Pfeiler vorbei. Falke macht einen DEX Save gegen den Blast; volle Deckung schützt nicht vor einem Flächeneffekt,
> der um sie herumgeht.

## Vergleich mit klassischem D&D 5E {#compared-to-classic-dd-5e}

- Halb (+2), Dreiviertel (+5) und volle Deckung sind identisch mit den klassischen 5E-Stufen und Boni.
- Deckung gewährt denselben Bonus auf DEX Saves wie auf AC, genau wie im klassischen 5E.
- Deckung vs. Concealment ist dieselbe Unterscheidung; Concealment ist mechanisch "Disadvantage auf Angriffe", gleich
  der Behandlung "lightly obscured" / "heavily obscured" im klassischen 5E.
- Der große Unterschied ist, wie *häufig* und *angreifbar* Deckung ist - Deckung ist der Standardzustand jedes
  Gefechts, nicht die Ausnahme, und das System gibt dir Werkzeuge, sie aufzubauen, zu ignorieren oder zu überwinden.
