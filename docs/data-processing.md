# Verarbeitung von GPX‑Daten – Übersicht

Dieses Dokument beschreibt in vereinfachter Form, wie RouteRhythm GPX‑Daten verarbeitet.  
Es enthält **keine technischen Details oder Quellcode‑Informationen**, sondern dient als transparente Übersicht für Nutzer und Entwickler.

---

## 1. Zweck der Verarbeitung

RouteRhythm verarbeitet GPX‑Daten, um:

- Touren zu analysieren  
- Höhenprofile, Steigungen und Geschwindigkeiten zu berechnen  
- Kurven, Kehren und Pässe zu erkennen  
- interaktive Karten darzustellen  
- PDF‑Berichte zu erstellen  

---

## 2. Verarbeitete Daten aus GPX‑Dateien

Ein GPX‑Track kann u. a. folgende Informationen enthalten:

- GPS‑Positionen (Breite, Länge)
- Zeitstempel
- Höhe
- Geschwindigkeit (falls vorhanden)
- Wegpunkte
- Routenpunkte

Diese Daten werden ausschließlich für Analyse‑ und Visualisierungszwecke genutzt.

---

## 3. Analyseprozesse (allgemein)

RouteRhythm führt u. a. folgende Analysen durch:

- Berechnung von Distanz, Höhenmetern und Steigungen  
- Erkennung von Kurven und Kehren  
- Identifikation von Pässen anhand einer internen Pass‑Datenbank  
- Segmentierung in Tagesabschnitte  
- Erstellung von Diagrammen (Höhe, Steigung, Geschwindigkeit)  
- Generierung einer interaktiven HTML‑Karte  
- Erstellung eines PDF‑Berichts  

Die genaue technische Implementierung ist nicht Bestandteil dieses Repositories.

---

## 4. Speicherung von GPX‑Daten

GPX‑Dateien und Analyseergebnisse werden gespeichert, um:

- wiederkehrenden Zugriff zu ermöglichen  
- Touren zu verwalten  
- PDF‑Berichte erneut zu generieren  
- Statistiken und Historien bereitzustellen  

Nutzer können ihre Daten im Rahmen der DSGVO löschen lassen.

---

## 5. Keine Weitergabe an Dritte

GPX‑Daten werden **nicht an Dritte weitergegeben**.  
Ausnahmen bestehen nur, wenn:

- eine gesetzliche Verpflichtung besteht  
- der Nutzer ausdrücklich einwilligt  

---

## 6. Sicherheit

- sichere Speicherung  
- Zugriff nur für autorisierte Systeme  
- keine Weitergabe an externe Analyseanbieter  

---

## 7. Hinweis

Dieses Dokument dient der Transparenz.  
Es ersetzt **nicht** die rechtlich verbindliche Datenschutzerklärung:

➡️ https://routerhythm.de/datenschutz
