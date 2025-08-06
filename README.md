# Basic VLAN and Inter-VLAN Routing Lab (CCNA)

This project simulates a small office network using VLAN segmentation and inter-VLAN routing via Router-on-a-Stick. It was built in Cisco Packet Tracer and demonstrates core CCNA concepts.

---

## 🖧 Topology Overview

- 2 VLANs: HR (10) and IT (20)  
- 1 Cisco 2960 Switch  
- 1 Cisco 1941 Router  
- 4 PCs (2 per VLAN)  
- Router-on-a-Stick configuration with sub-interfaces  

---

## 🧱 IP Addressing and VLANs

| VLAN | Name | Subnet          | Gateway        | Devices         |
|-------|------|-----------------|----------------|-----------------|
| 10    | HR   | 192.168.10.0/24 | 192.168.10.1   | HR-PC1, HR-PC2  |
| 20    | IT   | 192.168.20.0/24 | 192.168.20.1   | IT-PC1, IT-PC2  |

---

## ⚙️ What I Configured

- VLANs on the switch  
- Port assignment for VLANs  
- Trunk port to router  
- Sub-interfaces on router for inter-VLAN routing  
- Static IPs and default gateways on PCs  

---

## ✅ Testing Results

- Pings between same-VLAN devices ✅  
- Pings across VLANs (inter-VLAN) ✅  
- Pings to default gateways ✅  

---

## 🧠 What I Learned

This lab helped me understand:  
- How VLANs improve network segmentation  
- How to configure trunk ports on switches  
- How routers enable communication between VLANs using Router-on-a-Stick  
- Static IP addressing and connectivity testing with ping  

---

## 💼 Built With

- Cisco Packet Tracer 8.x (or latest)  
- Cisco 1941 Router  
- Cisco 2960 Switch  

---

## 📁 Folder Structure

- `PacketTracerFiles/` — The `.pkt` file to open in Cisco Packet Tracer  
- `Configurations/` — Router and switch configuration files  
- `Diagrams/` — Network topology image  

---

## 📷 Topology

![Network Topology](Diagrams/topology.png)
