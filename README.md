<img src="https://github.com/Dyonis89/NetRemote/blob/main/screenshots/AppBanner.png" alt="Logo" height="128"/>
NetRemote ist ein kompaktes, portables Remote‑Management‑Tool für Windows.
Es vereint SSH, SFTP, RDP und Webzugriffe in einer einzigen, schnellen und übersichtlichen Anwendung – komplett ohne Installation, Cloud‑Abhängigkeiten oder Telemetrie.

## Warum NetRemote?

Viele bestehende Admin‑Tools sind überladen, langsam oder unübersichtlich.  
NetRemote entstand aus dem Wunsch nach einer schnellen, minimalistischen und portablen Lösung, die alle wichtigen Funktionen für den täglichen Admin‑Alltag vereint.

Alle Daten bleiben vollständig lokal – keine Cloud, keine Telemetrie, keine externen Abhängigkeiten.

## Unterstützte Funktionen

### **SSH & SFTP**
Sichere Shell‑Verbindungen und Dateiübertragung für Server, Router, Switches und Netzwerkgeräte.  
Terminal und Verzeichnisstruktur werden übersichtlich nebeneinander dargestellt und können interagieren.

**Inklusive:**
- integrierte Medienvorschau (Bilder, Videos, Audio)
- Syntax‑Highlighting‑Editor für Konfigurationsdateien und Code

### **Remote Desktop (RDP)**
Komfortabler Zugriff auf Windows‑Systeme über eine integrierte RDP‑Ansicht.

### **Webbrowser‑Integration**
Direkte Einbindung von Weboberflächen – ideal für Firewalls, Access Points, Switches, IoT‑Geräte und interne Tools.
Dank integrierter WebView2‑Engine können eigene JavaScript‑Automationen direkt auf der Zielseite ausgeführt werden – ideal für Login‑Flows, Status‑Checks oder wiederkehrende Klick‑Abläufe.

## Einsatzgebiet

NetRemote richtet sich an:

- Netzwerk‑ und Systemadministratoren
- Homelab‑Enthusiasten
- alle, die regelmäßig mit SSH, RDP oder Servern arbeiten.

## Vorteile

- Alles in einer Anwendung
- Einheitliche Oberfläche für alle Protokolle
- Portabel, keine Installation notwendig
- Keine Cloud, keine Telemetrie
- Ideal für tägliche Admin‑Workflows

## Screenshots

### Verbindungsmanager

![App Screenshot](https://github.com/Dyonis89/NetRemote/blob/main/screenshots/Startscreen.png)

### SSH-Verbindungen

![App Screenshot](https://github.com/Dyonis89/NetRemote/blob/main/screenshots/SshBeispiel.png)

### RDP-Verbindungen

![App Screenshot](https://github.com/Dyonis89/NetRemote/blob/main/screenshots/RdpBeispiel.png)

### Webbrowser-Integration

![App Screenshot](https://github.com/Dyonis89/NetRemote/blob/main/screenshots/HttpBeispiel.png)

## Download

NetRemote wird in zwei Varianten bereitgestellt:

- **Framework‑Dependent** – kleiner Download, benötigt .NET Desktop Runtime  
- **Self‑Contained** – größer, aber vollständig eigenständig und ohne Abhängigkeiten

Beide Versionen sind portabel, funktional identisch und benötigen keine Installation.

Die aktuellen Versionen findest du unter **Releases**: https://github.com/Dyonis89/NetRemote/releases

## Hinweise zur Sicherheit

SSH‑Zugangsdaten werden sicher im Windows‑Anmeldeinformationsspeicher (Credential Manager) abgelegt.  
Es findet keine Cloud‑Speicherung oder Telemetrie statt.

RDP‑Zugangsdaten werden wie gewohnt durch Windows selbst verwaltet.

## Verwendete Bibliotheken

NetRemote verwendet verschiedene Drittanbieter‑Bibliotheken.  
Die zugehörigen Lizenzinformationen befinden sich in der Datei `THIRD_PARTY_LICENSES.md`.

## Unterstütze das Projekt

NetRemote entsteht komplett in meiner Freizeit.

Wenn dir das Tool gefällt oder du die Weiterentwicklung unterstützen möchtest, freue ich mich über eine kleine Anerkennung: [Unterstützen / Donate](DONATE.md)

## 📄 Lizenz

Die Anwendung ist Closed Source. Die Nutzung und Weitergabe der Binaries ist erlaubt.
Der Quellcode bleibt privat.
