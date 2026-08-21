# 🌐 OpenWrt Manager

![Flutter Version](https://img.shields.io/badge/Flutter-v3.x-02569B?logo=flutter)
![Dart Version](https://img.shields.io/badge/Dart-v3.x-0175C2?logo=dart)
![OpenWrt Compatible](https://img.shields.io/badge/OpenWrt-19.07%20|%2021.02%20|%2022.03%20|%2023.05-blue?logo=openwrt)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A modern, fast, and feature-rich native mobile application (Android/iOS) built with **Flutter** to monitor, manage, and configure **OpenWrt** routers. 
Designed as a sleek and native alternative to the LuCI web interface, it communicates directly with the router via **UBUS RPC** and shell commands.

## ✨ Key Features

### 📊 Real-Time Dashboard
* Live network traffic monitoring (Download/Upload speeds).
* CPU, RAM, and Load Average tracking.
* **Advanced 4G/5G Modem Support:** Smart detection of cellular interfaces (QMI, MBIM, NCM), accurate WAN IP extraction, and connection status.

### 📱 Connected Devices
* Intelligent detection of connected clients.
* Accurately distinguishes between **Wi-Fi** (Blue) and **Ethernet/Wired** (Green) devices using advanced ARP, DHCP leases, and `iwinfo` / `hostapd` data.
* Device categorization with smart icons (Phones, Consoles, TVs, Laptops).

### 🛡️ Firewall & Security (LuCI Parity)
* **Flow Offloading:** Native toggle for Software, Hardware, and None, fully synchronized with router defaults.
* **Zone Management:** Create and edit Firewall Zones (LAN, WAN, VPN, Guest) with Advanced and Conntrack settings.
* Traffic Rules & Port Forwarding (NAT) management.

### ⚙️ System & Network Control
* **Wi-Fi:** Enable/disable radios, change SSID, Encryption, and Passwords.
* **DHCP & DNS:** Full control over `dnsmasq` and `odhcpd` (IPv4/IPv6 leases, static IPs).
* **Package Management:** Browse and install OPKG packages directly from the app.
* **System Tools:** View System Logs (`logread`), manage Services/Daemons, Backup/Restore, and Firmware upgrades.
* **Diagnostics:** Built-in Ping, Traceroute, and a fallback LuCI WebView.

---

## 📸 Screenshots

*(Replace these placeholder links with actual screenshots of your app once uploaded to GitHub)*

| Dashboard | Connected Clients | Firewall & Offloading |
| :---: | :---: | :---: |
| <img src="https://via.placeholder.com/250x500.png?text=Dashboard" width="250"> | <img src="https://via.placeholder.com/250x500.png?text=Clients" width="250"> | <img src="https://via.placeholder.com/250x500.png?text=Firewall" width="250"> |

---
# STAY TUNED
