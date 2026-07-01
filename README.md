# Skyrim SKSE Bridge Plugin

SKSE Bridge Plugin to use DLSS, FSR3, FSR2, and XeSS3 in Skyrim. Also supports FSR3 Frame Generation to improve upscale quality for the main mod.

This mod acts as the bridge between the Skyrim game engine and the **GamePlug Skyrim Mod**. Designed specifically for SKSE users, it runs as an SKSE plugin to extract direct engine data (such as depth and motion vectors) and pass them to the main upscaler mod while the game is running, enhancing the reconstruction quality.

> [!NOTE]
> The main mod can function with or without this plugin; this bridge plugin is entirely **optional**, but highly recommended to achieve the best image quality. It also opens the door for future feature expansions.

---

## Main Features

- **Upscalers:** DLSS, FSR3, XeSS3, FSR2
- **Frame Generation:** FSR3 Frame Generation support
- **Nvidia Reflex** support
- **DLSS Preset** configuration

---

## Requirements

### Required Core Mods
- **Main Mod**: [GamePlug Skyrim Mod (Nexus Mods)](https://www.nexusmods.com/skyrimspecialedition/mods/180855)
- **Upscaler Plugin**: [upscaler-plugin-d3d11-d3d12](https://github.com/gameplug-labs/upscaler-plugin-d3d11-d3d12)
- **SKSE64 (Skyrim Script Extender)**: [Nexus Mods](https://www.nexusmods.com/skyrimspecialedition/mods/30379)
- **Address Library for SKSE Plugins**: [Nexus Mods](https://www.nexusmods.com/skyrimspecialedition/mods/32444)
- **SSE Display Tweaks**: [Nexus Mods](https://www.nexusmods.com/skyrimspecialedition/mods/34705)

### Optional (Download required files for your preferred upscaling type)
- **FSR2 v2.2.1 files**: [FidelityFX FSR2 DX11 Releases](https://github.com/gameplug-labs/FidelityFX-FSR2-DX11/releases/tag/v2.2.1)
- **FSR3 v3.1.2 files**: [FidelityFX SDK Releases](https://github.com/gameplug-labs/FidelityFX-SDK/releases/tag/fsr3-v3.1.2)
- **DLSS files**: [NVIDIA Streamline Releases](https://github.com/NVIDIA-RTX/Streamline/releases/tag/v2.11.1)
- **XeSS3 files**: [Intel XeSS Releases](https://github.com/intel/xess/releases/tag/v3.0.1)

---

## Installation

1. **Download the plugin files.**
2. **Extract the folder** directly into your main Skyrim game directory so that the plugin resolves to the following path:
   ```
   Skyrim\Data\SKSE\Plugins\
   ```
3. **Launch the game** using the SKSE64 bootloader.

---

## Framework

Powered by [GamePlug](https://github.com/gameplug-labs).

Join the [GamePlug Discord](https://discord.gg/TyyDD3C7wQ) for announcements, news, and new features!
