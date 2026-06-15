# 🏢 Small Business Network Design — HSK Company

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Cisco%20Packet%20Tracer-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" />
  <img src="https://img.shields.io/badge/Protocol-VLAN%20%7C%20DHCP%20%7C%20PAT-4B4B4B?style=for-the-badge&logo=cisco&logoColor=white" />
  <img src="https://img.shields.io/badge/Security-SSH%20%7C%20TFTP-E22C2C?style=for-the-badge&logo=cisco&logoColor=white" />
  <img src="https://img.shields.io/badge/Architecture-Router--on-a--Stick-green?style=for-the-badge&logo=cisco&logoColor=white" />
</p>

> 🏢 A secure, fully functional Cisco-based small business network designed for **HSK Company** — supporting Management, Operations, and Sales departments with VLAN segmentation, inter-VLAN routing, DHCP automation, PAT internet access, SSH remote management, and TFTP configuration backup.

---

## 📌 Overview

This project demonstrates end-to-end design and implementation of a **small business network** using Cisco Packet Tracer. The network supports three internal departments with isolated VLANs, automated IP management, secure internet access, and encrypted remote administration — reflecting real-world SMB network deployments.

---

## 🏗️ Network Architecture

### Departments & VLANs

| VLAN | Department | Purpose |
|------|-----------|---------|
| VLAN 10 | Management | IT administration and network management |
| VLAN 20 | Operations | Core business operations team |
| VLAN 30 | Sales | Customer-facing sales team |

### Design Pattern
- **Router-on-a-Stick** — single router interface with sub-interfaces for inter-VLAN routing
- **Trunking** — 802.1Q trunk between router and switch carrying all VLANs
- **PAT** — all internal hosts share a single public IP for internet access

---

## 🛠️ Technologies Implemented

### 🌐 Network Design
- **VLAN Segmentation** — isolated broadcast domains per department
- **802.1Q Trunking** — VLAN traffic between router and switch
- **Router-on-a-Stick** — inter-VLAN routing via sub-interfaces
- **Subnetting** — custom IP addressing scheme per VLAN

### 🔄 IP Services
- **DHCP** — automated IP assignment for all department VLANs
- **PAT (Port Address Translation)** — internet access for all internal hosts via single public IP
- **Default routing** — traffic forwarding to ISP gateway

### 🔒 Security & Management
- **SSH** — encrypted remote device management (Telnet disabled)
- **TFTP Backup Server** — automated configuration backup and restoration
- **Access Control** — privileged access restricted via AAA-style local authentication

---

## 🔑 Key Accomplishments

- ✅ Designed a complete multi-department VLAN network from scratch
- ✅ Configured Router-on-a-Stick for inter-VLAN communication
- ✅ Automated IP assignment across all VLANs using DHCP pools
- ✅ Enabled internet access for all departments via PAT
- ✅ Secured remote management using SSH — Telnet fully disabled
- ✅ Implemented TFTP-based configuration backup and verified restore process
- ✅ Verified end-to-end connectivity across all VLANs and to the internet

---

## 🗺️ Network Topology

![Network Topology](https://private-user-images.githubusercontent.com/260146593/607231727-57d59c54-25bd-41d4-91e1-858f6f99e07d.png)

> Full topology diagram available in `P1-Small Business Company Network Design.pdf`

**High-level layout:**

<img width="1288" height="860" alt="image" src="https://github.com/user-attachments/assets/57d59c54-25bd-41d4-91e1-858f6f99e07d" />

---

## 📋 Implementation Steps

| Step | Task |
|------|------|
| 1 | IP addressing scheme and subnet planning |
| 2 | Switch VLAN creation and port assignment |
| 3 | Trunk port configuration between router and switch |
| 4 | Router sub-interface configuration (Router-on-a-Stick) |
| 5 | DHCP pool creation per VLAN |
| 6 | PAT configuration for internet access |
| 7 | Default route to ISP gateway |
| 8 | SSH configuration and Telnet disabling |
| 9 | TFTP server setup and config backup |
| 10 | End-to-end connectivity testing |

---

## 📁 Repository Contents

```
📦 Small-Business-Network-Design
├── 📄 README.md
└── 📋 P1-Small Business Company Network Design.pdf   ← Full report & topology
```

---

## 🧠 Skills Demonstrated

`VLAN Design` `Router-on-a-Stick` `Inter-VLAN Routing` `DHCP` `PAT` `SSH` `TFTP` `Subnetting` `Cisco IOS` `Cisco Packet Tracer` `Network Security` `SMB Network Design` `Trunking`

---

## 💡 Real-World Relevance

Small business networks are the foundation of enterprise networking. This project demonstrates skills applicable to:
- **Network Administrator** roles — VLAN, DHCP, and routing configuration
- **Security+ / CCNA** exam domains — NAT, VLANs, SSH, access control
- **SOC Analyst** roles — understanding segmented network traffic flows
- **PhD research** — baseline network architecture for security research environments

---

## ⚠️ Disclaimer

This project was designed and implemented in Cisco Packet Tracer for academic and educational purposes. All company names, IP addresses, and configurations are fictitious.

---

## 👤 Author

**Hashan Kodippilige**  
M.S. Cybersecurity — Minnesota State University Moorhead  
📧 hashansharindu@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/hashankodippilige/)  
🐙 [GitHub](https://github.com/hashan-kodippilige)
