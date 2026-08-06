# 🚀 Lynqo — Local-First Creative Infrastructure

<div align="center">

# ⚡ Lynqo
### *Your desktop. Your server. Your rules.*

[![Local-First](https://img.shields.io/badge/Architecture-Local--First-007AFF?style=for-the-badge&logo=serverless)](https://github.com/maheshchambhare/lynqo-release)
[![macOS](https://img.shields.io/badge/Platform-macOS-black?style=for-the-badge&logo=apple)](https://github.com/maheshchambhare/lynqo-release/raw/main/mac/Lynqo-Installer.dmg)
[![Rust](https://img.shields.io/badge/Backend-Rust-orange?style=for-the-badge&logo=rust)](https://www.rust-lang.org/)
[![Flutter](https://img.shields.io/badge/Frontend-Flutter-blue?style=for-the-badge&logo=flutter)](https://flutter.dev/)
[![Zero Cloud](https://img.shields.io/badge/Cloud-Zero_Cloud-10B981?style=for-the-badge)](https://github.com/maheshchambhare/lynqo-release)

**Lynqo turns your Mac or PC into a blazing-fast local server.**  
Share huge video files, sync clipboards across all your devices, and get frame-accurate client feedback. All over Wi-Fi. **Zero cloud. Zero storage fees. Zero compromise.**

[📥 Download macOS Installer (`Lynqo-Installer.dmg`)](mac/Lynqo-Installer.dmg) • [📖 Installation Guide](#-macos-installer--setup-guide) • [✨ Key Features](#-key-features) • [⚔️ Comparison](#️-why-lynqo-hits-different)

---

</div>

## 📌 Overview

Traditional creative tools force you to upload multi-gigabyte video files to cloud servers, wait for upload bars, pay high monthly storage fees, and risk raw footage privacy. 

**Lynqo flips the script.** 
It runs a high-performance Rust server right on your machine (`localhost:7432`), allowing clients and devices on your network to stream content, drop frame-accurate feedback, and sync clipboards instantly over Wi-Fi.

---

## 💻 macOS Installer & Setup Guide

### 📦 Quick Download & Installation

The official release binary for macOS is available directly in this repository:

📍 **Installer Location:** [`mac/Lynqo-Installer.dmg`](file:///Users/mahesh/Desktop/Projects/backend/lynqo-release/mac/Lynqo-Installer.dmg)

#### Step-by-Step Installation:

1. **Download the DMG**:
   Click on [`mac/Lynqo-Installer.dmg`](mac/Lynqo-Installer.dmg) in this repository and click **Download Raw** (or clone this repository).
   
2. **Mount the Installer**:
   Double-click `Lynqo-Installer.dmg` to open the installer window.

3. **Install to Applications**:
   Drag the **Lynqo** application icon into your macOS **Applications** folder.

4. **Launching Lynqo for the First Time**:
   - Open **Lynqo** from your Applications folder or Spotlight (`Cmd + Space` -> type *Lynqo*).
   - If macOS displays a Security warning (*"Lynqo cannot be opened because it is from an unidentified developer"*):
     - Open **System Settings** -> **Privacy & Security**.
     - Scroll down to the *Security* section.
     - Click **Open Anyway** next to the Lynqo prompt, or right-click `Lynqo.app` in Finder and select **Open**.

5. **Permissions & Initial Setup**:
   - **Local Network Access**: Allow Lynqo to discover devices on your Wi-Fi via mDNS (`_lynqo._tcp.local`).
   - **System Menu Bar**: Lynqo lives quietly in your top macOS menu bar for background execution.
   - **Global Hotkey**: Press <kbd>Option</kbd> + <kbd>B</kbd> anywhere on macOS to toggle the floating Clipboard Sync window.

---

## ✨ Key Features

### 🎬 1. Video Review Studio `PRO FEATURE`
*Frame-accurate client feedback with zero file uploads.*
- **Timecode Commenting**: Clients open a secure browser link to drop comments at exact timestamp frames.
- **Real-Time Desktop Sync**: View live client comments and annotations directly inside the Lynqo desktop app.
- **Zero Upload**: Video files stream straight from your local hard drive.
- **Password Protection**: Secure review links with custom passwords.

### 📁 2. Instant Local File Sharing `ZERO CLOUD`
*Share 100GB files in seconds over local Wi-Fi.*
- **Instant LAN Serving**: Turns your computer into a media server at `localhost:7432`.
- **Directory Sharing**: Share entire project folders with a single click.
- **Cloudflare Tunnel Support**: Enable secure remote access when sharing files outside your local Wi-Fi.
- **Download Analytics**: Track download counts and revoke links anytime.

### 📋 3. P2P Clipboard Sync
*Copy on your Mac. Paste on your phone or Windows PC.*
- **Cross-Device Sync**: Real-time clipboard sharing between Mac, Windows, iOS, and Android.
- **History & Search**: Store up to 500 clipboard entries with fast content searching.
- **Global Hotkey**: Press <kbd>Option</kbd> + <kbd>B</kbd> to pop up the clipboard HUD anywhere.
- **Browser-to-Desktop**: Push text or snippets from mobile browsers straight to your desktop clipboard.

### 📡 4. Zero-Config mDNS Auto-Discovery
*Instant device connection without typing IP addresses.*
- **Automated Network Discovery**: Broadcasts `_lynqo._tcp.local` across your network.
- **QR Code Onboarding**: Scan the QR code on the desktop dashboard with any phone to connect instantly.
- **Device Management**: View connected device stats, latency, and manage access permissions.

### 🔒 5. Local-First & Privacy-Focused
*100% Zero-Knowledge architecture.*
- **Your Computer is the Server**: Files never land on third-party cloud servers.
- **Rust Backend**: Engineered for low resource utilization, high transfer throughput, and ironclad security.
- **No Analytics Tracking**: Zero telemetry or third-party file scanning.

---

## ⚔️ Why Lynqo Hits Different

| Feature | ⚡ Lynqo | WeTransfer | Frame.io | Google Drive | Dropbox |
|---|:---:|:---:|:---:|:---:|:---:|
| **Works offline / LAN** | ✅ **Yes** | ❌ No | ❌ No | ❌ No | ❌ No |
| **Zero upload required** | ✅ **Zero** | ❌ Full upload | ❌ Full upload | ❌ Full upload | ❌ Full upload |
| **Local-first server** | ✅ **Runs on host** | ❌ Cloud only | ❌ Cloud only | ❌ Cloud only | ❌ Cloud only |
| **Frame-accurate review** | ✅ **Timecode sync** | ❌ No | ✅ Yes | ❌ No | ❌ No |
| **Cross-device clipboard** | ✅ **Built-in** | ❌ No | ❌ No | ❌ No | ❌ No |
| **mDNS Auto-discovery** | ✅ **Instant QR** | ❌ Manual | ❌ Manual | ❌ Manual | ❌ Manual |
| **Per-GB storage fees** | ✅ **None (Unlimited)** | ❌ Pay per GB | ❌ Pay per GB | ❌ Pay per GB | ❌ Pay per GB |
| **Price** | **$20/mo (Pro)** | $15+/mo | $15–$35/mo | $10+/mo | $12+/mo |
| **Files leave your disk?** | ❌ **Never** | ✅ Always | ✅ Always | ✅ Always | ✅ Always |

---

## 💰 Plans & Pricing

### 🟢 Free Tier — `$0 / forever`
- Local file sharing (up to 3 active projects)
- Clipboard history & sync (up to 500 entries)
- mDNS auto-discovery & QR code onboarding
- 3 Video Review Studio projects
- Device management dashboard

### 💙 Lynqo Pro — `$20 / month` *(3-Day Free Trial)*
- Everything in Free tier
- **Unlimited Video Review Studio projects**
- **Frame-accurate timecode markers & drawing tools**
- **Live client collaboration & approval workflow**
- **Password-protected public share links**
- **Secure Cloudflare remote sharing tunnels**
- **Custom whitelabel branding**

---

## ❓ Frequently Asked Questions

<details>
<summary><b>1. How does Lynqo work without the internet?</b></summary>
Lynqo starts a local web server (Rust backend) on port 7432. Any device connected to the same Wi-Fi router can access Lynqo interfaces or stream files directly across the LAN without sending data to the internet.
</details>

<details>
<summary><b>2. Do I need to upload video files?</b></summary>
No! Lynqo streams video directly from your storage drive. Clients preview footage through a browser link that reads directly from your local disk.
</details>

<details>
<summary><b>3. Is my footage private?</b></summary>
Completely. Lynqo has zero cloud storage middleman. Your data stays on your drive unless you explicitly configure a public relay tunnel.
</details>

<details>
<summary><b>4. What platforms are supported?</b></summary>
The Lynqo Desktop application supports **macOS** and **Windows**. Clients can review videos or access shared files from any browser on macOS, Windows, Linux, iOS, or Android.
</details>

---

## 🛠️ Tech Stack & Architecture

- **Backend / Core**: Rust (High performance HTTP file server, WebSockets, mDNS daemon, P2P mesh)
- **Frontend / Desktop UI**: Flutter (Cross-platform native UI, system tray integration, global shortcuts)
- **Networking**: Local mDNS (`_lynqo._tcp.local`), WebSockets, Cloudflare Tunnel integration

---

<div align="center">

© 2024 Lynqo by mcrudra. All rights reserved.  
*Built with Rust + Flutter. Zero cloud. Zero compromise.*

</div>
