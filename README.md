# RouteRhythm – GPX Analyse für Motorrad, Fahrrad & Outdoor

RouteRhythm ist ein modernes Tool zur Analyse, Visualisierung und Auswertung von GPX‑Tracks.  
Es richtet sich an Motorradfahrer, Radfahrer, Wanderer und Outdoor‑Enthusiasten, die ihre Touren im Detail verstehen möchten – inklusive Kurven, Kehren, Pässen, Höhenprofil, Geschwindigkeit und professionellen PDF‑Berichten.

Dieses Repository enthält:
- Dokumentation
- Beispiel‑GPX‑Dateien
- Screenshots der Anwendung
- Beispielausgaben (HTML‑Map & PDF‑Report)

Der Anwendungscode selbst ist nicht öffentlich zugänglich.

---

## Funktionen

### GPX‑Analyse
- Mehrere Tracks gleichzeitig analysieren
- Kurven‑, Kehren‑ und Switchback‑Erkennung
- Höhenprofil, Steigung und Geschwindigkeitsanalyse
- **Automatische Pässe‑Erkennung** basierend auf einer Pass‑Datenbank
- Tagessegmentierung von Mehrtagestouren
- Interaktive Kartenansicht

### Visualisierung
- Farblich codierte Multi‑Track‑Karte
- Diagramme für Höhe, Steigung und Geschwindigkeit
- Tagesansichten mit eigenen Charts
- Statistikübersicht mit allen Kennzahlen

### PDF‑Export
- Kompletter Tourbericht
- Kartenansichten
- Diagramme (Höhe, Steigung, Geschwindigkeit)
- Tagesberichte
- Pass‑Tabelle (falls verfügbar)
- Professionelles Layout zum Drucken oder Teilen

---

## Repository‑Inhalte

```
/routerhythm-gpx-analysis
 ├── README.md
 ├── screenshots/
 │     ├── 01_Landing_Page.png
 │     ├── 02_Login.png
 │     ├── 03_Dashboard.png
 │     ├── 04_Statistik_Pässe.png
 │     ├── 06_Statistk_Tour.png
 │     ├── 07_HTML-MAP-Tour.png
 │     ├── 08_HTML-MAP-Tour.png
 │     ├── 09_HTML-MAP-Pass.png
 │     ├── 10_HTML-MAP-Kehre.png
 │     ├── 11_Elevation-Profile.png
 ├── examples/
 │     ├── sample-track.gpx
 ├── outputs/
 │     ├── html-map/
 │     │     ├── example-map.html
 │     ├── pdf-reports/
 │     │     ├── example-report.pdf
 ├── docs/
 │     ├── features.md
 │     ├── passes-detection.md
 │     ├── data-processing.md
 │     ├── output-formats.md
 │     ├── privacy.md
 ├── changelog.md
 ├── roadmap.md
```

### `/screenshots/`
Screenshots der Benutzeroberfläche (Dashboard, Karte, Höhenprofil, Pässe‑Erkennung).

### `/examples/`
Beispiel‑GPX‑Dateien zur Demonstration der Analysefunktionen.

### `/outputs/`
Beispielausgaben:
- **HTML‑Map** (interaktive Karte)
- **PDF‑Report** (kompletter Tourbericht)

### `/docs/`
Dokumentation zu:
- Features
- Datenverarbeitung (allgemein)
- Pässe‑Erkennung
- Ausgabeformaten
- Datenschutz

---

## Projektseite

Weitere Informationen und Live‑Version:  
https://routerhythm.de

---

## Kontakt

Projekt: RouteRhythm  
Website: https://routerhythm.de  
Owner: Christian
