## Paradigmen

### Objektorientierten Programmierung

Die Paradigmen der objektorientierten Programmierung (OOP) sind grundlegende Prinzipien oder Konzepte, die die Struktur und das Verhalten von Software in der objektorientierten Entwicklung definieren. Hier sind die vier Hauptparadigmen der OOP:

1. **Kapselung**: Dies bezieht sich auf die Bündelung von Daten (Attribute) und Methoden, die auf diese Daten operieren, innerhalb einer Einheit oder eines Objekts. Kapselung hilft dabei, die Komplexität zu reduzieren und die Wiederverwendbarkeit zu erhöhen, indem der interne Zustand eines Objekts vor direktem externem Zugriff geschützt wird.

2. **Abstraktion**: Abstraktion bedeutet, komplexe Realität zu vereinfachen, indem nur die relevanten Daten und Aktionen modelliert werden, während die weniger relevanten Details ausgeblendet werden. Dies ermöglicht es dem Programmierer, sich auf Interaktionen auf höherer Ebene zu konzentrieren, ohne sich um die interne Implementierungsdetails kümmern zu müssen.

3. **Vererbung**: Vererbung ist ein Mechanismus, bei dem eine neue Klasse (abgeleitete Klasse) die Eigenschaften einer bestehenden Klasse (Basis- oder Elternklasse) erbt. Dies unterstützt die Wiederverwendung von Code und kann die Hierarchie von Klassen darstellen, die gemeinsame Attribute und Methoden teilen.

4. **Polymorphismus**: Polymorphismus ist die Fähigkeit von Objekten, sich je nach Kontext unterschiedlich zu verhalten, während sie durch die gleiche Schnittstelle angesprochen werden. Dies kann durch Methodenüberladung (gleicher Methodenname, unterschiedliche Parameter) oder Methodenüberschreibung (gleicher Methodenname, unterschiedliche Implementierungen in abgeleiteten Klassen) erreicht werden.

Diese Prinzipien helfen dabei, Software zu entwickeln, die modular, wiederverwendbar und leicht zu pflegen ist.

### Generisch 

Sie ermöglichen es Programmierern, Klassen, Schnittstellen und Methoden zu schreiben, deren Typen parametrisiert sind, so dass sie mit verschiedenen Datentypen arbeiten können, ohne dass der Code dupliziert werden muss. Dies fördert die Wiederverwendbarkeit und Flexibilität von Code und ermöglicht es, allgemeine Algorithmen und Datenstrukturen zu schreiben, die mit unterschiedlichen Datentypen verwendet werden können.

### Abstrakte Klassen und Methoden

Konzepte, die dazu dienen, eine Basisklasse zu definieren, welche nicht vollständig implementiert ist und daher nicht direkt instanziiert werden kann.

### Interfaces

Sie definieren eine Schnittstelle, der von Klassen implementiert werden muss. Dies ermöglicht es, eine gemeinsame Schnittstelle für verschiedene Klassen bereitzustellen, die unterschiedliche Implementierungen haben können, aber die gleichen Methoden bereitstellen.

### Lambda-Ausdrücke

Sie ermöglichen es, Funktionen als Argumente an andere Funktionen zu übergeben oder als Ergebnisse zurückzugeben. Dies erleichtert die Implementierung von Funktionalitäten wie Filtern, Mappen und Reduzieren von Datenstrukturen.



# Funktionale Programmierung
Die funktionale Programmierung basiert auf einer Reihe von Paradigmen, die sich stark von denen der objektorientierten Programmierung unterscheiden. Hier sind die Hauptparadigmen der funktionalen Programmierung:

1. **Unveränderlichkeit (Immutability)**: In der funktionalen Programmierung werden Daten als unveränderlich betrachtet. Das bedeutet, dass einmal erstellte Datenobjekte nicht mehr geändert werden können. Stattdessen werden Änderungen durch Erzeugung neuer Datenobjekte aus bestehenden Daten durchgeführt, wodurch viele Probleme der Nebenläufigkeit vermieden werden können.

2. **Funktionen als First-Class Citizens**: Funktionen werden als erstklassige Bürger behandelt, was bedeutet, dass sie wie jede andere Variable verwendet werden können. Sie können als Argumente an andere Funktionen übergeben, von Funktionen zurückgegeben und Variablen zugewiesen werden.

3. **Reine Funktionen (Pure Functions)**: Reine Funktionen sind solche, die bei gleichen Eingabewerten immer dieselben Ausgabewerte liefern und keine Seiteneffekte haben (d.h., sie verändern keine Zustände außerhalb ihrer Scope oder interagieren mit der Außenwelt). Dies macht Programme vorhersehbarer und einfacher zu testen.

4. **Funktionale Komposition**: Funktionen können miteinander kombiniert werden, um komplexere Operationen durchzuführen. Die Ausgabe einer Funktion kann direkt als Eingabe einer anderen verwendet werden, wodurch eine Kette von Funktionsaufrufen entsteht (Komposition).

5. **Höhere Funktionen (Higher-Order Functions)**: Dies sind Funktionen, die andere Funktionen als Parameter nehmen oder als Ergebnis zurückgeben können. Diese ermöglichen flexible Manipulationen von Funktionen und Daten und sind zentral für viele funktionale Techniken wie Filtern, Reduzieren und Mappen von Datenstrukturen.

6. **Rekursion**: In der funktionalen Programmierung wird oft die Rekursion anstelle von Schleifen verwendet, um wiederholte oder iterative Prozesse durchzuführen. Da funktionale Sprachen oft optimierungen wie die Endrekursion unterstützen, kann Rekursion effizient gehandhabt werden.

Diese Paradigmen unterstützen die Entwicklung von Code, der einfacher zu verstehen, zu testen und zu warten ist, besonders in komplexen Systemen mit vielen Daten und Operationen.