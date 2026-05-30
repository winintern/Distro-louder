# 🚀 Distro ISO Downloader v6.0 (Console Edition)

[![Pascal](https://img.shields.io/badge/Made%20with-Pascal-%23003a6f?style=flat-square)](https://www.freepascal.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=flat-square)]()

**A console downloader for official ISO images of Linux and BSD distributions.**  
Downloads ISO files directly from copyright holder servers, without opening a browser or using intermediary websites.

## 📦 What is it and why

- Select the desired OS from a beautiful TUI menu
- The utility immediately starts downloading the ISO to `C:\Downloads`
- Shows a progress bar, download speed and status in real time
- Automatically creates SHA‑256 checksum files for integrity verification
- **Supports copying to a Ventoy‑prepared USB drive right after download**
- No ads, no unnecessary steps

Useful when:
- the official website is unavailable or overloaded, but you need to download the ISO quickly
- you are reinstalling the system and don't want to search for the link every time
- you just love the console and minimalism

## 🚫 Why Windows 11 was removed

In previous versions, a third‑party mirror was used to download Windows 11.  
**Due to concerns about copyright, Windows support has been completely removed.**  
The program now only works with distributions whose licences explicitly allow redistribution or direct downloading.  
This keeps the project safe and avoids any potential legal issues.

## 📜 Supported distributions

- **Ubuntu 22.04 LTS**
- **Kubuntu 22.04 LTS**
- **Lubuntu 22.04 LTS**
- **CachyOS 260426**
- **Slackware 15.0**
- **FreeBSD 14.2**
- **OpenBSD 7.6**
- **NetBSD 10.1**

All ISOs are downloaded from official mirrors or trusted sources.

## 🧪 Version history

| Version | Status |
|---------|--------|
| V6.0 (current) | Stable, Windows‑free |
| V5.x | Testing TUI, now abandoned |
| V4.0 | Stable, legacy |

## 🛠️ Requirements

- **Windows 10 / 11** (or another OS with WinAPI)
- [Free Pascal Compiler (FPC)](https://www.freepascal.org/) version **3.2.2** or higher

## ⚡ Quick start

```bash
git clone https://github.com/winintern/Distro-louder.git
cd distro-louder
fpc distro-louderV6.pas
distro-louderV6.exe

After launch, select the desired menu item and wait for the download to finish.
The ISO image will appear in the C:\Downloads folder.

💾 Ventoy support
After a successful download, the program can automatically copy the ISO to a Ventoy‑prepared USB flash drive.
Simply set the drive letter in downloader.cfg (or configure it interactively in the program), and the program will offer to copy the file.
Ventoy must be installed on the flash drive beforehand.
This way, you can create a multi‑boot USB stick without ever leaving the console.

🔧 How it works
The program is written in Object Pascal (Free Pascal).
Uses pure WinINet for downloading (no OpenSSL or other external dependencies).
Links to images point to official servers. You can easily add other versions or architectures if you wish.

📁 Where the file is saved
Images are saved to the C:\Downloads folder, which is created automatically.
Why there? Because the author decided so. It's simple, convenient, and you'll never lose the file.

⚠️ Important disclaimer
I do not steal or misappropriate the product of Canonical, FreeBSD Foundation or other owners.
All intellectual rights, distribution rights and trademarks belong to their respective owners.

The program is a non‑commercial project, created purely out of curiosity and a desire to help.
It does not modify or distribute pirated copies. ISO images are downloaded from official copyright holder servers.

On first launch, the program automatically creates a welcome.html file (in Russian and English), containing the full disclaimer text. Please read it before use.

📸 Animation and interface
During download you see:

A graphical progress bar [###...]

Real‑time speed (KB/s or MB/s)

File name and size

All this is wrapped in a retro‑style TUI with frames

The download process is not boring, but fascinating 😎

📝 From the author
I wrote this program in Pascal (Free Pascal).
It took me weeks of struggling with the compiler, HTTPS, WinINet and searching for working links.
But it was worth it: now you can download Linux or BSD with one click, without a browser.

I would be glad if you say thank you for my efforts — even if just mentally. Heh.

📁 Files
Main.exe — ready‑to‑use program

Main.pas — source code in Pascal

C:\Downloads\welcome.html — documentation (created automatically)

C:\Downloads\*.sha256 — checksum files (created automatically)
## 📧 Contact

For questions or suggestions, please contact: **[winitern1@gmail.com]**

📄 License
MIT — do whatever you want with the code, just keep the authorship notice.

Created with respect for Linux, BSD and love for Pascal.❤️
