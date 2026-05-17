# Warenherstellung Calculator

Statisches Webinterface für GitHub Pages. Es benötigt kein Backend, keine Datenbank und keinen Build-Prozess.

## Enthaltene Fabriken

- Stahlfabrik
- Fahrzeugfabrik
- Kleidungsfabrik
- Luftfahrzeugfabrik
- Bootsfabrik
- Ölfabrik
- Warenfabrik
- Chemiefabrik
- Illegale Waffenfabrik

## Funktionen

- Rezeptverwaltung je Fabrik
- Navigation über linke Sidebar statt horizontaler Header-Tabs
- einklappbares Menü auf kleineren Bildschirmen
- zentral gesetzte Überschrift
- Daten-Buttons unten in der Sidebar
- frei erweiterbare Materialstammdaten
- Produktionsplan mit Fabrik-, Waren- und Mengenauswahl
- automatische Berechnung der notwendigen Produktionsläufe
- aggregierte Materialbedarfsliste
- lokale Speicherung im Browser per `localStorage`
- JSON Export und Import für Backups oder Umzug auf andere Geräte

## GitHub Pages Deployment

1. Dateien in ein GitHub-Repository hochladen.
2. GitHub Repository öffnen.
3. `Settings` → `Pages` öffnen.
4. Source: `Deploy from a branch` wählen.
5. Branch: `main`, Ordner: `/root` wählen.
6. Speichern.

Danach stellt GitHub Pages die Seite unter der angezeigten Pages-URL bereit.

## Dateien

- `index.html` – Seitenstruktur
- `styles.css` – Layout und Styling
- `app.js` – Rezeptverwaltung, Calculator, Import/Export und Speicherung
