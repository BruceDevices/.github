<div align="center">

<img src="https://raw.githubusercontent.com/BruceDevices/firmware/main/media/pictures/bruce_banner.jpg" alt="Bruce" width="100%" />

# Bruce

**The open-source ESP32 firmware that turns your device into the ultimate multi-tool.**

Debug your gear, probe the airwaves, and learn how wireless really works. All from your pocket.

True open-source · Cross-platform · Pocket-sized.

## Currently we Support

**WiFi (2.4/5GHz) · BLE · Sub-GHz · nRF24 · NFC / RFID · IR · LoRa · GPS · FM · iButton · BadUSB**

<a href="https://bruce.computer"><img src="https://img.shields.io/badge/Website-bruce.computer-6f2da8?style=for-the-badge" alt="Website"></a>
<a href="https://bruce.computer/flasher"><img src="https://img.shields.io/badge/Flash_it-Web_Installer-00b3a4?style=for-the-badge" alt="Web Flasher"></a>
<a href="https://wiki.bruce.computer"><img src="https://img.shields.io/badge/Docs-Wiki-2d7dd2?style=for-the-badge" alt="Wiki"></a>
<a href="https://discord.gg/WJ9XF9czVT"><img src="https://img.shields.io/badge/Community-Discord-5865F2?style=for-the-badge" alt="Discord"></a>

<a href="https://github.com/BruceDevices/firmware"><img src="https://img.shields.io/github/stars/BruceDevices/firmware?style=social" alt="Stars"></a>
<img src="https://img.shields.io/badge/license-AGPL--3.0-blue" alt="License">
<img src="https://img.shields.io/badge/hardware-CERN--OHL--P--2.0-orange" alt="Hardware License">

</div>

---

## What is Bruce?

Bruce is a versatile ESP32 firmware packed with offensive-security tooling, built to make Red Team operations fast, portable, and open. One firmware, dozens of boards, from a keychain-sized M5StickC to our own **RF Reaper** dev board.

Everything here is open source: the firmware, the apps, the app store, the tooling, and the PCBs.

---

## Our Boards

We also design and sell some hardware built for Bruce from the ground up.

<table>
<tr>
<td width="50%" align="center" valign="top">

### RF Reaper

<img src="https://bruce.computer/img/reaper-pcb.png" width="260" /><br>
Our flagship dev board. ESP32-S3 (16MB Flash / 8MB PSRAM) with Sub-GHz (CC1101), 2.4GHz (nRF24), NFC/RFID, IR, iButton, GPS-ready and microSD. Flipper-friendly.

<a href="https://shop.bruce.computer"><img src="https://img.shields.io/badge/%20BUY%20RF%20REAPER%20-%E2%86%92-6f2da8?style=for-the-badge&logo=shopify&logoColor=white" alt="Buy RF Reaper" height="42"></a><br>
<sub>Official store · ships worldwide via Elecrow</sub>

</td>
<td width="50%" align="center" valign="top">

### Bruce PCB V2

<img src="https://bruce.computer/img/bruce-pcb.png" width="260" /><br>
ESP32-S3-WROOM-1 NF, 16MB Flash / 8MB Octal PSRAM, long-range RF modules (E07-433M20S, E01-2G4M27SX) and a GPIO extender. By Smoochiee.

<a href="https://www.elecrow.com/bruce-pcb-v2-smoochiee-1.html"><img src="https://img.shields.io/badge/%20BUY%20ON%20ELECROW%20-%E2%86%92-00b3a4?style=for-the-badge&logo=shopify&logoColor=white" alt="Buy Smoochiee V2 on Elecrow" height="42"></a>
<a href="https://www.pcbway.com/project/shareproject/Bruce_PCB_Smoochiee_d6a0284b.html"><img src="https://img.shields.io/badge/%20BUY%20ON%20PCBWAY%20-%E2%86%92-e8480c?style=for-the-badge&logo=kicad&logoColor=white" alt="Buy Smoochiee V2 on PCBWay" height="42"></a><br>
<sub>Official stores · ships worldwide</sub>

</td>
</tr>
</table>

Community hardware lives in [BruceDevices/PCBs](https://github.com/BruceDevices/PCBs), including the **Bruce Ultramarines** (M5Stick-compatible) and the **Pirata PCB** (M5StickC Plus with nRF24 and CC1101).

---

## Supported Devices

Bruce runs on a growing family of boards. The [Web Flasher](https://bruce.computer/flasher) always has the current builds.

| Vendor | Boards |
|---|---|
| **M5Stack** | Cardputer · StickC-Plus 1.1 · StickC-Plus 2 · StickS3 · Core (4MB / 16MB) · Core2 · CoreS3 · DinMeter |
| **LILYGO** | T-Deck · T-Deck Pro · T-Display-S3 (+ Touch / MMC) · T-Display-S3 Pro · T-Display TTGO · T-Embed · T-Embed CC1101 · T-HMI · T-LoRa Pager · T-Watch-S3 |
| **CYD** (Cheap Yellow Display) | 2432S028 · 2432W328C · 2432W328R / S024R · 2USB · 3248S035C · 3248S035R · NM-CYD-C5 |
| **Elecrow** | 24B · 28B · Advance 3.5" S3 |
| **ESP32-C5** | ESP32-C5 · ESP32-C5 TFT |
| **Marauder** | Mini · V4–V6 · v61 · v7 |
| **Bruce / Community** | RF Reaper · Smoochiee (Bruce PCB V2) · Phantom S024R · WaveSentry R1 · Awok Mini · Awok Touch · Arduino Nesso N1 · ESP32-S3 DevKitC |

---

## Features

**WiFi:** port/host scanning, AP mode, deauth, beacon spam, evil portal, packet sniffing, ARP spoof, LLMNR Poisoning, SSH/Telnet, WireGuard, Raw TCP Socket Client/Listener, Brucegotchi

**BLE:** scanning, BadBLE scripts, keyboard emulation, device spam (iOS / Windows / Samsung / Android)

**Sub-GHz (RF):** scan, copy, replay, spectrum analysis, jamming, CC1101

**RFID / NFC:** read, clone, NDEF write, Amiibo

**IR:** TV-B-Gone, custom protocols (NEC, SIRC, Samsung32, RC5/RC6)

**More:** FM broadcast, nRF24 jamming, iButton, BadUSB, QR codes, SD manager, WebUI, and a full JavaScript interpreter with its own [app store](https://bruce.computer/appstore)

---

## Get Started

1. Plug your board in and open the **[Web Flasher](https://bruce.computer/flasher)**, no toolchain needed
2. M5Stack users can OTA via M5Launcher / m5burner
3. Read the **[Wiki](https://wiki.bruce.computer)** and the **[FAQ](https://wiki.bruce.computer/faq/)**
4. Join our communities
5. Build your own apps with **[bruce-js-tooling](https://github.com/BruceDevices/bruce-js-tooling)**

---

## Repositories

| Repo | What it is |
|---|---|
| [**firmware**](https://github.com/BruceDevices/firmware) | The core ESP32 firmware (C++) |
| [**App**](https://github.com/BruceDevices/App) · [**App-IOS**](https://github.com/BruceDevices/App-IOS) | Companion apps for Android & iOS |
| [**Wiki**](https://github.com/BruceDevices/Wiki) | Documentation |
| [**App-Store**](https://github.com/BruceDevices/App-Store) · [**App-Store-Apps**](https://github.com/BruceDevices/App-Store-Apps) | The JS app store and its apps |
| [**bruce-js-tooling**](https://github.com/BruceDevices/bruce-js-tooling) | Types & tools for building Bruce apps |
| [**Compile-JS**](https://github.com/BruceDevices/Compile-JS) | Compiles Bruce JS into bytecode |
| [**PCBs**](https://github.com/BruceDevices/PCBs) | Open hardware designs |

---

## Community

<a href="https://discord.gg/WJ9XF9czVT"><img src="https://bruce.computer/img/discord.svg" width="34"></a> &nbsp;
<a href="https://youtube.com/@Bruce-fw"><img src="https://bruce.computer/img/youtube.svg" width="34"></a> &nbsp;
<a href="https://reddit.com/r/brucefw"><img src="https://bruce.computer/img/reddit.svg" width="34"></a> &nbsp;
<a href="https://www.instagram.com/bruce_firmware/"><img src="https://bruce.computer/img/instagram.svg" width="34"></a> &nbsp;
<a href="https://matrix.to/#/#general:matrix.bruce.computer"><img src="https://bruce.computer/img/matrix.svg" width="34"></a>

[Discord](https://discord.gg/WJ9XF9czVT) · [YouTube](https://youtube.com/@Bruce-fw) · [Reddit](https://reddit.com/r/brucefw) · [Instagram](https://www.instagram.com/bruce_firmware/) · [Matrix](https://matrix.to/#/#general:matrix.bruce.computer) · [Forum](https://forum.bruce.computer) · [contact@bruce.computer](mailto:contact@bruce.computer)

---

## Support Bruce

Bruce is free and open source, built by the community. If it is useful to you, please consider supporting continued development.

<div align="center">
<a href="https://bruce.computer/donate"><img src="https://img.shields.io/badge/%20Donate%20-%E2%9D%A4-e2306c?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="Donate" height="42"></a>
<br><sub>bruce.computer/donate</sub>
</div>

---

<div align="center">

Firmware licensed **AGPL-3.0** · Most of Hardware licensed **CERN-OHL-P-2.0**

**For authorized security testing and education only.** You are responsible for how you use it.

</div>
