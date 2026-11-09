# Infection Network — Downloads

Minecraft **1.21.1**, NeoForge **21.1.265**, original **ATM10 8.5** base.

## Windows launcher

[Download the Windows x64 launcher](https://github.com/keizuro/infection-network-releases/releases/download/stable/InfectionNetworkLauncher-Windows-x64.zip)

Run `InfectionNetwork.Launcher.exe`. Launcher **0.9.1** checks its signed self-update
when opened, then checks the signed Stable client profile before Play. English is
default; German is available in Settings. An existing ATM10 source may be selected,
or the launcher can install the official pack. Sign in to Microsoft inside Prism
yourself; account files and worlds are never copied between Stable and Beta.

## Standard Stable client: Building Utilities

Client profile **8.5.1** keeps all **494 original ATM10 8.5 mods** and automatically
adds these three client-only NeoForge releases:

- Forgematica **0.4.3+mc1.21.1**
- MaFgLib **0.4.3+mc1.21.1**
- Henny Fullbright **1.0** for NeoForge 1.21.1

**No manual mod downloads are needed.** Close Minecraft and Prism, reopen the
launcher, let its self-update finish, and use the normal Stable profile. The pack
update downloads the approved JARs from their pinned official Modrinth providers.
Missing or damaged owned addons are restored before launch. Compatible installed
files are reused; unknown conflicting extras require confirmation before backup
and disabling. Personal configs, schematics, shaders, resourcepacks and saves remain.

The three addons belong on the client only. They are not added to the dedicated
server. Stable does not include Spore, Infection Network or Squaremap. The separate
admin Beta channel is unchanged by this update; do not mix its game folder with Stable.

Further Minecraft/rendering/shader acceptance was cancelled at the owner's request;
these runtime functions remain unverified. Fullbright's default B binding can conflict
with existing controls; select an unused binding in the game's Controls menu.

## Sources and preservation

The original [ATM10 base profile](https://github.com/keizuro/infection-network-releases/releases/tag/profile-atm10-8.5-s13000001)
remains immutable. The new [Stable client profile](https://github.com/keizuro/infection-network-releases/releases/tag/profile-atm10-8.5-s13000002)
contains signed metadata and provider checksums. Third-party mod JARs and Minecraft
files are not rehosted here. [All releases](https://github.com/keizuro/infection-network-releases/releases)
contain public downloads only; project source is maintained in a private repository.
Never upload account files, tokens, private signing keys or player/world data here.
