# CiscoPacketTracer-project26-High-Density-Office-LAN-509PCs-in-Finance-VLAN-with-Centralised-Services
I’m pleased to share my latest Cisco Packet Tracer project – a dedicated Finance department network featuring 509+ desktop PCs (PCF1 … PCF509) all operating within a single VLAN (VLAN 20) or multiple access switches.

![image alt](https://github.com/Sameera54321/CiscoPacketTracer-project26-High-Density-Office-LAN-509PCs-in-Finance-VLAN-with-Centralised-Services/blob/main/11.png?raw=true)

## 📌 Summary

### Finance Department Network is a Cisco Packet Tracer simulation that models a large finance office with 509+ workstations (PCF1 through PCF509). The entire department is isolated in its own VLAN (e.g., VLAN 20) to ensure security and broadcast control. The topology typically includes:

    Multiple access switches (e.g., 2960‑24TT) to connect all PCs

    A distribution or core switch aggregating traffic

    A router or Layer 3 switch for inter‑VLAN routing (if other departments exist)

    A central server providing DHCP, file sharing, or financial database access

### The project focuses on:

    VLAN creation and port assignment for 500+ access ports

    Switch stacking or trunking to handle high host counts

    DHCP configuration (on router or server) with a large IP scope (e.g., /23 subnet)

    Port security (sticky MAC, maximum MAC addresses) on access ports

    Spanning‑Tree Protocol (STP) to prevent loops in redundant links

    Performance observation – broadcast traffic, CAM table utilisation, etc.

## ✨ Features

    ✅ 509+ workstations (PCF1 … PCF509) – realistic large department

    ✅ Dedicated Finance VLAN (e.g., VLAN 20) – isolates traffic from other departments

    ✅ Multiple Cisco 2960 switches – provide sufficient access ports

    ✅ DHCP service – automatic IP assignment for all PCs

    ✅ Central server (optional) – file, print, or database services for Finance

    ✅ Port security – prevents rogue device connections

    ✅ Scalability demonstration – handle 500+ hosts in a single broadcast domain (or routed)

    ✅ Full Packet Tracer file (.pkt) – ready to open and test

    ✅ Documentation – IP addressing plan, VLAN mapping, switch configs, DHCP scope

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – switch, router, and server configurations

    (Optional) Python – if used to generate PC hostnames or IP lists

## 🤝 Contributing

Contributions are welcome! To extend this lab:

    Fork the repository.

    Add more departments (e.g., HR, IT) with their own VLANs and inter‑VLAN routing.

    Implement VTP (VLAN Trunking Protocol) for centralised VLAN management.

    Add access control lists (ACLs) to restrict Finance access to other networks.

    Introduce redundant links and test STP convergence.

    Set up a syslog server to monitor switch port events.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
