<!--

author:  
email:   
version:  0.0.1
language: de
narrator: Deutsch Female

import:   
-->
# Machine-to-Machine-Kommunikation mit dem Standard OPC UA

Nicht angeschlossene Maschinen und Anlagen sollen in ein IP-basiertes Netzwerk mittels IoT-Technologien eingebunden werden.
Dabei steht die Standardisierung der Machine-to-machine-Kommunikation im Mittelpunkt. Dieses Ziel zu erreichen, bemühen sich Firmen und Konsortien auf der ganzen Welt, z. B. die OPC Foundation mit OPC UA.

## Machine-to-Machine (M2M)

Der automatisierte Informationsaustausch zwischen Maschinen, Anlagen, Automaten, Fahrzeugen und Containern wird als M2M bezeichnet. Das bedeutet, dass einzelne Maschinensteuerungen untereinander und mit einer zentralen Leitstelle kommunizieren können. Bestehende Maschinen und Anlagen können mit cyber-physischen Systemen nachgerüstet werden, um diesen M2M-lnformationsaustausch zu ermöglichen.

Eine von vielen zentralen Herausforderungen der Industrie 4., sowie dem industriellen Internet der Dinge (IoT) ist ein sicherer, standardisierter Daten- und Informationsaustausch zwischen Maschinen, Anlagen, cyber-physischen Systemen und auch Diensten verschiedener Branchen. Grundvoraussetzung für den Einsatz des Industriestandards OPC UA zur Kommunikation im IoT ist ein auf dem Internetprotokoll (IP) basierendes Netzwerk. Nur wenn die Vernetzung der zentralen Komponenten auf einem einheitlichen und globalen Kommunikationsstandard beruht, der die komplexer werdenden Anforderungen erfüllen kann, lässt sich die IoT-Vision erfüllen. Des Weiteren ist neben einem Publish/Subscriber-Modell wie MQTT ein sicheres und verbindungsorientiertes Client/Server-Kommunikationsmodell notwendig, um eine bidirektionale Kommunikation mit steuernden Eingriffen auf Aktoren zu ermöglichen. Zusätzliche Voraussetzungen sind zum einen die Skalierbarkeit und Integrationsfähigkeit über allen Ebenen sowie die Hersteller- und Plattformunabhängigkeit.

### OPC UA

OPC UA (Open Platform Communications Unified Architecture) ist ein Industriestandard für die Kommunikation zwischen Maschinen untereinander bzw. zwischen Maschinen und Computersystemen. Es handelt sich dabei um einen offenen Schnittstellenstandard. Der Standard ist herstellerunabhängig und kann mit zahlreichen Entwicklungsumgebungen programmiert werden.

![picture 1](assets/Logo_OPCUA.png)  


Die folgeden Anforderungen der Industrie 4.0 werden mit dem Standard OPC UA erfüllt:

- **Unabhängigkeit der Kommunikationstechnologie:** Die OPC Foundation ist eine herstellerunabhängige Non-Profit-Organisation. Weder für den Einsatz noch die Erstellung von OPC-UA-Produkten und -Technologien benötigt man eine Mitgliedschaft. OPC hat die größte Verbreitung im Bereich der Automatisierung, ist aber technologisch branchenneutral. OPC UA ist sowohl auf allen Betriebssystemen als auch auf Chip-Ebene ohne Betriebssystem lauffähig. OPC UA ist in vielen Programmiersprachen umsetzbar.
- **Skalierbarkeit:** Skalierbarkeit zur durchgängigen Vernetzung vom kleinsten Sensor über eingebettete (embedded)Geräte und SPS-Steuerungen bis PC und Smartphone sowie Großrechner und Cloudanwendungen; horizontale und vertikale Kommunikation über alle Ebenen
- **Sicherheit:** Sicherheit der Übertragung sowie Authentifizierung auf Anwender- und Anwendungsebene
- Serviceorientierte Architektur (SOA): SOA-Transport über etablierte Standards wie TCP/IP für den Austausch von Echtzeitdaten, historischen Daten, Kommandos und Ereignissen
- **Prüfbarkeit der Konformität zum definierten Standard:** OPC UA bereits IEC-Standard (IEC 62541)

#### Architektur

Das Grundprinzip der OPC UA-Architektur besteht aus vier zentralen Komponenten: der Bereitstellung einfacher Schnittstellen, eines einheitlichen Nachrichtenformats,flexibler Erweiterungsmöglichkeiten und der Implementierung hoher Sicherheitsstandards. Damit bietet die OPC UA eine anpassungsfähige Architektur, die sich schnell an die fortlaufend weiterentwickelte Industrieautomation anpassen kann. Egal ob Sensor oder Cloud, OPC UA kann auf jedem beliebigen Betriebssystem genutzt werden. Durch den herstellerunabhängigen Austausch an Informationen ist OPC UA zu einem wesentlichen Baustein für die Entwicklung der Industrie 4.0 geworden.

##### Topologie

OPC UA verwendet ein TCP-basiertes Protokoll, dem der Port 4840 zugewiesen wird. Da der binäre Datenaustausch von der OPC-UA-Spezifikation vorgeschrieben wird, kann er von jeder OPC-UA-Anwendung unterstützt werden. Darüber hinaus wird das Webservice-Protokoll verwendet, welches das Transportprotokoll HTTP oder HTTPS unterstützt. Auch in diesem Fall werden gegebenenfalls vorgeschriebene Ports zugewiesen (Port 80 und Port 443).

##### Client-Server-Prinzip

OPC UA geht nach dem Client-Server-Prinzip vor. Das bedeutet, dass der OPC-UA-Server sowohl Daten als auch Informationen bereitstellt, auf die OPC-UA-Clients zugreifen können. Ein Gerät kann Server und Client gleichzeitig sein.
##### Konfiguration

OPC UA nutzt IP-Adresse oder Gerätenamen zur genauen Adressierung. Der Local-Discovery-Server kann von dem Netzwerk verwendet werden, um nach verfügbaren OPC-UA-Servern zu suchen. Dabei ist die Verbindungssicherung ein zentrales Element bei der Verbindungskonfiguration. Je nachdem, welche Sicherheitsstufe angefordert wird, kann zusätzlich eine authentifizierte, signierte und verschlüsselte Verbindung aufgebaut werden. Die Konfiguration des OPC-Clients erfolgt weitestgehend automatisch.

##### Sicherheit

OPC UA nutzt in Bezug auf Cybersicherheit die neuesten Technologien, was für Datenübertragungen über das Internet von großem Vorteil ist. Das Sicherheitskonzept umfasst folgende Punkte:

- Sicherstellung der Informationssicherheit hinsichtlich Vertraulichkeit, Integrität und Verfügbarkeit
- Zugriffskontrolle mit Authentifizierung, Autorisierung und Auditierbarkeit
- Verschlüsselte und signierte Nachrichtenübertragung

Die meisten SPS-, MES- und Visualisierungshersteller unterstützen diesen Standard. Außerdem ermöglicht UE eine umfangreiche Skalierung von IoT-Anwendungen, welche von den kleinsten Geräten bis hin zu großen IT-Ebenen reicht.

## Quiz

Weisen Sie den folgenden Beschreibungen jeweils die richtige Abkürzung zu!

**Die Kommunikation zwischen unterschiedlichen Maschinen.**
[[ (M2M) | IoT | OPC UA ]]

**Abkürzung für das Internet der Dinge im industriellen Umfeld**
[[ M2M | (IoT) | OPC UA ]]

**Weltweit etablierter Datenaustauschstandard zur herstellrunabhängigen Kommunikation zwischen Maschinen**
[[ M2M | IoT | (OPC UA) ]]

**Welche Anforerungen der Indurstie 4.0 werden mit dem Standard OPC UA erfüllt?**

- [[x]] Unabhängigkeit der Kommunikationstechnologie
- [[x]] Skalierbarkeit
- [[x]] Sicherheit
- [[x]] Prüfbarkeit der Konformität zum definierten Standard

## Verständnisfragen

1. Beschreiben Sie mit eigenen Worten die Machine-to-Machine-Kommunikation und finden Sie Beispiele von Informationen, die Maschinen untereinander teilen können.
2. Erläutern Sie wesentliche Unterschiede zwischen MQTT und OPC UA.