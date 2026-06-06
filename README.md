# 🪐 Distro-louder v8.5 – *interstellar ISO transporter*
. .
. .
. .
| _ | _ |_ | | _ \
| |) | |) || | | | | |
| __/| _ < | | | || |
|| || ____| |____/

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![FPC](https://img.shields.io/badge/FPC-3.2.2-blue.svg)](https://www.freepascal.org/)
[![Windows](https://img.shields.io/badge/Platform-Windows-0078D6.svg)](https://www.microsoft.com/windows)

> *Beam down official Linux/BSD ISOs from orbit*

---

## 🌠 Mission features

- **🕹️ TUI cockpit** – arrow keys, starfield, responsive  
- **📡 Live telemetry** – speed, ETA, progress bar  
- **⏸️ Pause / resume** – `P` to hold orbit  
- **📦 Batch delivery** – auto‑skip existing ISOs  
- **💾 Ventoy dock** – copy ISO to USB with one click  
- **🔗 Custom cargo** – download any .iso with history  
- **⏰ Scheduled drops** – create .bat + Task Scheduler (run once, self‑delete)  
- **🕒 Stardate** – clock + download counters (Today/Total)  
- **🛡️ Safety shields** – clear warnings before any risky action  

---

## 🪐 Supported galaxies

Ubuntu 22.04 · Kubuntu 22.04 · Lubuntu 22.04 · CachyOS 260426 · Slackware 15.0 · FreeBSD 13.5 · OpenBSD 7.6 · NetBSD 10.1 · Arch Linux (2026.06.01) · Rocky Linux 9.6 · Void Linux (musl) · Alpine 3.19  

*All ISOs beamed from official sources.*

---

## 🚀 Launch sequence

### Pre‑compiled EXE  
[Download from Releases](https://github.com/winintern/Distro-louder/releases)

### Build from source  
Requires [Free Pascal Compiler](https://www.freepascal.org/) 3.2.2+  
```bash
git clone https://github.com/winintern/Distro-louder.git
cd Distro-louder
fpc distro-louderV8.5.pas
distro-louderV8.5.exe
🎮 Controls
Key	Action
↑ ↓	Select distribution
Enter	Start download
P	Pause / resume
C	Custom ISO (with history)
S	Schedule download
1–4 / F1–F4	Extra actions
Q	Quit
⚠️ Flight safety notice
Custom URLs – you are the captain. Verify the source before launch.

Scheduled downloads – the program creates a .bat file. Run it as Administrator to register a one‑time task in Task Scheduler. The task will delete itself after execution (/z).

The author assumes no liability for any damage, data loss, or legal issues resulting from misuse.

📜 License
MIT – free as space. Keep the original copyright notice
