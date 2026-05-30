# 🚀 Distro ISO Downloader v7.0

[![Pascal](https://img.shields.io/badge/Made%20with-Pascal-%23003a6f?style=flat-square)](https://www.freepascal.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=flat-square)]()

**A console downloader for ISO images of popular Linux and BSD distributions.**

Download official ISO files directly from developer servers — no browser, no extra clicks. Just a console, a menu, and a few keystrokes.

## ✨ What's new in version 7.0

- **Free disk space indicator** – always see how much space is left on the drive before downloading.
- **Batch download** – select multiple distributions and let the program download them one after another.
- **Mount ISO** – mount a downloaded image as a virtual drive without opening Explorer.
- **Checksum verification** – generate a `.sha256` checksum file **and** compare it against the expected value (when a local checksum file exists).
- **Visual improvements** – animated stars twinkle on the background, and a hidden ASCII cat watches your every move from the corner of the screen.
- **Legacy Ubuntu versions** – added Ubuntu 20.04, 18.04, 16.04 and 15.04 from `old‑releases.ubuntu.com`.

## 📦 Features

- 12 distributions to choose from (including FreeBSD, OpenBSD, NetBSD, CachyOS, Slackware and others)
- Direct ISO download from official mirrors (WinINet, no OpenSSL required)
- Real‑time speed, progress and file size display
- Automatic generation of SHA‑256 checksum files for integrity verification
- Copy ISO to a Ventoy‑prepared USB flash drive right after download
- Batch download of multiple distributions
- Mount ISO as a virtual drive
- Change the download folder without editing the config file manually
- Auto‑generated `welcome.html` on first launch
- **Secret cat easter egg** (try to find it 😉)

## 📜 Supported distributions

- Ubuntu 22.04 LTS
- Kubuntu 22.04 LTS
- Lubuntu 22.04 LTS
- CachyOS 260426
- Slackware 15.0
- FreeBSD 14.2
- OpenBSD 7.6
- NetBSD 10.1
- Ubuntu 20.04 LTS (legacy)
- Ubuntu 18.04 LTS (legacy)
- Ubuntu 16.04 LTS (legacy)
- Ubuntu 15.04 (legacy)

All images are downloaded from official servers or trusted mirrors.

## ⚡ Quick start

```bash
git clone https://github.com/winintern/Distro-louder.git
cd Distro-louder
fpc Main.pas
Main.exe
After launch, select the desired menu item and wait for the download to finish.
The ISO image will be saved to C:\Downloads (can be changed).

⚙️ Configuration
Settings are stored in downloader.cfg (created automatically). Example:

ini
[Paths]
SaveDir=C:\Downloads

[UI]
Theme=Dark

[Network]
UserAgent=DistroLoader/7.0
Retries=3

[Ventoy]
Drive=E
⚠️ Important disclaimer
I do not steal or misappropriate the product of Canonical, FreeBSD Foundation or other owners.
All intellectual property rights, distribution rights and trademarks belong to their respective owners.

This program is a non‑commercial project, created purely out of curiosity and a desire to help.
It does not modify or distribute pirated copies. ISO images are downloaded from official copyright holder servers.

On first launch, the program automatically creates a welcome.html file containing detailed documentation and the full disclaimer. Please read it before use.

📄 License
MIT — do whatever you want with the code, just keep the authorship notice.

Created with respect for Linux, BSD and love for Pascal.❤️
