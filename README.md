# Infection Network — Downloads

Official downloads for **Minecraft 1.21.1**, **NeoForge 21.1.265** and
**All the Mods 10, version 8.5**.

## Windows launcher

[Download the launcher for Windows x64](https://github.com/keizuro/infection-network-releases/releases/download/stable/InfectionNetworkLauncher-Windows-x64.zip)

Extract the ZIP and run `InfectionNetwork.Launcher.exe`. Under **Settings**, select
an existing CurseForge ATM10 8.5 installation. The launcher creates its own managed
installation and preserves the source profile and its worlds. Prism Launcher and
JDK 21 come from their official providers. Sign in to your Microsoft account in
Prism yourself; a valid Minecraft Java entitlement is required.

Launcher **0.5.0** starts in **English**. Choose **Settings → Language → Deutsch**
for German. The preference is saved and applies immediately. Managed Prism and
Minecraft follow the selected language on the next launch.

Normal play currently uses **original ATM10 8.5**, without Infection Network,
Spore or Squaremap. Every launch verifies the original mods. Recognized project
additions with matching checksums are moved into backups. Unknown additions or
modified originals stop the launch for review. JourneyMap and GeckoLib are part
of the original pack and stay installed.

Signed launcher updates are checked automatically when the app opens; signed
pack updates are checked before Play. A launcher update backs up and replaces its
own EXE, then restarts. Click Play again afterwards. Close Minecraft and Prism
before profile updates. Worlds, accounts and personal settings are preserved.

The frontend closes after a Minecraft window is confirmed. To retain it and the
Prism console, enable **Settings → Keep the log open after Minecraft starts**. Prism
continues as the necessary backend while Minecraft runs.

**Admins and local testing only:** the beta switch is deliberately inside
**Settings → Advanced settings → Administration and local testing** and requires
an explicit warning confirmation. The beta has a separate installation, server
address and signed update feed. It includes Spore and Infection Network and must
use disposable test worlds and a compatible test server. Sign in separately in
the beta's Prism installation; accounts and saves are not copied between profiles.

Launchers through 0.3.0 need one click on the former update button or installation
of the current package to acquire startup checking. The old 0.1.0 preview needs
one manual package replacement; self-updating exists from 0.2.0 onward.

## Pack sources

ATM10 stays pinned to the original 8.5 pack. Definitions, checksums and original
download references are in the [base profile release](https://github.com/keizuro/infection-network-releases/releases/tag/profile-atm10-8.5-s13000001).
Get the original [client pack](https://www.curseforge.com/minecraft/modpacks/all-the-mods-10/files/9431424)
and [server pack](https://www.curseforge.com/minecraft/modpacks/all-the-mods-10/files/9431427)
from CurseForge. Third-party mod JARs and Minecraft files are not redistributed here.

All versions and checksums are under [Releases](https://github.com/keizuro/infection-network-releases/releases).
This repository contains public downloads and player instructions only. Project
source is maintained separately in a private repository. Never upload private
signing keys, credentials or player data here.
