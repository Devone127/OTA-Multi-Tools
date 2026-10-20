<div align="center">

# OTA Multi Tools

<p align="center">
  <b>The ultimate all-in-one Android utility for OnePlus, Realme, and OPPO (ColorOS, OxygenOS, realme UI).</b><br>
  Find official OTA updates, download at maximum speed with aria2c, and extract partition images (payload.bin) on the fly without downloading entire archives.
</p>

[![Release](https://img.shields.io/github/v/release/Devone127/OTA-Multi-Tools?style=for-the-badge&color=00f2ff&logo=github)](https://github.com/Devone127/OTA-Multi-Tools/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Devone127/OTA-Multi-Tools/total?style=for-the-badge&color=8B5CF6&logo=android)](https://127.codes/OTA-Multi-Tools/apk)
[![Telegram Group](https://img.shields.io/badge/Telegram-Group-24A1DE?style=for-the-badge&logo=telegram)](https://t.me/OTAMultiTools)
[![Telegram Bot](https://img.shields.io/badge/Archive-Telegram_Bot-00f2ff?style=for-the-badge&logo=telegram)](https://t.me/Devone127_bot)
[![Website](https://img.shields.io/badge/Official-Website-0B0E11?style=for-the-badge&logo=google-chrome)](https://127.codes/OTA-Multi-Tools/)

<br>

[**English**](#english-overview) • [**Русский**](#russian-overview) • [**Download APK**](https://127.codes/OTA-Multi-Tools/apk) • [**Telegram Bot**](https://t.me/Devone127_bot)

---

</div>

<a name="english-overview"></a>
## 🌐 English Overview

> ⚠️ **Notice:** This repository is dedicated **strictly for distributing official pre-compiled APK releases** and release changelogs. The core application logic and algorithms are closed-source.

### 📥 Direct Fast Download
- **Fast Mirror (Always Latest APK):** [https://127.codes/OTA-Multi-Tools/apk](https://127.codes/OTA-Multi-Tools/apk)
- **GitHub Releases:** [GitHub Releases Page](https://github.com/Devone127/OTA-Multi-Tools/releases/latest)
- **Telegram Archive Bot:** [@Devone127_bot](https://t.me/Devone127_bot) — instant search across the `api.127.codes` firmware database.

---

### 🌟 Key Highlights & Features

1. **OTA Finder & OS Updater:**
   - **Direct Gateways:** Connects directly to encrypted OPPO/Realme Component OTA v3 servers across CN, EU, IN, and Global regions.
   - **Catalogs & Mirrors:** Integrated with *Oxygen Updater* and *Daniel Springer Mirror*.
   - **Smart Recency Scoring:** Automatically ranks and presents the newest build comparing security patches and timestamps across all live servers and archives.
   - **Delta/Incremental Packages:** Fetches small incremental updates tailored for your current build.

2. **Streamed Payload.bin Extractor:**
   - **Zero-Storage HTTP Extraction:** Extract specific partition images (`boot.img`, `init_boot.img`, `recovery.img`, `odm.img`) directly from remote HTTP range-request URLs **without downloading the multi-gigabyte ZIP archive**.
   - **Decompression Engines:** Native on-the-fly streaming decompression for `REPLACE_XZ` and `REPLACE_BZ` blocks.
   - **Anti-Rollback (ARB) Verification:** Inspects Qualcomm bootloader images (`xbl_config`) on native ARM64 with built-in `arbextract`.

3. **High-Speed Aria2c Downloader:**
   - Multi-connection segmented downloading up to 16 threads.
   - **Auto-Refresh URLs:** Background timer renews expiring temporary download tokens on the fly without breaking your download session.
   - Battery-optimized Foreground Service and WorkManager engines.

4. **EDL Service Firmware Finder:**
   - Discovers hidden emergency unbrick flash packages (EDL) via server-bucket range probing(realme).

---

### 📱 Application Preview

<div align="center">
  <img src="https://raw.githubusercontent.com/Devone127/OTA-Multi-Tools/main/docs/screenshots/finder.png" width="30%" alt="OTA Finder Screen" />
  <img src="https://raw.githubusercontent.com/Devone127/OTA-Multi-Tools/main/docs/screenshots/downloader.png" width="30%" alt="Aria2 Downloader Screen" />
  <img src="https://raw.githubusercontent.com/Devone127/OTA-Multi-Tools/main/docs/screenshots/extractor.png" width="30%" alt="Payload Extractor Screen" />
</div>

---

### ❓ Frequently Asked Questions (FAQ)

- **Q: Are Root rights (Magisk / KernelSU / APatch) required?**  
  **A:** No. You can dump `boot.img` directly from an OTA URL on your phone without root, patch it in Magisk Manager, and flash it via Fastboot from a PC.
- **Q: How does the Telegram Bot work?**  
  **A:** Search models, retrieve direct links, and check the latest builds without opening the app via [@Devone127_bot](https://t.me/Devone127_bot).

---

<a name="russian-overview"></a>
## 🇷🇺 Русское описание (Russian Overview)

**OTA Multi Tools** — это многофункциональный Android-комбайн для владельцев устройств **OnePlus, Realme и OPPO** (оболочки ColorOS, OxygenOS, realme UI).

Приложение заменяет громоздкие скрипты на Python и утилиты для ПК, перенося весь процесс поиска, скачивания и распаковки `payload.bin` прямо на ваш смартфон.

### 📥 Быстрая загрузка
- **Прямая ссылка на последний APK:** [https://127.codes/OTA-Multi-Tools/apk](https://127.codes/OTA-Multi-Tools/apk)
- **Страница релизов GitHub:** [Вкладка Releases](https://github.com/Devone127/OTA-Multi-Tools/releases/latest)
- **Телеграм-бот архива:** [@Devone127_bot](https://t.me/Devone127_bot) — моментальный поиск и получение ссылок на прошивки из облачной базы `api.127.codes`.
- **Официальный сайт проекта:** [https://127.codes/OTA-Multi-Tools/](https://127.codes/OTA-Multi-Tools/)

---

### 🛠 Основные модули и функционал

*   **OTA Finder & OS Updater:**
    *   Прямой криптографический опрос серверов обновлений OPPO Component OTA v3 (регионы CN, EU, IN, GL).
    *   Поддержка баз данных каталогов *Oxygen Updater* и зеркала *Daniel Springer*.
    *   Алгоритм сравнения версий (Recency Scoring): автоматический выбор самой свежей сборки по уровню патча безопасности и таймстампу.
    *   Генерация готового оформления BBCode для публикации прошивок на форуме 4PDA.
*   **Потоковый Extractor (дампер payload.bin):**
    *   **Распаковка без скачивания архива:** извлечение любых разделов (`boot`, `init_boot`, `recovery`, `vendor_boot`) прямо по ссылке из сети через HTTP Range Requests.
    *   Аппаратная декомпрессия блоков `XZ` и `BZip2`.
    *   Встроенная проверка Anti-Rollback (ARB) через анализ раздела `xbl_config` утилитой `arbextract`.
*   **Многопоточный загрузчик (Aria2c):**
    *   Скачивание до 16 потоков со стабильной докачкой.
    *   Автоматическое продление ссылок (серверные ссылки живут 30 минут — загрузчик обновляет токен в фоне без перезапуска скачивания).
*   **EDL Finder:**
    *   Инструмент сканирования серверов Realme для обнаружения скрытых сервисных образов экстренного восстановления (EDL)(realme).

---

### 💬 Сообщество и обратная связь

- **Telegram-канал и группа:** [t.me/OTAMultiTools](https://t.me/OTAMultiTools)
- **Telegram-бот:** [@Devone127_bot](https://t.me/Devone127_bot)
- **Баг-трекер:** [GitHub Issues](https://github.com/Devone127/OTA-Multi-Tools/issues)

<div align="center">
  <sub>© 2024–2026 Gor Petrosyan (Devone127). Designed with Material 3 & Jetpack Compose.</sub>
</div>
