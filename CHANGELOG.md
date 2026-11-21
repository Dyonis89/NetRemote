# Changelog

## 2.0.0 – Fluent UI Redesign & NetDiag Integration

### Veröffentlichungsdatum
2026-11-21

### Neues Fluent Design
- Benutzeroberfläche vollständig auf modernes Fluent Design umgestellt
- Überarbeitete Navigation und Dialoge
- Verbesserte Konsistenz und Bedienbarkeit der gesamten Anwendung

### NetDiag
- Netzwerkdiagnose vollständig integriert
- DNS-Auflösung
- ICMP/Ping-Tests
- TCP-Port-Erreichbarkeit
- TraceRoute

### Verbindungsverwaltung
- Suchfunktion vollständig überarbeitet
- Verbesserte Verwaltung von Verbindungen und Gruppen
- Optimiertes Änderungs-Tracking
- Schnellere Navigation innerhalb großer Verbindungslisten

### Plattform
- Migration auf .NET 10
- Modernisierung der Anwendungsarchitektur
- Verbesserte Performance
- Verbesserte Kompatibilität mit aktuellen Windows-Versionen

### Allgemein
- Zahlreiche UX-Verbesserungen
- Diverse Stabilitätsverbesserungen
- Zahlreiche Fehlerkorrekturen

## 1.1.3 – Quick Connect, API Tester und UX/UI-Verbesserungen
### Veröffentlichungsdatum
2026‑08‑12

### Quick Connect
- Quick Connect für einmal Verbindungen eingeführt
- Schnellzugriff auf zuletzt genutzte Quick Connect Verbindungen

### HTTP-Erweiterung
- API Tester als Sidebar hinzugefügt

### Allgemein
- Tastatur Fokus optimiert
- Verschiedenste UI Updates
- Datenspeicherung von Einstellungen und Profilen optimiert

## 1.1.2 – UI-Verbesserungen & Stabilitäts-Updates
### Veröffentlichungsdatum
2026‑07‑09

### RDP-Optimierungen
- Allgemeine RDP‑Stabilitäts‑ und Performance‑Verbesserungen

### VNC-Optimierungen
- Bugfix für VNC‑Input (Windows‑Shortcuts / Eingabeverarbeitung)
- VNC‑Toolbar integriert
- Session‑Handling optimiert (Reconnect, Disconnect‑Flow)

### SSH-Optimierungen
- Terminal‑Bugfix beim Kopieren von Text (Unicode‑Zeichen „Ȁ“ entfernt)
- Sidebar‑Größe speicherbar gemacht
- Option hinzugefügt: gleiche Sidebar‑Breite für alle Sessions

### Verbindungsverwaltung
- Auto‑Reload‑Option für Verbindungen hinzugefügt
- neue Info‑Sidebar statt zuklappendem Properties‑Panel
- Layout‑Optimierungen
- konsistentere Darstellung

### UI & UX
- Tab‑Namen sind jetzt änderbar

## 1.1.1 – VNC und Verbindungsverwaltungs‑Optimierungen
### Veröffentlichungsdatum
2026‑06‑04

### VNC-Optimierungen
- VNC Eingabe-Verarbeitung korrigiert (bezüglich Windows Shortcuts)
- View-Only als default gesetzt, mit Banner zum Steuerung übernehmen
- VNC Auto‑Reconnect funktioniert jetzt zuverlässig bei Verbindungsabbrüchen
- VNC Connect‑Timeout verhindert Hängenbleiben beim Verbindungsaufbau

### Verbindungsverwaltung
- Interne Optimierungen an der Verbindungsverwaltung und Changetracking der Profilspeicherung

---

## 1.1.0 – VNC‑Integration & UI‑/Funktions‑Optimierungen
### Veröffentlichungsdatum
2026‑05‑25

### VNC‑Integration
- Neues VNC‑Modul auf Basis von *RemoteViewing* integriert

### RDP‑Verbesserungen
- RDP‑Adapter eingeführt für Abwärtskompatibilität zu RDP‑Clients 7–12

### HTTP‑/Browser‑Modul
- Overlay‑System überarbeitet (neue Tabs, Schließen, Fokusverhalten)

### SSH, SFTP & Terminal
- Snippet‑System erweitert (lokale & globale Snippets mit Suchfunktion)
- SFTP‑Browser überarbeitet
- Media‑/Image‑Viewer im SSH‑Kontext eingeführt

### UI & UX
- Neue Suchfunktion für Verbindungen mit zuletzt genutzt Sortierung.  
- Einstellungen und About‑Seite in modale Overlays ausgelagert
- FontFamily‑Fallbacks für ältere Windows‑Versionen (Server, Win10)

### Installer
- Installer integriert 
- Dateizuordnungen (File Associations) integriert

---

## 1.0.1 – Erweiterte SSH‑Funktionen & Medienvorschau
### Veröffentlichungsdatum
2025‑01‑09

### SSH & SFTP
- SSH‑Subsystem komplett überarbeitet
- Terminal‑Größenänderungen werden jetzt dynamisch übernommen, ohne Reconnect
- Unterstützung für Passwort‑Authentifizierung
- Unterstützung für Keyboard‑Interactive‑Authentifizierung
- Unterstützung für Key‑basierte Authentifizierung
- SSH‑Zugangsdaten werden nun sicher im Windows Credential Manager gespeichert
- Stabilere SSH‑ und SFTP‑Verbindungen

### Verbindungsverwaltung & Speicherung
- Neue, auswählbare Speicherstrategie für Verbindungsdaten
  - Lokale Speicherung
  - Optionale Nutzung für z. B. Cloud‑Ablage / mehrere Endgeräte (je nach Setup)
- Verbesserte Strukturierung der Verbindungsdefinitionen

### Code‑/Config‑Editor
- Integrierter Editor für Konfigurations‑ und Textdateien
- Syntax‑Highlighting für typische Config‑/Code‑Formate
- Direkte Bearbeitung von Dateien aus SFTP heraus

### Medienvorschau
- Integrierte Medienvorschau für:
  - Bilder
  - Videos
  - Audio
- Einheitliche, moderne Modal‑Ansicht für Medieninhalte

### UI & UX
- Optimierte Darstellung der SSH‑/SFTP‑Ansicht
- Kleinere Layout‑ und Darstellungsverbesserungen
- Aktualisierte Dokumentation (README, Sicherheitshinweise, Lizenzinfos)

---

## 1.0.0 – Erstes öffentliches Release
### Veröffentlichungsdatum
2025‑01‑08

### Highlights
- Erstes öffentliches Release von NetRemote
- Portable Framework‑dependent Build
- Portable Self‑contained Build
- RDP‑Verbindungen
- SSH‑Verbindungen mit SFTP‑Funktionalitäten
- WebBrowser‑Integration  
  - Automatisierung über WebView2‑JavaScript‑Ausführung
- Tastaturkürzel für schnelle Navigation
- Fehler‑ und Ladezustände für bessere Nutzerführung
