<p align="center">
  <img src="https://raw.githubusercontent.com/mavksoft/scanner-macos-releases/main/logo.png" alt="Net-Analyzer Scanner" width="96">
</p>

<h1 align="center">Net-Analyzer Scanner for macOS</h1>

<p align="center">Ve cada dispositivo de tu red — desde la barra de menús de tu Mac.<br>Identificación de fabricante, Wake-on-LAN, alertas de nuevos dispositivos y herramientas de red integradas.</p>

<p align="center">
  <a href="https://scanner.net-analyzer.com"><img src="https://img.shields.io/badge/website-scanner.net--analyzer.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/scanner-macos-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/scanner-macos-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-macOS-black" alt="macOS">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/scanner-macos-releases/"><img src="https://img.shields.io/static/v1?label=docs&message=mavksoft.github.io/scanner-macos-releases&color=blue" alt="docs"></a></p>

<p align="center">🌍 <strong>🇪🇸 Español</strong> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Este repositorio publica únicamente releases oficiales** — el código fuente es privado. Descargas firmadas, checksums y feeds de auto-actualización.

## Descarga

| | |
|---|---|
| <img src='https://raw.githubusercontent.com/mavksoft/scanner-macos-releases/main/icons/apple.svg' width='15' style='vertical-align:-2px' alt='apple'> **Versión completa** | [Descargar el último DMG](https://github.com/mavksoft/scanner-macos-releases/releases/latest) — firmado y notarizado |
| <img src='https://raw.githubusercontent.com/mavksoft/scanner-macos-releases/main/icons/appstore.svg' width='15' style='vertical-align:-2px' alt='appstore'> **Mac App Store** | [Net-Analyzer — Escáner de red](https://apps.apple.com/es/app/net-analyzer-esc%C3%A1ner-de-red/id6746715754) |
| <img src='https://raw.githubusercontent.com/mavksoft/scanner-macos-releases/main/logo.png' width='15' style='vertical-align:-2px'> **Web oficial** | [scanner.net-analyzer.com](https://scanner.net-analyzer.com) |

## Qué es

Net-Analyzer Scanner es una app ligera de barra de menús que responde a la pregunta "¿qué hay conectado a mi Wi-Fi?" en segundos: descubre cada equipo de tu LAN, te dice quién lo fabricó y te avisa cuando aparece algo nuevo.

<p align="center"><img src="./screenshots/website.png" width="300" alt="screenshot"> <img src="./screenshots/ios-1.jpg" width="160" alt="screenshot"> <img src="./screenshots/ios-2.jpg" width="160" alt="screenshot"> <img src="./screenshots/ios-3.jpg" width="160" alt="screenshot"></p>

## Funciones

- **Descubrimiento completo** — Bonjour, SSDP, TCP, ARP, NDP, SNMP y SMB encuentran todo lo que hay en tu LAN.
- **Identificación de fabricante** — la base OUI te dice quién fabricó cada equipo (router, móvil, cámara, IoT…).
- **Alertas de nuevos dispositivos** — recibe un aviso cuando algo desconocido se une a tu red.
- **Wake-on-LAN** — despierta equipos a distancia con un clic.
- **Auditoría del router** — comprobaciones de seguridad contra tu puerta de enlace.
- **Herramientas de red** — ping, escaneo de puertos, histórico y notas por dispositivo.
- **Pensada para la barra de menús** — una app SwiftUI ligera que vive en la barra de menús.
- **Seis idiomas** — ES / EN / FR / IT / DE / PT, con actualizaciones gestionadas en remoto.

## Cómo se usa

1. Descarga el DMG, arrastra la app a Aplicaciones y ábrela.
2. El icono se instala en la barra de menús — pulsa y lanza un escaneo.
3. En segundos verás la lista de equipos: nombre, IP, MAC y fabricante.
4. Activa las alertas para enterarte cuando un dispositivo nuevo se conecte.
5. Usa Wake-on-LAN, ping o el escáner de puertos desde la ficha de cada equipo.

## Requisitos

macOS reciente · Apple Silicon e Intel (binario universal) · Firmado y notarizado por Apple.

## Qué contiene este repositorio

- `Scanner-Net-Analyzer-<versión>.dmg` — instalador firmado + notarizado
- `Scanner-Net-Analyzer-<versión>.zip` — archivo de actualización Sparkle (firmado EdDSA) para el auto-actualizador de la app
- La edición de Mac App Store se actualiza a través de la propia App Store.

[Última release](https://github.com/mavksoft/scanner-macos-releases/releases/latest)

## Preguntas frecuentes

**¿Por qué veo dispositivos "desconocidos"?**  
Muchos equipos no anuncian nombre ni servicios. El fabricante por MAC (OUI) suele dar la pista: busca "Apple", "Espressif" (IoT), "Samsung"…

**¿Puede despertar un PC apagado?**  
Sí, si el equipo tiene Wake-on-LAN activado en su BIOS/sistema y está en la misma red (o configurado para ello).

**¿Qué diferencia hay entre el DMG y la App Store?**  
La misma app; el DMG se actualiza con Sparkle y la edición App Store se actualiza vía Apple y va en sandbox.

## Soporte

- Web: [scanner.net-analyzer.com](https://scanner.net-analyzer.com)
- Email: [support@it-systems.es](mailto:support@it-systems.es)

---
<p align="center"><sub>Net-Analyzer Scanner for macOS · © MavkSoft / IT-Systems</sub></p>
