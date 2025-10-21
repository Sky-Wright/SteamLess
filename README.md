# SteamLess

**Run Windows applications on Linux using Proton - no Steam required**

[![Available on itch.io](https://img.shields.io/badge/Available%20on-itch.io-FA5C5C?style=for-the-badge&logo=itch.io&logoColor=white)](https://zivena.itch.io/steamless)
[![Support on Patreon](https://img.shields.io/badge/Support%20on-Patreon-FF424D?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/c/Sky_Wright)

---

## 🎉 LAUNCH SALE: $10 (regularly $25)

**Available now on [itch.io](https://zivena.itch.io/steamless)**

---

## What is SteamLess?

SteamLess is a comprehensive Proton-based Windows application launcher that provides a complete Wine replacement for Linux users. Using Steam's battle-tested Proton compatibility layer, SteamLess enables seamless execution of Windows games and applications directly on Linux without the complexity and maintenance overhead of traditional Wine installations.

**Commercial software with auditable source code** - Full transparency, no telemetry, no mystery binaries.

---

## Key Features

### Core Functionality
- **Launch Windows games and applications** with Proton (Steam's compatibility layer)
- **Works without Steam installed** (Steam installed = access to official Proton builds for even better compatibility)
- **Sideload any .exe into any prefix** - Right-click any app → "Sideload .exe" → run installers, patches, mods, dependencies (DirectX, .NET, VC++ redists), or any Windows executable directly in that app's environment. No winetricks, no terminal commands, no guessing which prefix to use
- **Automatic system setup** - Takes a fresh Linux install and makes it capable of running Windows software - handles all dependencies automatically
- **Universal Linux compatibility** - Extensively tested on Arch Linux, Ubuntu, and Linux Mint - should work on most modern distributions

### Desktop Integration
- **Right-click any .exe** → "Open with SteamLess" → guided setup wizard with dedicated prefix isolation
- Native file associations and MIME types
- Desktop shortcuts

### Advanced Features
- **Dual-boot save file synchronization** with conflict detection and resolution
- **Per-application environment variables** - GPU selection via DRI_PRIME, Vulkan ICD, or any custom vars you need
- **MangoHUD and Gamemode integration** - Toggle on/off per application
- **ISO and disc mounting** with drive letter mapping
- **Custom Windows drive mappings** for complex setups
- **Windows version selection** - XP through 11
- **Custom theming** - KDE Plasma auto-fusion, 4 built-in themes for other DEs

### Battle-Tested Apps
Extensively tested and confirmed working:
- **Game Launchers**: Battle.net, Epic Games Launcher, EA app, GOG Galaxy, Steam
- **Professional Tools**: Blender, Unity, UE5
- **Games**: FFXIV, Guild Wars 2, Black Desert Online, heavily modded Skyrim with Mod Organizer 2
- **And many more**

**Known Limitations**: Kernel-level anti-cheat (Fortnite, Valorant, Battlefield 6, etc...) won't work. This is a top level decision by the respective corporations to hard disable linux in these titles~ not a failure of SteamLess

---

## Why SteamLess?

After 26 years on Windows, I switched to Linux and fell in love with finally having control over my system. But running my heavily-modded game library and professional tools (Unity, Blender) through Wine and Lutris was a nightmare and some of my projects simply would not port to Linux native.

So I figured out how to use Proton directly with shell scripts, built a simple GUI for myself, and used it daily for 6+ months across two different distros and a GPU upgrade. It worked so well I realized other people need this too.

**SteamLess is the tool I built for myself and used every day before deciding to share it.**

---

## Installation

**[Download from itch.io](https://zivena.itch.io/steamless)**

1. Download the installer
2. Extract the zip file
3. Run `SteamLess-Installer`
4. Follow the setup wizard
5. Right-click any .exe file → "Open with SteamLess" to get started

---

## System Requirements

**For SteamLess itself:**
- Any modern Linux distribution (tested on Arch, Ubuntu, Mint)
- Minimal resources (Python + Tkinter - installer handles dependencies)

**For running Windows apps:**
- Same requirements as Proton/Steam
- Vulkan-compatible GPU recommended
- Actual requirements depend on the Windows software you're running (general rule of thumb is to match the windows requirements at bare minimal)

---

## Documentation

Complete documentation is included with your purchase and available after installation in the `docs/` folder.

For licensing terms, see the LICENSE file included in the download.

---

## Support & Bug Reports

Found a bug or have a feature request? Please [open an issue](https://github.com/Sky-Wright/SteamLess/issues) on GitHub.

---

## License

**All Rights Reserved** - Commercial software with auditable source code for transparency.

See [LICENSE](LICENSE) for complete terms.

---

## About the Developer

Built by an indie developer who switched to Linux and needed this to exist. Battle-tested daily for 6+ months before release.

**Find my work:**
- [itch.io](https://zivena.itch.io) - Commercial projects
- [GitHub](https://github.com/Sky-Wright) - Open source tools, documentation, and support
- [Patreon](https://www.patreon.com/c/Sky_Wright) - Support ongoing development

---

**One-time purchase. Free updates. No subscriptions. No DRM.**

**[Get SteamLess on itch.io](https://zivena.itch.io/steamless)**
