<p align="center">
  <img src="https://raw.githubusercontent.com/mavksoft/scanner-macos-releases/main/logo.png" alt="Net-Analyzer Scanner" width="96">
</p>

<h1 align="center">Net-Analyzer Scanner for macOS</h1>

<p align="center">Vedi ogni dispositivo della tua rete — direttamente dalla barra dei menu del Mac.<br>Identificazione del produttore, Wake-on-LAN, avvisi sui nuovi dispositivi e strumenti di rete integrati.</p>

<p align="center">
  <a href="https://scanner.net-analyzer.com"><img src="https://img.shields.io/badge/website-scanner.net--analyzer.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/scanner-macos-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/scanner-macos-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-macOS-black" alt="macOS">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/scanner-macos-releases/"><img src="https://img.shields.io/badge/docs-mavksoft.github.io%2Fscanner-macos-releases-blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <strong>🇮🇹 Italiano</strong> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Questo repository pubblica solo release binarie ufficiali** — il codice sorgente è privato. Download firmati, checksum e feed di aggiornamento automatico.

## Download

| | |
|---|---|
| <img src='https://raw.githubusercontent.com/mavksoft/scanner-macos-releases/main/icons/apple.svg' width='15' style='vertical-align:-2px' alt='apple'> **Versione completa** | [Scarica l'ultimo DMG](https://github.com/mavksoft/scanner-macos-releases/releases/latest) — firmato e notarizzato |
| <img src='https://raw.githubusercontent.com/mavksoft/scanner-macos-releases/main/icons/appstore.svg' width='15' style='vertical-align:-2px' alt='appstore'> **Mac App Store** | [Net-Analyzer — Scanner di rete](https://apps.apple.com/es/app/net-analyzer-esc%C3%A1ner-de-red/id6746715754) |
| <img src='https://raw.githubusercontent.com/mavksoft/scanner-macos-releases/main/logo.png' width='15' style='vertical-align:-2px'> **Sito ufficiale** | [scanner.net-analyzer.com](https://scanner.net-analyzer.com) |

## Che cos'è

Net-Analyzer Scanner è un'app leggera da barra dei menu che risponde in pochi secondi a «cosa c'è connesso al mio Wi-Fi?»: scopre ogni dispositivo della LAN, dice chi lo ha prodotto e avvisa quando compare qualcosa di nuovo.

<p align="center"><img src="./screenshots/website.png" width="300" alt="screenshot"> <img src="./screenshots/ios-1.jpg" width="160" alt="screenshot"> <img src="./screenshots/ios-2.jpg" width="160" alt="screenshot"> <img src="./screenshots/ios-3.jpg" width="160" alt="screenshot"></p>

## Funzionalità

- **Scoperta completa** — Bonjour, SSDP, TCP, ARP, NDP, SNMP e SMB trovano tutto sulla LAN.
- **Identificazione del produttore** — il database OUI dice chi ha costruito ogni dispositivo (router, telefono, telecamera, IoT…).
- **Avvisi sui nuovi dispositivi** — ricevi una notifica quando qualcosa di sconosciuto entra in rete.
- **Wake-on-LAN** — sveglia le macchine a distanza con un clic.
- **Audit del router** — controlli di sicurezza contro il gateway.
- **Strumenti di rete** — ping, scansione porte, cronologia e note per dispositivo.
- **Pensata per la barra dei menu** — un'app SwiftUI leggera che vive nella barra.
- **Sei lingue** — ES / EN / FR / IT / DE / PT, con aggiornamenti gestiti da remoto.

## Come si usa

1. Scarica il DMG, trascina l'app in Applicazioni e aprila.
2. L'icona si installa nella barra dei menu — clicca e avvia una scansione.
3. In pochi secondi vedi la lista dei dispositivi: nome, IP, MAC e produttore.
4. Attiva gli avvisi per sapere quando un nuovo dispositivo si connette.
5. Usa Wake-on-LAN, ping o lo scanner di porte dalla scheda di ogni dispositivo.

## Requisiti

macOS recente · Apple Silicon e Intel (binario universale) · Firmato e notarizzato da Apple.

## Cosa contiene questo repository

- `Scanner-Net-Analyzer-<versione>.dmg` — installer firmato + notarizzato
- `Scanner-Net-Analyzer-<versione>.zip` — archivio di aggiornamento Sparkle (firmato EdDSA) per l'auto-updater
- L'edizione Mac App Store si aggiorna tramite l'App Store.

[Ultima release](https://github.com/mavksoft/scanner-macos-releases/releases/latest)

## Domande frequenti

**Perché vedo dispositivi "sconosciuti"?**  
Molti dispositivi non annunciano né nome né servizi. Il produttore MAC (OUI) di solito dà la risposta — cerca "Apple", "Espressif" (IoT), "Samsung"…

**Può svegliare un PC spento?**  
Sì, se Wake-on-LAN è attivo nel BIOS/sistema e la macchina è sulla stessa rete (o configurata per esserlo).

**Differenza tra DMG e App Store?**  
La stessa app; il DMG si aggiorna via Sparkle, l'edizione App Store tramite Apple e gira in sandbox.

## Assistenza

- Sito: [scanner.net-analyzer.com](https://scanner.net-analyzer.com)
- Email: [support@it-systems.es](mailto:support@it-systems.es)

---
<p align="center"><sub>Net-Analyzer Scanner for macOS · © MavkSoft / IT-Systems</sub></p>
