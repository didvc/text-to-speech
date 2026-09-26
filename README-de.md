[English](README.md) · [日本語](README-ja.md) · [繁體中文](README-zh-TW.md) · [简体中文](README-zh.md) · Deutsch · [Français](README-fr.md) · [Español](README-es.md) · [Bahasa Indonesia](README-id.md)

# VoiceFlow - Fortgeschrittene Text-to-Speech-Anwendung

[![Live Demo](https://img.shields.io/badge/Live_Demo-blue?style=for-the-badge)](https://text-speech.pages.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/issues)
[![GitHub stars](https://img.shields.io/github/stars/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/stargazers)

Eine moderne, funktionsreiche Text-to-Speech-Webanwendung, gebaut mit React und TypeScript. VoiceFlow bietet eine intuitive Oberfläche, um Text in natürlich klingende Sprache umzuwandeln, mit Wortmarkierung in Echtzeit, anpassbaren Stimmeinstellungen und Inhaltsverwaltung.

## Screenshots

![Oberfläche der VoiceFlow-Anwendung](https://res.cloudinary.com/dxowqxqtj/image/upload/v1753415581/text-to-speech/voiceflow-main-screenshot.png)

*Die intuitive Oberfläche von VoiceFlow mit Wortmarkierung in Echtzeit, anpassbaren Sprachreglern und Inhaltsverwaltung.*

## Funktionen

### Kernfunktionen
- Text-to-Speech: hochwertige Sprachsynthese über die Web Speech API
- Wortmarkierung in Echtzeit: animierte Hervorhebung der Wörter während der Wiedergabe
- Wiedergabesteuerung: Abspielen, Pausieren und Stoppen mit reaktionsschnellen Reglern
- Mehrere Stimmen: Auswahl aus den Systemstimmen mit Spracherkennung

### Anpassung
- Einstellbare Sprechgeschwindigkeit: Wiedergabe von 0,5x bis 2x
- Tonhöhe: Stimmhöhe fein einstellen für das beste Hörerlebnis
- Lautstärke: Ausgabepegel anpassen
- Stimmauswahl: aus den verfügbaren Systemstimmen wählen

### Inhaltsverwaltung
- Textbibliothek: mehrere Textdokumente mit Titeln organisieren
- Hinzufügen, Bearbeiten, Löschen: vollständige Verwaltung der Texte
- Wechsel zwischen Inhalten: nahtlos zwischen verschiedenen Texten wechseln
- Dauerhafte Speicherung: Inhalte werden lokal im Browser gespeichert

### Benutzeroberfläche
- Modernes dunkles Design: elegant und augenschonend
- Responsives Design: funktioniert auf Desktop, Tablet und Smartphone
- Farbverläufe: schöne Verlaufsschrift und visuelle Elemente
- Intuitive Bedienung: benutzerfreundlich mit klarem visuellem Feedback

## Erste Schritte

### Voraussetzungen
- Node.js (Version 16 oder neuer)
- npm oder yarn
- Moderner Browser mit Unterstützung für die Web Speech API

### Installation

1. Repository klonen
   ```bash
   git clone https://github.com/didvc/text-to-speech.git
   cd text-to-speech
   ```

2. Abhängigkeiten installieren
   ```bash
   npm install
   # or
   yarn install
   ```

3. Entwicklungsserver starten
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Browser öffnen
   Unter `http://localhost:5173` erscheint die Anwendung

### Build für die Produktion

```bash
npm run build
# or
yarn build
```

Die gebauten Dateien liegen danach im Verzeichnis `dist/`.

## Bedienung

### Grundlagen
1. Text wählen oder hinzufügen: aus den vorgeladenen Beispielen wählen oder eigenen Text hinzufügen
2. Einstellungen anpassen: Stimme, Geschwindigkeit, Tonhöhe und Lautstärke nach Wunsch einstellen
3. Abspielen: auf den Play-Button klicken, um die Sprachausgabe zu starten
4. Mitlesen: die Wortmarkierung in Echtzeit verfolgen, während der Text gelesen wird

### Erweiterte Funktionen
- Inhaltsverwaltung: mehrere Dokumente in der Textbibliothek organisieren
- Stimmwechsel: verschiedene Stimmen und Sprachen ausprobieren
- Geschwindigkeit: Lesetempo für Verständnis oder Barrierefreiheit anpassen
- Mobile Unterstützung: voller Funktionsumfang auf Mobilgeräten

## Tech-Stack

- Frontend-Framework: React 18
- Sprache: TypeScript
- Build-Tool: Vite
- Styling: Tailwind CSS
- Icons: Lucide React
- Sprach-API: Web Speech API (SpeechSynthesis)

## Browserkompatibilität

VoiceFlow läuft in modernen Browsern, die die Web Speech API unterstützen:

- Chrome/Chromium (empfohlen)
- Edge
- Safari
- Firefox (eingeschränkte Stimmauswahl)
- Mobile Browser (iOS Safari, Chrome Mobile)

## Responsives Design

VoiceFlow ist so gebaut, dass es auf allen Gerätetypen reibungslos funktioniert:
- Desktop: voller Funktionsumfang mit optimiertem Layout
- Tablet: touchfreundliche Oberfläche mit anpassbaren Reglern
- Smartphone: kompaktes Design mit gut erreichbaren Kernfunktionen

## Mitwirken

Beiträge aus der Community sind willkommen! Wie du anfängst, steht in den [Richtlinien für Beiträge](CONTRIBUTING.md).

### Schnellstart für Mitwirkende
1. Repository forken
2. Feature-Branch anlegen (`git checkout -b feature/amazing-feature`)
3. Änderungen vornehmen
4. Änderungen committen (`git commit -m 'Add amazing feature'`)
5. Branch pushen (`git push origin feature/amazing-feature`)
6. Pull Request öffnen

## Lizenz

Dieses Projekt steht unter der MIT-Lizenz; Details stehen in der Datei [LICENSE](LICENSE).

## Fehler und Support

- Fehlerberichte: [Issue erstellen](https://github.com/didvc/text-to-speech/issues/new?template=bug_report.yml)
- Funktionswünsche: [Funktion vorschlagen](https://github.com/didvc/text-to-speech/issues/new?template=feature_request.yml)
- Diskussionen: [An der Diskussion teilnehmen](https://github.com/didvc/text-to-speech/discussions)

## Danksagungen

- Der Web Speech API für die Sprachausgabe
- Den Communitys von React und TypeScript für hervorragende Werkzeuge
- Tailwind CSS für das schöne Styling-System
- Lucide React für die klaren, modernen Icons

## Projektmerkmale

- Build-Größe: für schnelles Laden optimiert
- Abhängigkeiten: minimal und sorgfältig ausgewählt
- Performance: flüssige Animationen mit 60 fps und reaktionsschnelle Interaktion
- Barrierefreiheit: WCAG-konform mit Tastaturbedienung

---

<div align="center">

[VoiceFlow live ausprobieren](https://text-speech.pages.dev) | [Dokumentation](https://github.com/didvc/text-to-speech/wiki) | [Diskussionen](https://github.com/didvc/text-to-speech/discussions)

Erstellt von [didvc](https://github.com/didvc)

</div>