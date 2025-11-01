# meshtastic-alt-il
Community guide for configuring Meshtastic devices with our shared frequency, encryption, and network settings.
# Community telegram 
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
- Optional integrations (MQTT, Android, Node-RED, etc.)

---

## 🛠 Getting Started

### 1. Flash Your Device
Use the [Meshtastic Flasher](https://flasher.meshtastic.org/) or `esptool` to install the latest firmware.

### 2. Load Our Configuration
You can import the shared `.toml` or `.json` config from [config/](config/) directory:
```bash
meshtastic --configure ./config/community.toml

