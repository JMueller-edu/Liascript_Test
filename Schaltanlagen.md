
<!--
author:   

email:    

version:  0.0.1

language: Deutsch

narrator: Deutsch Female

comment:  LF10 Elektroniker für Betriebstechnik

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

-->

# Schaltanlagen

![Abb.: Schaltanlage](assets/Schaltanlage.png)  

![Abb.: Übersichtsplan Schaltanlage](assets/Schaltanlage_Uebersicht.png)

## Transformatoren [^1]

Die Drehstrom-Transformatoren wurden bereits im Lernfeld 5 behandelt. Die Schaltgruppen, deren Eigenschaften sowie der Schutz von Transformatoren wurden dort erläutert. Wir beschäftigen uns deshalb hier nur mit dem Transformator Tl unserer Anlage.

![Abb.: Übersichtsplan Schaltanlage](assets/Schaltanlage_Uebersicht.png) 
 
### Analyse wichtiger Bemessungsdaten

![Abb.: Leistungsschild des Transformators T1](assets/Leistungsschild_Transformator.png)  

- **Oberspannung: 11 kV `1`** Da der Transformator Tl für eine Bemessungsspannung von 10 kV benötigt wird, ist die Primärseite füreine Spannungserhöhung bis zu 10 % ausgelegt.
- **Unterspannung: 400 V `2`** Die Sekundärseite gibt die gewünschte Netzspannung ab.
- **Schaltgruppe: Dyn5 `3`** Die Wicklungen der Primärseite sind im Dreieck (D), die Sekundärseite ist im Stern (y) geschaltet, weil das anschließende Verbrauchernetz die verketteten Spannungen benötigt. Deshalb ist auch der Neutralleiter (n) herausgeführt. Die Kennzahl 5 gibt an, dass die Sekundärspannung der Primärspannung um 5 x 30° nacheilt.
- **Relative Kurzschlussspannung: 4 % `4`** Die Kurzschlussspannung lässt Rückschlüsse auf den Spannungsfall zu. Sie kann durch den mechanischen Aufbau von Kern und Spulen beeinflusst werden. Je enger die Primär- und Sekundärspulen beieinander liegen, desto kleiner ist die Kurzschlussspannung. Der Wert = 4 % ist für solche Transformatoren ein üblicher Wert.

Sollte die Leistung des Transformators Tl (250 kVA) für die Versorgung der Anlage nicht ausreichen, muss ein zweiter Transformator parallel geschaltet werden. Bei der Parallelschaltung von Spannungsquellen müssen alle Ausgangsspannungen zu jedem Zeitpunkt gleich sein. Ist dies nicht der Fall, fließen **Ausgleichsströme [circulation currents]**. Diese Ströme fließen auch, wenn keine Last angeschlossen ist. Man nennt sie auch Kreisströme. Abb. 4 zeigt ein vereinfachtes Ersatzschaltbild zweier Spannungsquellen. Die Differenzspannung $\Delta U$ verursacht einen Stromfluss nur innerhalb der Spannungsquellen. Die Spannungsquelle wird damit belastet, ohne Energie an die Verbraucher
abzugeben.

![Abb.: Parallelschaltung von Spannungsquellen](assets/Parallelschlatung_Spannungsquelle_klein.png)  

### Welche Anforderungen muss der parallel zu schaltende Transformator erfüllen?

Wie bei jeder Parallelschaltung von Spannungsquellen muss auch hier darauf geachtet werden, dass kein Ausgleichsstrom [circulating current] zwischen den Objekten fließen kann. Dies wird immer dann erreicht, wenn beide Transformatoren identisch sind. Das ist aber üblicherweise nicht der Fall. Um angenähert diesen Zustand zu erreichen, schreibt DIN VDE 0532 folgende Bedingungen vor:

- **Gleiche Bemessungsspannungen:** Ungleiche Sekundärspannungen führen zu Ausgleichsströmen (von der höheren Spannung zurniedrigeren Spannung).
- **Gleiche Kennzahlen:** Ungleiche Kennzahlen bedeuten ungleiche Phasenlagen. Auch das führt zu Ausgleichsströmen.
- **Möglichst gleiche Übersetzungsverhältnisse:** Damit wird erreicht, dass die Unterspannungen auch im Leerlauf gleich groß sind.
- **Nahezu gleiche Kurzschlussspannungen:** Ungleiche Kurzschlussspannungen führen zu ungleichmäßigen Belastungen der Transformatoren. Der Transformator mit der geringeren Kurzschlussspannung wird möglicherweise überlastet.
- **Verhältnis der Bemessungsleistungen < 3:1:** Bei größeren Leistungsverhältnissen würde der „kleinere" Transformator überlastet werden.

### Zusammenfassung Transformatoren

- Ausgleichsströme belasten Transformatoren, ohne dass eine Energieübertragung zur Last vorliegt.
- Gleiche Transformator-Kenngrößen vermeiden Ausgleichsströme.

### Quiz Transformatoren

**Ordnen Sie die im folgenden Typenschild gekennzeichneten Bemessungsdaten zu!**

![Abb.: Leistungsschild des Transformators T1](assets/Leistungsschild_Transformator.png)

<!-- 
    data-randomize 
    data-solution-button="off"
-->
- [[1] [2] [3] [4]]
- [(x) ( ) ( ) ( )]  Oberspannung
- [( ) (x) ( ) ( )]  Unterspannung
- [( ) ( ) (x) ( )]  Schaltgruppe
- [( ) ( ) ( ) (x)]  Relative Kurzschlusspannung

**Welche Anforderungen müssen parallel zu schaltende Transformator erfüllen?**

<!-- 
    data-randomize 
    data-solution-button="off"
-->
[[x]] Gleiche Bemessungsspannungen
[[x]] Geliche Kennzahlen
[[x]] Möglichest gleiche Übersetzungsverhältnisse
[[x]] Nahezu gleiche Kurzschlussspannungen
[[x]] Verhältnis der Bemessungsleistungen < 3:1

[^1] Die Inhalte dieses Kapitels beinhalten Ausszüge aus dem Buch Elektrotechnik Betiebstechnik Lernfelder 5-13; 3. Auflage; Westermann Bildungsmedien Verlag GmbH; Kapitel 10.2.4
## Messeinrichtung [^2]

Die folgende Abbildung zeigt einen Ausschnitt aus dem Übersichtsschaltplan der Mittelspannungsschaltanlage der Firma Metallbau KG. Für den Zähleranschluss sind die Wandler B1 und B2 vorbereitet. Bevor jetzt Zähler installiert werden, müssen die Aufgaben,Schaltungen und Schutzmaßnahmen der Wandler bekannt sein. Im Folgenden werden deshalb die notwendigen Erläuterungen gegeben.

![Abb.: Ausschnitt aus Übersichtsplan](assets/Uebersichtsplan_Ausschnitt.png)

### Wie werden Wandler eingesetzt?

Wandler sind Transformatoren, die entweder

- hohe Spannungen (Spannungswandler) oder
- hohe Stromstärken (Stromwandler)

auf niedrige Werte transformieren. Die daran anzuschließenden Zähleinrichtungen können dann kleinere Abmessungen und eine geringe Isolation besitzen.

**Spannungswandler [voltage transformer]** werden häufig in der V-SchaItung `1` betrieben, weil dabei nur zwei Objekte notwendig sind. Um die Wicklungen und den angeschlossenen Zähler gegen Überlastung zu schützen, muss die Sekundärseite `2` abgesichert werden.

![Abb.: Wandler-Schaltung in der Messzelle](assets/Wandler_Schaltung.png)  

**Stromwandler [current transformer]** dürfen auf keinen Fall im Leerlauf betrieben werden, weil offene Klemmen einen großen Widerstand darstellen. Durch das Transformieren wird der Primärkreis - und damit die Anlage - stark belastet ($R_1 = R_2 \cdot ü^2$). An den Offenen Klemmen ergibt sich wegen des großen Widerstandes ($R_2 \rightarrow \infty$) eine hohe Spannung, die für Personen und Anlagen gefährlich ist. Daraus folgt, dass Stromwandler nicht abgesichert werden dürfen. Im Leerlauf werden die Sekundärwicklungen kurzgeschlossen, damit ist der Widerstand nahezu Null.

Beide Wandlerarten müssen in Mittel- und Hochspannungsanlagen sekundärseitig an den Schutzleiter `3` und damit an die Erde angeschlossen werden.

### Wie werde die Zähler angschlossen?

Hierzu muss eine Bestandsaufnahme gemacht und festgelegt werden, welche Größen gemessen werden sollen. Wir gehen deshalb in folgenden drei Schritten vor:

1. Welche Objekte sind vorhanden?
2. Was soll gezählt werden?
3. Wie werden die Messgeräte angeschlossen?

#### Vorhandene Objekte

Aus dem Übersichtsschaltplan ist zu ersehen, dass zwei Wandler installiert sind. Ihre Anschlüsse sind auf die Klemmleiste X1 geführt.

![Abb.: Ausschnitt aus Übersichtsplan](assets/Uebersichtsplan_Ausschnitt.png)

#### Benötigte Zähler

In der beschriebenen Anlage sollen die Wirkarbeit und die Blindarbeit gemessen werden. Es werden deshalb zwei Zähler benötigt.

Der **Wirkarbeitszähler [watthour meter]** misst die gelieferte elektrische Energie. Der Zähler wird in der Aron-Schaltung verwendet, weil damit sowohl symmetrische als auch unsymmetrische Belastungen gemessen werden können.

Der **Blindarbeitszähler** ist notwendig, weil der Produktionsbetrieb der Firma Metallbau KG viele Motoren installiert hat und die Kompensationsanlage die Blindleistung nicht vollständig kompensiert.

#### Anschluss der Zähler

Beide Zähler werden an die Klemmleiste X1 angeschlossen.

![Abb.: Zähler-Anschlüsse](assets/Zaehler_Anschluesse.png)

![Abb.: Schaltungsnummern](assets/Schaltungsnummern.png)

Für die vorgestellte Mittelspannungsanlage nimmt ein Mitarbeiter des betreffenden VNB diese Anschlussarbeiten vor. Da sie als neue Schaltanlage zunächst spannungsfrei ist, kann die Installation einfach durchgeführt werden. Sollen in einer bestehenden Anlage Zähler ausgewechselt werden, sind weitere Schalthandlungen notwendig, die im Folgenden beschrieben werden.

Beim Zähleraustausch müssen folgende Schritte in der aufgeführten Reihenfolge eingehalten werden:

1. Stromwandler kurzschließen
2. Sicherungen aus den Spannungswandler-Leitungen entfernen.
3. Zähler entfernen
4. Neuen Zähler einbauen und anschließen
5. Sicherungen in Spannungswandler-Zuleitungen einsetzen
6. Kurzschluss-Brücken bei Stromwandlern entfernen.

### Zusammenfassung Messeinrichtungen

- In Mittel- und Hochspannungs-Schaltanlagen werden die Zähler über Wandler angeschlossen.
- Stromwandlerklemmen dürfen nicht offen sein. Entweder ist ein Gerät angeschlossen oder die Klemmen sind kurzgeschlossen.
- Stromwandler dürfen nicht abgesichert werden.
- Spannungswandler müssen abgesichert werden.
  
### Quiz Messeinrichtungen

**Ordnen Sie die Schritte beim Zählertausch chronologisch!**

<!-- 
  data-randomize 
  data-solution-button="off"
-->
- [[1.] [2.] [3.] [4.] [5.] [6.]]
- [(x) ( ) ( ) ( ) ( ) ( )]  Stromwandler kurschließen
- [( ) (x) ( ) ( ) ( ) ( )]  Sicherungen aus den Spannungswandler-Leitungen entfernen.
- [( ) ( ) (x) ( ) ( ) ( )]  Zähler entfernen
- [( ) ( ) ( ) (x) ( ) ( )]  Neuen Zähler einbauen und anschließen
- [( ) ( ) ( ) ( ) (x) ( )]  Sicherungen in Spannungswandler-Zuleitungen einsetzten
- [( ) ( ) ( ) ( ) ( ) (x)]  Kurzschluss-Brücken beim Stromwandler entfernen

[^2] Die Inhalte dieses Kapitels beinhalten Ausszüge aus dem Buch Elektrotechnik Betiebstechnik Lernfelder 5-13; 3. Auflage; Westermann Bildungsmedien Verlag GmbH; Kapitel 10.2.5
