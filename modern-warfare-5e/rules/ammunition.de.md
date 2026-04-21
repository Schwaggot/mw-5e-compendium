---
title: Munition
aliases: [ Ammunition, Magazine, Mags, Ammo, Ersatzmagazine, Nachschub ]
tags: [ rules, weapon, combat ]
---

# Munition

Feuerwaffen in Modern Warfare 5E haben einen endlichen Vorrat. Das Magazin einer Waffe fasst eine feste Anzahl Schuss
(die `Ammo N` Eigenschaft auf jedem Waffenstatblock). Wenn es leer ist, lädst du nach, indem du eines der Ersatzmagazine
aus deinem Rig einsetzt. Diese Seite legt fest, wie viele Magazine du zu Beginn hast, wie viel sie wiegen und wie du an
Nachschub kommst.

## Geladenes Magazin {#loaded-magazine}

Jedes Magazin in deinem getragenen Vorrat hat einen eigenen Füllstand. Bei der Charaktererstellung und nach
vollständigem Nachschub ist jedes Magazin bis zur `Ammo N`-Kapazität der Waffe gefüllt; während eines Einsatzes können
sie teilgefüllt sein (siehe [Nachladen](#reloading) unten).

- Beim Feuern ziehst du Schuss aus dem geladenen Magazin ab, gemäß den Feuermodus-Regeln in
  [Combat Actions](combat-actions.md). Single Shot kostet 1 Schuss, Burst Fire kostet 3, Spray / Riddle /
  Controlled Burst kosten 1d4+2, Suppressive Fire kostet 3 / 1d4+2 / 1 Burst pro Ziel.
- Eine Waffe bei 0 Schuss ist leer und kann erst nach dem Nachladen wieder feuern.

> **Beispiel (Munitionsverbrauch):** Falkes Assault Rifle ist Select Fire S/B/A mit vollem 30/30-Magazin. Er nutzt
> Spray gegen drei Militante in einem Korridor - 1d4+2 Schuss pro Ziel. Er würfelt 5, 4 und 6 = **15 Schuss in einer
> Aktion verbraucht**. Das geladene Magazin fällt auf 15/30. Noch eine Salve wie diese und er wechselt auf ein frisches.

## Nachladen {#reloading}

Ein Reload (Action oder ein Angriff, gemäß [Weapon Properties](weapon-properties.md) und der
[Reload Action](combat-turn.md#actions)) tauscht das geladene Magazin gegen ein beliebiges aus deinem Vorrat. Standardmäßig
greifst du zu einem vollen Magazin - du kannst aber auch bewusst ein bestimmtes Teilmagazin wählen, wenn die Situation
es erfordert.

Das herausgenommene Magazin wird **nicht zerstört**. Was damit passiert, hängt davon ab, wie du nachlädst:

- **Stowed Reload** (Standard): Das getauschte Magazin wandert in den Dump Pouch oder zurück ans Rig. Es behält die
  verbliebenen Schuss und bleibt als Teilmagazin im Vorrat. Das ist der normale Tactical Reload.
- **Speed Reload** (narrativ): Du wirfst das alte Magazin weg, um den Herzschlag zu sparen, der fürs Verstauen nötig
  wäre. Das Magazin ist verloren, es sei denn, du hebst es später als Free Object Interaction wieder auf. GM-Entscheidung
  - die meisten Operator machen nur dann einen Speed Reload, wenn es wirklich darauf ankommt.

> **Beispiel (Tactical Reload):** Falke hat nach einem Flurgefecht noch 5 Schuss in seinem 30er-Rifle-Magazin. Vor dem
> nächsten Raum opfert er seine Action zum Nachladen und verstaut das Teilmagazin. Sein Vorrat hält jetzt **3 volle
> Magazine + 1 Teil bei 5/30**. Das Teilmagazin liegt im Dump Pouch, bis er später zusammenfasst.

> **Beispiel (Speed Reload unter Feuer):** Falke ist festgenagelt, Gewehr leer, ein Militanter stapelt sich an seiner
> Tür. Er macht einen Speed Reload, schleudert das leere Magazin in den Flur, um Zeit zu sparen. Wenn er den
> Breach überlebt, entscheidet der GM, dass er zurückkriechen und es aufheben könnte - aber in diesem Moment ist es
> **weg aus seinem Inventar**.

## Teilmagazine zusammenfassen {#consolidating-partials}

Außerhalb des Kampfes kannst du Schuss aus einem teilgefüllten Magazin in ein anderes umfüllen - eine **1-Minuten**-
Aktivität. Schuss werden zwischen Magazinen verschoben; es werden keine Schuss erzeugt oder zerstört. Leere,
weggeworfene Magazine werden nicht automatisch wiedergewonnen - hebe sie vom Boden auf, wenn du sie zurück haben willst.

> **Beispiel (Zusammenfassen):** Falke beendet eine Patrouille mit drei Teilmagazinen - 22/30, 11/30 und 5/30
> (insgesamt 38 Schuss über drei Magazine). Er verbringt 1 Minute mit dem Zusammenfassen: 22 + 8 aus dem 11er-Magazin
> füllen ein Magazin auf 30/30, 3 Schuss bleiben übrig; diese 3 kombinieren sich mit den anderen 5 zu einem zweiten
> Teilmagazin bei 8/30. Sein Vorrat ist jetzt **1 voll (30/30), 1 Teil (8/30) und 1 leer**.

## Startloadout {#starting-loadout}

Jede Waffe, die du bei der Charaktererstellung mitbringst, kommt ohne zusätzliche Requisitionskosten mit einer Baseline
an Magazinen. Die Zahl unten *enthält* das bereits in der Waffe geladene Magazin:

| Waffenklasse                                   | Magazine / Schuss enthalten |
|------------------------------------------------|-----------------------------|
| Pistole, Revolver                              | 3 Magazine                  |
| SMG, Shotgun                                   | 4 Magazine                  |
| Assault Rifle, Semi-Auto Rifle, Bolt-Action    | 6 Magazine                  |
| Machine Gun (SAW / GPMG / HMG)                 | 3 Gurte                     |
| Rocket Launcher                                | 2 Schuss                    |
| Grenade Launcher (standalone)                  | 4 Schuss                    |
| Grenade Launcher (unterlauf, z.B. M203)        | 6 Schuss                    |

Du kannst bei der Charaktererstellung oder in der Downtime weitere Magazine kaufen, zu **0.5 Req pro Ersatzmagazin**
(Pistole, SMG, Shotgun, Rifle) oder **1 Req pro Gurt, Rakete oder Granate**. Zusätzliche Mags zählen zum Tragegewicht -
siehe unten.

## Magazingewicht {#magazine-weight}

Geladene Magazine und Gurte wiegen wie folgt. Zähle sie zum Tragegewicht in [Encumbrance](encumbrance.md).

| Magazintyp                             | Geladenes Gewicht |
|----------------------------------------|-------------------|
| Pistole / Revolver (6-17 Schuss)       | 0.2 kg            |
| SMG (20-30 Schuss)                     | 0.3 kg            |
| Shotgun (5-8 Schuss, in Box)           | 0.2 kg            |
| 5.56 / 5.45 Rifle (20-30 Schuss)       | 0.4 kg            |
| 7.62 Rifle (10-20 Schuss)              | 0.5 kg            |
| .50 / Anti-Materiel (5-10 Schuss)      | 0.8 kg            |
| SAW-Gurt (100-200 Schuss, Trommel/Box) | 2.5 kg            |
| GPMG-Gurt (100-200 Schuss)             | 3.0 kg            |
| 40mm Granate (einzelne)                | 0.2 kg            |
| Rakete / AT-Schuss (einzelne)          | 2.5 kg            |

Ein leeres Magazin wiegt etwa die Hälfte des geladenen Werts; runde auf den geladenen Wert, es sei denn, der GM will
mehr Präzision.

## Magazin-Modifikationen {#magazine-modifications}

Die [Weapon Modifications](weapon-modifications.md#magazines) kennen drei magazin-bezogene Optionen:

- **Extended Magazine.** Erhöht die Kapazität pro Magazin (+10 bis +20 Schuss je nach Waffenklasse). Jedes Magazin in
  deinem Startvorrat nutzt die erhöhte Kapazität ohne zusätzliche Kosten über den Req-Preis der Modifikation hinaus.
  Das Gewicht skaliert proportional mit der neuen Schusszahl.
- **Drum Magazine.** Gleiche Regel, größerer Zuwachs (+30 bis +70 Schuss). Trommeln sind sichtbar klobig; der GM kann
  Disadvantage auf Stealth (Sleight of Hand zum Verbergen) wegen der Silhouette verhängen.
- **Quick Mag.** Nachladen wird zu einer **Free Action**. Keine Änderung an Kapazität oder Gewicht.

**Gewichtsskalierung.** Das Gewicht eines modifizierten Magazins ist das Basisgewicht (aus der Tabelle oben) mal dem
Verhältnis von neuer zu alter Kapazität. Ein 5.56 Extended (30 → 50 Schuss) wiegt `0.4 × 50/30 ≈ 0.65 kg`. Eine 5.56
Trommel (30 → 100 Schuss) wiegt `0.4 × 100/30 ≈ 1.3 kg`. Runde auf eine Dezimalstelle.

> **Beispiel (Extended Mag):** Falkes Beretta AR70/90 (Baseline Ammo 30) hat die Extended-Magazine-Modifikation (+20
> Schuss). Sein Startvorrat besteht weiterhin aus 6 Magazinen, aber jedes hält jetzt **50/50 Schuss** und wiegt ~0.65
> kg. Das Gesamt-Magazingewicht steigt von 2.4 kg auf 3.9 kg - es lohnt sich, die [Encumbrance](encumbrance.md)-Stufe
> vor dem Ruck-up zu prüfen.

## Nachschub {#resupply}

- **Long Rest an einem sicheren, versorgten Ort** (Basis, FOB, eingerichteter Cache): Alle Magazine werden wieder auf
  den Startloadout-Stand aufgefüllt. Das ist der Standardweg, wie Munition zurück ins Rig kommt.
- **Long Rest im Feld ohne Versorgungszugang**: Die Munition bleibt, wie sie ist. Du kannst während der Rast weiterhin
  Teilmagazine zusammenfassen.
- **Short Rest mit Cache vor Ort**: Fülle das geladene Magazin aus Ersatzmagazinen auf; fasse Teilmagazine zusammen.
  Kein Netto-Zuwachs an Munition, nur Umverteilung.
- **Scavenging**: Kompatible feindliche Magazine (gleiche Waffe oder Kaliber) können nach GM-Ermessen direkt genutzt
  werden. Schuss aus inkompatiblen Magazinen oder aus Munitionskisten werden bei **1 Minute pro 10 Schuss** ausgebaut.

> **Beispiel (Nachschub an der Basis):** Falke rollt nach einer dreitägigen Patrouille zurück zum FOB. Sein Rifle-Vorrat
> ist auf 1 voll, 2 Teilmagazine (14/30 und 7/30) und 1 leer geschrumpft - das sechste Magazin hat er beim Breach an
> Tag zwei speed-reloaded und nie wieder aufgehoben. Nach seinem Long Rest am FOB ist sein Vorrat wieder bei **6 vollen
> Magazinen**. Das verlorene Magazin wird aus dem Depot ersetzt; die Teilmagazine füllen wieder auf.

## Vergleich mit klassischem D&D 5E {#compared-to-classic-dd-5e}

- Klassisches 5E trackt Munition einzeln, Pfeil für Pfeil. Dieses Kompendium trackt **Magazine als Einheit**, mit
  Einzelschuss-Zählung nur im aktuell geladenen Magazin - deutlich weniger Buchhaltung bei gleichem taktischen Druck.
- Die Tragegrenze ist die Standard-[Encumbrance](encumbrance.md)-Rechnung, kein dediziertes Slot-System. Jedes
  zusätzliche Magazin kostet Kilogramm, keinen Sonder-Slot.
- Nachschub beim Long Rest an der Basis ist das moderne Äquivalent zu "in der Stadt Pfeile nachkaufen". Feldoperationen
  ohne Versorgungszugang halten den Munitionsdruck bis zur Extraktion aufrecht.
