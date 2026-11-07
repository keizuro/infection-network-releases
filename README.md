# Infection Network – Downloads

Offizielle Downloads für Infection Network auf **Minecraft 1.21.1**, **NeoForge
21.1.265** und **All the Mods 10, Version 8.5**.

## Windows-Launcher

[Launcher für Windows x64 herunterladen](https://github.com/keizuro/infection-network-releases/releases/download/stable/InfectionNetworkLauncher-Windows-x64.zip)

ZIP entpacken und `InfectionNetwork.Launcher.exe` starten. In der Einrichtung
einmalig den installierten ATM10-8.5-Ordner wählen. Der Launcher erstellt eine
eigene Installation und erhält das ursprüngliche Profil und dessen Welten.
Prism Launcher und JDK 21 werden von den offiziellen Quellen geladen. Die
Microsoft-Anmeldung findet in Prism statt und muss selbst bestätigt werden.

Aktuell ist **reines ATM10 8.5 ohne Infection Network, Spore und Squaremap**
freigegeben. Launcher **0.4.0** prüft vor dem Start die Original-Mods und verschiebt
bekannte Projektzusätze mit passenden Prüfsummen in Sicherungen. Unbekannte
zusätzliche oder veränderte Original-Mods stoppen den Start zur Prüfung.
JourneyMap und GeckoLib gehören zur originalen Basis und bleiben enthalten.

Launcher-Updates werden bereits beim Öffnen automatisch geprüft. Vor dem Spielen
wird zusätzlich das signierte Serverprofil geprüft.
Launcher-Updates werden nach dem Beenden der Anwendung mit Sicherung installiert;
danach startet der Launcher neu. Anschließend erneut Spielen wählen.

Nach einem bestätigten Minecraft-Fenster schließt sich die Launcher-Oberfläche
standardmäßig. Unter **Einrichtung → Protokoll nach dem Minecraft-Start offen
halten** lässt sich das Protokoll stattdessen geöffnet lassen. Prism bleibt als
notwendiger Hintergrundprozess während des Spiels aktiv.

**Nur für Admins und lokale Tests:** Unter **Einrichtung → Erweiterte Einstellungen
→ Administration und lokale Tests** lässt sich nach einer ausdrücklichen Warnung
ein getrenntes Beta-Profil aktivieren. Es enthält Spore und Infection Network,
verwendet einen eigenen Spielordner und übernimmt keine normale Serveradresse.
Nur entbehrliche Testwelten und passende Testserver verwenden. Die Anmeldung
in Prism erfolgt im Beta-Profil einmalig separat.

Bis einschließlich 0.3.0 benötigt die erste Übernahme der neuen Startprüfung
einmal „Updates prüfen“ oder das aktuelle Paket. Ab 0.4.0 genügt das Öffnen.

Wer die lokale Vorschau **0.1.0** verwendet, muss einmalig dieses neue Paket
installieren. Ab **0.2.0** ist der Selbstupdater enthalten. Vorhandene eigene
Spielordner und Einstellungen werden weiterverwendet.

## Umfang

Die ATM10-Mods bleiben auf dem originalen Packstand 8.5. Packdefinition,
Prüfsummen und Original-Downloadverweise stehen im
[Basisprofil-Release](https://github.com/keizuro/infection-network-releases/releases/tag/profile-atm10-8.5-s13000001).
Das originale [Clientpaket](https://www.curseforge.com/minecraft/modpacks/all-the-mods-10/files/9431424)
und [Serverpaket](https://www.curseforge.com/minecraft/modpacks/all-the-mods-10/files/9431427)
werden weiterhin über CurseForge bezogen. Fremde Mod-JARs
oder Minecraft-Dateien werden hier nicht verteilt. Eine gültige Minecraft-Java-
Spielberechtigung ist erforderlich.

Alle Versionen und Prüfsummen befinden sich unter [Releases](https://github.com/keizuro/infection-network-releases/releases).
Dieses Repository enthält öffentliche Downloads und Anleitungen; der Projektcode
wird separat privat verwaltet. Private Schlüssel und Kontodaten gehören nicht hierher.
