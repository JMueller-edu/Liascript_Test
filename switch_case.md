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

import: https://raw.githubusercontent.com/LiaScript/CodeRunner/master/README.md

-->
# Verzweigung des Codeablaufs mit dem switch-case-Konstrukt in C\#

Die C#-Programmiersprache ist jeder von Menschen geschriebenen oder gesprochenen Sprache in dem Sinne ähnlich, dass Sie damit dasselbe auf verschiedene Art ausdrücken können. Einige Wörter und Ausdrücke sind beschreibender, genauer oder prägnanter als andere. Es gibt verschiedene Möglichkeiten, Verzweigungslogik zu Ihrer Anwendung hinzuzufügen, und je nach Kontext sind einige ausdrucksstärker und prägnanter als andere.

Angenommen, wir wollten unserer Anwendung ein Feature hinzufügen, das den Titel eines Mitarbeiters in der Firma neben seinem Namen anzeigt. Da sich die Titelnamen jedoch gelegentlich ändern, speichern wir nur die Ebene des Mitarbeiters, die ein numerisches Äquivalent zu seinem Titel ist.

Wenn wir ihren Titel anzeigen möchten, müssen wir die numerische Ebene auswerten und den Titel zurückgeben.

Es gibt mehrere Ebenen und passende Titel. Gelegentlich fügt das Unternehmen neue Ebenen und Titel hinzu. Wenn dies vor der Aktualisierung unserer Anwendung auftritt, müssen wir einen generischen Titel „Mitarbeiter“ verwenden, bis wir unsere Software aktualisieren können.

In diesem Szenario könnten wir ganz einfach ein `if-elseif-else`-Verzweigungskonstrukt verwenden. Wenn es jedoch viele mögliche Ebenen und Titel gibt, ist die `switch`-Anweisung möglicherweise einfacher zu lesen, zu verstehen und zu ändern.

In diesem Modul verwenden Sie das `switch-case`-Konstrukt, um eine Verzweigungslogik hinzuzufügen, in der Sie eine Variable oder einen Ausdruck mit vielen möglichen Werten vergleichen müssen.

Am Ende dieses Moduls können Sie einfache Anwendungen erstellen, die Benutzereingaben akzeptieren, diese mit literalem Text kombinieren und das Ergebnis an den Benutzer ausgeben.

## Übung - Verwenden der switch-case-Anweisung

In der Einleitung haben wir ein Szenario beschrieben, bei dem wir eine Zahl, die die Ebene des Mitarbeiters repräsentiert, mit dem Titel vergleichen mussten. 

In dieser Übung verwenden wir ein `switch-case`-Konstrukt, das diese Verzweigungslogik implementiert.

### Was ist die switch-Anweisung?

 `switch` ist eine Auswahlanweisung, die einen einzelnen switch-Abschnitt aus einer Liste von Kandidaten auswählt, die auf einem Mustervergleich mit dem Vergleichsausdruck basieren. Eine switch-Anweisung umfasst einen oder mehrere switch-Abschnitte. Jeder switch-Abschnitt enthält mindestens eine case-Bezeichnung (entweder eine case- oder eine Standardbezeichnung), gefolgt von mindestens einer Anweisung. Die switch-Anweisung kann höchstens eine Standardbezeichnung enthalten, die in einen beliebigen switch-Abschnitt eingefügt wird.

Die switch-Anweisung wird am besten in folgenden Situationen verwendet:

- Wenn Sie über einen einzelnen Wert verfügen, den Sie mit vielen möglichen Werten vergleichen möchten, aber:
- Sie müssen für jede gegebene Übereinstimmung höchstens ein paar Codezeilen ausführen.

Es ist möglich, dass mehrere Fälle gelten. C# wählt jedoch den ersten übereinstimmenden Ausdruck aus.

#### Schritt 1: Verstehen der switch-Anweisung

Führen Sie folgenden Code aus, indem sie auf den `</>` Button unter dem Codeblock klicken

```csharp
int employeeLevel = 200;
string employeeName = "John Smith";

string title = "";

switch (employeeLevel)
{
    case 100:
        title = "Junior Associate";
        break;
    case 200:
        title = "Senior Associate";
        break;
    case 300:
        title = "Manager";
        break;
    case 400:
        title = "Senior Manager";
        break;
    default:
        title = "Associate";
        break;
}

Console.WriteLine($"{employeeName}, {title}");
```
@LIA.dotnet

Das `switch`-Schlüsselwort definiert den Zweck des folgenden Codeblocks. Neben dem Schlüsselwort steht der Vergleichsausdruck in Klammern `(employeeLevel)`.

Im Codeblock befinden sich ein oder mehrere `switch`-Abschnitte. Jeder `switch` -Abschnitt enthält mindestens eine Bezeichnung. Eine Bezeichnung beginnt mit dem Schlüsselwort `case` und einem Muster für den Abgleich. Die Runtime vergleicht den Wert des Vergleichsausdrucks mit jedem passenden Muster, bis sie eine Übereinstimmung findet.

Sobald die Runtime eine passende Bezeichnung findet, führt sie den Code in diesem bestimmten switch-Abschnitt aus.

Es kann nur ein `switch`-Abschnitt ausgeführt werden. Das `break`-Schlüsselwort ist eine von mehreren Möglichkeiten, um einen switch-Abschnitt zu beenden und der switch-Anweisung buchstäblich zu entkommen. Wenn Sie das `break`-Schlüsselwort (oder optional das Schlüsselwort `return`) vergessen, generiert der Compiler einen Fehler.

Wenn keine übereinstimmenden Bezeichnungen vorhanden sind, wird die optionale Bezeichnung `default` verglichen. Wenn `default` nicht definiert ist, wird die `switch`-Anweisung nur dann ausgeführt, wenn einer der Fälle zutrifft.

Die optionale Bezeichnung `default` muss nach den restlichen Fällen nicht definiert werden. Die meisten Entwickler entscheiden sich jedoch dazu, sie an letzte Stelle zu setzen, da sie logisch als „Standard“ oder „letzte Option“ Sinn machen.

#### Schritt 2: Ändern des Werts der Ebenenvariablen, um ihre Auswertung durch die switch-Anweisung zu prüfen

Um den Standardfall zu üben, ändern wir die Ebene des Mitarbeiters, indem wir die folgende Zeile des Codes ändern:

```csharp
int employeeLevel = 201;
```

Somit lautet der neue Code:

```csharp
int employeeLevel = 201;
string employeeName = "John Smith";

string title = "";

switch (employeeLevel)
{
    case 100:
        title = "Junior Associate";
        break;
    case 200:
        title = "Senior Associate";
        break;
    case 300:
        title = "Manager";
        break;
    case 400:
        title = "Senior Manager";
        break;
    default:
        title = "Associate";
        break;
}

Console.WriteLine($"{employeeName}, {title}");
```
**Welche Ausgabe erzeugt der Code jetzt?**

- [[ ]] John Smith Junior Associate
- [[ ]] John Smith Senior Associate
- [[ ]] John Smith Manager
- [[ ]] John Smith Senior Manager
- [[x]] John Smith Associate
   
#### Schritt 3: Ändern der Anwendung zum Verwenden einer Methode zum Fortfahren

Unser Unternehmen hat sich dazu entschieden, allen Mitarbeitern der Ebene 100 den Titel „Leitender Mitarbeiter“ zu verleihen, denselben Titel wie den Mitarbeitern der Ebene 200. 

Als Entwickler entscheiden Sie sich dafür, dies durch Entfernen des ersten zur Bezeichnung `case 100:` gehörenden switch-Abschnitts zu implementieren und stattdessen zuzulassen, dass sowohl die Bezeichnungen `case 100:` als auch `case 200:` denselben switch-Abschnitt ausführen.

Zunächst ändern wird den Code, um `employeeLevel` auf `100` festzulegen:

```csharp
int employeeLevel = 100;
```

Als nächstes ändern wir den Code in:

```csharp
    case 100:
    case 200:
        title = "Senior Associate";
        break;
```

Entsprechend sieht der geänderte Code folgendermaßen aus:

```csharp
int employeeLevel = 100;
string employeeName = "John Smith";

string title = "";

switch (employeeLevel)
{
    case 100:
    case 200:
        title = "Senior Associate";
        break;
    case 300:
        title = "Manager";
        break;
    case 400:
        title = "Senior Manager";
        break;
    default:
        title = "Associate";
        break;
}

Console.WriteLine($"{employeeName}, {title}");
```
**Welche Ausgabe liefert der Code nun?**

<!-- 
    data-randomize 
    data-solution-button="off"
-->
- [[ ]] John Smith Junior Associate
- [[x]] John Smith Senior Associate
- [[ ]] John Smith Manager
- [[ ]] John Smith Senior Manager
- [[ ]] John Smith Associate
***
Beide case-Bezeichnungen (100 und 200) werden jetzt mit dem switch-Abschnitt gekoppelt, der den Titel auf den Zeichenfolgenwert Senior Associate festlegt.

***

## Zusammenfassung

Hier sind die wichtigsten Erkenntnisse, die Sie zur switch-Anweisung gelernt haben:

- Verwenden Sie die switch-Anweisung, wenn ein Wert mit vielen möglichen Übereinstimmungen vorliegt, wobei jede Übereinstimmung einen Zweig in Ihrer Codelogik erfordert.
- Ein einzelner switch-Abschnitt, der Codelogik enthält, kann mit einer oder mehreren Bezeichnungen verglichen werden, die durch das Schlüsselwort case definiert sind.
- Verwenden Sie das optionale Schlüsselwort default, um eine Bezeichnung und einen switch-Abschnitt zu erstellen, die verwendet werden, wenn keine anderen case-Bezeichnungen übereinstimmen.

## Herausforderung

Angenommen, Sie arbeiten für einen Souvenirladen in einer Universitätsstadt, der T-Shirts, Sweatshirts und andere Geschenkartikel mit dem Logo und den Farben der Universität verkauft. 

Ein monatlicher Umsatzbericht verwendet die vollständige Beschreibung sowie die Stock Keeping Unit (SKU) der verkauften Produkte. Sie wurden gebeten, bestimmte Teile des Codes neu zu schreiben, um dessen Lesbarkeit zu verbessern. 

Eine der Aufgaben besteht darin, die Konvertierung einer SKU in eine Beschreibung mithilfe der switch-Anweisung zu vereinfachen.

### SKU-Code

Der folgende Code konvertiert eine SKU in eine ausführliche Beschreibung (z. B. steht die SKU 01-MN-L für „large maroon sweat shirt“ (kastanienbraunes Sweatshirt in Größe L).

```csharp
// SKU = Stock Keeping Unit
string sku = "01-MN-L";

string[] product = sku.Split('-');

string type = "";
string color = "";
string size = "";

if (product[0] == "01")
{
    type = "Sweat shirt";
} else if (product[0] == "02")
{
    type = "T-Shirt";
} else if (product[0] == "03")
{
    type = "Sweat pants";
}
else
{
    type = "Other";
}

if (product[1] == "BL")
{
    color = "Black";
} else if (product[1] == "MN")
{
    color = "Maroon";
} else
{
    color = "White";
}

if (product[2] == "S")
{
    size = "Small";
} else if (product[2] == "M")
{
    size = "Medium";
} else if (product[2] == "L")
{
    size = "Large";
} else
{
    size = "One Size Fits All";
}

Console.WriteLine($"Product: {size} {color} {type}");
```

**Ändern Sie den Code, um eine switch-Anweisung zu verwenden.**

**Das Ergebnis sollte dasselbe sein.**

```csharp
// Hier können Sie ihren Code entwickeln.
// Für Debug Funktionalität verwenden Sie bitte eine Entwicklungsumgebung.

```
@LIA.dotnet
## Quiz

**Welche der folgenden Aussagen über das `switch-case`-Konstrukt trifft zu?**

<!-- 
    data-randomize 
    data-solution-button="off"
-->
- [[x]] Ein einzelner switch-Abschnitt kann mehrere case-Bezeichnungen aufweisen.
- [[ ]] Ein switch-Konstrukt muss einen Standard-switch-Abschnitt enthalten.
- [[ ]] Zwei case-Bezeichnungen können das gleiche Abgleichsmuster aufweisen.
- [[ ]] Der Doppelpunkt am Ende der case-Bezeichnung ist optional.

**Welchen Zweck hat das Schlüsselwort `new`?**

<!-- 
    data-randomize 
    data-solution-button="off"
-->
- [[ ]] Das Schlüsselwort break weist die Runtime an, mit der Auswertung anderer case-Abschnitte im switch-Konstrukt fortzufahren.
- [[x]] Das Schlüsselwort break weist die Runtime an, die Auswertung anderer case-Abschnitte im switch-Konstrukt zu beenden.
- [[ ]] Das Schlüsselwort break weist die Runtime an, die Anwendung zu beenden.
- [[ ]] Das Schlüsselwort break weist die Runtime an, die Methode zu beenden.
