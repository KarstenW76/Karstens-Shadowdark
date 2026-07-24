---
{"dg-publish":true,"dg-path":"Regeln/Regeln für SL/Regelübersicht für SL.md","permalink":"/Regeln/Regeln für SL/Regelübersicht für SL/","dg-note-properties":{}}
---


# Regeln für Spieler

## Unsichere Rast in Wildnis/Dungeon

- **Dauer** 2 Tagesabschnitte = 8 Stunden; jeder Held verbraucht 1 Ration (sonst siehe *Entbehrung & Schlafmangel*)
- **Lagerfeuer**: Benötigt 3 Fackeln; brennt bis zu 8 Stunden, solange mindestens ein Held *nah* bleibt; wirft Licht in *naher* Distanz
- Offen im Dungeon sehr riskant (hohe Entdeckungsgefahr durch Licht oder Überraschungsangriff wenn kein Licht; sicherer Raum schwer zu finden)
- **Unterbrechung**: Jede stressige Unterbrechung der Rast (insbes. Kampf) erfordert von jedem Held eine KON-Probe SG 12; bei Misserfolg hat er keinen Nutzen aus der Rast
- **Wenn Rast erfolgreich abgeschlossen**: Regeneration TP in Höhe geworfener Trefferwürfel; Regeneration 1d4 Attributsschaden (Spieler verteilt); Zauberwirker regenerieren verlorene Zauber (Priester mit Buße-Erfordernis nicht)

### Entbehrung & Schlafmangel

**Rast ohne Rationen**: Wird eine Rast ohne den Verbrauch einer Ration abgeschlossen, verfällt jeglicher Nutzen der Rast (keine Heilung, keine Zauber), mit Ausnahme, dass sie als "erfolgreich abgeschlossen" gilt (für manche Talente relevant). Darüber hinaus beachte die 24 Stunden Regel zu *Nahrung und Schlaf*.

**Nahrung und Schlaf**: Ein Held kann maximal 6 Tagesabschnitte = 24 Stunden ohne *Nahrung* (umfasst Essen + Trinken) und *Schlaf* auskommen. Dann wird der Held *Erschöpft*: Du hast *Nachteil* auf alle Proben, bis du dein Grundbedürfnis gedeckt hast:
- **Nahrung**: Verbrauche eine Ration (dauert 1 Dungeon-Runde = 6 Minuten)
- **Schlaf**: Schließe eine Rast erfolgreich ab. 

---

## Schaden, Heilung und Tod

### Schaden erleiden

**Angriff**: Erfolgreicher Treffer verursacht Waffenschaden (siehe [[00 Digital Garden Publish/Regeln/Regeln für SL/Regelübersicht für SL#Kampf\|#Kampf]])

**Brennen**: 1d4 Schaden/Rd. bis Feuer mit Aktion und GES SG 12 gelöscht; siehe auch [[00 Digital Garden Publish/Regeln/Regeln für SL/Regelübersicht für SL#Ölflaschen\|#Ölflaschen]] und [[00 Digital Garden Publish/Regeln/Regeln für SL/Regelübersicht für SL#Laternen\|#Laternen]]

**Ertrinken**: Bei Misserfolg der *Atem anhalten* Probe (KON SG 12 je Runde) erleidest du 1d6 Schaden/Rd. bis Atmen wieder möglich

**Stürzen**: 1d6 Schaden pro 3m (2 Grid-Felder)

### Heilung

**Rast**: Erfolgreich abgeschlossene Rast regeneriert TP und Attributsschaden, siehe [[00 Digital Garden Publish/Regeln/Regeln für SL/Regelübersicht für SL#Unsichere Rast in Wildnis/Dungeon\|#Unsichere Rast in Wildnis/Dungeon]]

**Stabilisieren**: Berührung, INT-Probe SG 15; bei Erfolg Ziel nicht mehr *Sterbend* und wacht mit 1 TP auf, ist aber *Erschöpft*: Du hast *Nachteil* auf alle Proben, bis du eine Dungeon-Runde (6 Minuten) durchschnaufen konntest.

### Sterben (Todestimer)

**Wenn TP = 0**: Held wird *bewusstlos* und ist *Sterbend*; Start *Todes-Timer*.

**Todes-Timer**: 1d4 + KON-Mod Runden (Min. 1); zu Beginn jeder seiner Runden wirft der Held 1d20, bei Nat. 20 steht er mit 1 TP wieder auf; nach Zeitablauf stirbt der Held, wenn er nicht *Stabilisiert* oder geheilt wurde

**Schaden wenn Sterbend**: Ist ein Held *Sterbend* und erhält Schaden, verringert sich sein Todes-Timer sofort um 1 (bzw. um 2 bei einem Krit)

**Nahtoderfahrung**: Kehrst du von *Sterbend* zurück (durch Nat. 20 oder weil stabilisiert/geheilt), bist du *Erschöpft*: Du hast *Nachteil* auf alle Proben, bis du eine Dungeon-Runde (6 Minuten) durchschnaufen konntest.

### Optional: Vom Tod gezeichnet

Zusatzwert im Char-Bogen: "Dem Tod entkommen:" mit 2x Checkbox. Wenn Du auf 0 TP landest, wähle:
1. Werde *bewusstlos*, sei *Sterbend* und starte den Todestimer (siehe [[00 Digital Garden Publish/Regeln/Regeln für SL/Regelübersicht für SL#Sterben (Todestimer)\|#Sterben (Todestimer)]]).
2. Nur wenn 0 TP durch Angriffshandlung: Springe dem Tod von der Schippe und markiere eine Checkbox (du kannst dies zwei mal im Leben tun), regeneriere Trefferwürfel deiner Klasse in Höhe deines halben Levels (abgerundet) zurück und bleibe aktiv im Kampf. Wirf auf der Tabelle *Heldenfähigkeiten* (du hast innewohnende Kräfte geweckt), aber auch auf der Tabelle *Verstümmelung* (alles hat seinen Preis).
3. Führe eine letzte heldenhafte Aktion mit automatisch kritischem Erfolg aus und stirb als Held.

| **d6** | **Heldenfähigkeit**                                                                                                                                                  |
| :----: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1    | **Abhärtung**: Deine KON steigt um +2 (Wenn bereits 18: Neuwurf)                                                                                                     |
|   2    | **Schlächter**: +1 auf alle Schadenswürfe im Nah- und Fernkampf                                                                                                      |
|   3    | **Robust**: +1 auf deine RK                                                                                                                                          |
|   4    | **Blutrache**: Erleidest du direkten Schaden durch einen Feind, hast du in deinem folgenden Zug bei deinem Angriffswurf gegen diesen Gegner *Vorteil*.               |
|   5    | **Zäh wie Leder**: 1x pro Rast. Wirst du von einem kritischen Treffer getroffen, wandle diesen in einen normalen Treffer um. Wiederholter Wurf: +1 Nutzung pro Rast. |
|   6    | **Glückskind**: Du erhältst zu Beginn jeder Spielsitzung 1 zusätzlichen Glückstoken.                                                                                 |

| **d6** | **Verstümmelung** |
| :----: | ---- |
|   1    | **Zerschmettertes Bein**: Du hinkst stark. Deine normale Bewegung sinkt von *Nah* auf *Doppelt-Direkt*. Mit zweiter Bewegungsaktion kannst du dich um *Nah* bewegen. |
|   2    | **Verlorenes/Blindes Auge**: Dein räumliches Sehen ist hinüber. Du hast *Nachteil* auf alle WEI-Proben, die mit *Sehen* zu tun haben und im Kampf *Nachteil* auf Fernkampf-Angriffe in Distanz *Fern*. |
|   3    | **Verstümmelter Arm**: Ein Arm ist unbrauchbar oder abgetrennt. Du hast *Nachteil* auf *Klettern* und *Schwimmen* und kannst keine zweihändigen Waffen oder Schilde mehr nutzen. |
|   4    | **Schwere Schädelfraktur**: Du hast einen heftigen Schlag gegen den Kopf kassiert. Du hast ein permanentes Pfeifen im Ohr und bekommst manchmal Migräne. Du hast *Nachteil* auf alle WEI-Proben, die mit *Hören* und deiner *Balance* zu tun haben und auf *Initiative*-Proben. |
|   5    | **Grausig entstelltes Gesicht:** Du hast eine tiefe, hässliche Narbe quer durchs Gesicht, eine zertrümmerte Nase oder verbrannte Haut. Du hast *Nachteil* auf CHA-Proben bei nichtfeindlichen sozialen Interaktionen, aber *Vorteil* auf Proben zum *Einschüchtern*. |
|   6    | **Innere Verletzung:** Du hast einen schlecht zusammengewachsenen Rippenbruch oder einen Lungenschaden. Wenn du eine 1 bei einer STR / GES / KON Probe (inkl. Angriff) würfelst, erleidest du vor Schmerz sofort 1d4 Schaden (dies kann dich aber nicht unter 1 TP bringen). |

---

## Vergleichsproben

Agieren 2 Kreaturen gegeneinander, muss die Kreatur, die etwas am Status Quo ändern will, das höhere Ergebnis erreichen (*z.B. WEI gegen GES um Schleichen zu entdecken oder STR gegen STR um eine zugehaltene Tür aufzudrücken*).

---

## Zeit vergeht

### Tagesabschnitt

Ein Tag besteht aus 6 Abschnitten mit je 4 Stunden; *Reihenfolge: Spieler (nach Bedarf in fester Reihenfolge oder individuell) beschreiben ihr Tun -> SL reagiert*
- **Vorsichtig weiter (2 Abschnitte / 1 Hex-Feld)**: Das nächste Hex-Feld erkunden und dabei nach Gefahren Ausschau halten -> meist keine Würfe erforderlich
- **Normal weiter (1 Abschnitt / 1 Hex-Feld)**: Wie *Vorsichtig* Erkundung des nächsten Hex-Feldes, aber in halber Zeit -> meist Chance auf Rettungswurf
- **Schnell weiter (1 Abschnitt / 2 Hex-Felder)**: Wie *Normal*, aber doppelte Entfernung -> meist keine Chance auf Rettungswurf
- **Jagen (1 Abschnitt)**: Proviant sammeln / jagen
- **Rast (2 Abschnitte)**: Eine Rast dauert 2 Tagesabschnitte (Schlafen, Wache, Essen/Trinken, Wunden versorgen, Zauber regenerieren usw.). Jeder Held verbraucht 1 Ration (sonst kein Nutzen)

### Dungeon-Runde

Entspricht 6 Minuten der Erkundung in unbekanntem Terrain; Reihenfolge *Spieler & SL abwechselnd*
- **Vorsichtig weiter**: Bis zu *Nah (9m / 6 Grid-Felder)* bewegen bzw. kleinen Raum (bis zu 12 Grid-Felder) erkunden und dabei nach Gefahren suchen -> geringe Laustärke, meist Gefahrankündigung ohne Wurf
- **Normal weiter**: Bis zu *Doppelt-Nah (18m / 12 Grid-Felder)* bewegen bzw. größeren Raum (bis zu 25 Grid-Felder) oberflächlich erkunden -> leicht reduzierte Laustärke, meist Chance auf Rettungswurf vor Gefahren
- **Schnell weiter**: Bis zu *Extrem (72m / 48 Grid-Felder)* bewegen, keine Erkundung -> laut, meist keine Chance auf Rettungswurf vor Gefahren
- **Begegnung**: Sozial oder Kampf (siehe [[00 Digital Garden Publish/Regeln/Regeln für SL/Regelübersicht für SL#Kampf\|#Kampf]]) oder Kampf vermeiden
- **Verschnaufen**: Verschnaufen, Looten, Erste Hilfe, schnelles Essen / Trinken

### Kampfrunde

siehe [[00 Digital Garden Publish/Regeln/Regeln für SL/Regelübersicht für SL#Kampf\|#Kampf]]; Reihenfolge *Initiative*


---
---


# Regeln für SL

## Boss-Monster

- Bosse agieren nicht in regulärer Initiative-Reihenfolge, stattdessen führen sie einen ihrer **Angriffe nach jeder Runde eines Helden** durch (und ggf. verbleibende am Ende)
- Bosse haben meist *Glückstoken* und setzen gerne *Schicksalstoken* ein

---

## Crawling-Uhr & Wandernde Monster

- Crawling-Uhr startet mit Betreten eines Dungeons und beginnt bei 24
- SL würfelt am Ende jeder Runde einen Crawler-Würfel gem. Gefahrenstufe und reduziert die Uhr um das Ergebnis
	- **Unsicher**: d4
	- **Riskant**: d6
	- **Tödlich**: d8
- Eine zufällige Begegnung findet statt, wenn die Crawling-Uhr auf null sinkt.

| 1d6 | Entfernung | | 2d6 | Aktivität | | 2d6 + CHA-Mod | Reaktion |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Direkt | | 2-4 | Jagen | | 0-6 | Feindselig |
| 2-4 | Nah | | 5-6 | Essen | | 7-8 | Misstrauisch |
| 5-6 | Fern | | 7-8 | Bauen/Nisten | | 9 | Neutral |
| | | | 9-10 | Soziales/Spielen | | 10-11 | Neugierig |
| | | | 11 | Bewachen | | 12+ | Freundlich |
| | | | 12 | Schlafen | | | |

---

## Moral

Halbieren der TP eines intelligenten Gegners oder der Hälfte einer Gegnergruppe: Flucht, falls WEI-Probe gegen SG 15 misslingt (bei größerer Gruppe Probe durch Anführer)

---

## Orte volatiler Magie

Orte, die Schauplatz großer Katastrophen oder kosmischer Ereignisse waren, sind häufig wild von arkaner Energie durchdrungen und machen den Einsatz von Magie unberechenbar und gefährlich.

An solchen Orten werden kritische Erfolge beim Zauberwirken durch ein Ergebnis von 16-20 auf dem d20 erzielt, und kritische Fehlschläge treten bei einem Würfelergebnis von 1-5 auf dem d20 ein.

---

## Rast

- Während einer Rast (8 Stunden) im Dungeon wird die *Crawling-Uhr* pausiert
- Der SL würfelt je Wache einen d6 auf eine Zufallsbegegnung; bei einer **1** (oder modifiziert, siehe Tabelle) wird die Wache gestört
- Risiko und Umstände einer Begegnung hängen völlig von den Entscheidungen der Helden ab:

| Lager-Zustand | Begegnungs-Chance (d6) | Auswirkung bei Kampf / Überraschung |
| :--- | :---: | :--- |
| **Sicherer Raum**<br>*(verbarrikadiert)* | **Nur 1 Wurf**<br>*(für die gesamte Rast)* | Monster müssen Barrikade durchbrechen (Lärm!); keine Überraschung, Gruppe kann sich formieren |
| **Ungesichert & Offen**<br>*(z.B. in einem Hauptflur)* | **1–2** | Normaler Kampf. Die Wache ist zwar aufmerksam, aber der Ort zieht durch die exponierte Lage mehr Durchgangsverkehr an. |
| **Mit Lagerfeuer**<br>*(offen im Raum/Flur)* | **1–2**<br>*(ggf. 1–3)* | Wache kann sehen, Licht lockt aber Monster an; bei sehr langen/offenen Sichtlinien kann der SL die Chance auf 1–3 erhöhen; Keine Überraschung für die Wache. |
| **Im Dunkeln**<br>*(offen, ohne Feuer)* | **1** | **Hinterhalt!** Geringste Chance, entdeckt zu werden, aber wenn, überraschen die Monster die Gruppe; Helden haben *Nachteil* auf alle Würfe solange kein Licht ist. |

---

## Schätze

**Goldfund (Gruppe)**
Pro Schatzfund sollte jede Gruppe etwa den Wert von 10 GM x ihrem durchschnittlichen Gruppen-Level erhalten, oder:
* 20 GM Gegenwert, Level 0-3
* 50 GM Gegenwert, Level 4-6
* 80 GM Gegenwert, Level 7-9
<br>

**EP (jeder Held)**

| Qualität | EP | Beschreibung | Beispiele |
| :--- | :--- | :--- | :--- |
| **Kläglich** | 0 | Profan, geringer Wert, gewöhnlich, unspektakulär | Beutel mit Silber, gebrauchter Dolch, Knochen-Spielwürfel |
| **Normal** | 1 | Guter Wert, schützenswert, nützlich | Beutel mit Gold, Edelstein, edle Rüstung, magische Schriftrolle |
| **Sensationell** | 3 | Unglaublich, kostbar, gut bewacht | Magisches Schwert, riesiger Diamant, Mithral-Kettenhemd |
| **Legendär** | 10 | Mythisch, einzigartig, einer Quest würdig | Der Stab von Ord, der Wunsch eines Dschinns, ein Drachenhort |

---

## Schwierigkeitsgrad (SG)

| | | |
| :--- | :--- | :--- |
| Einfach | 9 | Über einen schmalen Abgrund springen, sich an eine unaufmerksame Wache heranschleichen |
| Normal | 12 | Eine klemmende Tür auftreten, ein einfaches Schloss knacken |
| Schwer | 15 | Gegen eine starke Strömung anschwimmen, Sterbenden Gefährten stabilisieren |
| Extrem | 18 | Einhändig eine rutschige Klippe erklimmen, einen rasenden Löwen bändigen |
