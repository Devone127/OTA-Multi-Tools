# OTA Multi Tools

<div align="center">

![Version](https://img.shields.io/badge/version-1.4.2-00f2ff?style=for-the-badge)
![Build](https://img.shields.io/badge/build-42-00f2ff?style=for-the-badge)
![Android](https://img.shields.io/badge/Android-7.0%2B-3DDC84?style=for-the-badge&logo=android)
![License](https://img.shields.io/badge/license-Proprietary-red?style=for-the-badge)

**Native Android application for OTA firmware search**  
**Realme • OPPO • OnePlus**

[Download Latest APK](https://github.com/devone127/OTA-Multi-Tools/releases/latest) • [Website](https://devone127.me/omt/) • [Report Issue](https://github.com/devone127/OTA-Multi-Tools/issues)

</div>

---

## ✨ Features

### 🔍 OTA Finder
- Search for official firmware updates across all regions (Global, China, India, Europe)
- Multi-region server support with automatic fallback
- Detailed update information (version, size, changelog, MD5)
- Direct download links to official servers

### 🚀 Smart Downloader
- Built-in download manager with pause/resume support
- Automatic MD5 verification
- Download progress tracking
- Custom filename support

### 🛠️ EDL Package Finder
- Emergency Download Mode (EDL) package search
- Multi-threaded search (up to 40 threads)
- Support for `ota_common.txt` import
- Automatic model variant detection

### 📦 Payload Extractor
- Extract partitions from `payload.bin` files
- Support for both local files and direct URLs
- Selective partition extraction
- Progress tracking with detailed status

### 🌍 Multi-language Support
- English
- Русский (Russian)
- Հայերեն (Armenian)
- Slovenčina (Slovak)

---

## 📱 Supported Devices

### Brands
- **Realme**
- **OPPO**
- **OnePlus**

---

## 📥 Installation

### Requirements
- **Android 7.0 (Nougat)** or higher (API 24+)
- **Storage permission** for downloading and extracting files
- **~7 MB** free space for installation

### Download
1. Go to [Releases](https://github.com/devone127/OTA-Multi-Tools/releases/latest)
2. Download `app-release-1.4.2.apk`
3. Enable "Install from Unknown Sources" in Android settings
4. Install the APK file

### Alternative Download
- Direct link: [devone127.me/omt](https://devone127.me/omt/app-release.apk)

---

## 🎨 Technical Details

### Stack
- **Language:** Kotlin
- **UI Framework:** Jetpack Compose
- **Design System:** Material Design 3
- **Architecture:** MVVM with Coroutines
- **Network:** OkHttp
- **Min SDK:** 24 (Android 7.0)
- **Target SDK:** 34 (Android 14)

### Features
- ✅ **Lightweight** - Only ~7 MB APK size
- ✅ **Native Performance** - Pure Kotlin/Android implementation
- ✅ **Modern UI** - Material Design 3 with glass morphism effects
- ✅ **Offline Support** - Works without constant internet connection
- ✅ **Secure** - Official servers only, MD5 verification, signed APK
- ✅ **No Ads** - Completely free, no advertisements

---

## 🔒 Security & Privacy

- ✅ **Official Sources Only** - All firmware links from official manufacturer servers
- ✅ **MD5 Verification** - Automatic checksum validation for downloaded files
- ✅ **Digital Signature** - APK is digitally signed and verified
- ✅ **No Telemetry** - No analytics, tracking, or data collection
- ✅ **Open Permissions** - Only requests necessary permissions (storage)
- ⚠️ **Modified Versions** - Modified APKs may not work correctly and are not supported

---

##  Changelog

### v1.4.2 (Build 42) - Feb 14, 2026
- ✅ Fixed scroll issues across all screens
- ✅ Improved text readability in dialogs
- ✅ Added ability to stop EDL search
- ✅ Fixed minor bugs
- ✅ Enhanced dialog contrast

### v1.3.0 (Build 13) - Feb 12, 2026
- ✅ Initial stable release
- ✅ OTA Finder with multi-region support
- ✅ Built-in downloader with pause/resume
- ✅ EDL package search
- ✅ Payload extractor
- ✅ Multi-language support (EN, RU, HY, SK)

[View Full Changelog](https://github.com/devone127/OTA-Multi-Tools/releases)

---

## 🤝 Contributing

This is a closed-source project. The source code is not publicly available.

However, you can contribute by:
- 🐛 [Reporting bugs](https://github.com/devone127/OTA-Multi-Tools/issues)
- 💡 [Suggesting features](https://github.com/devone127/OTA-Multi-Tools/issues)
- 🌍 Helping with translations
---

## ⚠️ Disclaimer

- T🙏 Credits

This project uses code and inspiration from:

- **[OMT (OTA Multi Tools)](https://github.com/stanislawrabel/omt)** by [Stanislav Rabel](https://github.com/stanislawrabel) - Original OTA search implementation and EDL finder logic
- **[Payload Dumper Compose](https://github.com/rcmiku/Payload-Dumper-Compose)** by [rcmiku](https://github.com/rcmiku) - Payload extraction functionality

Special thanks to these developers for their excellent work! 🎉

---

## his application is **not affiliated** with Realme, OPPO, or OnePlus
- Use at your own risk - the author is not responsible for any damage to your device
- **Flashing firmware** can brick your device if done incorrectly
- Always backup your data before installing firmware updates
- Only use firmware intended for your specific device model and region

---

## 📜 License

Copyright (c) 2024-2026 Devone127. All rights reserved.

This software is provided under a proprietary license.  
**Free for personal use only. Commercial use prohibited.**

See [LICENSE](LICENSE) file for full terms.

---

## 🔗 Links

- **Website:** [devone127.me/omt](https://devone127.me/omt/)
- **Releases:** [GitHub Releases](https://github.com/devone127/OTA-Multi-Tools/releases)
- **Issues:** [Report a Bug](https://github.com/devone127/OTA-Multi-Tools/issues)
- **Author:** [Devone127](https://devone127.me)

---

<div align="center">

**Made with ❤️ by Devone127**

If you find this app useful, consider starring ⭐ this repository!

</div>
