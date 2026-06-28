# Enterprise Network Design — Sakura Corp

> Academic project for Data Communication & Computer Networks course — COMSATS University Lahore

---

## 📌 Overview
Designed and implemented a full enterprise network for a 3-site company (Head Office + 2 branches) using Cisco Packet Tracer.

---

## 🏢 Network Topology
- **Head Office** — Server Farm (DHCP, DNS, HTTP servers)
- **Branch A** — Connected via WAN serial links
- **Branch B** — Connected via WAN serial links

---

## ⚙️ Features Implemented
- **VLSM** — Variable Length Subnet Masking for efficient IP allocation
- **OSPF** — Dynamic routing protocol configured in Area 0 across all sites
- **DHCP Relay** — PCs across branches receive IPs from central DHCP server
- **Router-on-a-Stick** — Inter-VLAN routing at Head Office
- **VTP v2** — VLAN Trunk Protocol for VLAN management
- **Port Security** — MAC address based access control on switches
- **Extended ACLs** — Restricting guest traffic from accessing server farm
- **HTTP Server** — Web server accessible from all branches

---

## 🛠️ Tech Stack
| Component | Technology |
|-----------|-----------|
| Simulation Tool | Cisco Packet Tracer |
| Routing Protocol | OSPF (Area 0) |
| IP Addressing | VLSM |
| Switching | VTP v2, Port Security |

---

## 👤 Author
**Muhammad Saad Junaid**
Computer Engineering Student — COMSATS University Lahore
🔗 [LinkedIn](https://linkedin.com/in/m-saad-junaid)
