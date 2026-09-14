# cslol-manager

> **⚠️ Maintenance Mode:** cslol-manager is currently in maintenance/deprecation mode.
> Significant new features and development have shifted to the new [LTK Manager](https://github.com/LeagueToolKitts/ltk-manager).

A mod manager for **League of Legends** that allows you to install, manage and apply custom mods easily.

## 📥 Download

Go to the [Releases](https://github.com/LeagueToolKitts/cslol-manager/releases) page and download the latest version for your platform:

- `cslol-manager-windows.exe` — Windows installer
- `cslol-manager-macos.tar.xz` — macOS archive

## 🚀 Features

- Install and manage League of Legends mods
- Enable/disable mods without reinstalling
- Profile system to switch between mod sets
- Supports WAD-based mods

## 🛠️ Build from Source

```bash
cmake -B build -S .
cmake --build build --config Release
```

**Requirements:** Qt 6, CMake 3.16+

## 📂 Project Structure

```
src/        — C++ & QML source files
dist/       — Distribution scripts and tools
docs/       — Documentation and screenshots
```

## 📄 License

This project is open source. See source files for details.
