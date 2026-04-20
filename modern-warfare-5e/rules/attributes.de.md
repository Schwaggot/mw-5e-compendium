---
title: Attribute
aliases: [ Ability Scores, Stats, STR, DEX, CON, INT, WIS, CHA ]
tags: [ rules, character ]
---

# Attribute

Jeder Operator wird durch sechs Attribute beschrieben (im klassischen D&D 5E "Ability Scores" genannt). Sie reichen
von 8 (Grundfitness, kann einen Rucksack tragen) bis 18 (Spitzenleistung, Tier-1-Selection-tauglich). Die meisten
Würfe im Spiel addieren den *Modifier* eines Attributs auf einen d20.

Es sind dieselben sechs Attribute wie im klassischen D&D 5E, daher wird sich die Mathematik vertraut anfühlen - was
sich ändert, ist das Flavor. Strength ist "den Verwundeten hochheben", nicht "ein Greatsword schwingen"; Wisdom ist
"den Raum und das Dach lesen", nicht "mit der Natur kommunizieren".

## Modifier-Tabelle {#modifier-table}

Der Modifier ist das, was du tatsächlich auf Würfe addierst. Der Score selbst zählt nur für ein paar Dinge (HP auf
Level 1, Belastung, der Point-Buy in [Character Creation](../character-creation.md#step-2-attributes)).

| Score | Modifier |
|-------|----------|
| 8     | -1       |
| 9     | -1       |
| 10-11 | +0       |
| 12-13 | +1       |
| 14-15 | +2       |
| 16-17 | +3       |
| 18    | +4       |

Formel: `Modifier = (Score - 10) / 2`, abgerundet. Identisch mit klassischem 5E.

## Die sechs Attribute {#the-six-attributes}

### Strength (STR) {#strength-str}

Reine körperliche Kraft: heben, ziehen, Breaching, klettern, eine Tür gegen einen heranschlagenden Körper
zuhalten.

- **Attack Rolls:** Melee-Waffen (Messer, Bajonett, Gewehrkolben) und Wurfwaffen.
- **Häufige Checks:** Athletics (klettern, schwimmen, springen, Grapple, Shove), brachiales Breaching, einen
  Verwundeten unter Feuer schleppen.
- **Saves:** Widerstand gegen Gepackt-werden, Gestoßen-werden oder körperlich gefesselt zu werden.
  Siehe [Saving Throws](saving-throws.md).
- **Tragen:** Belastung wird gegen STR gerechnet (siehe deinen Character Sheet).
- **Beispielmomente:**
    - Einen verwundeten Teamkollegen aus einem umgekippten Fahrzeug ziehen, während es Kraftstoff verliert.
    - Eine verstärkte Tür aus dem Rahmen treten, wenn die Breaching-Ladung zwei Räume weit weg ist.
    - Einen eingestürzten Balken lange genug hochhalten, bis der Medic einen Verwundeten freizieht.
    - Einen wehrhaften Gefangenen bei einer Snatch-Operation zu Boden ringen.
    - Eine SAW mit voller Gurtladung über zwei Klicks unwegsames Gelände tragen, ohne das Tempo zu verlieren.
    - An einem verknoteten Fast-Rope Hand über Hand in voller Ausrüstung hochklettern.

### Dexterity (DEX) {#dexterity-dex}

Geschwindigkeit, Feinmotorik und Abzugsdisziplin.

- **Attack Rolls:** Alle Ranged-Waffen (Feuerwaffen, Granatwerfer, Wurfgranaten) und Finesse-Melee. Das am häufigsten
  gewürfelte Attribut im Kompendium.
- **Häufige Checks:** Acrobatics (auf den Beinen bleiben, Gleichgewicht halten), Sleight of Hand (Lockpicks,
  Taschendiebstahl, Verstecken), Stealth.
- **Saves:** In Deckung hechten, einer Explosion ausweichen, fallenden Trümmern ausweichen. Die meisten
  "die Explosion ist gerade hochgegangen"-Würfe sind DEX Saves.
- **AC:** Addiert zur AC in Lite-Rüstung und den meisten Medium-Rüstungen (siehe [Armor](../armor.md)).
- **Initiative:** Initiative ist ein DEX Check.
- **Beispielmomente:**
    - Einen frischen Magazin in den Schacht fallen lassen, während du dich zur nächsten Deckung bewegst.
    - Einen Schuss zwischen zwei Geiseln an einem Engpass hindurchfädeln.
    - Ein Vorhängeschloss in 30 Sekunden knacken, während die Patrouille zwei Ecken entfernt ist.
    - Aus einem schwebenden Helo bei Seitenwind auf ein Dach fast-ropen.
    - Einen Kastenwagen durch eine Straßensperre fahren, ohne die Spiegel zu verlieren.
    - Ein Tourniquet einhändig in unter zehn Sekunden festziehen.
    - Am Taschenlampenkegel einer Wache vorbeischleichen, indem du dich in einen Graben legst.

### Constitution (CON) {#constitution-con}

Ausdauer, Schmerztoleranz, rohe körperliche Widerstandskraft.

- **Hit Points:** HP auf Level 1 = 10 + dein voller CON Score. Jedes Level nach dem 1. fügt 1d10 (oder 6) +
  CON-Modifier hinzu.
- **Häufige Checks:** Luft anhalten, stundenlang rennen, bei einer 36-stündigen Operation wach bleiben, der Kälte
  widerstehen.
- **Saves:** Gegen Gift, Krankheit, Schockschaden, Suppression-Effekte und das Schlimmste einer Druckwelle widerstehen.
- **Beispielmomente:**
    - Achtzehn Stunden bewegungslos in einem Ghillie-Suit auf Overwatch liegen.
    - Nach einer Kaltwasser-Insertion noch gerade schießen können.
    - Den zweiten Tag einer mehrtägigen Patrouille mit drei Stunden Schlaf durchstehen.
    - Nach einer Blendgranate auf kurze Distanz bei Bewusstsein bleiben.
    - Eine CS-Gas-Exposition während eines Room Clears schlucken und weiterhin Ziele melden.
    - Mit einem Durchschuss, der dich eigentlich umhauen sollte, noch aus eigener Kraft herauslaufen.

### Intelligence (INT) {#intelligence-int}

Bildung, logisches Denken, Erinnerung. Das Fachwissens-Attribut.

- **Häufige Checks:** Investigation (eine Szene lesen, einem Hinweis nachgehen), History, Nature (Gelände, Wetter),
  Tech-Analyse, Sprengstoffmathematik, Sprache und Code-Arbeit.
- **Saves:** Widerstand gegen mentale Eindringversuche, Täuschung, Illusion und Desorientierung.
- **Skills auf Level 1 gewählt:** Anzahl der Start-Skills = 2 + INT-Modifier. INT zieht bei der Charaktererstellung
  auch für Nicht-Techs mit.
- **Beispielmomente:**
    - Ein feindliches Gewehr allein an der Kadenz erkennen.
    - Im Kopf eine P-for-Plenty-Ladung für einen unbekannten Stahlträger ausrechnen, während das Breach-Fenster sich
      schließt.
    - Die Kontaktliste eines erbeuteten Handys mit dem Target Package im Vorbeigehen abgleichen.
    - Ein verschlüsseltes Squad-Net auf geliehenen zivilen Funkgeräten aufbauen.
    - Marke und Ausstattung eines Fahrzeugs aus einem halbsekündigen CCTV-Blick erkennen.
    - Einen Bauplan in einer fremden Sprache gut genug lesen, um die tragenden Wände zu finden.

### Wisdom (WIS) {#wisdom-wis}

Aufmerksamkeit, Intuition, Lagebild. Was einen kompetenten Schützen von einem trennt, der überlebt.

- **Häufige Checks:** Perception (der am häufigsten gewürfelte Skill im Spiel), Insight, Survival, Animal Handling,
  Medicine.
- **Saves:** Widerstand gegen Angst (Shaken), Charm und sich zu etwas Dummem überreden zu lassen.
- **Passive Perception:** 10 + WIS-Mod + relevantes Training. Wird vom GM ständig für Hinterhalt, Stealth und "merkst
  du etwas" verwendet.
- **Beispielmomente:**
    - Das Aufblitzen eines Scopes auf einem Dach zwei Blocks entfernt erkennen.
    - Frisch umgegrabene Erde neben der Straße entdecken und den Konvoi zum Halten bringen.
    - Die Körpersprache eines Checkpoint-Wachpostens lesen und merken, dass er dich schon hat auffallen sehen.
    - Wissen, dass der verwundete Teamkollege untertreibt und der Triage Code schlimmer ist als er sagt.
    - Vorhersagen, dass das Wetterfenster vor dem Exfil schließt, und die Zeitlinie vorziehen.
    - Die Nerven behalten, wenn eine Splittergranate im eigenen Foxhole landet und noch etwas zu tun ist.

### Charisma (CHA) {#charisma-cha}

Persönlichkeitsstärke. Kommando-Präsenz auf einem freundlichen Element, Einschüchterung auf einem feindlichen, sich
an einem Checkpoint vorbeireden.

- **Häufige Checks:** Intimidation, Persuasion, Deception, Performance (Cover-Identity-Arbeit).
- **Saves:** Widerstand gegen Effekte, die dein Selbstgefühl unterdrücken - Mind-Control-Narrative, tiefe Coercion,
  unter Verhör brechen.
- **Leadership:** [Unit Leader](../designations/unit-leader.md) Features basieren auf CHA.
- **Beispielmomente:**
    - Einen nervösen Grenzwächter davon abbringen, nach dem zweiten Papiersatz zu fragen.
    - Einer Milizkommandantin, die dich schon halb durchschaut, eine Journalisten-Cover-Story verkaufen.
    - Ein Briefing geben, das eine müde, angeschlagene Squad für das zweite Ziel wieder auf die Beine bringt.
    - Einen Gefangenen in den ersten zehn Minuten brechen, ohne Hand an ihn zu legen.
    - Eine Cover-Identität auf einer dreistündigen Social-Veranstaltung voller Leute halten, die dich erschießen würden.
    - Sichere Passage mit einem Dorfältesten aushandeln, nachdem der Übersetzer weggelaufen ist.

## Vergleich mit klassischem D&D 5E {#compared-to-classic-dd-5e}

- Die sechs Attribute, die Modifier-Formel und die +0-Baseline bei 10 sind unverändert.
- DEX ist hier noch dominanter als im klassischen 5E, weil fast alle Waffen Ranged sind.
- CON treibt HP stärker: auf Level 1 bekommst du deinen *vollen CON Score* an HP, nicht nur den Modifier.
- INT ist kein Dump-Stat. Es bestimmt deine Start-Skill-Anzahl und das meiste Tradecraft (Sprengstoffe, Kommunikation,
  Tech).
- WIS übernimmt die Arbeit, die Perception/Insight im klassischen 5E leisten - es gibt keine Naturgeister, aber es
  gibt Sniper auf Dächern.
- CHA wird selten gewürfelt, aber hat hohen Einsatz. Du bardst dich nicht durch einen Kampf, aber du redest dich durch
  einen Checkpoint.
