---
title: Rast
aliases: [ Short Rest, Long Rest, Ruhen, Erholung ]
tags: [ rules, character ]
---

# Rast

Eine Rast ist eine Auszeit, die lang genug ist, damit sich ein Operator erholen kann - Wunden versorgen, Magazine auffüllen, essen, trinken und
das Schlimmste des Tages verschlafen. Das System kennt zwei Varianten: einen **Short Rest** (etwa eine Stunde, in Deckung, Waffen
scharf) und einen **Long Rest** (acht Stunden, gesicherter Perimeter, Schlaf). Die meisten Klassen- und Designation-Features, die sich aufladen, nutzen
eine dieser beiden Uhren.

## Short Rest {#short-rest}

Ein Short Rest ist **mindestens 1 Stunde** niedrig-intensiver Aktivität: Waffenpflege, ein MRE essen, ein Tourniquet neu anlegen,
Funkchecks durchführen. Du kannst wachsam und bewaffnet sein; du darfst dich nicht in aktivem Kampf oder anhaltender schwerer Anstrengung befinden.

Während eines Short Rest:

- **Hit Dice ausgeben.** Du kannst eine beliebige Anzahl deiner Hit Dice ausgeben. Für jeden Würfel würfle den Würfel und addiere deinen Constitution-
  Modifikator - das sind die HP, die durch diesen Würfel regeneriert werden. Dein aktueller [Triage Code](hit-points.md#triage-code) teilt das Ergebnis
  immer noch. **Triage Red blockiert das Ausgeben von Hit Dice vollständig.**
- **Features regenerieren.** Alles, was sich "per Short Rest" oder "per Short oder Long Rest" auflädt, kommt zurück. Dies
  umfasst [Second Wind](../operator-class.md#second-wind), [Action Surge](../operator-class.md#action-surge), [Unit Leader Leadership Dice](../designations/unit-leader.md),
  und mehrere andere Designation-Fähigkeiten.
- **Stress heilen.** Stress-Schaden heilt bei einem Short Rest mit der Rate, die in der
  [Stress Damage](damage-types.md#stress-damage) Tabelle angegeben ist.
- **Feldbehelfe herstellen.** Ein [Combat Medic](../designations/combat-medic.md) kann während eines Short Rest ein improvisiertes Stim oder Antidot
  herstellen. Tech- und Demolitions-Spezialisten nutzen Short Rests ebenfalls für kleine Reparaturen.

Du kannst an den meisten Tischen **bis zu zwei Short Rests** zwischen Long Rests machen - der GM kann je nach
operativem Tempo anders entscheiden.

> **Beispiel:** Falke (3 Hit Dice, CON +0) beendet ein Ziel bei 12 / 34 HP (Orange). Er ruft einen Short Rest in einem
> geräumten Gebäude aus. Er gibt 2 Hit Dice aus: würfelt 7 und 4, jeweils +0 = 7 und 4 HP geheilt vor dem Teiler. Oranges
> Teiler ist "5 pro 1", also wird aus der 7 1 HP und aus der 4 0. Er ist bei 13 HP, immer noch Orange. Second Wind hat sich dagegen
> aufgeladen - und umgeht den Teiler, wenn er es im nächsten Zug einsetzt.

## Long Rest {#long-rest}

Ein Long Rest ist eine Periode von **mindestens 8 Stunden**, von denen mindestens 6 Schlaf sind. Der Operator kann bis zu zwei
Stunden leichter Wache in der Mitte übernehmen, ohne die Rast zu brechen. Ein Long Rest erfordert Sicherheit und Schutz - ein Hide Site, eine
FOB, ein Safehouse, ein Hotelzimmer. Du kannst keinen Long Rest bei aktivem Kontakt, auf einem fahrenden Exfil-Flugzeug oder unter Feuer
machen.

Nach einem Long Rest:

- **HP vollständig wiederhergestellt.** Du wachst bei maximalen HP und Triage Green auf, unabhängig davon, wo du gestartet bist (vorausgesetzt du hast
  die Nacht überlebt).
- **Hit Dice regeneriert.** Du erhältst ausgegebene Hit Dice bis zur **Hälfte deines Gesamtwerts** zurück (Minimum 1).
- **Alle "per Long Rest" Features werden zurückgesetzt.
  ** [Indomitable](../operator-class.md#indomitable), [Resourceful](../operator-class.md#resourceful) und die meisten
  Designation-Features richten sich nach dieser Uhr.
- **Stress-Schaden heilt** mit der Long-Rest-Rate aus der [Stress Damage](damage-types.md#stress-damage) Tabelle.
- **Erschöpfung sinkt um 1 Stufe.** Es sei denn, sie wird durch eine dauerhafte Ursache gehalten (Triage Red addiert immer noch 2, solange du dort bleibst).

Der HP-Wiederherstellungsschritt eines Long Rest ist für die Zwecke des Triage-Teilers eine Heilungsquelle - aber er umgeht den Teiler,
weil er auf "volle HP" statt auf einen Wurf eingestellt ist. Du wachst immer frisch auf, auch wenn du in Red geschlafen hast.

> **Beispiel:** Falke beendet den Tag bei 13 / 34 HP, Orange, Erschöpfung 2 (1 von Orange, 1 von einem früheren Fehlschlag). Die
> Squad erreicht das Safehouse und legt sich schlafen. Er macht einen Long Rest: HP zurück auf 34, Triage Green, Hit Dice zurück von 0 → 1 (Hälfte
> von 3, abgerundet, Minimum 1), Erschöpfung sinkt von 2 auf 1. Am Morgen ist er wieder kampfbereit.

## Interrupted Rests {#interrupted-rests}

Wenn eine Rast vor ihrer Mindestzeit unterbrochen wird - Kontakt, Alarm, Verwundeter - gewährt sie keinen Nutzen. Die Uhr startet wieder
bei Null, sobald die Bedrohung bewältigt ist.

Ein Short Rest von weniger als 1 Stunde gibt nichts. Ein Long Rest von weniger als 8 Stunden zählt als Short Rest, wenn er mindestens
1 Stunde gelaufen ist, andernfalls nichts.

## Compared to Classic D&D 5E {#compared-to-classic-dd-5e}

- 1 Stunde Short / 8 Stunden Long ist die gleiche Baseline wie klassisches 5E.
- Hit Dice ausgeben bei Short Rests funktioniert auf die gleiche Weise; der Triage-Code-Teiler ist die Homebrew-Schicht darüber.
- Long Rest heilt vollständig und erstattet die Hälfte der ausgegebenen Hit Dice zurück - gleich wie im klassischen 5E.
- Erschöpfung sinkt um 1 pro Long Rest, gleich wie im klassischen 5E.
- Die große Änderung ist **operative Realismus**: Du kannst keinen Long Rest in aktiven Operationen machen, und der Triage Code kann
  Hit-Dice-Wert drosseln oder sie ganz blockieren. Deshalb sind Feldsanitäter und Stims so wichtig.
