# Changelog

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
