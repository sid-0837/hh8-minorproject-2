# 🔐 WireGuard VPN with Kill Switch (Windows)

## 📌 Project Overview
This project demonstrates the setup of a **secure WireGuard VPN tunnel** with a **Kill Switch (Key Switch) mechanism on Windows** to prevent data leakage if the VPN connection drops unexpectedly.

The lab focuses on **privacy, secure tunneling, and traffic control**, ensuring that all network traffic is blocked unless the VPN tunnel is active.

---

## 🎯 Objectives
- Configure a secure **WireGuard VPN tunnel**
- Encrypt all outgoing and incoming traffic
- Implement a **Kill Switch on Windows**
- Prevent IP and DNS leaks when VPN disconnects
- Understand low-level network routing and firewall rules

---

## 🛠️ Tools & Technologies Used
- **WireGuard**
- **Windows Defender Firewall**
- **PowerShell**
- **Linux (VPN Server)**
- **Public / Private Key Cryptography**
- **IPv4 Routing**

---

## 🧠 Key Concepts
- VPN tunneling
- Public–Private key authentication
- Encrypted peer-to-peer communication
- Firewall-based traffic filtering
- Fail-safe network security (Kill Switch)

---
## 🏗️ Architecture

[ Windows Client ]
|
| Encrypted Tunnel (WireGuard)
|
[ Linux VPN Server ]
|
|
[ Internet ]
