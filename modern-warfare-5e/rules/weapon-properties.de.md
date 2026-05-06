---
title: Waffeneigenschaften
aliases: [ ]
tags: [ rules, weapon ]
---

# Waffeneigenschaften

**1H / 2H:** Ob die Waffe einhändig oder zweihändig geführt wird. Eine 2H-Waffe kann ohne
das entsprechende Training nicht einhändig abgefeuert werden.

**Ammunition ( - / - ):** Zwei Zahlen - Schuss pro Magazin / Schusstyp. Du kannst nur feuern, wenn geladen.

**Accurate (-):** +N auf alle Angriffswürfe mit dieser Waffe.

**Deviation (-):** Nominiere einen Punkt innerhalb der Reichweite. Würfle einen Angriff vs AC 10 (+5 pro
Reichweitenschritt jenseits des ersten). Bei einem
Fehlschlag würfle den Streu-Würfel und einen Abweichungs-Würfel (ziehe DEX-Bonus ab, Min 1); Ergebnis = 5 ft Schritte
abgewichen in Streu-
Richtung. Auf großer Reichweite haben Ziele Advantage auf Saves und Abweichungs-Würfel sind verdoppelt.

<a id="range"></a>**Range:** Die in Fuß angegebene Reichweite einer Waffe ist ihre **normale** (x1) Reichweite. Darüber
hinaus wird die Distanz in Range Multiples (x2, x3, x4) gemessen und löst kumulative Strafen aus. Jenseits von x4 ist
das Ziel außer Reichweite und kann nicht getroffen werden.

| Distanz-Band          | Range Multiple | Strafe               |
|-----------------------|----------------|----------------------|
| 0 bis Reichweite      | x1 (Normal)    | Keine                |
| Reichweite, bis 2x    | x2             | Disadvantage         |
| 2x Reichweite, bis 3x | x3             | Disadvantage und -5  |
| 3x Reichweite, bis 4x | x4             | Disadvantage und -10 |
| jenseits 4x           | -              | Außer Reichweite     |

Auf großer Reichweite (x3 und darüber) haben Ziele Advantage auf vom Angriff ausgelöste Saves, und Deviation-Würfel
werden verdoppelt. Burst, Controlled Burst, Spray und Riddle erhalten **zusätzlich -5 pro Range Multiple jenseits x1** (
also -5 bei x2, -10 bei x3, -15 bei x4), die auf die Tabelle oben aufaddiert werden.
Siehe [Combat Actions](combat-actions.md) für die vollständigen Feuermodus-Regeln.

> **Beispiel (Pistole, Range 30 ft):** Bänder sind 0-30 (x1), 31-60 (x2), 61-90 (x3), 91-120 (x4). Ein Ziel auf 70 ft
> liegt im **x3-Band = Disadvantage und -5**. Ein Controlled Burst auf dieselbe Distanz addiert nochmal **-10** (
> Burst/Auto: -5 pro Multiple jenseits x1, summiert über x2 und x3) - Gesamt: **Disadvantage und -15**.
>
> **Beispiel (Sturmgewehr, Range 120 ft):** Bänder sind 0-120 (x1), 121-240 (x2), 241-360 (x3), 361-480 (x4). Ein Ziel
> auf 300 ft liegt im **x3-Band = Disadvantage und -5** für einen Single Shot. Ein Controlled Burst auf 300 ft addiert
> nochmal **-10** - Gesamt: **Disadvantage und -15**. Ein Ziel auf 500 ft ist komplett außer Reichweite.

**Reloading:** Gib eine Action oder einen Angriff aus, um nachzuladen, wenn leer. Ein Nachladen verbraucht ein
Ersatzmagazin aus deinem getragenen Vorrat; siehe [Munition](ammunition.md).

**Recoil (-):** Wenn Strength geringer als der Recoil-Wert ist, -1 auf Single-Shot Angriffswürfe; für Burst/Auto ist die
Angriffs-
strafe = Recoil - Strength.

**Critical Success/Failure:** Natürliche Würfe auf oder unter dem Critical-Failure-Bereich sind automatische
Fehlschläge; natürliche Würfe auf oder über
dem Critical-Bereich erzielen einen Critical (doppelte Schadenswürfel).

**Close Quarter Combat (CQC):** Kein Disadvantage beim Feuern innerhalb von 5 ft eines Feindes.

**Covert:** Advantage auf Sleight of Hand zum Verbergen.

**Manual Action:** Nach dem Feuern gib eine Action aus oder opfere einen Angriff, um die nächste Patrone zu laden.

**Blast (-ft):** Kreaturen innerhalb des Radius machen einen DEX Save DC 8 + Proficiency + DEX Mod (falls Proficient).
Fehlschlag = voller
Schaden; bestanden = halber.

**Braced:** Disadvantage auf Angriffswürfe, es sei denn, abgestützt (Bipod, Wand, Sandsäcke usw.).

**Dependable:** Bei einem Misfire würfle zwei d100 und nimm den höheren.

**Ignite:** Bei Schaden an einer Kreatur, die Stoff trägt, entzündet sich für 1d6 Feuerschaden pro Runde, bis gelöscht (
Action).

**Inaccurate (-):** -N Strafe auf Angriffswürfe mit dieser Waffe.

**Lite:** Kompakt, leichtgewichtig und leicht verdeckt zu tragen. Erlaubt Off-Hand-Bonus-Action-Angriffe ohne
Dual-Wielding-Training und gewährt Advantage auf Sleight of Hand zum schnellen Ziehen. (Unterscheidet sich von der "
Light" Rüstungs-Gewichtsklasse.)

**Mounted:** Kann nicht ohne Stativ, Bipod oder Fahrzeughalterung abgefeuert werden. Die Halterung aufzubauen kostet
eine Action.

**Select Fire (S/B/A):** Die Waffe bietet mehr als einen Feuermodus - beliebige Kombination aus Single-Shot, Burst und
Auto.
Modi wechseln als Free Action in deinem Zug.

**Engulf (-ft):** Kegel; Ziele machen DEX Save DC 8 + DEX + Prof; bestanden = halber Schaden.

**Misfire:** Natürlicher Wurf auf oder unter Misfire = Angriff verfehlt; würfle d100 auf dem Misfire-Chart.

| d100   | Ergebnis                                                                                                                                |
|--------|-----------------------------------------------------------------------------------------------------------------------------------------|
| 1      | FUBAR - zerstört; volle Ersatzkosten                                                                                                    |
| 2-5    | Benötigt Ersatzteile (% der Vollkosten d100), dann Tag Arbeit + DC 15 Weapon Maintenance und Armorer's Tools Checks. Fehlschlag = FUBAR |
| 6-10   | Kaputt. Long Rest + DC 15 Armorer's Tools. Fehlschlag = behandle als 4-10%                                                              |
| 11-15  | Kaputt. Short Rest + DC 10 Weapon Maintenance. Fehlschlag = behandle als 11-20%                                                         |
| 16-60  | Verklemmt. Action + DC 10 DEX Check. Fehlschlag = behandle als 21-45%                                                                   |
| 61-100 | Waffe in Ordnung; du hast einfach verfehlt                                                                                              |

**Takedown:** Bei Schaden, Ziel-CON Save (DC = Schaden). Fehlschlag = Liegend.

**Quirky:** Nicht-proficiente Nutzer feuern mit Disadvantage.

**Imprecise:** Disadvantage beim Feuern in einen Nahkampf.

**Unreliable:** Bei einem Misfire würfle zwei d100 und nimm den niedrigeren.
