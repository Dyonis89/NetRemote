# Changelog

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
