---
title: Ability Checks
aliases: [ Skill Checks, Ability Check, Check, DC, Contested Check, Passive Check ]
tags: [ rules, character ]
---

# Ability Checks

Ein **Ability Check** ist ein d20-Wurf, den der GM verlangt, wenn ein Operator etwas versucht, dessen Ausgang ungewiss
ist - eine Tür eintreten, ein Schloss knacken, eine Karte bei schwachem Licht lesen, einen Checkpoint-Wachposten
beschwichtigen. Zusammen mit Angriffswürfen und [Saving Throws](saving-throws.md) sind Checks die dritte der drei
zentralen d20-Säulen im System.

Wenn der GM nicht darum bittet, würfelst du nicht. Routinehandlungen ohne Einsatz gelingen einfach (oder scheitern
einfach, wenn die Situation aussichtslos ist). Checks kommen dann ins Spiel, wenn sowohl eine Erfolgschance als auch
eine bedeutsame Konsequenz für Misserfolg besteht.

## Die Grundformel {#the-basic-formula}

`1d20 + Ability-Modifier + Proficiency Bonus (wenn ausgebildet) + situative Modifier`

Der GM nennt eine **Difficulty Class (DC)**. Wurf ≥ DC = Erfolg; Wurf < DC = Misserfolg. Ability und eine etwaige
Ausbildung werden zusammen genannt: ein "DEX (Stealth) Check" ist `1d20 + DEX mod`, plus dein Proficiency Bonus, wenn
du Skills Training in Stealth hast (siehe [Proficiency](proficiency.md)).

| DC | Schwierigkeit                                  |
|----|------------------------------------------------|
| 5  | Sehr leicht (ein untrainierter Zivilist meist) |
| 10 | Leicht (ein trainierter Operator meist)        |
| 13 | Mäßig                                          |
| 15 | Schwer                                         |
| 18 | Sehr schwer                                    |
| 20 | Heroisch                                       |
| 25 | Nahezu unmöglich                               |
| 30 | Stoff für After-Action-Legenden                |

Der GM wählt die DC anhand der Situation, nicht anhand der Charakterwerte.

## Das Attribut wählen {#choosing-the-attribute}

Die meisten Checks werden nach Attribut und Skill zusammen benannt: STR (Athletics), DEX (Sleight of Hand),
WIS (Perception), CHA (Intimidation) und so weiter. Der Skill benennt, um welche Art von Handlung es sich handelt;
das Attribut benennt, welche Art von Anstrengung dahintersteckt. Der GM kann eine ungewöhnliche Kombination verlangen,
wenn die Situation es rechtfertigt - ein STR (Intimidation) Check, um sich körperlich über einen Gefangenen zu
erheben, ein CHA (Performance) Check, um eine Tarnidentität auf einer Veranstaltung zu halten. Das Attribut richtet
sich nach der *Art der Anstrengung*, nicht nach einer festen Liste. Siehe [Attributes](attributes.md) für das, was
jedes abdeckt.

## Contested Checks {#contested-checks}

Wenn zwei Charaktere direkt gegeneinander stehen - einer schleicht, einer beobachtet; einer versteckt eine Waffe,
einer durchsucht; ein Armdrücken - machen beide einen Check. Der höhere Gesamtwert gewinnt. **Bei Gleichstand gewinnt
der Verteidiger** (derjenige, der nicht aktiv versucht, die Situation zu ändern). Wenn keiner der Verteidiger ist,
ergibt ein Gleichstand keine Veränderung.

> **Beispiel:** Falke (DEX +3, ausgebildet in Stealth, Proficiency +2) schleicht an einer patrouillierenden Wache
> (WIS +1, untrainiert in Perception) vorbei. Falke würfelt einen DEX (Stealth) Check: **1d20 → 12**, insgesamt
> 12 + 3 + 2 = **17**. Die Wache würfelt einen WIS (Perception) Check: **1d20 → 18**, insgesamt 18 + 1 = **19**. Die
> 19 der Wache schlägt die 17. Falke wird entdeckt.

## Passive Checks {#passive-checks}

Ein **Passive Check** ist ein Check, den der GM im Kopf mit der Annahme würfelt, dass der Würfel eine 10 zeigt. Wird
für andauernde Aktivitäten verwendet oder für Dinge, die du tun würdest, ob du es merkst oder nicht - einen
Stolperdraht bemerken, einen Schritt hören, die Stimmung eines Fremden einschätzen.

`Passive-Wert = 10 + Ability-Modifier + Proficiency Bonus (wenn ausgebildet) + situative Modifier`

- **Advantage auf dem relevanten Wurf**: +5 auf den Passive-Wert.
- **Disadvantage**: -5 auf den Passive-Wert.

Das Kompendium stützt sich am stärksten auf **passive Perception**, vom GM genutzt, um Schwellen für Hinterhalt,
Stealth und "merkst du etwas" festzulegen. Awareness Training erhöht sie direkt;
siehe [Awareness Programs](../training/awareness-programs.md).

## Group Checks {#group-checks}

Wenn die ganze Squad dasselbe tut - lautlos patrouillieren, durch einen Sumpf waten, einbrechen und eindringen - kann
der GM einen **Group Check** verlangen. Alle würfeln; wenn **die Hälfte oder mehr** gelingen, gelingt der Gruppe der
Check. Starke Mitglieder tragen schwache, aber nur bis zu einem gewissen Punkt.

## Hilfe, Werkzeug und Zusammenarbeit {#help-tools-and-working-together}

- **Help Action**: Ein Verbündeter neben dir kann seine Action nutzen, um dir Advantage auf deinen nächsten Ability
  Check zu gewähren, sofern er plausibel helfen könnte (ein Sniper-Spotter, der dem Schützen hilft; ein Teamkollege,
  der dich über eine Mauer hievt). Nur ein Helfer pro Check.
- **Werkzeuge und Kits**: Wenn du das passende Kit und Tools Training dafür hast, addierst du den Proficiency Bonus
  auf den Check. Ohne das Kit kann der GM entscheiden, dass der Check unmöglich ist oder mit Disadvantage erfolgt.
- **Wiederholungsversuche**: Bei Handlungen ohne Zeitdruck kann der GM nach einer kurzen Pause einen erneuten Versuch
  erlauben. Bei zeitkritischen Handlungen bekommst du in der Regel einen Wurf.

## Wann nicht gewürfelt wird {#when-not-to-roll}

Der GM sollte keinen Check verlangen, wenn:

- die Handlung offensichtlich gelingen würde (eine Türklinke drehen, eine Treppe hochgehen).
- die Handlung unabhängig vom Wurf unmöglich ist (ein Fahrzeug mit bloßen Händen heben).
- die Information die Wahl des Spielers nicht ändern würde (Insight auf einen bekannten Verbündeten würfeln, der ein
  ehrliches Briefing gibt).

## Beispiele {#examples}

> **Beispiel:** Falke liest die Range Card eines Snipers auf Paschtu. Der GM verlangt einen DC 13 INT Check, aber
> Falke hat Language Training nur in Deutsch und Englisch - kein Paschtu. Er würfelt **1d20 → 14**, +1 INT = **15**.
> Er würde die DC schaffen, aber der GM entscheidet, dass die Sprachbarriere bedeutet, er kann die *Zahlen* und das
> *Raster* lesen, aber nicht die Randnotizen, also bekommt er nur Teilinformationen.

> **Beispiel - contested mit Disadvantage:** Ein Kämpfer versucht, Falke das Gewehr aus den Händen zu ringen. Beide
> machen contested STR (Athletics) Checks. Falke hat nur eine Hand frei (er war am Nachladen), also gibt ihm der GM
> Disadvantage. Falke würfelt **2d20 → 16 und 4**, nimmt die 4, +0 STR +2 Proficiency = **6**. Der Kämpfer würfelt
> **1d20 → 11**, +2 STR (keine Ausbildung) = **13**. Falke verliert das Gewehr.

## Vergleich mit klassischem D&D 5E {#compared-to-classic-dd-5e}

- Die Formel d20 + mod + Proficiency und die DC-Leiter sind identisch.
- Die Skill-Liste ist gekürzt (kein Arcana, Religion, Performance ist selten) und neu interpretiert (Investigation ist
  Szenen-Lesen, Nature ist Gelände/Wetter).
- Passive Checks funktionieren genauso; Advantage/Disadvantage passen ±5 an wie im klassischen 5E.
- Contested Checks bei Gleichstand zum Verteidiger, wie im klassischen 5E.
- Help, Group Checks und Tool Proficiencies funktionieren alle gleich; die Quelle der Ausbildung ist nur anders.
