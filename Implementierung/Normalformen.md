## Normalformen

Normalisierung ist notwendig damit Anomalien und Redundanzen in Datenbanken vermieden werden.

**Redundanz:**
Wiederholung von Daten in einer Datenbank, die zu Inkonsistenzen und Inkonsistenzen führen kann.

**Anomalien:**
Probleme, die bei der Einfügung, Aktualisierung oder Löschung von Daten auftreten können.

**Normalformen:**

- **Erste Normalform (1NF):**
  Eine Tabelle ist in der ersten Normalform, wenn alle Attribute atomar sind, das heißt, sie keine wiederholten oder mehrwertigen Attribute enthalten.

- **Zweite Normalform (2NF):**
   Eine Tabelle ist in der zweiten Normalform, wenn sie in der ersten Normalform ist und alle Nicht-Schlüsselattribute voll funktional abhängig vom Primärschlüssel sind.

- **Dritte Normalform (3NF):**
   Eine Tabelle ist in der dritten Normalform, wenn sie in der zweiten Normalform ist und keine transitiven Abhängigkeiten zwischen den Attributen bestehen.

### Anomalien in Datenbanken

- **Einfügeanomalie:** Eine Einfügeanomalie tritt auf, wenn ein neuer Datensatz nicht eingefügt werden kann, weil ein Attribut, das nicht NULL sein darf, nicht bekannt ist.

- **Löschungsanomalie:** Eine Löschungsanomalie tritt auf, wenn das Löschen eines Datensatzes dazu führt, dass auch andere

- **Änderungsanomalie:** Eine Änderungsanomalie tritt auf, wenn eine Änderung an einem Attribut dazu führt, dass mehrere Datensätze geändert werden müssen.

## Vorteile der Normalisierung

- **Redundanzreduzierung:** Die Normalisierung reduziert Redundanzen in der Datenbank, was die Speicherplatznutzung optimiert und die Konsistenz der Daten verbessert.

- **Datenkonsistenz:** Durch die Normalisierung wird die Datenkonsistenz verbessert, da die Daten in einer strukturierten Form gespeichert werden.

- **Verbesserte Datenintegrität:** Die Normalisierung verbessert die Datenintegrität, da die Daten in einer konsistenten und strukturierten Form gespeichert werden.

- **Effiziente Datenverwaltung:** Die Normalisierung erleichtert die Verwaltung von Daten, da sie in einer strukturierten Form gespeichert werden und Anomalien vermieden werden.

- **Bessere Performance:** Normalisierte Datenbanken können in der Regel effizienter abgefragt werden, da sie in einer strukturierten Form gespeichert sind.

### Schritte zur Normalisierung

#### Nullte Normalform (0NF)

- alle Daten unnormiert in einer Tabelle

#### Erste Normalform (1NF)

- Alle Attribute sind atomar (Attribut ist eine Spalte, Atomar -> nicht weiter zerlegbar)
  - Jede Spalte enthält nur einen Wert (zb. Name -> Vorname, Nachname)


#### Zweite Normalform (2NF)

- jedes Nicht-Schlüsselattribut ist voll funktional abhängig vom Primärschlüssel

- Primärschlüssel: eindeutige Identifikation eines Datensatzes(unterstrichen in der Tabelle)

#### Dritte Normalform (3NF)

- keine transitiven Abhängigkeiten zwischen den Attributen

- Transitiv: Transitivität ist eine Eigenschaft von Beziehungen zwischen Attributen in einer Datenbanktabelle. Eine transitive Abhängigkeit liegt vor, wenn ein Attribut A von einem Attribut B abhängt, das wiederum von einem Attribut C abhängt.
- zb Postleitzahl -> Ort. Ort ist transitiv abhängig von Postleitzahl

### Zusammenfassung

**1 Normalform (1NF)** Jedes Datenfeld hat nur einen Eintrag

**2 Normalform (2NF)** Alle Datenfelder sind vom Primärschlüssel "funktional" abhängig

**3 Normalform (3NF)** alle Datenfelder außer Schlüssel dürfen nicht "funktional" abhängig sein