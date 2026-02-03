# Chronos - Android Launcher

<div align="center">
  <img width="100%" style="max-width: 800px;" alt="Chronos Launcher Banner" src="https://github.com/user-attachments/assets/88cf07d2-ba89-4250-96fc-10b80f836799" />

  <br>

  [![Android](https://img.shields.io/badge/Android-5.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/diegolix29/Chronos-Android-Launcher)
  [![Tech](https://img.shields.io/badge/Built%20With-.NET%20MAUI%20%2F%20Xamarin-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/en-us/apps/maui)
  [![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

</div>

**Chronos** is a high-performance, feature-rich Android launcher built specifically for gaming and multimedia enthusiasts. Developed with .NET MAUI and Xamarin.Android, it replaces your stock home screen with a seamless interface designed to unify your game library, emulators, and music collection into one cohesive experience.

---

## ✨ Key Highlights

### 🕹️ Universal RetroArch Integration
Chronos doesn't just launch RetroArch—it deeply integrates with it.
* **Complete Core Support:** From obscure classics like **Vectrex** to 16-bit powerhouses like **Sega CD**, Chronos handles launch arguments for the entire RetroArch library.
* **Unified Library:** Your RetroArch ROMs appear alongside your modern emulator games in one clean grid.

### ⬇️ Smart Emulator Fetching
Forget manually searching for APKs.
* **Auto-Installation:** The integrated **Setup Guide** and **Game Pages** detect if you are missing a required emulator.
* **One-Click Fetch:** Directly download and install supported emulators (like NetherSX2, Dolphin, Citra, etc.) from within the launcher.

---

## 📱 Features

### 🎮 Gaming Hub
* **Multi-Emulator Support:** Native launch support for industry leaders including NetherSX2, Dolphin, Citra, Yuzu, Mupen64Plus, MelonDS, Cemu, and many others.
* **Automated Library:** Scans your storage to categorize games and populate beautiful grid layouts.
* **SteamGridDB Integration:** Automatically fetches high-quality box art, backgrounds, and logos for your library.
* **Per-Game Configuration:** Customize launch settings, distinct QSS themes, and performance profiles for individual titles.

### 🎵 Multimedia System
* **Integrated Music Player:** A full-featured audio player with background playback support.
* **Bluetooth Media Controls:** Full support for external controllers and headsets.
* **Audio Downloader:** Built-in browser/utility to download MP3s directly to your library.

### 🎨 Customization & System
* **Advanced Theming:** Switch between Light/Dark modes or import your own **custom `.qss` stylesheets** for total visual control.
* **App Drawer:** A clean, optimized interface for standard Android applications.
* **Home Replacement:** Designed to function as your primary Android launcher (Home App).

---

## 🎯 Supported Emulators

Chronos automatically detects, configures, and can help install the following:

### Nintendo
| Console | Emulator | Package Name |
|---------|----------|--------------|
| **Switch** | Yuzu / Sudachi / Ryujinx | `org.yuzu.yuzu_emu` |
| **Switch** | Eden (Standard/Optimized) | `dev.eden.eden_emulator` |
| **Switch** | Citron | `org.citron.citron_emu` |
| **Wii U** | Cemu | `info.cemu.cemu` |
| **GC / Wii** | Dolphin (Official / MMJR2) | `org.dolphinemu.dolphinemu` |
| **3DS** | Citra (Nightly / MMJ) | `org.citra.citra_emu` |
| **DS** | MelonDS / DraStic | `me.magnum.melonds` |
| **N64** | Mupen64Plus AE | `org.mupen64plusae.v3.alpha` |
| **GBA** | VBA-M / GBA.emu / Pizza Boy | `org.vbam.vbam` |
| **GB/GBC** | Gearboy / GBC.emu | `it.ignazioc.gearboy` |

### Sony
| Console | Emulator | Package Name |
|---------|----------|--------------|
| **PS3** | PS3 (Aenu) | `aenu.aps3e` |
| **PS2** | NetherSX2 / AetherSX2 | `xyz.aethersx2.android` |
| **PS1** | DuckStation | `com.github.stenzek.duckstation` |
| **PSP** | PPSSPP | `org.ppsspp.ppsspp` |

### Other & Retro
| Console | Emulator | Package Name |
|---------|----------|--------------|
| **Xbox 360** | Xbox 360 (Aenu) | `aenu.ax360e.free` |
| **Universal** | **RetroArch** (All Cores) | `com.retroarch.aarch64` |

---

## 🚀 Quick Start

1.  **Download:** Get the latest APK from the [**Releases Page**](https://github.com/diegolix29/Chronos-Android-Launcher/releases).
2.  **Install:** Allow installation from unknown sources if prompted.
3.  **Permissions:** Grant Storage and Network permissions on first launch.
4.  **Setup Wizard:**
    * Follow the on-screen guide to select your game folders.
    * **Tip:** If you are missing an emulator, use the "Fetch" button in games page to download it immediately.
5.  **Enjoy:** Set Chronos as your default Home Launcher in Android settings.

---

## 📦 Requirements

* **OS:** Android 5.0 (Lollipop) or higher
* **Architecture:** ARM64 or ARMv7
* **Storage:** ~200 MB free space
* **Permissions:** Storage (Media/Files) & Network

## 🔗 Tech Stack

* **Core:** .NET MAUI / Xamarin.Android
* **Data:** Newtonsoft.Json
* **UI:** AndroidX AppCompat, Google Material Design
* **Media:** AndroidX Media & DocumentFile

---

<div align="center">
  <b>Made with ❤️ for the Android gaming community</b>
</div>
