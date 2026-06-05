# 🐧# Distro-louder v8.3

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![FPC](https://img.shields.io/badge/FPC-3.2.2-blue.svg)](https://www.freepascal.org/)
[![Windows](https://img.shields.io/badge/Platform-Windows-0078D6.svg)](https://www.microsoft.com/windows)
[![Status](https://img.shields.io/badge/Status-Stable-brightgreen.svg)]()

Console ISO downloader for Linux and BSD distributions.  
Downloads official ISOs directly from developers' servers. No bullshit.

---

## Features

- Keyboard-driven TUI with starry background  
- Real-time download info: progress bar, speed, ETA  
- Pause and resume (P key)  
- Batch download (select multiple ISOs)  
- Mount ISO as virtual drive (Windows native)  
- Copy to Ventoy USB (configurable)  
- Automatic sorting into subfolders (Ubuntu, BSD, Arch, etc.)  
- Event logging to `download.log`  
- Configurable via `downloader.cfg`  
- Screen saver after 60 seconds of inactivity  
- State icons: `[✓]` for downloaded ISOs  

---

## Supported distributions (v8.3)

| Distribution   | Version / Release          |
|----------------|----------------------------|
| Ubuntu         | 22.04 LTS                  |
| Kubuntu        | 22.04 LTS                  |
| Lubuntu        | 22.04 LTS                  |
| CachyOS        | 260426                     |
| Slackware      | 15.0                       |
| FreeBSD        | 13.5                       |
| OpenBSD        | 7.6                        |
| NetBSD         | 10.1                       |
| Arch Linux     | 2026.06.01 (rolling)       |
| Rocky Linux    | 9.6                        |
| Void Linux     | musl 20250401              |
| Alpine Linux   | 3.19                       |

---

## How to get it

### Pre-compiled EXE  
Download from [Releases](https://github.com/winintern/Distro-louder/releases).

### Compile from source  
Requires [Free Pascal Compiler](https://www.freepascal.org/) 3.2.2 or newer.

```bash
git clone https://github.com/winintern/Distro-louder.git
cd Distro-louder
fpc distro-louderV8.3.pas
distro-louderV8.3.exe
---
## 📥 How to get it

### Option 1: Download pre‑compiled EXE
Grab the latest `distro-louderV8.2.exe` from the [Releases page](https://github.com/winintern/Distro-louder/releases).

### Option 2: Compile from source
Requires [Free Pascal Compiler](https://www.freepascal.org/) 3.2.2 or newer.

```bash
git clone https://github.com/winintern/Distro-louder.git
cd Distro-louder
fpc distro-louderV8.2.pas
distro-louderV8.2.exe

---
🎮 How to use

1. Run distro-louderV8.2.exe.
2. Use arrow keys (↑/↓) to select a distribution.
3. Press Enter to start downloading.
4. During download:
   · Press P to pause/resume.
   · Press Q to cancel.
5. After download, you can copy the ISO to a Ventoy USB or mount it directly.

Additional menu options (press number keys 1‑4):

· 1 – Verify checksum (disabled in v8.2, will be back)
· 2 – Change download directory
· 3 – Batch download
· 4 – Mount existing ISO as virtual drive

Easter eggs:

· Ctrl+K – secret cat that watches your choice and meows.
· Ctrl+U – download Ubuntu 15.04 (hidden classic).

---

⚙️ Configuration

On first run, downloader.cfg is created. Edit it to change:

```ini
[Paths]
SaveDir=C:\Downloads

[UI]
Theme=Dark   ; Dark/Light/Orange

[Network]
UserAgent=DistroLoader/8.2
Retries=3

[Ventoy]
Drive=E      ; Drive letter of your Ventoy USB
```

---

🐞 Feedback & bug reports

If you find a bug or have a question, please write to:
📧 winitern1@gmail.com

---

📜 Legal notice

This is a non‑commercial personal project.
All trademarks (Ubuntu, Kubuntu, Lubuntu, CachyOS, Slackware, FreeBSD, OpenBSD, NetBSD, Debian, Fedora, Manjaro, Alpine) belong to their respective owners.
ISO files are downloaded directly from official sources – no piracy, no redistribution.
The author does not claim any affiliation with or endorsement by any of the trademark holders.

---

📄 License

Distributed under the MIT License. See LICENSE file for details.
Do whatever you want with the code, just keep the authorship notice.

---
Made with ❤️







