# EthOS

![EthOS Logo](path/to/logo.png)  <!-- optional, replace with your branding -->

**A lightweight, secure, and fully proprietary Linux OS for EthoHome smart devices.**

---

## Overview

**EthOS** is a custom embedded Linux operating system designed specifically for **EthoHome devices** like EthoHub, EthoVoice, and EthoSwitch.  

It is:

- Lightweight and optimized for Raspberry Pi 4/5
- Secure by design, with SSH key-only access and overlay filesystems
- Modular and future-proof, ready for OTA updates and native backend integration

---

## Key Features

- **Minimal OS footprint** – optimized for speed and low memory usage  
- **Native backend execution** – no Docker overhead  
- **Systemd init** – reliable service management  
- **Networking ready** – DHCP, optional Wi-Fi, mDNS  
- **Secure SSH** – key-based authentication  
- **Persistent storage** – `/data` overlay for configs and logs  
- **First-boot provisioning** – host keys, users, and storage ready  
- **Future OTA support** – compatible with RAUC or swupdate  

---

## Architecture

