<div align="center">

# 🐱 NekoBox

### Modern Bulk Image Downloader for Image Boards & Galleries

![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-blue)
![License](https://img.shields.io/badge/License-Proprietary-red)
![Electron](https://img.shields.io/badge/Electron-28.0-47848f?logo=electron)
![React](https://img.shields.io/badge/React-18.2-61dafb?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178c6?logo=typescript)

---

**A high-performance desktop application for bulk downloading images and galleries from popular image boards and art platforms. Built with Electron, React, TypeScript, and Python.**

[Features](#-features) • [Supported Sites](#-supported-sites) • [Installation](#-installation) • [Usage](#-usage) • [Technologies](#-technologies)

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### ⚡ High-Speed Downloads
- **5-50 concurrent downloads**
- Individual file progress tracking
- Real-time speed monitoring
- MB/s display for each file

</td>
<td width="50%">

### 🎯 Intelligent Download Modes
- **Single Mode**: Direct image/post URLs
- **Batch Mode**: Entire galleries & profiles
- Configurable download limits
- Smart queue management

</td>
</tr>
<tr>
<td width="50%">

### 🎨 Modern Interface
- Dark-themed UI built with Chakra UI
- Real-time progress visualization
- Expandable download cards
- Responsive design

</td>
<td width="50%">

### ⚙️ Flexible Configuration
- Custom download directories
- Quality settings
- File type filtering
- Naming pattern customization

</td>
</tr>
</table>

---

## 🌐 Supported Sites

### 🚀 Native High-Performance Scrapers
Built-in, optimized scrapers for:
- **Pixiv** (User galleries, bookmarks, rankings, tags)
- **Rule34** (Tag search, pools, posts)

### 🔌 Extensible Support (1000+ Sites)
Integration with **gallery-dl** enables support for thousands of additional sites including Reddit, DeviantArt, Danbooru, Gelbooru, and [many more](SUPPORTED_SITES.md).

📋 See the full [**Supported Sites List**](SUPPORTED_SITES.md) for details.

---

## 📥 Installation

### Download the App

1. Download the latest release from the [Releases](../../releases) page
2. Run the installer
3. Launch the application

### Install Gallery-dl (Optional but Recommended)

Gallery-dl is an **optional external extension** that provides support for 1000+ sites.

**Quick Install:**
```bash
pip install gallery-dl
```

📚 **See [GALLERY-DL-SETUP.md](GALLERY-DL-SETUP.md) for detailed installation instructions.**

### Why is Gallery-dl Optional?

Gallery-dl is licensed under **GPL-2.0+** (GNU General Public License). To maintain licensing flexibility and comply with GPL requirements, gallery-dl is kept as an optional external dependency that users install separately.

**Benefits:**
- ✅ Clear license boundaries
- ✅ Users choose whether to install it
- ✅ Always get the latest gallery-dl version
- ✅ Respects GPL-2.0+ licensing requirements

---

## 🚀 Quick Start

1. **Set Download Folder**: Go to Settings → Download Location → Browse
2. **Test Gallery-dl** (if installed): Settings → Gallery-dl Diagnostics → Test Gallery-dl
3. **Start Downloading**: 
   - Paste URLs in the Download tab
   - Choose Single or Batch mode
   - Click "Start Download"

---

## 📖 Usage

### Single Mode
- Download individual images or threads
- Paste direct image URLs or post URLs
- Perfect for specific content

### Batch Mode
- Download entire subreddits, galleries, or profiles
- Set a limit or download unlimited files
- Ideal for bulk downloading

### Queue Management
- View all downloads in the Queue tab
- Pause/resume individual downloads
- See detailed progress for each file
- Expand downloads to see individual file progress

---

## 🛠️ Technologies

<div align="center">

| Frontend | Backend | Tools |
|:--------:|:-------:|:-----:|
| **Electron** | **Python** | **Gallery-dl** |
| Desktop Framework | Scraping Engine | External Engine |
| **React** | **C++** | **Vite** |
| UI Framework | Download Engine | Build Tool |
| **TypeScript** | | |
| Type Safety | | |
| **Chakra UI** | | |
| Components | | |
| **Zustand** | | |
| State Management | | |

</div>

---

## 📄 License

**Copyright © 2026. All Rights Reserved.**

This project is for **demonstration and portfolio purposes only**. The source code is available for viewing, but you are not permitted to use, modify, distribute, or compile this software for any purpose without explicit written permission from the owner.

> **Note**: This application uses gallery-dl as an optional external dependency. Gallery-dl is licensed under GPL-2.0+ and is not bundled with this application. Users must install it separately if they wish to use its features.

---

## 🙏 Credits

- **Gallery-dl**: [mikf/gallery-dl](https://github.com/mikf/gallery-dl) - GPL-2.0+
- Built with Electron, React, and TypeScript

---

## 💬 Support

For issues or questions about this portfolio project, please contact via GitHub.

---

<div align="center">

**⚠️ Disclaimer**

This tool is for personal use only. Please respect the terms of service of the websites you download from and respect copyright laws.

---

Made with ❤️ for the community

</div>
