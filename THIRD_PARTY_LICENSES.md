# Third‑Party Licenses

NetRemote verwendet verschiedene Open‑Source‑Bibliotheken.  
Die folgenden Komponenten werden gemäß ihren jeweiligen Lizenzen genutzt.  
Die vollständigen Lizenztexte befinden sich in den jeweiligen Projektrepositories oder NuGet‑Paketen.

## SSH.NET  
**Autor:** Renci  
**Lizenz:** MIT  
**Repository:** https://github.com/sshnet/SSH.NET

## Microsoft.Extensions.DependencyInjection  
**Autor:** Microsoft  
**Lizenz:** MIT  
**Repository:** https://github.com/dotnet/runtime

## CommunityToolkit.MVVM  
**Autor:** Microsoft / .NET Community Toolkit  
**Lizenz:** MIT  
**Repository:** https://github.com/CommunityToolkit/dotnet

## AvalonEdit  
**Autor:** ICSharpCode / AvalonEdit  
**Lizenz:** MIT  
**Repository:** https://github.com/icsharpcode/AvalonEdit

## HorizontalScroll  
**Autor:** radj307  
**Lizenz:** MIT (laut NuGet/Repository)  
**Repository:** https://github.com/radj307/HorizontalScroll

## NStack.Core
**Autor:** Miguel de Icaza / Xamarin / Mono Project  
**Lizenz:** MIT  
**Repository:** https://github.com/migueldeicaza/NStack

## Microsoft.Xaml.Behaviors.Wpf
**Autor:** Microsoft  
**Lizenz:** MIT  
**Repository:** https://github.com/microsoft/XamlBehaviorsWpf

## LibVLC / VideoLAN
**Autor:** VideoLAN  
**Lizenz:** LGPL 2.1  
**Repository:** https://code.videolan.org/videolan/vlc  
**Hinweis:** NetRemote verwendet LibVLC für die Medienwiedergabe (Video/Audio).  
Die Bibliothek wird dynamisch eingebunden und nicht modifiziert.

## LibVLCSharp
**Autor:** VideoLAN  
**Lizenz:** MIT  
**Repository:** https://github.com/videolan/libvlcsharp

## XtermSharp (modifizierte Version)
**Originalautor:** Miguel de Icaza
**Lizenz:** MIT
**Repository:** https://github.com/migueldeicaza/XtermSharp
**Hinweis:** Diese Version wurde von mir angepasst, um mehrere Fehler zu beheben und die Bibliothek auf .NET 8 zu portieren.
Die vorgenommenen Änderungen betreffen ausschließlich Debugging‑Korrekturen und Kompatibilitätsanpassungen.

# Hinweis

Alle oben genannten Bibliotheken werden dynamisch oder als NuGet‑Abhängigkeiten eingebunden.  
Die jeweiligen Lizenztexte sind in den NuGet‑Paketen enthalten und können dort eingesehen werden.

NetRemote selbst bleibt Closed Source.  
