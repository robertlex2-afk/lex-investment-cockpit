LEX Investment Cockpit 6.2.1 – Prototyp

Installation:
1. ZIP entpacken.
2. Dateien auf ein HTTPS-Hosting laden (z. B. GitHub Pages).
3. Auf dem iPhone in Safari öffnen und Teilen > Zum Home-Bildschirm.

Bereiche:
- Mein Vermögen: Dividendendepot (Scalable Capital) und Wachstumsdepot (Trade Republic).
- Depot Verlobte: separater Scalable-Capital-Import und eigene Auswertung.
- Gemeinsam: optionale Addition der Einstandskosten.
- CSV-Import: Vorschau, Formatprüfung, Dublettenprüfung pro Depot.
- Dividendenkalender: importierte historische Zahlungen je Jahr.
- Quartalsberichtskalender: erste recherchierte Termine mit Quellen und Status (geschätzt/bestätigt/veröffentlicht); Recherchelinks werden aus Positionen und Watchlists erstellt.
- Vermögenssimulator: Sparrate, Rendite und Zeitraum.
- JSON-Sicherung: alle lokalen Daten exportieren/importieren.

Wichtige Grenzen:
- Der Scalable-Parser ist auf den bereitgestellten Export mit 707 Buchungen und den Spalten date/reference/assetType/type/isin/shares/amount usw. abgestimmt; bitte Vorschau vor dem Übernehmen prüfen.
- Trade-Republic-Import muss anhand eines echten aktuellen Trade-Republic-CSV-Exports validiert werden; unbekannte Spalten werden nicht zuverlässig erkannt.
- Die Positionsberechnung ist eine vereinfachte Auswertung. Für steuerliche Einstandskurse, Kapitalmaßnahmen, Depotüberträge, Teilverkäufe und Fremdwährungen ist ein vollständiger Abgleich mit Brokerabrechnungen nötig.
- Die Terminrecherche öffnet Suchseiten; sie liest Suchergebnisse nicht automatisch aus. Termine müssen nach Prüfung gespeichert werden. Automatische Online-Abfrage, Übersetzung und Push-Mitteilungen benötigen eine angebundene Datenquelle sowie Backend/Push-Infrastruktur.
- Alle Daten liegen lokal im Browser. Regelmäßig Sicherungen exportieren. Für ein gemeinsames Gerät ist Zugriffsschutz/Benutzertrennung noch nicht implementiert.
- Keine vertraulichen Zugangsdaten oder API-Schlüssel in die HTML-Dateien eintragen.

Vorausgefüllte Berichtstermine (Stand 12.11.2026): Siemens 12.11.2026, CrowdStrike 01.12.2026, ASML 27.01.2027, Airbus 18.02.2027, Infineon 03.02.2027 (vorläufig). Termine können sich ändern; offizielle Quellen sind jeweils verlinkt.
