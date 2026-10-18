<p align="center">
  <img src="https://raw.githubusercontent.com/mavksoft/scanner-macos-releases/main/logo.png" alt="Net-Analyzer Scanner" width="96">
</p>

<h1 align="center">Net-Analyzer Scanner for macOS</h1>

<p align="center">See every device on your network — right from your Mac's menu bar.<br>Vendor identification, Wake-on-LAN, new-device alerts and built-in network tools.</p>

<p align="center">
  <a href="https://scanner.net-analyzer.com"><img src="https://img.shields.io/badge/website-scanner.net--analyzer.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/scanner-macos-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/scanner-macos-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-macOS-black" alt="macOS">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/scanner-macos-releases/"><img src="https://img.shields.io/badge/docs-mavksoft.github.io%2Fscanner-macos-releases-blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <strong>🇬🇧 English</strong> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **This repository publishes official binary releases only** — the source code is private. Signed downloads, checksums and auto-update feeds.

## Download

| | |
|---|---|
| <img src='https://raw.githubusercontent.com/mavksoft/scanner-macos-releases/main/icons/apple.svg' width='15' style='vertical-align:-2px' alt='apple'> **Full version** | [Download the latest DMG](https://github.com/mavksoft/scanner-macos-releases/releases/latest) — signed & notarized |
| <img src='https://raw.githubusercontent.com/mavksoft/scanner-macos-releases/main/icons/appstore.svg' width='15' style='vertical-align:-2px' alt='appstore'> **Mac App Store** | [Net-Analyzer — Network scanner](https://apps.apple.com/es/app/net-analyzer-esc%C3%A1ner-de-red/id6746715754) |
| <img src='https://raw.githubusercontent.com/mavksoft/scanner-macos-releases/main/logo.png' width='15' style='vertical-align:-2px'> **Website** | [scanner.net-analyzer.com](https://scanner.net-analyzer.com) |

## What it is

Net-Analyzer Scanner is a lightweight menu-bar app that answers "what's connected to my Wi-Fi?" in seconds: it discovers every device on your LAN, tells you who made it, and alerts you when something new shows up.

<p align="center"><img src="./screenshots/website.png" width="300" alt="screenshot"> <img src="./screenshots/ios-1.jpg" width="160" alt="screenshot"> <img src="./screenshots/ios-2.jpg" width="160" alt="screenshot"> <img src="./screenshots/ios-3.jpg" width="160" alt="screenshot"></p>

## Features

- **Full device discovery** — Bonjour, SSDP, TCP, ARP, NDP, SNMP and SMB scanning finds everything on your LAN.
- **Vendor identification** — the OUI database tells you who made each device (router, phone, camera, IoT…).
- **New-device alerts** — get notified when something unknown joins your network.
- **Wake-on-LAN** — wake machines remotely with one click.
- **Router audit** — security checks against your gateway.
- **Network tools** — ping, port scan, history and per-device notes.
- **Menu-bar first** — a lightweight SwiftUI app that lives in the menu bar.
- **Six languages** — ES / EN / FR / IT / DE / PT, with remotely managed updates.

## How to use it

1. Download the DMG, drag the app to Applications and open it.
2. The icon sits in the menu bar — click it and run a scan.
3. Within seconds you get the device list: name, IP, MAC and vendor.
4. Enable alerts to be told when a new device connects.
5. Use Wake-on-LAN, ping or the port scanner from each device's card.

## Requirements

Recent macOS · Apple Silicon & Intel (universal binary) · Signed & notarized by Apple.

## What's in this repository

- `Scanner-Net-Analyzer-<version>.dmg` — signed + notarized installer
- `Scanner-Net-Analyzer-<version>.zip` — Sparkle update archive (EdDSA-signed) used by the in-app auto-updater
- The App Store edition is updated through the App Store itself.

[Latest release](https://github.com/mavksoft/scanner-macos-releases/releases/latest)

## FAQ

**Why do I see "unknown" devices?**  
Many devices don't advertise a name or services. The MAC vendor (OUI) usually gives it away — look for "Apple", "Espressif" (IoT), "Samsung"…

**Can it wake a powered-off PC?**  
Yes, if the machine has Wake-on-LAN enabled in BIOS/OS and is on the same network (or configured accordingly).

**What's the difference between the DMG and the App Store build?**  
Same app; the DMG updates via Sparkle while the App Store edition updates through Apple and runs sandboxed.

## Support

- Website: [scanner.net-analyzer.com](https://scanner.net-analyzer.com)
- Email: [support@it-systems.es](mailto:support@it-systems.es)

---
<p align="center"><sub>Net-Analyzer Scanner for macOS · © MavkSoft / IT-Systems</sub></p>
