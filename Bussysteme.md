<!--
author:   

email:    

version:  0.0.1

language: Deutsch

narrator: Deutsch Female

comment:  

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

-->

# Bussysteme

![Alt text](assets/Bussysteme.png)

## Bussystemen in der Elektrotechnik

Bussysteme in der Elektrotechnik, auch bekannt als Binary Unit System, sind Datenübertragungssysteme, die zum standardisierten Verbinden dezentral angeordneter Geräte, der sogenannten Busteilnehmer, dienen[^4]. Sie ermöglichen den einheitlichen Austausch von Daten zwischen verschiedenen Teilnehmern bzw. Komponenten[^5]. 

Die übertragenen Daten dienen dem Melden und Steuern und anderen betriebstechnischen Funktionen[^4]. Bussysteme bilden die Voraussetzung für eine umfassende Gebäudeautomation[^4]. Sie sind vergleichbar mit dem menschlichen Blutkreislauf, der Nährstoffe zu den einzelnen Organen transportiert, und bringen Energie und Daten zu den einzelnen Komponenten des Netzwerks[^3].

Einige Beispiele für Bussysteme sind PROFIBUS, CAN, I2C und Ethernet[^1]. Diese Systeme müssen elektrisch und mechanisch sehr robust sein, um in einer rauen industriellen Umgebung zuverlässig zu funktionieren[^1]. 

Moderne Bussysteme zeichnen sich dadurch aus, dass nicht jeder Sensor eine eigene Leitung z.B. zu einer Zentralsteuereinheit hat, sondern dass nur eine einzige Leitung existiert, die durch alle Sensoren geführt wird[^1]. Die Informationen werden daher nicht mehr gleichzeitig auf parallelen laufenden Leitungen, sondern zeitversetzt seriell auf einer gemeinsamen Leitung übertragen[^1]. Dazu muss jeder Information eine Adresse zur Identifikation mitgegeben werden[^1].

[^1]: BUS-Technik - Heizung - Regelung - Baunetz_Wissen. https://www.baunetzwissen.de/heizung/fachwissen/regelung/bus-technik-161246.
[^2]: Was ist Bus (Elektrotechnik)? Binary Unit System - schnell erklärt. https://heinen-elektronik.de/glossar/bus/.
[^3]: Industrielle Bussysteme – Funktionsweise und Anforderungen. https://industrie-wegweiser.de/bussysteme/.
[^4]: Was sind Bussysteme, Schnittstellen und Sensornetze? Erklärung .... https://www.industry-of-things.de/was-sind-bussysteme-schnittstellen-und-sensornetze-erklaerung-funktionsweise-und-ueberblick-a-683219/.
[^5]: Bussystem Grundprinzip - Aufbau Bussystem - Funktion Bussystem. https://dein-elektriker-info.de/grundprinzip-bussystem/.

### Vorteile

Bussysteme werden in der Elektrotechnik aus verschiedenen Gründen verwendet:

1. **Automatisierung und Kontrolle**: Mithilfe von Bussystemen können verschiedene Prozesse und Geräte in Gebäuden miteinander vernetzt und zentral überwacht sowie gesteuert werden[^6]. 
2. **Energieeffizienz und Kosteneinsparungen**: Die Bus-/Gebäudesystemtechnik kann dazu beitragen, den Energieverbrauch in Gebäuden zu reduzieren, indem sie die Beleuchtung, Heizung, Klimatisierung und Belüftung automatisch reguliert und an die Bedürfnisse der Nutzer und des Gebäudes anpasst[^1]. Die Reduzierung des Energieverbrauchs und die Optimierung der Wartung und Instandhaltung verringert zugleich die Kosten[^1].
3. **Sicherheit**: Die Integration von Sicherheitskomponenten kann die Sicherheit von Gebäuden erhöhen und Schäden durch Einbrüche oder Brände verhindern[^1].
4. **Flexibilität**: Durch die Möglichkeit, die Steuerung und Überwachung von Gebäuden zentral zu verwalten, kann die Bus-/Gebäudesystemtechnik eine hohe Flexibilität und Anpassungsfähigkeit bieten[^6].
5. **Vereinfachte Installation und Wartung**: Im Gegensatz zur klassischen Elektroinstallation, bei der Steuerfunktion und Energieverteilung fest verbunden sind, trennt das Bussystem die Steuerung der Geräte und die Stromversorgung[^2]. Dies führt zu Kostensenkungen in Bezug auf Material und Arbeitsaufwand[^5].
6. **Datenaustausch**: Ein Bus (Binary Unit System) stellt die Verbindung zwischen verschiedenen Teilnehmern bzw. Komponenten her und ermöglicht somit den einheitlichen Austausch von Daten[^7].

[^6]: Grundprinzip von Bussystemen | Elektro - Baunetz Wissen. https://www.baunetzwissen.de/elektro/fachwissen/gebaeudesystemtechnik/grundprinzip-von-bussystemen-153070.
[^7]: Anwendung von Bussystemen und Protokollen. https://www.kunbus.de/anwendung-von-bussystemen-und-protokollen.

### Nachteile

Bussysteme bieten viele Vorteile, aber sie haben auch einige Nachteile:

1. **Nachrüstung**: Kabel-Bussysteme lassen sich nur schlecht nachrüsten und erfordern eine detaillierte Planung.
2. **Reichweite und Störanfälligkeit**: Funkbasierte Systeme sind in ihrer Reichweite beschränkt und haben ein höheres Störrisiko.
3. **Kosten der Steuereinheit und Erweiterungen**: Bei einem BUS-System kommen noch die Kosten der Steuereinheit und diverser Erweiterungen hinzu.
4. **Komplexität**: Je komplexer das Gebäude und die Ansprüche, umso eher lohnt sich ein Bussystem. Bei weniger komplexen Anforderungen ist die konventionelle Methode immer noch preislich im Vorteil.

### 1. Quiz 

## Netzwerktopologien

Es gibt verschiedene Arten von Netzwerktopologien, die in Eingesetzt verwendet werden können:

1. **Stern-Topologie (Star Topology)**: In dieser Topologie ist jeder Knoten (z.B. Computer, Drucker) über eine separate Verbindung direkt mit einem zentralen Netzwerkknoten verbunden. Der zentrale Netzwerkknoten könnte ein Netzwerk-Switch, Hub oder Router sein.
2. **Ring-Topologie (Ring Topology)**: In einer Ring-Topologie sind alle Knoten in Form eines geschlossenen Schleifenrings miteinander verbunden. Jeder Knoten ist genau mit zwei anderen Knoten verbunden.
3. **Bus-Topologie (Bus Topology)**: Bei einer Bus-Topologie sind alle Knoten entlang einer einzigen Kabelstrecke, dem sogenannten "Backbone", verbunden. 
4. **Baum-Topologie (Tree Topology)**: Eine Baum-Topologie ist eine Erweiterung der Stern-Topologie. In der Baum-Topologie sind mehrere Stern-Topologien auf einem zentralen Bus aufgebaut.
5. **Maschen-Topologie (Mesh Topology)**: In einer Maschen-Topologie ist jeder Knoten mit vielen (in einigen Fällen mit allen) anderen Knoten verbunden. 

Jede Topologie hat ihre spezifischen Einsatzmöglichkeiten und Vorteile. Die Wahl der Bustopologie hängt von den spezifischen Anforderungen des Netzwerks ab.

### 2. Quiz
## OSI-Schichten Modell

Das OSI-Modell (Open Systems Interconnection) ist ein Referenzmodell für Netzwerkprotokolle[^8]. Es wurde von der International Organization for Standardization (ISO) entwickelt, um die standardisierte Kommunikation zwischen verschiedenen Computersystemen zu ermöglichen[^9]. Das Modell besteht aus sieben Schichten[^10]:

1. **Physical Layer (Bitübertragungsschicht)**: Diese Schicht ist für die physikalische Übertragung von Daten zuständig.
2. **Data Link Layer (Sicherungsschicht)**: Diese Schicht stellt eine fehlerfreie Verbindung zwischen den Netzwerkknoten her und kontrolliert den Datenfluss.
3. **Network Layer (Vermittlungsschicht)**: Diese Schicht ist für die Wegewahl (Routing) und die Vermittlung von Datenpaketen zuständig.
4. **Transport Layer (Transportschicht)**: Diese Schicht stellt eine zuverlässige Ende-zu-Ende-Verbindung her und sorgt für die korrekte Reihenfolge der Datenpakete.
5. **Session Layer (Sitzungsschicht)**: Diese Schicht ermöglicht den Aufbau, die Steuerung und den Abbau von Sitzungen zwischen Anwendungsprozessen.
6. **Presentation Layer (Darstellungsschicht)**: Diese Schicht ist für die Darstellung der Daten verantwortlich und sorgt dafür, dass die Daten so umgewandelt werden, dass sie von der Anwendungsschicht verstanden werden können.
7. **Application Layer (Anwendungsschicht)**: Diese Schicht stellt Funktionen für Anwendungen bereit und ermöglicht den Zugriff auf Netzwerkdienste.

Jede Schicht erfüllt dabei eine bestimmte Aufgabe und kommuniziert mit den Schichten direkt über und unter ihr. Die Schichten können miteinander kommunizieren und Daten unter sich austauschen. Bei der Kommunikation zwischen zwei Systemen werden alle sieben Schichten mindestens zwei Mal angewendet: jeweils einmal beim Sender und einmal beim Empfänger[^11]. 

Das OSI-Modell ist kein konkreter Netzwerkstandard, sondern beschreibt in abstrakter Form, welche Vorgänge geregelt werden müssen, damit die Kommunikation über ein Netzwerk funktioniert. Es bietet als konzeptioneller Rahmen eine Design-Grundlage für herstellerunabhängige Kommunikationsstandards[^9].

[^8]: OSI-Modell - Wikiwand. https://www.wikiwand.com/de/OSI-Modell.
[^9]: OSI Modell • 7 Schichten Modell, Erklärung, Anwendung. https://studyflix.de/informatik/osi-modell-5524.
[^10]: Das Osi Schichtenmodell: Einfach und verständlich erklärt!. https://praxistipps.chip.de/das-osi-schichtenmodell-einfach-und-verstaendlich-erklaert_160368.
[^11]: Grundlagen OSI-Modell einfach erklärt - simpleclub. https://simpleclub.com/lessons/fachinformatikerin-grundlagen-osi-modell.

### 3. Quiz
## Feldbusse

Feldbussysteme sind Datennetzwerke auf der industriellen Feldebene[^12]. Sie sind ein Oberbegriff für verschiedene Bussysteme, die in der Automatisierung, Fertigungstechnik, Gebäudeautomation sowie im Bereich Automotive zum Einsatz kommen und Bestandteil nahezu jeder komplexen Maschine oder Anlage sind[^13]. 

In einem Feldbussystem sind alle Komponenten mit der Regel- oder Steuerebene verbunden[^13]. Sie werden in Maschinen und Anlagen eingesetzt, um Sensoren und Aktoren (Motor) miteinander und mit einem oder mehreren zentralen Leitrechnern (Industrie-PC, SPS) zu verbinden[^14].

Ein Feldbus ist ein Bussystem, das in einer Anlage Feldgeräte wie Messfühler (Sensoren) und Stellglieder (Aktoren) zur Kommunikation mit einem Automatisierungsgerät verbindet[^1]. Wenn mehrere Kommunikationsteilnehmer ihre Nachrichten über dieselbe Leitung senden, dann muss festgelegt sein, wer (Kennung) was (Messwert, Befehl) wann (Initiative) sagt[^1]. Hierfür gibt es normierte Protokolle[^15].

Die erste Generation der Feldbustechnik wurde in den 1980er Jahren entwickelt, um die bis dahin übliche Parallelverdrahtung binärer Signale sowie die analoge Signalübertragung durch digitale Übertragungstechnik zu ersetzen. Heute sind viele unterschiedliche Feldbussysteme mit unterschiedlichen Eigenschaften am Markt etabliert. Seit 1999 werden Feldbusse in der Norm IEC 61158 (Digital data communication for measurement and control – Fieldbus for use in industrial control systems) weltweit standardisiert[^15].

[^12]: Feldbus – Wikipedia. https://de.wikipedia.org/wiki/Feldbus.
[^13]: Feldbussysteme - NANOTEC. https://de.nanotec.com/knowledge-base-artikel/feldbussysteme/.
[^14]: Was ist ein Feldbus? Grundlagen schnell erklärt - Glossar. https://heinen-elektronik.de/glossar/feldbus/.
[^15]: CAN-Bus Aufbau und Funktion. http://www.antal.de/htm/can.htm.

## ASi Feldbus

Das Actuator-Sensor-Interface, kurz ASi, ist ein Feldbussystem, das heute in nahezu allen Industriezweigen anzutreffen ist. Es wird seit Anfang der 1990er eingesetzt, um induktive, kapazitive und opto-elektronische Sensoren effektiver in automatisierte Produktionsprozesse einzubinden[^16].

AS-Interface ist als offener Standard nach IEC 62026-2 genormt und vollständig im TIA Portal integriert[^17]. Es ermöglicht eine Verkabelung mit frei wählbarer Topologie und ersetzt die aufwendige, herkömmliche Parallelverdrahtung. Die Verkabelung kann an Steuerungssysteme mit unterschiedlichen Feldbussystemen (etwa EtherNet/IP, Profibus-DP, Profinet, EtherCat etc.) angebunden werden[^18].

Ein zweiadriges Flachkabel überträgt Daten und Energie, wodurch die aufwendige Parallelverdrahtung entfällt. Die ausgereifte AS-Interface Technologie bietet eine hohe Zuverlässigkeit, Störsicherheit und vielfältige Diagnosemöglichkeiten. Der modulare Aufbau und die flexible Anschlusstechnik sorgen für eine einfache Eingliederung in die Anlage[^18].

AS-Interface ist ein effektives, leistungsstarkes Bussystem, das die Sensoren und Aktoren in der untersten Feldebene mit der übergeordneten Steuerung verbindet[^16]. Es ist einfach zu implementieren, flexibel, preiswert und einfach erweiterbar. Sichere und nicht sichere Informationen können über das gleiche System verarbeitet werden. Es bietet zudem eine Reduzierung von Klemmstellen durch modularen und flexible Anschlusstechnik[^18].

[^16]: ASi Bus System im Überblick - ifm - ifm electronic. https://www.ifm.com/de/de/shared/technologien/as-interface/systemuberblick.
[^17]: AS-Interface Basiswissen – So funktioniert das Bussystem für die .... https://www.elektormagazine.de/articles/as-interface-basiswissen-so-funktioniert-das-bussystem-fur-die-industrieautomation.
[^18]: ASi Bus/AS-Interface - Tools & Diagnosegeräte - Indu-Sol. https://www.indu-sol.com/produkte/as-interface/diagnose/.
### Komponenten des AS-Interface
Das ASi-System besteht aus vier Hauptkomponenten:

- **ASi-Master:** Der ASi-Master organisiert den Datenverkehr im Netzwerk und stellt die Verbindung zwischen dem ASi-Kreis und der übergeordneten Steuerung her. Er behandelt die Eingabe eines ASi-Netzwerks in ein vorhandenes Feldbus- oder Ethernet-System genauso einfach wie die Integration eines beliebigen E/A-Moduls[^1].
- **ASi-Netzteil:** Das ASi-Netzteil liefert die benötigte Energie für das System.
- **ASi-Kabel:** Das gelbe ASi-Kabel ist eine ungeschirmte, zweipolige Leitung, die sowohl Daten als auch Energie überträgt. Dank der Durchdringungstechnik können Teilnehmer einfach auf das profilierte und damit verpolungssichere ASi-Kabel montiert werden. Eine zusätzliche Versorgung mit 24 V ist dank eines zusätzlichen AUX Profilkabels problemlos möglich[^1].
- **ASi-Teilnehmer:** Die ASi-Teilnehmer sind die Sensoren und Aktuatoren, die mit dem ASi-Master über das ASi-Kabel verbunden sind. Jeder Teilnehmer kann standardmäßig über jeweils vier Eingänge zum Auslesen von vier Sensoren und vier Ausgänge zum Steuern von Aktuatoren verfügen[^2].

[^1]: https://www.bihl-wiedemann.de/de/unternehmen/technologische-grundlagen/bussysteme/asi-bussystem
[^2]: https://www.as-interface.de/de/as-interface/technik/

#### ASi-Master

Der AS-Interface Master ist die zentrale Einheit des AS-Interface-Systems. 
Er übernimmt die Steuerung des Datenaustauschs zu den einzelnen Teilnehmern (Slaves) im AS-Interface-Netzwerk. Der Master wertet die Telegramme der Slaves aus, sendet neue Funktionsparameter und überwacht gleichzeitig die Busfunktion[^3].

Der AS-Interface Master ist in der Regel ein SIMATIC-Produkt, das für Industrie-PCs und Automatisierungsgeräte angeboten wird. 
Die Palette der verfügbaren Masteranschaltungen wird laufend erweitert, sodass das AS-Interface-System flexibel angepasst werden kann[^4].

Die Hauptaufgaben des AS-Interface Masters sind:

- Steuerung des Datenaustauschs zu den Slaves
- Auswertung der Telegramme der Slaves
- Senden neuer Funktionsparameter
- Überwachung der Busfunktion
- Kommunikation mit der übergeordneten Steuerung

Der AS-Interface Master arbeitet im Master-Slave-Verfahren, bei dem es pro AS-Interface-Netzwerk nur einen Master gibt, der den Datenaustausch steuert. 
Dieser ruft nacheinander alle AS-Interface-Slaves auf und erwartet deren Antwort[^4].

[^3]: https://www.weka.de/elektrosicherheit/as-interface/
[^4]: https://www.manualslib.de/manual/181576/Siemens-As-Interface.html

#### ASi-Netzteil

Ein AS-Interface Netzteil ist ein spezielles Netzteil, das zur Versorgung des AS-Interface (ASi) Systems mit Strom verwendet wird. Es hat die Aufgabe, die angeschlossenen Module, Sensoren und Aktuatoren zuverlässig mit Strom zu versorgen. 

Neben der Versorgung des Netzes muss das ASi Netzteil gleichzeitig eine Datenentkopplung gewährleisten. Deswegen dürfen für die Versorgung des Netzes keine Standardnetzteile, sondern nur spezielle AS-Interface-Netzteile verwendet werden.

Ein typisches AS-Interface Netzteil hat einen primärseitigen Anschluss an 120 V AC / 230 V AC (1-phasig) mit automatischer Bereichsumschaltung. Der sekundärseitige Ausgang liefert 30 V DC bei max. 8A. Es verfügt über eine Diagnose-LED und einen Meldekontakt "30 V okay".

#### ASi-Kabel

Als bevorzugte Leitung zum Aufbau von AS-Interface Netzwerken wurde folgendes gelbe Zweileiter-Flachband entwickelt.

![Alt text](assets/ASI_Flachbandkabel.png)

Es ist Basis der Elektromechanik von AS-Interface für die Schutzart IP67 und erlaubt den Einsatz der Durchdringungstechnik. Die Leiter haben typischerweise einen Querschnitt von 1,5mm² oder 2,5mm².

Das Kabel gibt es in der Mantelfarbe "verkehrsgelb" für das AS-Interface Netzwerk sowie in der Mantelfarbe "schwarz" für die Hilfsenergie, die für manche Feldgeräte separat zugeführt werden kann.

Für eine IP20 Umgebung, wie zum Beispiel in Schaltschränken, Verteilerkästen und ähnlich geschützten Umgebungen, kann auch das folgende Doppeladerkabel zum Einsatz kommen.

![Alt text](assets/ASi_Doppelader.png)

Dessen Leiterquerschnitte belaufen sich auf 2 x 0,8mm². Diese Doppelader ist optimiert für die Kontaktierung mittels Schneidklemm-Technik.

Die Leitungslänge beträgt 100 m, erweiterbar auf bis zu 1.000 m, mit Lichtwellenleitern auf bis zu 3.000 m möglich


Die Durchdringungstechnik, auch als Klick-and-Go-Technik bezeichnet, ist eine spezielle Montagetechnik, die bei AS-Interface verwendet wird[^1]. Sie basiert auf der Verwendung des meist gelben ASi Kabels, einer verpolsicheren Flachleitung mit zwei Leitern[^1].

Bei der Montage bohren sich die Durchdringungsdorne des anzuschließenden Geräts in die Leiter des Kabels und stellen sicher den Kontakt her[^1]. Dies ermöglicht einen direkten, einfachen Anschluss von Sensoren/Aktuatoren oder Modulen[^1]. 

Einige Vorteile dieser Technik sind[^1]:
- **Verpolsichere Flachleitung**: Daten und Energie werden auf einer Leitung übertragen.
- **Einfachste Anschlusstechnik**: Sichere Kontaktierung, Schutzart IP67.
- **Ablängen und Abisolieren unnötig**: An jeder beliebigen Stelle montierbar.
- **Problemloses Versetzen durch Selbstheilungsfähigkeit des Kabels**: Je nach Kabeltyp möglich.

Die Durchdringungstechnik sorgt für den zuverlässigen Anschluss des ASi Bauteils an die Leitung des ASi Netzes[^1].

[^1]: Montage mit Durchdringungstechnik - Beckhoff Automation. https://infosys.beckhoff.com/content/1031/el6201/2328957963.html.
[^2] AS-Interface – Wikipedia. https://de.wikipedia.org/wiki/AS-Interface.
[^3] Was bedeutet Durchdringungstechnik - Definition. https://www.meister-automation.de/durchdringungstechnik/.
[^4] ASi/AS-Interface | DriveCon-Lexikon. https://www.drivecon.de/de/lexikon/asi.
#### ASi-Teilnehmer

AS-Interface Teilnehmer, auch als Slaves bezeichnet, sind alle Geräte im AS-Interface System, die vom Master überwacht und angesprochen werden. Es gibt grundsätzlich drei verschiedene Arten von Slaves[^5]:

1. **AS-Interface-Module**: Diese sind spezielle Module, die für die Kommunikation mit dem AS-Interface entwickelt wurden.
2. **Sensoren und Aktoren mit integriertem AS-Interface-Anschluss**: Diese Geräte haben einen eingebauten AS-Interface-Anschluss, der es ihnen ermöglicht, direkt mit dem AS-Interface zu kommunizieren.
3. **AS-Interface-Analog-Slaves**: Diese Geräte können analoge Signale über das AS-Interface senden und empfangen.

Die Teilnehmer werden mithilfe der Durchdringungstechnik an die Leitung kontaktiert. Diese Methode ermöglicht einen kleinen Übergangswiderstand und garantiert eine sichere Datenverbindung.

Im AS-Interface können Sie bis zu **31 Slaves** im Standardmodus einbinden[^6]. In der erweiterten Version, die durch Verwendung des Datenbits D3 als sechstes Bit zur Adressierung dient, können sogar **62 Slaves** adressiert werden[^7]. Es ist zu beachten, dass die Zykluszeit mit der Anzahl der Slaves variiert. Sie beträgt 5 ms mit 31 Slaves und 10 ms mit 62 Slaves[^8].

[^5]: Das AS-Interface in aller Kürze: Was Sie unbedingt wissen sollten!. https://www.weka.de/elektrosicherheit/as-interface/.
[^6]: ASI Anzahl E/As grundlagen Problem - SPS-Forum. https://www.sps-forum.de/threads/asi-anzahl-e-as-grundlagen-problem.75133/.
[^7]: AS-Interface Introduction - Siemens. https://assets.new.siemens.com/siemens/assets/api/uuid:278af380-950c-4a80-82e7-15e55dc2c9ed/chapter-14a-as-interface.pdf.
[^8]: Das AS-Interface in aller Kürze: Was Sie unbedingt wissen sollten!. https://www.weka.de/elektrosicherheit/as-interface/.

#### 4. Quiz
### Kommunikationsprinzip

