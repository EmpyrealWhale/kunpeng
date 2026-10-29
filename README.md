<div align="center">

  <img src="assets/kunpeng_logo.webp" alt="KunPeng Logo" width="120" height="120" style="border-radius: 28px;" />

  # KunPeng • 鲲鹏
  
  **A fast, modern, offline-first Chinese-English dictionary for Android.**

  [![Latest Release](https://img.shields.io/github/v/release/EmpyrealWhale/kunpeng?label=Latest%20Release&color=38bdf8&style=flat-square)](https://github.com/EmpyrealWhale/kunpeng/releases/latest)
  [![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-22c55e?style=flat-square)](https://github.com/EmpyrealWhale/kunpeng/releases/latest)
  [![Status](https://img.shields.io/badge/Status-Beta%20v0.9.1-f59e0b?style=flat-square)](https://github.com/EmpyrealWhale/kunpeng/releases/latest)
  [![Website](https://img.shields.io/badge/Web-GitHub%20Pages-6366f1?style=flat-square)](https://empyrealwhale.github.io/kunpeng/)

  <p align="center">
    <a href="https://github.com/EmpyrealWhale/kunpeng/releases/latest"><b>Download APK</b></a> •
    <a href="#-screenshots">Screenshots</a> •
    <a href="#-features">Features</a> •
    <a href="#-installation">Installation</a> •
    <a href="#-bug-reports--feedback">Feedback</a> •
    <a href="#-credits--attributions">Credits</a>
  </p>

</div>

---

## ⚡ Overview

**KunPeng (鲲鹏)** is designed for learners and linguists who need a responsive, beautiful, and completely offline Chinese dictionary. Powered by Jetpack Compose and high-performance on-device recognition, it offers instantaneous lookups, stroke-order animations, and radical breakdowns with zero latency and zero tracking.

---

## 📸 Screenshots

<div align="center">
  <table>
    <tr>
      <td align="center"><b>Dictionary & Search</b></td>
      <td align="center"><b>Stroke Order & Writing</b></td>
      <td align="center"><b>Tactile Flashcards</b></td>
      <td align="center"><b>Word Lists & Zen Study</b></td>
    </tr>
    <tr>
      <td align="center">
        <img src="assets/screenshots/screenshot_search.webp" width="200" alt="Search & Dictionary" onerror="this.onerror=null; this.src='https://placehold.co/400x850/1e1e1e/e0e0e0?text=Search+Screen';" />
      </td>
      <td align="center">
        <img src="assets/screenshots/screenshot_practice.webp" width="200" alt="Calligraphy & Stroke Order" onerror="this.onerror=null; this.src='https://placehold.co/400x850/1e1e1e/e0e0e0?text=Practice+Writing';" />
      </td>
      <td align="center">
        <img src="assets/screenshots/screenshot_flashcards.webp" width="200" alt="Flashcards Review" onerror="this.onerror=null; this.src='https://placehold.co/400x850/1e1e1e/e0e0e0?text=Flashcards+Deck';" />
      </td>
      <td align="center">
        <img src="assets/screenshots/screenshot_lists.webp" width="200" alt="Word Lists & Categories" onerror="this.onerror=null; this.src='https://placehold.co/400x850/1e1e1e/e0e0e0?text=Word+Lists';" />
      </td>
    </tr>
  </table>
</div>

---

## ✨ Features

- **📖 100% Offline Database**: Complete CC-CEDICT database with over 120,000+ entries, pinyin annotations, and multi-definition search.
- **✍️ Digital Ink Recognition**: Real-time on-device handwriting input engine — recognize handwritten Hanzi and stroke sequences instantly without an internet connection.
- **🎨 Stroke Order Animations**: Vector-based dynamic stroke order animations and radical component analysis powered by *Make Me a Hanzi*.
- **🔍 Radical & Component Decomposition**: Explore characters hierarchically by stroke counts, radicals, and similar glyph groupings.
- **🔊 Multi-Speed Audio Pronunciation**: Built-in Text-To-Speech with adjustable playback speeds and custom tone indicator preferences.
- **🎴 Spaced & Tactile Flashcards**: 3D tactile card deck with smooth gesture swiping and dual tap controls.
- **🌗 Material You & Zen Theming**: Adaptive light and dark themes designed with modern, calming Zen aesthetics.

---

## 📥 Installation

1. Navigate to the **[Releases Page](https://github.com/EmpyrealWhale/kunpeng/releases/latest)**.
2. Download the APK suited for your device:
   - `KunPeng-arm64-v8a.apk` (Recommended for modern Android phones and tablets)
   - `KunPeng-armeabi-v7a.apk` (For older 32-bit Android devices)
   - `KunPeng-universal.apk` (Compatible with all devices)
3. Open the downloaded `.apk` file on your device and tap **Install** (allow *Install from Unknown Sources* if prompted).

> **System Requirements**: Android 8.0 (API Level 26) or newer.

---

## 🛠️ Remote Announcements & Updates

This repository acts as the official update and announcement feed for the KunPeng app via [`app_config.json`](app_config.json). When connected to Wi-Fi, the app securely verifies this repository for version updates, maintenance notices, and dictionary announcements.

---

## 🐛 Bug Reports & Feedback

If you encounter any issues, missing definitions, or want to suggest new features, please submit an issue on our [Issue Tracker](https://github.com/EmpyrealWhale/kunpeng/issues).

---

## 📜 License & Terms of Use

Copyright © 2026 **EmpyrealWhale**. All rights reserved.

KunPeng is free to download, install, and use for personal, educational, and non-commercial purposes. Redistribution, modification, or repackaging of the APK binary without prior permission is strictly prohibited.

---

## 🙏 Credits & Attributions

KunPeng is built upon exceptional open-source databases and research:

- **[CC-CEDICT](https://cc-cedict.org/)**: The comprehensive community-driven Chinese-English dictionary dataset.
- **[Make Me a Hanzi](https://github.com/skishore/makemeahanzi)**: Open stroke order vector data and radical decompositions.
