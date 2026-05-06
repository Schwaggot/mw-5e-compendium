---
title: Kampfaktionen
aliases: [ Homebrew Rules, Firing Modes ]
tags: [ rules, combat ]
---

# Kampfaktionen

Homebrew-Regeln, Mods und Actions im Kampf. Der Standard-Feuermodus für jeden Fernkampfangriff ist **Single Shot**. Die
unten beschriebenen Modi erweitern oder ersetzen diesen Standard und sind an Waffen-Eigenschaften (Burst, Automatic,
Manual Action) aus den [Weapon Properties](weapon-properties.md) gekoppelt.

**Firing into Melee:** Disadvantage auf den Angriff. Natural 1 = kein Misfire; du triffst stattdessen ein zufälliges
Ziel im Handgemenge (GM randomisiert).

## Single Shot {#single-shot}

Der Standard-Feuermodus, verfügbar für jede funktionsfähige Schusswaffe.

- **Action Economy:** ein Angriff aus deiner Attack Action.
- **Ziele:** eines.
- **Munitionsverbrauch:** 1 Schuss.
- **Strafen:** nur die Standard-[Range](weapon-properties.md#range)-Strafen.

> **Beispiel (Single Shot):** Falke feuert seine Pistole (Range 30 ft) auf einen Militanten in 50 ft Entfernung. 50 ft
> liegt im x2-Band (31-60 ft), also greift er mit **Disadvantage** an. Er verbraucht **1 Schuss** aus dem Magazin.

## Aim {#aim}

Action: auf ein Ziel zielen. +2 auf Ranged-Attack-Rolls gegen dieses Ziel. Nur ein Ziel gleichzeitig; bricht, sobald die
Line of Sight bricht.

## Burst Fire {#burst-fire}

Für Waffen mit der **Burst**-Eigenschaft. Eine kurze, mechanisch fixierte 3-Schuss-Salve.

- **Action Economy:** ein Burst pro Angriff aus deiner Attack Action.
- **Ziele:** eines.
- **Munitionsverbrauch:** 3 Schuss.
- **Strafen:** Standard-[Range](weapon-properties.md#range)-Strafen **plus zusätzlich -5 pro Range Multiple jenseits x1
  ** (also -5 bei x2, -10 bei x3, -15 bei x4).
- **Extra-Treffer:** siehe [Extra-Treffer-Regel](#extra-hit-rule).

> **Beispiel (Burst Fire):** Falkes PDW (Range 60 ft, Burst) zielt auf einen Militanten in 70 ft. 70 ft liegt im
> x2-Band (61-120 ft). Range-Tabelle bei x2 = Disadvantage; Burst addiert -5 pro Multiple jenseits x1, bei x2 also nochmal
> -5. Gesamt: **Disadvantage und -5**. Er verbraucht **3 Schuss**.

## Automatische Feuermodi {#automatic-firing-modes}

Für Waffen mit der **Automatic**-Eigenschaft kannst du Controlled Burst, Spray oder Riddle anstelle eines Single Shot
oder Burst nutzen.

### Controlled Burst {#controlled-burst}

Eine kurze Auto-Fire-Salve variabler Länge; das Auto-Fire-Pendant zu Burst Fire.

- **Action Economy:** ein Controlled Burst pro Angriff aus deiner Attack Action.
- **Ziele:** eines.
- **Munitionsverbrauch:** 1d4+2 Schuss (pro Burst gewürfelt).
- **Strafen:** Standard-[Range](weapon-properties.md#range)-Strafen **plus -5 pro Range Multiple jenseits x1**.
- **Extra-Treffer:** siehe [Extra-Treffer-Regel](#extra-hit-rule).

### Spray {#spray}

Streuendes Auto-Fire über mehrere benachbarte Ziele ("horizontales" Auto-Fire).

- **Action Economy:** Action (ersetzt deine Attack Action).
- **Ziele:** bis zum DEX-Modifier; Ziele müssen aneinander grenzen (jedes innerhalb 5 ft zum nächsten).
- **Munitionsverbrauch:** 1d4+2 Schuss **pro Ziel** (separat pro Ziel gewürfelt).
- **Strafen:** **-5 pro Ziel jenseits des ersten** (kumulativ: -0 / -5 / -10 / ...).
  Standard-[Range](weapon-properties.md#range)-Strafen gelten zusätzlich pro Angriffswurf.
- **Extra-Treffer:** siehe [Extra-Treffer-Regel](#extra-hit-rule); Cap = Schuss in der jeweiligen Salve.

### Riddle {#riddle}

Konzentriertes Auto-Fire auf ein einzelnes Ziel über mehrere Salven ("vertikales" Auto-Fire).

- **Action Economy:** Action.
- **Ziele:** genau eines.
- **Salven:** wähle eine Anzahl Salven bis zum DEX-Modifier; jede Salve ist ein eigener Angriffswurf.
- **Munitionsverbrauch:** 1d4+2 Schuss **pro Salve** (separat pro Salve gewürfelt).
- **Strafen:** **-5 pro Salve jenseits der ersten** (kumulativ). Standard-[Range](weapon-properties.md#range)-Strafen
  gelten.
- **Extra-Treffer:** siehe [Extra-Treffer-Regel](#extra-hit-rule); pro Salve berechnet.

> **Beispiel (Spray vs Riddle):** Falke (DEX 16, +3) stellt drei Militante in einem Türrahmen, alle innerhalb von 5 ft
> zueinander.
>
> - Mit **Spray** zielt er auf alle drei. Angriffsstrafen stapeln: Ziel 1 mit -0, Ziel 2 mit -5, Ziel 3 mit -10.
    Munition wird pro Ziel separat gewürfelt: z.B. 4 + 6 + 5 = **15 Schuss**.
> - Mit **Riddle** ignoriert er die anderen zwei und stapelt **3 Salven** in den Anführer. Strafen: Salve 1 mit -0,
    Salve 2 mit -5, Salve 3 mit -10. Munition pro Salve gewürfelt: z.B. 5 + 3 + 6 = **14 Schuss**.

## Extra-Treffer-Regel {#extra-hit-rule}

Burst, Controlled Burst, Spray und Riddle können zusätzliche Schuss auf dasselbe Ziel landen, wenn der Angriff deutlich
über AC liegt. **Pro volle 5 Punkte, um die dein Angriffswurf die AC des Ziels übertroffen hat, erzielst du einen
zusätzlichen Treffer** (jeder addiert die Schadenswürfel der Waffe). Die maximale Anzahl an Zusatztreffern ist auf die
in dieser Salve abgefeuerten Schuss begrenzt.

> **Beispiel (Extra-Treffer):** Falke feuert einen Controlled Burst auf einen Militanten (AC 14) und würfelt **24** zum
> Treffer - 10 über AC. Das sind zwei volle 5er-Stufen, also Original-Treffer **+ 2 Extra-Treffer = 3x Schadenswürfel der
Waffe**. Er hat 5 Schuss für den Burst gewürfelt, das Cap von 5 wird also nicht erreicht.

## Suppressive Fire {#suppressive-fire}

Action; halte Feinde nieder, ohne auf Kills zu zielen. Schließt die Attack Action im selben Zug gegenseitig aus.

- **Ziele:** Kreaturen innerhalb von 10 ft zueinander, bis zum DEX-Modifier.
- **Munition pro Ziel:** 3 Schuss (Burst-Waffen), 1d4+2 (Automatic-Waffen) oder 1 von der Waffe definierter Burst.
- **Effekt:** Unterdrückte Ziele haben Disadvantage auf Ranged Attacks und auf WIS (Perception) Checks bis zum Ende
  ihres nächsten Zuges.
- **Einschränkung:** kann nicht mit Manual-Action-Waffen verwendet werden.

> **Beispiel (Suppression):** Falkes Squad bekommt Feuer von zwei Schützen 8 ft auseinander in einer Fensterreihe. Falke
> nutzt Suppressive Fire mit seinem Automatic Carbine. Beide Ziele liegen innerhalb 10 ft zueinander und in Reichweite
> seines DEX-Modifiers (3). Er verbraucht **2 x 1d4+2 = 9 Schuss**. Beide Schützen haben Disadvantage auf Ranged Attacks
> gegen das Squad und auf Perception bis zum Ende ihres nächsten Zuges, sodass sein Team repositionieren kann.

## Ranged Opportunity Attack {#ranged-opportunity-attack}

Wenn sich eine Kreatur, auf die du zielst, während ihres Zuges mehr als 5 ft bewegt, darfst du deine Reaction nutzen, um
einen Ranged Attack gegen sie zu machen (in Reichweite und Line of Sight).
