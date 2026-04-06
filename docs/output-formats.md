# Ausgabeformate – Übersicht

RouteRhythm erzeugt verschiedene Ausgabeformate, um GPX‑Analysen übersichtlich darzustellen und für unterschiedliche Anwendungsfälle nutzbar zu machen.  
Dieses Dokument beschreibt die öffentlich sichtbaren Ausgabeformate: **interaktive HTML‑Karte** und **PDF‑Bericht**.

---

## 1. Interaktive HTML‑Karte

Die HTML‑Karte visualisiert den GPX‑Track und alle erkannten Elemente direkt im Browser.  
Sie eignet sich ideal zur detaillierten Analyse und zur Weitergabe an andere Nutzer.

### Inhalte der HTML‑Karte

- vollständiger GPX‑Track  
- farblich codierte Abschnitte (z. B. Geschwindigkeit, Steigung)  
- markierte Kurven und Kehren  
- automatisch erkannte Pässe  
- Start‑ und Endpunkt  
- Tagesabschnitte (falls vorhanden)  

### Funktionen

- Zoom & Pan  
- interaktive Marker  
- Tooltip‑Informationen  
- Darstellung mehrerer Tracks gleichzeitig  

### Beispiel

Eine Beispielkarte befindet sich im Repository unter:

```
/outputs/html-map/example-map.html
```

---

## 2. PDF‑Bericht

Der PDF‑Bericht fasst alle Analyseergebnisse in einem professionellen, druckbaren Format zusammen.  
Er eignet sich für Tourendokumentation, Archivierung oder Weitergabe.

### Inhalte des PDF‑Berichts

- Übersichtskarte der Tour  
- Höhenprofil  
- Steigungsdiagramm  
- Geschwindigkeitsverlauf  
- Tagesabschnitt‑Diagramme  
- Statistiken (Distanz, Höhenmeter, Geschwindigkeit usw.)  
- optional: Pass‑Tabelle (falls Pässe erkannt wurden)  

### Eigenschaften

- klar strukturiertes Layout  
- optimiert für A4‑Druck  
- geeignet für digitale Weitergabe  
- konsistente Darstellung aller Diagramme  

### Beispiel

Ein Beispielbericht befindet sich im Repository unter:

```
/outputs/pdf-reports/example-report.pdf
```

---

## 3. Weitere Ausgabeformen (plattformabhängig)

Je nach Nutzungskontext können zusätzliche Formate bereitgestellt werden, z. B.:

- JSON‑Export einzelner Analysewerte  
- GPX‑Export (bereinigt oder segmentiert)  
- Bildexport von Diagrammen  

Diese Formate sind nicht Bestandteil des öffentlichen Repositories.

---

## 4. Hinweis

Dieses Dokument beschreibt ausschließlich die öffentlich sichtbaren Ausgabeformate.  
Die technische Implementierung der Analyse‑ und Exportfunktionen ist nicht Bestandteil dieses Repositories.
