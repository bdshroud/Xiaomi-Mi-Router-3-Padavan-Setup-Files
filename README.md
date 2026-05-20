# Xiaomi-Mi-Router-3-Padavan-Setup-Files
This repository contains all important files required for installing Padavan firmware on the Xiaomi Mi Router 3 (R3).
# Xiaomi Mi Router 3 Padavan Setup Files

This repository contains all important files required for installing Padavan firmware on the Xiaomi Mi Router 3 (R3).

---

# 📦 Download Links

## 1️⃣ VMware Workstation Pro 17.0.2
Used for running the Prometheus build environment.

🔗 Download:  
https://archive.org/download/vmwareworkstationarchive/17.x/VMware-workstation-full-17.0.2-21581411.exe

---

## 2️⃣ Mi-R3-Prometheus
Prometheus build tool for Xiaomi Mi Router 3 Padavan firmware.

🔗 Download:  
https://drive.google.com/file/d/1vYLzELL1Jgel7cj8ZD_FLsfi7QdTYi4w/view?usp=sharing

---

## 3️⃣ MI-3_3.4.3.9L-106-42d790934.trx
Padavan firmware file for Xiaomi Mi Router 3 (R3).

🔗 Download:  
https://drive.google.com/file/d/1zLJvE41HumXKMmK0jC5A_LLRuiajUrV-/view?usp=sharing

---

# ⚠️ Important Notes

- This firmware is ONLY for Xiaomi Mi Router 3 (R3)
- Do NOT flash on R3G or other router models
- Flashing the wrong firmware may brick your router
- Always back up the current firmware/settings before flashing

---

# 🚀 Installation Overview

## Step 1 — Enable SSH
Enable SSH access on MiWiFi stock firmware.

---

## Step 2 — Install Breed Bootloader
Flash Breed bootloader using SSH commands.

---

## Step 3 — Flash Padavan Firmware
Upload `.trx` firmware using Breed Web UI.

---

# 🔧 Default Padavan Login

| Item | Value |
|------|------|
| Router IP | `192.168.123.1` |
| Username | `admin` |
| Password | `admin` |

---

# ✅ Padavan Features

- Better Wi-Fi stability
- USB modem support
- Advanced QoS
- VPN support
- Traffic control
- Better performance than stock firmware
- Improved customization

---

# 🛡️ Recommended After Install

- Change admin password
- Disable WPS
- Configure WPA2-Personal + AES
- Backup router settings
- Set proper Wi-Fi channels

---

# ⚡ Disclaimer

Use at your own risk.  
Custom firmware flashing may void warranty or brick your router if done incorrectly.

---
Privacy, control, and features. As mentioned above, this is great piece of hardware that's held back by lacking software (Not to mention it's all in Chinese (Edit: There's a new english version available as of writing this)). But mainly, I don't trust Xiaomi with the gateway of most of my internet usage; their privacy track record isn't exactly great. Switching it to open source firmware gives me piece of mind.

Padavan feature highlights:

Customizable and intuitive user Interface

Hardware offload support (WAN/LAN)

VPN server/client

USB applications: FTP server, Torrent client (Transmission), SMB Server, UPnP/DLNAMedia Server, iTunes Media Server (Firefly)

Support for Entware or Optware Packages

Support for USB 3G/4G modems

ssh/telnet access

Extra DDNS services

Detailed network traffic graph

AiDisk (share your files over the internet)

SAMBA/FTP/Printer Share (via USB port)

# ❤️ Credits

- Padavan / N56U Community
- Breed Bootloader Developers
- Xiaomi Router Community
- Prometheus Project
