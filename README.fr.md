<p align="center">
  <img src="./logo.png" alt="Net-Analyzer Scanner" width="96">
</p>

<h1 align="center">Net-Analyzer Scanner for macOS</h1>

<p align="center">Voyez chaque appareil de votre réseau — depuis la barre de menus de votre Mac.<br>Identification du fabricant, Wake-on-LAN, alertes de nouveaux appareils et outils réseau intégrés.</p>

<p align="center">
  <a href="https://scanner.net-analyzer.com"><img src="https://img.shields.io/badge/website-scanner.net--analyzer.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/scanner-macos-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/scanner-macos-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-macOS-black" alt="macOS">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <strong>🇫🇷 Français</strong> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Ce dépôt publie uniquement les releases officielles** — le code source est privé. Téléchargements signés, sommes de contrôle et flux de mise à jour automatique.

## Téléchargement

| | |
|---|---|
| 📥 **Version complète** | [Télécharger le dernier DMG](https://github.com/mavksoft/scanner-macos-releases/releases/latest) — signé et notarisé |
| 🍎 **Mac App Store** | [Net-Analyzer — Scanner réseau](https://apps.apple.com/es/app/net-analyzer-esc%C3%A1ner-de-red/id6746715754) |
| 🌍 **Site officiel** | [scanner.net-analyzer.com](https://scanner.net-analyzer.com) |

## Qu'est-ce que c'est

Net-Analyzer Scanner est une app légère de barre de menus qui répond en quelques secondes à « qu'est-ce qui est connecté à mon Wi-Fi ? » : elle découvre chaque appareil du LAN, indique son fabricant et vous alerte quand un inconnu apparaît.

<p align="center"><img src="./screenshots/website.png" width="300" alt="screenshot"> <img src="./screenshots/ios-1.jpg" width="160" alt="screenshot"> <img src="./screenshots/ios-2.jpg" width="160" alt="screenshot"> <img src="./screenshots/ios-3.jpg" width="160" alt="screenshot"></p>

## Fonctionnalités

- **Découverte complète** — Bonjour, SSDP, TCP, ARP, NDP, SNMP et SMB trouvent tout sur votre LAN.
- **Identification du fabricant** — la base OUI indique qui a fabriqué chaque appareil (routeur, téléphone, caméra, IoT…).
- **Alertes de nouveaux appareils** — soyez prévenu quand un appareil inconnu rejoint le réseau.
- **Wake-on-LAN** — réveillez des machines à distance en un clic.
- **Audit du routeur** — vérifications de sécurité contre votre passerelle.
- **Outils réseau** — ping, scan de ports, historique et notes par appareil.
- **Pensée pour la barre de menus** — une app SwiftUI légère qui vit dans la barre de menus.
- **Six langues** — ES / EN / FR / IT / DE / PT, avec mises à jour gérées à distance.

## Mode d'emploi

1. Téléchargez le DMG, glissez l'app dans Applications et ouvrez-la.
2. L'icône s'installe dans la barre de menus — cliquez et lancez un scan.
3. En quelques secondes, la liste des appareils s'affiche : nom, IP, MAC et fabricant.
4. Activez les alertes pour être informé des nouvelles connexions.
5. Utilisez Wake-on-LAN, ping ou le scanner de ports depuis la fiche de chaque appareil.

## Configuration requise

macOS récent · Apple Silicon et Intel (binaire universel) · Signé et notarisé par Apple.

## Contenu de ce dépôt

- `Scanner-Net-Analyzer-<version>.dmg` — installateur signé + notarisé
- `Scanner-Net-Analyzer-<version>.zip` — archive de mise à jour Sparkle (signée EdDSA) pour l'auto-updater
- L'édition Mac App Store se met à jour via l'App Store.

[Dernière version](https://github.com/mavksoft/scanner-macos-releases/releases/latest)

## Questions fréquentes

**Pourquoi des appareils « inconnus » ?**  
Beaucoup d'appareils n'annoncent ni nom ni services. Le fabricant MAC (OUI) donne généralement la réponse — cherchez « Apple », « Espressif » (IoT), « Samsung »…

**Peut-elle réveiller un PC éteint ?**  
Oui, si Wake-on-LAN est activé dans le BIOS/système et que la machine est sur le même réseau (ou configurée pour).

**Différence entre le DMG et l'App Store ?**  
La même app ; le DMG se met à jour via Sparkle, l'édition App Store via Apple et tourne en sandbox.

## Assistance

- Site : [scanner.net-analyzer.com](https://scanner.net-analyzer.com)
- E-mail : [support@it-systems.es](mailto:support@it-systems.es)

---
<p align="center"><sub>Net-Analyzer Scanner for macOS · © MavkSoft / IT-Systems</sub></p>
