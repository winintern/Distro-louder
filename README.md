🚀 Distro-louder v8.2
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![FPC](https://img.shields.io/badge/FPC-3.2.2-blue.svg)](https://www.freepascal.org/)
[![Windows](https://img.shields.io/badge/Platform-Windows-0078D6.svg)](https://www.microsoft.com/windows)
[![Status](https://img.shields.io/badge/Status-Stable-brightgreen.svg)]()

Console ISO downloader for Linux & BSD distributions
No bullshit, just downloads from official sources.

✨ What's new in v8.2?
Why 8.2, not 8.1?
Version 8.1 worked but had two annoying problems:

Laggy comets – the star animation made the menu sluggish.

Dead links – old Ubuntu (16.04, 18.04, 20.04) and some BSD releases stopped working.

v8.2 fixes that:

✅ Comets are now rare and non‑blocking (2% chance, no background loops).

✅ Replaced broken links with working ones: FreeBSD 13.5, Alpine Linux, Debian 12, Fedora 40, Manjaro 24 (note: some may fail due to server redirects – not a program bug).

✅ Easter egg – press Ctrl+U to download Ubuntu 15.04 (hidden treasure).

✅ Checksum verification temporarily disabled for speed and stability (will be back later).

✅ Full 12‑item menu with automatic sorting into subfolders (Ubuntu, BSD, Debian, etc.).

Why is the code smaller now?
I intentionally reduced the source size to:

Make debugging faster and easier.

Speed up compilation.

Reduce chance of random side‑effect bugs.

All core features are still there:
⬇️ ETA & speed display
⏸️ Pause & resume (P key)
📁 Batch download
💿 ISO mounting (Windows native)
💾 Copy to Ventoy
⭐ Animated stars (smooth)
🐱 Secret cat easter egg (Ctrl+K)

🖥️ How to compile & run
bash
git clone https://github.com/winintern/Distro-louder.git
cd Distro-louder
fpc distro-louderV8.2.pas
distro-louderV8.2.exe
Requires Free Pascal Compiler 3.2.2 or newer.

📫 Feedback & bug reports
If you have questions or find a bug, please write to:
winitern1@gmail.com

📜 Notice
This is a non‑commercial personal project.
All trademarks belong to their respective owners.
ISO files are downloaded directly from official sources – no piracy, no redistribution.

🙏 Thanks
For using, testing
