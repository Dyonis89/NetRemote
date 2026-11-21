# Third‑Party Licenses

NetRemote verwendet verschiedene Open‑Source‑Bibliotheken sowie Komponenten von Drittanbietern.
Die folgenden Komponenten werden gemäß ihren jeweiligen Lizenzen genutzt.  
Die vollständigen Lizenztexte befinden sich in den jeweiligen Projektrepositories oder NuGet‑Paketen.

## SSH.NET  
**Autor:** Renci  
**Lizenz:** MIT  
**Repository:** https://github.com/sshnet/SSH.NET

## NStack.Core
**Autor:** Miguel de Icaza / Xamarin / Mono Project  
**Lizenz:** MIT  
**Repository:** https://github.com/migueldeicaza/NStack

## XtermSharp (modifizierte Version)
**Originalautor:** Miguel de Icaza
**Lizenz:** MIT
**Repository:** https://github.com/migueldeicaza/XtermSharp
**Hinweis:** Diese Version wurde von mir angepasst, um mehrere Fehler zu beheben und die Bibliothek auf .NET 10 zu portieren.
Die vorgenommenen Änderungen betreffen ausschließlich Debugging‑Korrekturen und Kompatibilitätsanpassungen.
Meine Änderungen unterliegen ebenfalls den Bedingungen der MIT-Lizenz des Originalprojekts.

## Microsoft Remote Desktop ActiveX Control
**Autor:** Microsoft
**Lizenz:** Bestandteil von Microsoft Windows
**Hinweis:** Wird für die integrierte RDP-Funktionalität verwendet.

## RemoteViewing (Lemutec.RemoteViewing)  
**Autor:** James F. Bellinger / Lemutec  
**Lizenz:** MIT  
**Repository:** https://github.com/Quamotion/remoteviewing  
**Hinweis:** Wird für VNC‑Funktionalität genutzt (Raw, Hextile, CopyRect, Zlib).

## BouncyCastle.Cryptography
**Autor:** Legion of the Bouncy Castle Inc.  
**Lizenz:** MIT  
**Repository:** https://github.com/bcgit/bc-csharp
**Hinweis:** Wird als transitive Abhängigkeit genutzt (Kryptographie‑Funktionen, u. a. für RemoteViewing/Zlib).

## Microsoft.Web.WebView2
**Autor:** Microsoft
**Lizenz:** Microsoft Software License Terms
**Repository:** https://github.com/MicrosoftEdge/WebView2Samples
**Hinweis:** Wird für die integrierte Browserfunktionalität verwendet.

---

## Microsoft.Extensions.DependencyInjection  
**Autor:** Microsoft  
**Lizenz:** MIT  
**Repository:** https://github.com/dotnet/runtime

## Microsoft.Extensions.DependencyInjection.Abstractions
**Autor:** Microsoft  
**Lizenz:** MIT  
**Repository:** https://github.com/dotnet/runtime

## CommunityToolkit.MVVM  
**Autor:** Microsoft / .NET Community Toolkit  
**Lizenz:** MIT  
**Repository:** https://github.com/CommunityToolkit/dotnet

## Microsoft.Xaml.Behaviors.Wpf
**Autor:** Microsoft  
**Lizenz:** MIT  
**Repository:** https://github.com/microsoft/XamlBehaviorsWpf

## Microsoft.Extensions.Logging.Abstractions
**Autor:** Microsoft  
**Lizenz:** MIT  
**Repository:** https://github.com/dotnet/runtime

---

## HorizontalScroll  
**Autor:** radj307  
**Lizenz:** MIT (laut NuGet/Repository)  
**Repository:** https://github.com/radj307/HorizontalScroll

## AvalonEdit  
**Autor:** ICSharpCode / AvalonEdit  
**Lizenz:** MIT  
**Repository:** https://github.com/icsharpcode/AvalonEdit

## System.ValueTuple  
**Autor:** Microsoft  
**Lizenz:** MIT  
**Repository:** https://github.com/dotnet/runtime

## LibVLCSharp / LibVLCSharp.WPF  
**Autor:** VideoLAN  
**Lizenz:** LGPL 2.1  
**Repository:** https://github.com/videolan/libvlcsharp  
**Hinweis:** Wird als .NET‑Binding für LibVLC genutzt.  
Die Bibliothek wird dynamisch eingebunden und nicht modifiziert.

## VideoLAN.LibVLC.Windows  
**Autor:** VideoLAN  
**Lizenz:** LGPL 2.1  
**Repository:** https://code.videolan.org/videolan/vlc  
**Hinweis:** Enthält die LibVLC‑Runtime für Windows (libvlc.dll, libvlccore.dll, Plugins).  
Die Bibliothek wird dynamisch eingebunden und nicht modifiziert.

LibVLC und LibVLCSharp werden unter der LGPL 2.1 bereitgestellt.
NetRemote nutzt diese Bibliotheken unverändert und dynamisch eingebunden.
Der Quellcode der Bibliotheken sowie die Lizenztexte sind über die jeweiligen Projektseiten verfügbar.

# Hinweis

Alle oben genannten Bibliotheken werden dynamisch oder als NuGet‑Abhängigkeiten eingebunden.  
Die vollständigen Lizenztexte können über die jeweiligen Projektseiten, Repositorys oder NuGet-Pakete eingesehen werden.

NetRemote selbst bleibt Closed Source.  
