<div align="center">

# 🗂️ WiFi-Man
### The Intelligent Local Network Dashboard & SMB Suite for Android

<p align="center">
  <img src="https://raw.githubusercontent.com/abhijit-108/wifi-man/main/app_logo.png" width="100" height="100" alt="WiFi-Man Icon" style="border-radius: 22px;" />
</p>

[![Version](https://img.shields.io/badge/v5.3.1-Latest%20Release-7C3AED?style=flat-square)](https://raw.githubusercontent.com/abhijit-108/wifi-man/main/app-debug.apk)
[![Android](https://img.shields.io/badge/Platform-Android%208.0%2B-10B981?style=flat-square&logo=android&logoColor=white)](https://github.com/abhijit-108/wifi-man)
[![Design](https://img.shields.io/badge/Theme-Cyber%20Dark%20M3-090C15?style=flat-square)](https://github.com/abhijit-108/wifi-man)
[![Compose](https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)](https://github.com/abhijit-108/wifi-man)
[![License](https://img.shields.io/badge/License-Personal%20Use-64748B?style=flat-square)](https://github.com/abhijit-108/wifi-man)

<br/>

</div>

---

## 🚀 Quick Download & Deploy

<table>
  <tr>
    <th width="35%">Asset</th>
    <th width="40%">Description</th>
    <th width="25%">Action</th>
  </tr>
  <tr>
    <td><b>📦 app-debug.apk</b></td>
    <td>Compiled signed APK payload (v5.3.1)</td>
    <td><a href="https://raw.githubusercontent.com/abhijit-108/wifi-man/main/app-debug.apk"><b>📥 Download Direct APK</b></a></td>
  </tr>
  <tr>
    <td><b>🧬 Source Archive (.7z)</b></td>
    <td>Complete Android Studio project tree and assets</td>
    <td><a href="https://raw.githubusercontent.com/abhijit-108/wifi-man/main/Android%20Studio%20Wifi%20Man.7z"><b>📦 Download Source (.7z)</b></a></td>
  </tr>
  <tr>
    <td><b>📄 version.json</b></td>
    <td>Live release manifest and update metadata</td>
    <td><a href="https://raw.githubusercontent.com/abhijit-108/wifi-man/main/version.json"><b>🔍 View Manifest</b></a></td>
  </tr>
</table>

---

## ✨ Key Features

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📶 Live Station Intelligence</h3>
      <p>Instantaneous scanning of every authenticated hardware station. Displays real-time signal power (<code>-dBm</code>), IP mapping, device hostnames, and dynamic live MB/GB throughput telemetry.</p>
      <sub style="color: #8B5CF6;">⚡ Refreshed every 2000ms</sub>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ 15s Foreground Sentinel</h3>
      <p>Low-overhead background daemon polling router association tables continuously. Issues high-priority heads-up system banners on new device connections with lifetime join counts.</p>
      <sub style="color: #10B981;">🛡️ Persistent with boot auto-revival</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎨 Cyber Dark Glassmorphism</h3>
      <p>Engineered with deep space navy (<code>#090C15</code>) and slate surface cards (<code>#111625</code>). Features a floating bottom navigation bar with active neon purple capsule indicators.</p>
      <sub style="color: #3B82F6;">✨ Pure AMOLED zero-strain palette</sub>
    </td>
    <td width="50%" valign="top">
      <h3>📁 Compose SMB File Streamer</h3>
      <p>Native Samba protocol explorer built with Jetpack Compose. Effortlessly browse and stream high-bitrate Movies and Anime directly from router-attached USB drives with zero stutter.</p>
      <sub style="color: #EC4899;">🎬 Leak-proof handle pooling</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🕹️ Scheduled Game Mode</h3>
      <p>Auto-activates during peak gaming hours (10:00 PM – 12:30 AM). Maximizes network visibility and immediately flags bandwidth-heavy streaming devices.</p>
      <sub style="color: #F59E0B;">🎮 Low-ping session optimizer</sub>
    </td>
    <td width="50%" valign="top">
      <h3>🔄 In-App OTA Updater</h3>
      <p>Direct GitHub release checking powered by <code>version.json</code>. Delivers instant changelog cards with one-tap background APK downloads.</p>
      <sub style="color: #06B6D4;">📦 Frictionless updates</sub>
    </td>
  </tr>
</table>

---

## 🧩 Hardware Topology

```mermaid
graph LR
    subgraph Client ["Android App"]
        Core[WiFi-Man Engine v5.3.1]
    end

    subgraph Mesh ["Managed Network APs"]
        AX23["TP-Link Archer AX23 v1<br/><i>Wi-Fi 6 5GHz</i>"]
        DIR["D-Link DIR-2640 A1<br/><i>Wave 2 MU-MIMO</i>"]
        C60["TP-Link Archer C60 v3<br/><i>High-Gain Beam</i>"]
        RE200["TP-Link RE200 v4<br/><i>Range Extender</i>"]
    end

    Core <-->|Live RF Telemetry| AX23
    Core <-->|Client Stats| DIR
    Core <-->|Station Data| C60
    Core <-->|Bridge Info| RE200
```

---

## 📋 Changelog

<table>
  <tr>
    <th colspan="2" align="left">
      <span style="font-size: 1.15em;">🚀 <b>v5.3.1</b></span> &nbsp;·&nbsp; <i>July 27, 2026</i>
      <span align="right" style="float: right;">
        <img src="https://img.shields.io/badge/Latest_Release-7C3AED?style=flat-square" alt="Current" />
      </span>
    </th>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>🎨 Permanent Cyber Dark UI</b>
      <p>Enforced deep space navy (<code>#090C15</code>) and dark slate surfaces (<code>#111625</code>) across both XML Dashboard and SMB Compose views, preventing blinding white mode overrides.</p>
      <b>🪪 Cyber Station Card Redesign</b>
      <p>Redesigned station cards with vibrant avatar chips (purple, gold, indigo), crisp dark borders, and dynamic superscript RSSI power text (<code>-57 dBm</code>) next to the header title.</p>
    </td>
    <td width="50%" valign="top">
      <b>🎛️ Horizontal Monitor Widget</b>
      <p>Reconstructed the Background Wi-Fi Monitor widget into a clean, horizontal card row with real-time status indicators and custom purple toggle styling.</p>
      <b>💊 Floating Capsule Navigation</b>
      <p>Built a floating dark container for bottom navigation featuring an active neon purple capsule indicator (<code>#261B4E</code> / <code>#A855F7</code>) and improved MB/GB contrast.</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <th colspan="2" align="left">
      <span style="font-size: 1.15em;">⚡ <b>v5.2.1</b></span> &nbsp;·&nbsp; <i>July 26, 2026</i>
      <span align="right" style="float: right;">
        <img src="https://img.shields.io/badge/Sentinel_Engine-0070F3?style=flat-square" alt="Sentinel" />
      </span>
    </th>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>🛡️ 15s Foreground Sentinel</b>
      <p>Added a persistent background Wi-Fi Monitor Foreground Service that continuously polls router station tables every 15s even when the app is closed, with automatic boot recovery.</p>
    </td>
    <td width="50%" valign="top">
      <b>🔔 Heads-Up Connection Alerts</b>
      <p>Added high-priority system alert banners formatted to <code>[Device] Connected | Total X Times</code> using live system log parsing (<code>calculateConnectCountFromLogs</code>).</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <th colspan="2" align="left">
      <span style="font-size: 1.15em;">📁 <b>v5.0.2</b></span> &nbsp;·&nbsp; <i>June 24, 2026</i>
      <span align="right" style="float: right;">
        <img src="https://img.shields.io/badge/SMB_Compose-10B981?style=flat-square" alt="SMB" />
      </span>
    </th>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>🎬 SMB Files Jetpack Compose Hub</b>
      <p>Replaced the legacy router tab with a native SMB file browser featuring dynamic routing for Dashboard, Movies, and Anime folders.</p>
    </td>
    <td width="50%" valign="top">
      <b>🪟 Glassmorphic Sidebar & Stability</b>
      <p>Introduced a glassmorphic sidebar showing real-time WiFi Channel stats and fixed SMB explorer crashes from stale DiskShare handles.</p>
    </td>
  </tr>
</table>

<details>
<summary><b>View Earlier Release History (v5.0.1 – v4.0.2)</b></summary>
<br>

| Version | Date | Highlights |
| :--- | :--- | :--- |
| **v5.0.1** | June 18, 2026 | Added dynamic "New Version Available" badge in sidebar; removed redundant data clear actions. |
| **v4.0.7** | April 25, 2026 | Added new router hostname resolution and updated launch splash screen credits. |
| **v4.0.5** | March 31, 2026 | Added one-tap "Reupdate" button directly in the glassmorphic sidebar. |
| **v4.0.4** | March 25, 2026 | Introduced client device grouping, slicker menu bar, and restructured settings menu. |
| **v4.0.2** | March 22, 2026 | Fixed device sorting criteria and refreshed station list animations. |

</details>

---

<div align="center">
  <sub>Crafted by <b>Abhijit</b> • Powered by Jetpack Compose & Cyber Dark Architecture</sub>
</div>
