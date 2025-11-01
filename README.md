# Meshtastic-alt-il 
Community guide for configuring Meshtastic devices with our shared frequency, encryption, and network settings.
# Telegram community
https://t.me/+QtB8ra5kUtE3OTVk

# Meshtastic Community Setup Guide 🌐

Welcome to our shared Meshtastic configuration project!  
This guide explains how to set up your device to join our community mesh network.

---

## 📡 Overview

This document helps users configure their Meshtastic devices with:
- The correct frequency and modem settings
- Shared channel name and encryption
- Recommended hardware and power setups

---

## 🛠 Getting Started

### 1. Flash Your Device
Use the [Meshtastic Flasher](https://flasher.meshtastic.org/) to install the latest firmware.

### 2. Load Our Configuration
You can import the shared `.toml` or `.json` config from [config/](config/) directory:

meshtastic --configure ./config/community.toml

## ⚙️ Configuration Summary


| Parameter | Setting | Notes |
|------------|----------|-------|
| **Region** | United States | Set this in device settings |
| **Preset** | Long and Fast | Good balance of range and latency |
| **Frequency Slot** | 70 | |
| **Center Frequency** | 919.375 MHz | |
| **MQTT** | ✅ Enabled | OK to use with community broker |
| **Transmission** | ✅ Enabled | |
| **Max Hops** | 7 | Recommended for stable mesh performance |

```bash
sss
