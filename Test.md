<!--
author:   J.Müller

email:    Jan.Mueller4@schule.hessen.de

version:  0.0.1

language: Deutsch

narrator: Deutsch Female

comment:  

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

translation: Deutsch  translations/German.md

translation: Français translations/French.md
-->

# Eingabeobjekte

## Signale

Nach dem EVA-Prinzip wird eine Steuerung in die drei Ebenen Eingabe, Verarbeitung und Ausgabe eingeteilt. Diesem Prinzip folgend sollen zunächst
die Informationsquellen (**Sensoren** [sensors] und Bedienelemente [operating devices]) sowie die Objekt betrachtet werden, die die Verarbeitungsergebnisse im System umsetzen (Aktoren [actuators]).

Bei der stark vereinfachten Systemdarstellung (Abb. 1 ) wird deutlich, dass die Signale der Eingabeebene in der Verarbeitungsebene ausgewertet werden, bzw. die Verarbeitungsergebnisse an die Aktoren (Ausgabe) übermittelt werden.

Die Ausgangsinformationen des vorangehenden Objektes stellen die Eingangsinformationen des folgenden Objektes dar 1. Diese Übergabepunkte werden
Schnittstellen [interfaces] genannt. Schnittstellen sind normiert, da in der Steuerungstechnik oftmals Produkte unterschiedlicher Hersteller Verwendung finden und daher zueinander kompatibel sein müssen.

![Abb 1: Zusammenwirkung der Objekte](assets/Zusammenwirkung_Objekte.png "Abb 1: Zusammenwirkung der Objekte")  

### Binärsignale

Bei Binärsignalen sind nur zwei Zustände möglich (bi: lat. zwei). Diese können sehr einfach ausgewertet werden und lassen sich durch Pegel darstellen.

|Hoher Pegel | Niedrieger Pegel |
|------------|------------------|
| An | Aus |
| High | Low |
| H | L |
| 1 | 0 |

#### Beispiel

- Ein unbetätigter Schließer (Kontakt, der im unbetätigten Zustand geöffnet ist, (2)) ist „0", „Aus" oder „Low" (kurz „L").
- Ein betätigter Schließer @ ist „1", „An"oder „High" (kurz „H").

![Abb.2: Schließer und Öffner](assets/Pegel.png "Abb.2: Schließer und Öffner") 

während der Pegel den Zustand bzw. das Signalniveau beschreibt, verbirgt sich hinter dieser sehr allgemeinen Eingabe ein von der eingesetzten Steuerung abhängiger Spannungsbereich. Die in der Steuerungstechnik gängigsten Bereiche sind 0 12 V, 0 V... 24 V und 0 V...230 v.

Dabei wird ein niedriger Spannungsbereich als „0"-Signal und ein hoher als „1 "-Signal festgelegt. Dazwischen liegt der „verbotene Bereich" 4, 5 als eindeutige Trennung zwischen den Pegeln (Abb. 3). In dieser Zone kann ein Signal keinem Pegel korrekt zugeordnet werden.

 ![picture 4](assets/Spannungsbereiche.png "Abb. 3: Spannungsbereiche der 0/1 - Signale bei unterschiedlichen Pegeln")  

### Analoge Signale

Der Windsensor der Windenergieanlage liefert ein analoges Signal. Dieses kann in einem begrenzten Bereich jeden beliebigen Wert annehmen. So entspricht eine Ausgangsspannung von z. B. 4,5 V einer bestimmten Windstärke.

Viele Sensoren verwenden folgende genormten Schnittstellenwerte für Analogsignale:

- 0 V bis 10 V
- 4 mA bis 20 mA
- 0 mA bis 20 mA

### Zuammenfassung

- Damit die Objekte einer Steuerung zusammen arbeiten können, müssen ihre Schnittstellen angepasst sein.
- Binärsignale werden bestimmten Pegeln zugeordnet. Dabei ist das 1-Signal der höhere Pegel und das 0-Signal der niedrigere Pegel.
- Analogsignale werden im Bereich der Automatisierungstechnik meist in den Größen 0 V bis 10 V, 4 mA bis 20 mA oder O mA bis 20 mA dargestellt.

## Bedienelemente

Bedienelemente können Taster oder Schalter sein. Da sie zur Befehlseingabe von Hand eingesetzt werden, stellen sie die Verbindung zwischen Mensch und Steuerung her. Im Folgenden werden die Bedienelemente und Sensoren der Windenergieanlage mit ihren Alter- nativen vorgestellt.

Drucktaster, Schalter und Touch-Panel werden zur Befehlseingabe von Hand verwendet, wenn z. B. zwischen Hand- und Automatikbetrieb gewählt wird. In der Sturmschutz-Steuerung kommen sie zum Einsatz, wenn ein Zeitglied vorzeitig zurückgesetzt(quittiert) werden soll, um den Rotor vorzeitig wieder in den Wind zu fahren.

### Drucktaster und Schalter

Ist ein Taster (Abb. 4) sowohl mit Schließer- als auch Öffner-Kontakten ausgestattet, muss beachtet werden, dass bei einer Betätigung immer zunächst der Öffnerkontakt (1) öffnet, bevor der Schließerkontakt (2) schließt (Tasterverriegelung).
Dieser Zusammenhang ist in dem Signal-Betätigungsweg-Diagramm der Abb. 4 verdeutlicht.

![picture 4](assets/Taster_Betaetigung.png "Abb. 4: Verhalten der Taster-Kontakte bei Betätigung")  

Die Farbe des Tasters (Abb. 5) weist auf die Funktion hin. Entsprechend der Abb. 6 werden den unterschied
lichen Bedeutungen und Anwendungen bestimmte Far
ben zugeordnet. Die Farbe Gelb wird zur Beseitigung
einer anormalen Bedingung oder unerwünschten Ände-
rung verwendet. Bei der Windenergieanlage wird Gelb
daher für die Quittierung der Sturmschutz-Zeit verwen-
det. Weitere festgelegte Farbkennzeichnungen gelten