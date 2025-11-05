# ISO 27001:2022 Cybersicherheits-Selbstbewertung für Lieferanten

Ein umfassendes, eigenständiges HTML-Bewertungstool für Lieferanten zur Bewertung und Dokumentation ihres Reifegrads im Bereich Cybersicherheit in Übereinstimmung mit den ISO 27001:2022-Standards.

## Überblick

Dieses Tool ermöglicht es Lieferanten, eine detaillierte Cybersicherheits-Selbstbewertung durchzuführen, die 10 wichtige Sicherheitsbereiche mit 39 Fragen abdeckt. Die Bewertung wird lokal als HTML-Datei gespeichert, die erneut geöffnet, geändert und per E-Mail geteilt werden kann.

## Hauptmerkmale

- **Eigenständige HTML-Datei** - Kein Server, keine Datenbank oder Internetverbindung erforderlich
- **Automatische Fortschrittsverfolgung** - Visuelle Fortschrittsanzeige wird aktualisiert, wenn Sie Fragen beantworten
- **Echtzeit-Reifegradwertung** - Sofortige Punkteberechnung basierend auf Ihren Antworten
- **Antwortpersistenz** - Speichert Antworten direkt in der HTML-Datei beim Download
- **Erneut öffnen und bearbeiten** - Kann erneut geöffnet und Antworten vor der endgültigen Einreichung geändert werden
- **Mehrsprachige Unterstützung** - Verfügbar auf Englisch, Spanisch, Französisch und Deutsch

## Schnellstartanleitung für Lieferanten

### Schritt 1: Bewertung Öffnen
1. Laden Sie die Datei `supplier-cybersecurity-assessment.html` herunter
2. Doppelklicken Sie auf die Datei, um sie in Ihrem Webbrowser zu öffnen
3. Die Bewertung wird offline geöffnet - keine Internetverbindung erforderlich

### Schritt 2: Unternehmensinformationen Ausfüllen
Füllen Sie die erforderlichen Felder oben aus:
- Firmenname
- Kontaktperson
- E-Mail-Adresse
- Telefonnummer
- Bewertungsdatum (wird automatisch mit dem heutigen Datum ausgefüllt)

### Schritt 3: Sicherheitsfragen Beantworten
Die Bewertung umfasst 10 Sicherheitsbereiche:
1. Informationssicherheitsrichtlinie & Governance
2. Asset-Management
3. Zugangskontrolle
4. Datenschutz
5. Physische & Umweltsicherheit
6. Betriebssicherheit
7. Netzwerksicherheit
8. Vorfallsmanagement
9. Geschäftskontinuität
10. Compliance & Überwachung

Wählen Sie für jede Frage Ihren Reifegrad:

| Stufe | Punkte | Beschreibung |
|-------|--------|--------------|
| **Nicht Implementiert** | 0 | Kontrolle nicht vorhanden |
| **Teilweise Implementiert** | 1 | Kontrolle teilweise vorhanden, inkonsistente Anwendung |
| **Implementiert** | 3 | Kontrolle vorhanden und konsistent angewendet |
| **Vollständig Ausgereift** | 5 | Kontrolle vollständig integriert, überwacht und kontinuierlich verbessert |
| **Nicht Zutreffend** | N/V | Frage trifft auf Ihre Organisation nicht zu |

### Schritt 4: Fortschritt Verfolgen
- Die Fortschrittsanzeige zeigt den Fertigstellungsprozentsatz (basierend auf beantworteten Fragen)
- Die Punktzahl wird automatisch aktualisiert, wenn Sie Fragen beantworten
- Sehen Sie Ihre aktuelle Reifegradpunktzahl in Echtzeit

### Schritt 5: Bewertung Speichern
1. Klicken Sie unten auf die Schaltfläche **"💾 Bewertung auf Festplatte Speichern"**
2. Ihr Browser lädt eine Datei mit dem Namen herunter: `security_assessment-[ihrfirma]-[datum].html`
3. Die Datei enthält alle Ihre Antworten und kann später erneut geöffnet werden

### Schritt 6: Überprüfen oder Ändern (Optional)
1. Finden Sie die gespeicherte Datei in Ihrem Downloads-Ordner
2. Doppelklicken Sie, um sie in Ihrem Browser erneut zu öffnen
3. Alle Ihre vorherigen Antworten werden angezeigt
4. Nehmen Sie erforderliche Änderungen vor
5. Klicken Sie erneut auf **"💾 Bewertung auf Festplatte Speichern"**, um die aktualisierte Version zu speichern
6. Hinweis: Das Datum im Dateinamen wird aktualisiert, um zu zeigen, wann Sie es zuletzt gespeichert haben

### Schritt 7: An Kunden Senden
1. Senden Sie die endgültige gespeicherte HTML-Datei per E-Mail an Ihren Kundenkontakt
2. Sie können sie in jedem Browser öffnen, um Ihre Antworten zu überprüfen
3. Ihre Reifegradpunktzahl ist im Dokument sichtbar

## Bewertungssystem

### Punkteberechnung
- **Maximal mögliche Punktzahl:** 195 Punkte (39 Fragen × 5 Punkte jeweils)
- **Die Bewertung ist kumulativ:** Ihre Gesamtpunktzahl ist die Summe aller beantworteten Fragen
- **"Nicht Zutreffend"-Antworten** tragen nicht zur Punktzahl bei

### Reifegrade

| Punktebereich | Reifegrad | Beschreibung |
|---------------|-----------|--------------|
| **0** | Keine Bewertung | Bewertung nicht begonnen |
| **1-50** | Initial | Erhebliche Verbesserungen erforderlich |
| **51-100** | In Entwicklung | Grundlegende Sicherheitspraktiken vorhanden |
| **101-150** | Definiert | Gute Sicherheitspraktiken etabliert |
| **151-195** | Optimiert | Ausgereifte Sicherheitspraktiken |

## Technische Details

### Dateinamenskonvention
Gespeicherte Dateien folgen diesem Format:
```
security_assessment-firmenname-JJJJ-MM-TT.html
```
- Firmenname wird auf maximal 12 Zeichen gekürzt
- Datum wird bei jedem Speichern automatisch aktualisiert
- Beispiel: `security_assessment-meinefirma-2025-11-05.html`

### Browser-Kompatibilität
- ✅ Chrome/Edge (empfohlen)
- ✅ Firefox
- ✅ Safari
- ✅ Alle modernen Browser

### Datenschutz & Datensicherheit
- **Keine Datenübertragung** - Alles bleibt auf Ihrem Computer
- **Kein Tracking** - Keine Analysen oder externe Verbindungen
- **Vollständig offline** - Funktioniert ohne Internet
- **Sie kontrollieren die Datei** - Sie entscheiden, wann und wie Sie sie teilen

## Support

Bei Fragen oder Problemen:
- Überprüfen Sie, ob Sie einen modernen Webbrowser verwenden
- Stellen Sie sicher, dass JavaScript in Ihrem Browser aktiviert ist
- Überprüfen Sie, ob Sie die Berechtigung zum Herunterladen von Dateien haben
- Versuchen Sie, die Datei in einem anderen Browser zu öffnen, wenn Probleme auftreten

## Lizenz

Dieses Tool wird wie besehen für Zwecke der Lieferanten-Sicherheitsbewertung bereitgestellt.

---

**Version:** 2.0  
**Letzte Aktualisierung:** November 2025  
**Compliance-Framework:** ISO 27001:2022
