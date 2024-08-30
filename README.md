# StarryNightsHotel

## Projektübersicht

**StarryNightsHotel** ist eine umfassende Hotelverwaltungssoftware, die sowohl für Gäste als auch für das Hotelmanagement eine breite Palette von Funktionen bietet. Die Anwendung ermöglicht die Verwaltung von Zimmerbuchungen, die Abwicklung von Zahlungen, die Verwaltung von Gästeinformationen und vieles mehr.

### Hauptfunktionen:
- **Zimmerbuchung**: Gäste können Zimmer direkt über die Anwendung buchen, inklusive Auswahl der Zimmerkategorie und -ausstattung.
- **Zahlungsabwicklung**: Integration von verschiedenen Zahlungsmethoden zur Abwicklung von Buchungen.
- **Gästeverwaltung**: Detaillierte Verwaltung der Gästedaten, einschließlich Check-in/Check-out, Sonderwünsche und Historie der Aufenthalte.
- **Berichterstellung**: Generierung von Berichten zur Auslastung, Einnahmen und Kundenzufriedenheit für das Management.

## Genutzte Technologien

- **Frontend**: [Vaadin](https://vaadin.com/)
- **Backend**: Java
- **Datenbank**: MySQL
- **CI/CD**: [z.B. Jenkins, GitHub Actions, etc.]

## Installation und Ausführung

1. **Voraussetzungen**:
   - Java JDK 11 oder höher
   - MySQL-Datenbank installiert und konfiguriert
   - Maven installiert

2. **Projekt klonen**:
   ```bash
   git clone https://github.com/JuohinaKhaled/StarryNightsHotel.git
   cd StarryNightsHotel

3. **Datenbank konfigurieren**:
- Erstelle eine MySQL-Datenbank und aktualisiere die application.properties-Datei im Backend-Projekt mit den entsprechenden Datenbankverbindungsdetails.
- Abhängigkeiten installieren und Anwendung starten:
- Backend starten:
  - cd backend
  - mvn clean install
  - mvn spring-boot:run
- Frontend (Vaadin) ist bereits integriert im Backend und wird zusammen mit dem Backend gestartet.
  
- Die Anwendung ist unter http://localhost:8080 erreichbar.



