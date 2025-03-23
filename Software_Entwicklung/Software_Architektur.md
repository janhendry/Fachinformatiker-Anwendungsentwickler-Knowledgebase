## Software Architektur

### Funktionale Anforderungen

- **Spezifikation von Funktionen:** Beschreiben spezifische Verhaltensweisen oder Funktionen des Systems.
- **Nutzerinteraktionen:** Definieren, wie Benutzer mit dem System interagieren und welche Aktionen durchgeführt werden können.
- **Datenmanagement:** Beinhalten das Erfassen, Speichern und Verarbeiten von Daten.
- **Geschäftsregeln:** Enthalten Geschäftslogik und -regeln, die das System implementieren muss.
- **Authentifizierung und Autorisierung:** Spezifizieren Anforderungen für Sicherheitsmechanismen, um sicherzustellen, dass nur berechtigte Nutzer Zugang zu Funktionen und Daten haben.
- **Transaktionsverhalten:** Beschreiben, wie Transaktionen verarbeitet werden sollen, einschließlich Fehlerbehandlung und Rückgängigmachung von Aktionen.

### Nicht-funktionale Anforderungen

- **Leistung:** Beschreiben die erwartete Antwortzeit des Systems, Durchsatzanforderungen und andere Leistungsmerkmale.
- **Zuverlässigkeit:** Definieren die geforderte Fehlertoleranz, Verfügbarkeit und Wiederherstellbarkeit des Systems.
- **Benutzbarkeit:** Spezifizieren Anforderungen an die Benutzeroberfläche und die Benutzererfahrung, um die einfache Bedienbarkeit zu gewährleisten.
- **Effizienz:** Betreffen die optimale Nutzung von Systemressourcen wie CPU, Speicher und Netzwerk.
- **Skalierbarkeit:** Beschreiben die Fähigkeit des Systems, seine Leistung unter wachsender Last zu steigern oder effektiv zu verwalten.
- **Sicherheit:** Enthalten Vorgaben bezüglich Datenschutz, Datenintegrität und -sicherheit.
- **Portabilität:** Definieren die Anforderungen für die Software, auf verschiedenen Plattformen und Umgebungen zu funktionieren.
- **Wartbarkeit:** Beschreiben die Erwartungen an die Leichtigkeit, mit der das System modifiziert, korrigiert, gewartet oder erweitert werden kann.

### Quantitative Merkmale

Quantitative Merkmale in der Software sind messbare Eigenschaften, die in Zahlen ausgedrückt werden können. Sie dienen dazu, objektive Kriterien für die Bewertung der Softwareleistung und -funktionalität festzulegen.

**Beispiele:**

1. **Leistungsmetriken:**
   - Antwortzeiten
   - Durchsatz (z.B. Anzahl der Transaktionen pro Sekunde)
   - Ressourcennutzung (CPU, Speicher, Netzwerk)

2. **Benutzerstatistiken:**
   - Anzahl aktiver Benutzer
   - Tägliche oder monatliche aktive Benutzer
   - Wachstumsraten der Benutzerbasis

3. **Fehlermetriken:**
   - Anzahl der Bugs und Fehler im System
   - Fehlerhäufigkeit
   - Zeit bis zur Fehlerbehebung (Mean Time to Repair, MTTR)

4. **Testabdeckung:**
   - Prozentualer Anteil des Codes, der durch automatisierte Tests abgedeckt ist
   - Anzahl der durchgeführten Testfälle

5. **Code-Metriken:**
   - Code-Komplexität
   - Anzahl der Codezeilen
   - Wiederverwendung von Code

### Qualitative Merkmale

Qualitative Merkmale in der Software betreffen Aspekte, die sich mehr auf die Qualität der Erfahrung, die Benutzerfreundlichkeit und das Design beziehen. Sie sind subjektiver Natur und oft durch Beobachtungen, Nutzerfeedback und Expertenmeinungen bewertet.

**Beispiele:**
1. **Benutzerfreundlichkeit:**
   - Intuitivität der Benutzeroberfläche
   - Zugänglichkeit für Menschen mit Behinderungen
   - Klarheit der Benutzerführung und -dokumentation

2. **Ästhetik:**
   - Designqualität
   - Visuelle Attraktivität der Benutzeroberfläche
   - Konsistenz des visuellen Designs

3. **Sicherheitsempfinden:**
   - Vertrauen der Benutzer in die Sicherheitsmaßnahmen der Software
   - Wahrgenommene Datenschutzpraktiken

4. **Zufriedenheit und Akzeptanz:**
   - Benutzerzufriedenheit mit den Funktionen und der Leistung der Software
   - Akzeptanz der Software bei den Endbenutzern

5. **Skalierbarkeit und Wartbarkeit:**
   - Einfachheit der Skalierung der Software für wachsende Benutzerzahlen
   - Wartbarkeit und Erweiterbarkeit des Codes aus der Sicht von Entwicklern

Diese Merkmale spielen eine entscheidende Rolle in der Softwareentwicklung und -evaluation. Quantitative Merkmale bieten dabei klare, messbare Ziele, während qualitative Merkmale wichtig sind, um die nicht messbaren Aspekte der Benutzererfahrung und -zufriedenheit zu erfassen und zu verbessern. Beide Typen von Merkmalen ergänzen sich und sollten gemeinsam betrachtet werden, um ein umfassendes Bild der Softwarequalität zu erhalten.

Die Verschlüsselungsverfahren lassen sich in zwei Hauptkategorien unterteilen: symmetrische (synchron) und asymmetrische (asynchron) Verschlüsselung. Beide haben spezifische Anwendungsbereiche und Sicherheitseigenschaften. Hier ist ein Überblick über beide Arten von Verschlüsselungsverfahren:
