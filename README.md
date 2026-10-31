<div align="center">

# 🗂️ WiFi-Man
### The Intelligent Local Network Dashboard & SMB Suite for Android

<p align="center">
  <img src="https://raw.githubusercontent.com/abhijit-108/wifi-man/main/app_logo.png" width="96" height="96" alt="WiFi-Man Icon" style="border-radius: 24px;" />
</p>

[![Version](https://img.shields.io/badge/v5.3.1-Latest%20Release-7C3AED?style=flat-square)](https://raw.githubusercontent.com/abhijit-108/wifi-man/main/app-debug.apk)
[![Android](https://img.shields.io/badge/Android-8.0%2B-10B981?style=flat-square&logo=android&logoColor=white)](https://github.com/abhijit-108/wifi-man)
[![Design](https://img.shields.io/badge/UI-Cyber%20Dark%20M3-3B82F6?style=flat-square)](https://github.com/abhijit-108/wifi-man)
[![License](https://img.shields.io/badge/License-Personal%20Use-64748B?style=flat-square)](https://github.com/abhijit-108/wifi-man)

<br/>

</div>

---

## 🍱 Feature Grid

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📶 Live Station Intelligence</h3>
      <p>Instantaneous scanning of every device authenticated to your access point. Tracks signal amplitude (dBm), MAC identities, private IPs, and dynamic MB/GB throughput.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ 15s Foreground Sentinel</h3>
      <p>An untethered foreground service polling every 15 seconds. Emits high-priority heads-up banners on fresh connections with lifetime connect counts.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎨 Cyber Dark Glassmorphism</h3>
      <p>Engineered with an AMOLED deep space navy canvas (<code>#090C15</code>), slate card frames (<code>#111625</code>), and floating capsule navigation highlights.</p>
    </td>
    <td width="50%" valign="top">
      <h3>📁 Compose SMB File Streamer</h3>
      <p>Integrated Samba client written in Jetpack Compose. Effortlessly browse and stream high-bitrate Movies and Anime stored on your NAS / router disk.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🕹️ Scheduled Game Mode</h3>
      <p>Automatically triggers during prime gaming hours (10:00 PM – 12:30 AM). Maximizes connection stability and surfaces latency-critical alerts.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🔄 OTA GitHub Updater</h3>
      <p>Automated version detection against <code>version.json</code>. Delivers instant changelog previews and one-tap in-app APK upgrades.</p>
    </td>
  </tr>
</table>

---

## 🧩 Supported Router Endpoints

```mermaid
graph LR
    App[WiFi-Man Client] --> AX23[TP-Link AX23 v1]
    App --> DLink[D-Link DIR-2640 A1]
    App --> C60[TP-Link Archer C60 v3]
    App --> RE200[TP-Link RE200 v4]
    AX23 -. Logs & Stations .-> App
    DLink -. Throughput Telemetry .-> App
```

---

## 🚀 Quick Download

| Asset | Details | Direct Link |
| :--- | :--- | :--- |
| **Production APK** | `v5.3.1` Compiled Debug Binary | [📥 Download `app-debug.apk`](https://raw.githubusercontent.com/abhijit-108/wifi-man/main/app-debug.apk) |
| **Full Project Bundle** | Android Studio 7z Project Tree | [📦 Download Project Archive](https://raw.githubusercontent.com/abhijit-108/wifi-man/main/Android%20Studio%20Wifi%20Man.7z) |
| **Release Manifest** | JSON Update Schema | [📄 Inspect `version.json`](https://raw.githubusercontent.com/abhijit-108/wifi-man/main/version.json) |

---

<div align="center">
  <sub>Developed by <b>Abhijit</b> • Crafted with Jetpack Compose & Cyber Dark Architecture</sub>
</div>
