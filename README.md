<img src="https://github.com/Dyonis89/NetRemote/blob/main/screenshots/AppBanner.png" alt="Logo" height="128"/>
NetRemote ist ein kompaktes, portables Remote‑Management‑Tool für Windows.
Es vereint die wichtigsten Zugriffs‑ und Verwaltungsprotokolle für Netzwerkadministration in einer einzigen Anwendung.

## Warum NetRemote?

Ich habe NetRemote entwickelt, weil mir viele bestehende Alternativen zu überladen, unübersichtlich oder schlicht zu langsam waren.  
Mein Ziel war eine minimalistische, schnelle und portable Lösung, die ohne lange Ladezeiten auskommt und trotzdem alle wichtigen Funktionen für den täglichen Admin‑Alltag bietet.

Inzwischen bietet NetRemote sogar mehr Funktionen als viele etablierte Admin‑Tools – und ich freue mich, es nun veröffentlichen zu können.

Ein weiterer wichtiger Punkt für mich: Alle Daten bleiben vollständig lokal.  
Es gibt keine Cloud‑Abhängigkeiten und keine Telemetrie.

## Unterstützte Funktionen

### **SSH & SFTP**
Sichere Shell‑Verbindungen und Dateiübertragung für Server, Router, Switches und Netzwerkgeräte.  
Terminal und Verzeichnisstruktur werden übersichtlich nebeneinander dargestellt und können interagieren.

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

Die aktuellen Versionen findest du unter **Releases**: https://github.com/Dyonis89/NetRemote/releases

## Hinweise zur Sicherheit

Zugangsdaten werden derzeit für SSH Verbindungen lokal und unverschlüsselt gespeichert.  
Eine optionale Verschlüsselung ist für zukünftige Versionen vorgesehen.
RDP Zugangsdaten werden durch Windows verwaltet, daher kann auch kein Passwort parametriert werden.

## Verwendete Bibliotheken

NetRemote verwendet verschiedene Drittanbieter‑Bibliotheken.  
Die zugehörigen Lizenzinformationen befinden sich in der Datei `THIRD_PARTY_LICENSES.md`.

## Unterstütze das Projekt

NetRemote entsteht komplett in meiner Freizeit.

Wenn dir das Tool gefällt oder du die Weiterentwicklung unterstützen möchtest, freue ich mich über eine kleine Anerkennung: [Unterstützen / Donate](DONATE.md)

## 📄 Lizenz

Die Anwendung ist Closed Source. Die Nutzung und Weitergabe der Binaries ist erlaubt.
Der Quellcode bleibt privat.
