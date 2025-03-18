## Schutzzielen

In der IT-Sicherheit gibt es eine Vielzahl von Schutzzielen, die darauf abzielen, Systeme, Netzwerke, Daten und Benutzer vor Bedrohungen zu schützen und die Integrität, Verfügbarkeit und Vertraulichkeit von Informationen sicherzustellen. Hier sind einige der wichtigsten Schutzziele in der IT-Sicherheit:

### Vertraulichkeit (Confidentiality)

**Ziel:** Sicherstellen, dass Informationen nur von autorisierten Personen eingesehen werden können.
**Methoden:** Verschlüsselung, Zugriffskontrollen, sichere Kommunikationsprotokolle.

### Integrität (Integrity)

**Ziel:** Schutz der Daten vor unerlaubten Änderungen, sowohl während der Übertragung als auch bei der Speicherung.
**Methoden:** Hashfunktionen, digitale Signaturen, Integritätsprüfungsprotokolle.

### Verfügbarkeit (Availability)

**Ziel:** Gewährleistung, dass IT-Systeme und Daten jederzeit zugänglich sind, wenn sie benötigt werden.
**Methoden:** Redundante Systeme, regelmäßige Wartung, DDoS-Schutzmaßnahmen.

### Authentizität (Authenticity)

**Ziel:** Sicherstellung der Echtheit von Daten, Transaktionen und Benutzern.
**Methoden:** Authentifizierungsprotokolle, digitale Zertifikate.

### Zurechenbarkeit (Accountability)

**Ziel:** Möglichkeit, Aktionen eindeutig einem Verantwortlichen zuzuordnen.
**Methoden:** Protokollierung, Audit-Trails, Monitoring.

### Nicht-Abstreitbarkeit (Non-repudiation)

**Ziel:** Verhindern, dass eine Partei die Durchführung einer Aktion leugnet.
**Methoden:** Digitale Signaturen, forensische Tools, sichere Protokollierung.

### Privatsphäre (Privacy)

**Ziel:** Schutz der Privatsphäre von Benutzern und Verhinderung unerwünschter Datenerhebung und -verarbeitung.
**Methoden:** Datenschutzrichtlinien, Anonymisierung, Datenschutz durch Technikgestaltung und durch datenschutzfreundliche Voreinstellungen (Privacy by Design and by Default).

### Zuverlässigkeit (Reliability)

**Ziel:** Sicherstellen, dass Systeme konsistent und korrekt funktionieren.
**Methoden:** Fehlerkorrekturverfahren, regelmäßige Überprüfungen, robustes Design.

Diese Schutzziele sind in verschiedenen Sicherheitsstandards und Best Practices integriert, wie zum Beispiel in ISO/IEC 27001, NIST und anderen nationalen und internationalen Richtlinien. Sie dienen als Grundlage für die Entwicklung von Sicherheitspolitiken und -maßnahmen und helfen Organisationen, ihre kritischen Assets effektiv zu schützen.

### Authentizität

Unter der Authentizität eines Objekts wird die Echtheit und Glaubwürdigkeit des Objekts erstanden, die anhand einer eindeutigen Identität und charakteristischen Eigenschaften überprüfbar sind.

**Zwei-Faktor-Authentifizierung (2FA)**: Dies erhöht die Sicherheit, indem es Benutzer erfordert, zwei verschiedene Authentifizierungsfaktoren zu verwenden, um den Zugang zu sichern. Typischerweise eine Kombination aus etwas, das sie wissen (Passwort), und etwas, das sie besitzen (Handy für SMS-Codes).
**Challenge-Response-Verfahren**: Dieses Protokoll stellt sicher, dass die kommunizierende Partei die ist, die sie vorgibt zu sein, indem sie auf eine Herausforderung (Challenge) mit einem gültigen Beweis (Response) antwortet, der oft kryptographisch generiert wird.

### Nicht-Abstreitbarkeit

**Digitale Signaturen**: Sie stellen sicher, dass eine beteiligte Partei die Durchführung einer Transaktion oder das Senden einer Nachricht nicht abstreiten kann, da die Signatur eindeutig mit ihrem privaten Schlüssel verknüpft ist.

### Integrität

**Checksummen und Hashes**: Durch die Berechnung von Prüfsummen und Hashwerten für Daten kann bei deren Empfang überprüft werden, ob sie während der Übertragung verändert wurden.

### Verfügbarkeit

**Redundante Systeme**: Durch den Einsatz von Redundanz in kritischen Systemkomponenten, wie Servern und Netzwerkverbindungen, kann die Verfügbarkeit erhöht werden, indem bei Ausfall einer Komponente sofort auf eine Reserve umgeschaltet wird.
**Load Balancing**: Verteilt den Datenverkehr gleichmäßig über mehrere Server, um Überlastung zu vermeiden und eine hohe Verfügbarkeit zu gewährleisten, besonders bei hohem Anfragevolumen.

### Vertraulichkeit

**Verschlüsselung**: Schützt Daten, indem sie in eine Form umgewandelt werden, die ohne den entsprechenden Schlüssel nicht lesbar ist. Wird sowohl für Daten in Ruhe als auch für Daten in Übertragung verwendet.
**Zugriffskontrollen**: Beschränken den Zugang zu Informationen auf autorisierte Benutzer durch Mechanismen wie Passwörter, biometrische Daten und Zugriffskontrolllisten (ACLs).
