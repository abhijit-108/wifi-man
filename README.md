# 📡 Delsgade WiFi Manager

<p align="center">
  <img src="https://raw.githubusercontent.com/abhijit-108/wifi-man/main/app_logo.png" alt="Delsgade WiFi Manager Logo" width="100" height="100" />
</p>

<p align="center">
  <strong>Real-time WiFi station monitor, persistent device connection tracker, router log parser, and SMB file browser for Android. Featuring Cyber Dark glassmorphic design and multi-router endpoint management.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-v5.3.1-9D4EDD?style=for-the-badge" alt="Version" />
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Platform" />
  <img src="https://img.shields.io/badge/Theme-Cyber_Dark-090C15?style=for-the-badge" alt="Cyber Dark" />
  <img src="https://img.shields.io/badge/UI-Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Compose" />
  <img src="https://img.shields.io/badge/Engine-Foreground_Monitor-FF007F?style=for-the-badge" alt="Monitor" />
</p>

---

## ✨ Features

- **Real-Time Station Monitoring**: Live station feed showing active clients, RSSI signal strength (`-dBm`), IP addresses, uptime, and real-time MB/GB data counters.
- **Background Wi-Fi Monitor Service**: Persistent 15-second polling foreground service with boot recovery and heads-up push notifications for device connections.
- **Multi-Router Endpoint Management**: Centralized monitoring across multiple routers and repeaters (TP-Link Archer AX23, C60, D-Link DIR-2640, and RE200).
- **Cyber Dark Glassmorphic UI**: Deep space navy (`#090C15`) and dark blue-slate palette with neon purple accents (`#A855F7`), translucent cards, and a floating capsule navigation bar.
- **Router Log Parser**: Live parsing and display of router activity logs with color-coded event filtering and historical connection tracking.
- **SMB File Explorer**: Jetpack Compose-powered local network file manager with dynamic navigation for Movies, Anime, and shared storage.
- **Smart Game Mode**: QoS and polling rate optimization mode scheduled between 10:00 PM and 12:30 AM with on-screen indicators.
- **In-App Updater**: Direct GitHub version checks (`version.json`) with an interactive changelog viewer and APK updater.

---

## 🛠️ Tech Stack & Compatibility

- **UI Framework**: Custom Cyber Dark XML Dashboard + Jetpack Compose (SMB Files & Glassmorphic Surfaces)
- **Background Tasks**: Android Foreground Service + AlarmManager Boot Recovery
- **Network & Storage**: Router REST / Web API Polling, Syslog Parsing Engine, SMB/Samba Protocol
- **Supported Hardware**: TP-Link Archer AX23 v1, D-Link DIR-2640 A1, TP-Link Archer C60 v3, TP-Link RE200 v4
- **Target OS**: Android 8.0 (API 26) – Android 15+

---

## 📥 Download

Download the latest APK directly from the repository:

- 📦 **[Download latest app-debug.apk](https://raw.githubusercontent.com/abhijit-108/wifi-man/main/app-debug.apk)**


---

## 📋 Changelog

### `v 5.3.1`
- **Permanent Cyber Dark Theme**: Enforced deep space navy (`#090C15`) and dark blue-slate surfaces (`#111625`) across XML Dashboard and SMB Compose UI.
- **Redesigned Station Cards**: High-contrast avatar chips (purple, gold, indigo), dark slate borders, and enhanced MB/GB data readout legibility.
- **Horizontal Monitor Widget**: Redesigned background Wi-Fi monitor card row with active indicators and custom purple toggle switch.
- **Floating Bottom Navigation**: Sleek dark capsule navigation container with neon purple pill highlight (`#261B4E` / `#A855F7`).
- **Dynamic RSSI Header**: Superscript RSSI signal indicator in purple accent beside the main title.

### `v 5.2.1`
- **Persistent Wi-Fi Monitor Service**: Continuous 15-second station polling foreground service running even when the app is minimized.
- **Heads-Up Notifications**: High-priority alert banner triggering on device connect with IP and historical connection count.
- **Log Parsing Engine**: Integrated `calculateConnectCountFromLogs` for live router log matching.
- **Station Card Polishing**: 16dp rounded corners, network accent bars, and increased typography sizes for enhanced legibility.

### `v 5.0.2`
- **SMB Files Integration**: Added SMB Files tab into bottom navigation with dynamic routing.
- **Glassmorphic Sidebar**: Redesigned sidebar with gradient surfaces, WiFi Channel indicator, and default start tab selection.
- **Stability Fixes**: Fixed SMB explorer crashes from stale/closed DiskShare handles.

### `v 5.0.1`
- **Dynamic Router Routing**: Replaced legacy router tab with SMB Files browser.
- **Update Checker**: Added dynamic "New Version Available" badge in sidebar footer powered by `version.json`.
