# -Campus-Network-Using-Wireless-LAN
Simulated a university-wide wireless LAN in Cisco Packet Tracer, integrating DNS, Email, and Web servers with secure protocols and subnetting for scalable, reliable connectivity.
## 📜 Introduction

This project involves designing a **wireless network** for a university that connects students, faculty, and administrative staff.  
The network spans **academic blocks, hostels, library, and IT consulting areas**, enabling smooth internet access and communication.  

It includes:
- **DNS, Email, and Web servers** for resource sharing and communication.
- **Secure protocols** like SSH and console passwords.
- **Segmentation** for efficient traffic management between campus and hostel areas.

---

## 🎯 Objectives

1. Design a university wireless network using Cisco Packet Tracer.
2. Ensure reliable internet access across campus.
3. Set up DNS, Email, and Web servers.
4. Provide secure and dependable network connections.
5. Make the network scalable for future expansion.
6. Enhance collaboration and data sharing.

---

## 🛠️ Tools & Technologies

- **Cisco Packet Tracer** (Network simulation)
- Networking devices:
  - Routers (Cisco 1941)
  - Switches (Cisco 2960-24TT)
  - Wireless Access Points
  - PCs, Laptops, Smartphones
  - Servers (DNS, Email, HTTP/Web)

---

## 📐 Network Topology

**Main Components:**
- **Core Router** connected to:
  - Server Switch (connected to DNS, Email, Web servers)
  - Campus Router (serving academic blocks & library)
  - Hostel Router (serving boys' and girls' hostels)
- **Wireless Access Points** in each building for mobile device connectivity.
- **Segmentation** into campus and hostel subnets.

---

## 📊 Device & IP Addressing

- Example from **OC Lab 1**:  
- 192.168.1.14 - Laptop
- 192.168.1.15 - PC
- Subnet Mask: 255.255.255.0
- Default Gateway: 192.168.1.1
- DNS Server: 192.168.2.3

Example from **Boys Hostel**:  
- 192.168.3.6 - PC
- 192.168.3.9 - Smartphone
- Subnet Mask: 255.255.255.0
- Default Gateway: 192.168.3.1
- DNS Server: 192.168.2.3


*(Full IP table included in project files)*

---

## ⚙️ Implementation Steps

1. **Placed core devices** (routers, switches, servers) in Cisco Packet Tracer.
2. Connected:
   - Core Router to Server Switch (Copper straight-through cable).
   - Campus Router and Hostel Router (Serial DCE cable).
3. Configured DNS, Email, and Web servers.
4. Connected switches to **Home Routers** in academic blocks and hostels.
5. Connected PCs, laptops, and smartphones to wireless access points.
6. Configured IP addresses, gateways, and DNS settings.
7. Implemented **console passwords & SSH** for secure remote access.

---

## 🔒 Security Measures

- SSH Protocol for secure data transfer.
- Console passwords for device access control.
- Network segmentation to control traffic flow.

---

## 📌 Features

- Wireless connectivity in all major campus locations.
- Centralized server system for resource sharing.
- Mobility support for laptops and smartphones.
- Scalability for future expansion.

---

## 📜 Conclusion

This project successfully demonstrates the implementation of a **wireless LAN-based campus network** in Cisco Packet Tracer.  
It meets the requirements for **mobility, scalability, and security**, ensuring students and staff have reliable access to resources and services.

---

## 💡 Skills Demonstrated

- Network Design & Simulation
- Wireless LAN Configuration
- Subnetting & IP Addressing
- Server Configuration (DNS, Email, Web)
- Secure Remote Access (SSH)
- Network Troubleshooting

---
