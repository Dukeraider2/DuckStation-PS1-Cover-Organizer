# 🎮 DuckStation PS1 Cover Organizer Add-on

This script-based add-on resizes and organizes PlayStation 1 cover art downloaded via DuckStation’s built-in tool. It prepares covers in a **PS3-compatible 512x512 JPEG format**, with optional future support for 1024x1024 AI-upscaled covers.

---

## ✅ Features

- 🔄 Auto-resizes all `.jpg` covers to 512x512 with preserved aspect ratio and padding
- 📂 Organizes covers into folders named by game serial
- 📜 Logs all operations to a timestamped `.log` file
- 🚫 Removes hyphens from filenames/folder names
- 🧼 Cleans up temporary folders after use
- 🛠️ Compatible with any DuckStation installation (user directory detection)

---

## 🕹 Step 1: Enable DuckStation's Cover Downloader

DuckStation includes a cover-downloading tool. Here's how to set it up:

1. Open **DuckStation**
2. Go to **Tools → Cover Downloader**
3. Paste one of the following URLs:

Flat covers:
https://raw.githubusercontent.com/xlenore/psx-covers/main/covers/default/${serial}.jpg

3D covers:
https://raw.githubusercontent.com/xlenore/psx-covers/main/covers/3d/${serial}.png

4. ✅ Check “Use Serial Files Name”
5. Hit **Start**

---

## 🧩 Step 2: Installation

1. Download or clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/DuckStation-PS1-Cover-Organizer.git
   
2. Run:
launch_resize.bat
All resized covers will appear inside:
DuckStation\coverexport\<SERIAL>\

🔮 Future Roadmap
 Optional AI upscaling to 1024x1024

 GUI frontend

 Automatic DuckStation detection

📜 Acknowledgements
🕹 DuckStation development team for their outstanding emulator.

🖼️ GitHub user @xlenore for maintaining the psx-covers database used for downloads.

⚖ License
MIT License (see LICENSE)

