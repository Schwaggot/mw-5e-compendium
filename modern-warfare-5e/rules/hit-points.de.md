---
title: Hit Points
aliases: [ HP, Triage, Triage Code, Downed, Dying, Death Saves, Hit Dice ]
tags: [ rules, combat, character ]
---

# Hit Points

Hit Points (HP) messen, wie viel Kampfkraft einem Operator noch übrig bleibt. Sie sind keine wörtliche Zählung von Wunden - ein hoher
HP-Wert ist die Abstraktion für Panzerung, die den Treffer abbekommen hat, Körperpanzerung, die Prellungen erzeugte aber nicht
brach, die Kugel, die ein Magazin statt einer Arterie streifte, und den Willen, trotzdem weiter zu machen. Wenn die HP aufgebraucht sind, beginnt echter Schaden.

Wo du auf deiner HP-Skala stehst, ordnet dich einem von fünf **Triage Codes** zu, dem im Universum gebräuchlichen Etikett, das Sanitäter über Funk verwenden, um
den Zustand eines Verwundeten zu beschreiben. Der Triage Code steuert die natürliche Heilung, Erschöpfungsstrafen und welche medizinischen Fähigkeiten bei dir
angewendet werden können.

## Calculating Hit Points {#calculating-hit-points}

Aus der [Operator Class](../operator-class.md#hit-points):

- **1. Stufe:** `10 + dein voller Constitution-Wert` (der Wert, nicht der Modifikator).
- **Jede Stufe nach der 1.:** `1d10 (oder 6) + Constitution-Modifikator`.
- **Hit Dice:** `1d10 pro Operator-Stufe`. Werden verwendet, um HP bei einem [Short Rest](rest.md#short-rest) zu regenerieren.

> **Beispiel:** Falke (CON 11) startet bei 21 HP. Er steigt auf Stufe 2 auf und würfelt eine 7 auf seinem Hit Die, also gewinnt er 7 + 0 = 7 HP,
> was ihn auf 28 Max bringt. Auf Stufe 3 nimmt er stattdessen den Durchschnitt und gewinnt 6 + 0 = 6 HP, für 34 Max.

## Taking Damage {#taking-damage}

Wenn du getroffen wirst, würfelt der Angreifer einen Schadenswurf. Ziehe das Ergebnis von deinen aktuellen HP ab. Zwei Dinge verändern den
eingehenden Wert, bevor er landet:

- **Armor / Deckung** absorbiert Schaden gemäß den [Armor](../armor.md)-Regeln und
  jeder [Damage Reduction (DR)](damage-types.md#damage-reduction), die durch Ausrüstung gewährt wird.
- **Damage type** kann zusätzlich zum HP-Verlust Nebeneffekte auslösen - Blutung, Slowed, Betäubt, Taub usw.
  Siehe [Damage Types](damage-types.md).

Wenn der Treffer auf Red oder Orange Triage erfolgt, können [piercing](damage-types.md#damage-types) und slashing Schaden auch
[Bleed oder Major Bleed](conditions.md) auslösen, was weiter HP zwischen den Zügen abzieht, bis es gestoppt wird.

## Triage Code {#triage-code}

Jeder Charakter hat immer genau einen Triage Code, abgeleitet von seinen aktuellen HP als Prozentsatz des Maximums.

| Code                       | % Gesundheit | Natürliche Heilung                                                 | Erschöpfung |
|----------------------------|--------------|--------------------------------------------------------------------|-------------|
| 5: Black, Deceased         | 0%           | Keine                                                              | 5           |
| 4: Red, Critically Wounded | 1%-25%       | Benötigt medizinische Hilfe; Hit Dice heilen nicht mehr; 10 HP pro 1 geheilt | 2  |
| 3: Orange, Wounded         | 26%-50%      | 5 HP pro 1 geheilt                                                 | 1           |
| 2: Yellow, Injured         | 51%-75%      | 2 HP pro 1 erhalten                                                | -           |
| 1: Green, Healthy          | 76%-100%     | Normale Rate                                                       | -           |

Die rechten Spalten steuern einige wichtige nachgelagerte Regeln:

- **Natürliche Heilung** skaliert den Wert jedes HP-Punkts, den du durch Rast, Hit Dice oder nicht-medizinische Quellen regenerieren würdest.
  Bei Yellow bekommst du nur 1 HP für je 2, die die Quelle gewürfelt hat; bei Red bekommst du 1 HP für je 10 *und* du kannst keine
  Hit Dice mehr ausgeben. Feldsanitäter ([Combat Medic](../designations/combat-medic.md), Stim Pack, Quick Clot usw.) umgehen
  diesen Teiler.
- **Erschöpfung** wird zu deinem aktuellen Erschöpfungswert addiert, solange du in diesem Code bleibst. Geh in der Skala wieder nach oben und
  der Bonus-Erschöpfung entfällt.
- **Second Wind, Stim Pack, mehrere Unit Leader Features** und jede andere Fähigkeit, die eine Triage-Anforderung auflistet, wird nur
  innerhalb ihrer genannten Codes ausgelöst. Siehe jedes Feature.

> **Beispiel:** Falke hat 34 Max HP und liegt derzeit bei 12 HP - das sind 35%, was ihn auf Orange setzt. Er gibt einen Hit
> Die bei einem Short Rest aus und würfelt 7. Oranges Spalte für natürliche Heilung sagt "5 HP pro 1 geheilt", also werden aus der 7 1 HP
> geheilt (7 ÷ 5, abgerundet). Er ist immer noch bei 13 HP und immer noch Orange. Wenn ein Sanitäter ihn stattdessen mit einem Stim Pack versorgt,
> gilt der Teiler nicht.

## Going Down at 0 HP {#going-down-at-0-hp}

Wenn Schaden deine aktuellen HP auf 0 senkt (und nicht direkt auf tot), bist du **Downed**. Mechanisch:

- Du fällst **Bewusstlos** und **Liegend**. Du lässt fallen, was du in der Hand hältst.
- Deine HP bleiben bei 0; weiterer Schaden löst Death Saves aus, keine Subtraktion.
- Zu Beginn jedes deiner Züge, während du Downed bist, würfle einen **Death Saving Throw**.

### Death Saving Throws {#death-saving-throws}

Ein Death Save ist ein `1d20`-Wurf ohne Modifikator. Er ist *kein* [Saving Throw](saving-throws.md) für die Zwecke von
Features, die Saves modifizieren, es sei denn, ein Feature sagt das ausdrücklich.

- **10 oder höher → Erfolg.** Zähle mit.
- **9 oder niedriger → Fehlschlag.** Zähle mit.
- **Natürliche 20 → du erhältst 1 HP zurück** und stehst an Yellows unterer Grenze wieder auf (noch Wounded, aber bei Bewusstsein).
- **Natürliche 1 → zählt als zwei Fehlschläge.**

Wenn du **3 Erfolge** vor 3 Fehlschlägen erreichst: du bist **stabil**. Du hörst mit dem Würfeln auf, aber du bist immer noch bei 0 HP und immer noch
bewusstlos. Nach 1d4 Stunden erhältst du 1 HP zurück und wachst bei Triage Red auf. Jede Heilung während des stabilen Fensters weckt
dich ebenfalls sofort beim neuen HP-Wert.

Wenn du **3 Fehlschläge** vor 3 Erfolgen erreichst: du stirbst. Triage Code fällt auf Black.

### Damage While Downed {#damage-while-downed}

Jeder erlittene Schaden bei 0 HP kostet dich einen Death-Save-Fehlschlag - 1 Fehlschlag für einen normalen Treffer, **2 Fehlschläge für einen Treffer
innerhalb von 5 ft** (Nahdistanz-Exekutionsschuss) oder für jeden Treffer, der einen Critical Hit erzielt. Wenn der Schaden des einzelnen Treffers dein
HP-Maximum erreicht oder überschreitet, stirbst du sofort (direkt Black) ohne weitere Saves.

### Stabilizing a Casualty {#stabilizing-a-casualty}

Ein Verbündeter in der Nähe kann die Blutung stoppen, ohne HP wiederherzustellen:

- **Wisdom (Medicine) Check, DC 10** als Action. Erfolg = der Verwundete ist stabil. Fehlschlag = kein Fortschritt, erneut versuchen.
- Ein medizinischer Gegenstand mit dem Tag `stops-bleed` (siehe [Gear](../gear.md)) stabilisiert einen blutenden Verwundeten automatisch.
- Ein medizinischer Gegenstand mit dem Tag `revives` (z.B. Riechsalz, bestimmte Stims) kann ein bewusstloses Ziel zurück auf
  Yellow bringen, nach GM-Ermessen.
- Mehrere [Combat Medic](../designations/combat-medic.md) Features stabilisieren und heilen in derselben Action.

Ein stabiler Verwundeter ist immer noch bei 0 HP und Triage Code Red - er ist nicht wieder im Kampf, sondern stirbt nur nicht mehr aktiv. Bring
ihn zu einem Sanitäter.

> **Beispiel:** Falke nimmt einen Burst, der ihn von 4 HP auf -7 bringt. Er ist bei 0 HP, Downed, Bewusstlos, Liegend. In seinem
> nächsten Zug würfelt er einen Death Save: **8** → 1 Fehlschlag. Der Sanitäter kriecht herüber und würfelt einen Wisdom (Medicine) Check
> gegen DC 10: **14** → Erfolg, Falke ist stabil. Er bleibt bei 0 HP / Triage Red, bis er Heilung bekommt oder 1d4 Stunden
> vergehen. Der Stim Pack eines Teamkollegen zehn Sekunden später gibt ihm 12 HP zurück - er wacht sofort bei Triage Yellow auf.

## Healing {#healing}

HP kommen aus einigen Quellen zurück. Der Triage-Code-Teiler für natürliche Heilung gilt nur für nicht-medizinische Quellen.

| Quelle                                                                 | Menge                                           | Kosten / Cooldown                                                     |
|------------------------------------------------------------------------|-------------------------------------------------|-----------------------------------------------------------------------|
| **[Second Wind](../operator-class.md#second-wind)**                    | `1d10 + Operator-Stufe`                         | Bonus Action; einmal pro Short oder Long Rest. Triage Orange oder besser. |
| **Hit Dice bei einem [Short Rest](rest.md#short-rest)**                | Pro Würfel: `1d10 + CON Mod`                    | Jeder ausgegebene Würfel. Bei Triage Red können keine Hit Dice ausgegeben werden. |
| **[Long Rest](rest.md#long-rest)**                                     | Volle HP; regeneriere bis zur Hälfte deiner Hit Dice | 8 Stunden.                                                       |
| **Medizinische Ausrüstung (IFAK, Stims, Quick Clot, Liquid Skin Patch)** | Gegenstandspezifisch                          | Action; verbraucht den Gegenstand. Umgeht den Teiler.                 |
| **[Combat Medic](../designations/combat-medic.md) Features**           | Featurespezifisch                               | Pro Feature; viele umgehen den Triage-Teiler.                         |
| **[Unit Leader](../designations/unit-leader.md) Get In The Fight Die** | `1d10 + Unit Leader Stufe`                      | Action; nur bei Zielen auf Triage Yellow oder Green.                  |

## Compared to Classic D&D 5E {#compared-to-classic-dd-5e}

- HP ist mechanisch die gleiche Zahl, aber das System legt Triage Code darüber, um zu modellieren, dass das Erleiden schweren Schadens
  tatsächlich deine Erholung verlangsamt und Erschöpfung stapelt.
- Hit Dice funktionieren wie im klassischen 5E (1d10 hier, wie ein Fighter), aber der Triage-Teiler kann verkleinern, was jeder Würfel tatsächlich
  liefert, wenn du schon verletzt bist.
- Death Saving Throws funktionieren genau wie im klassischen 5E - 3/3, Nat 20 stellt dich wieder auf, Nat 1 zählt doppelt, Treffer bei 0 HP kosten
  einen Fehlschlag (oder zwei, wenn innerhalb von 5 ft oder kritisch).
- Der "stabile" Zustand hält 1d4 Stunden, bevor du bei 1 HP aufwachst, wie im klassischen 5E.
- Bleed (hinzugefügt durch piercing/slashing auf Red oder Orange) ersetzt das "du blutest nicht aus, es sei denn, du versagst Saves" des klassischen 5E
  - hier kannst du sowohl stabil bei Death Saves sein als auch aktiv HP durch eine Bleed-Condition verlieren, bis jemand
  sie stoppt.
