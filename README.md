# Integrated Faculty Network Infrastructure Simulation 🎓🌐

## Project Overview
This project involves the design and simulation of a robust, scalable, and secure network infrastructure for a University Faculty using **Cisco Packet Tracer**. The design follows the hierarchical network model and incorporates VLANs, Inter-VLAN routing, Wireless connectivity, and Firewall security mechanisms.

## 🏗️ Network Topology
![Topology Diagram](Network_topology.png)


## 🚀 Key Features
* **Hierarchical Design:** Core, Distribution, and Access layers for optimized traffic flow.
* **VLAN Segmentation:** Separated traffic for Management (10), Servers (20), Admin (30), Academic (40), Students (50/60), Workshop (70), Canteen (80), and Guests (90).
* **Server Farm:** Centralized DNS, DHCP, Web, and Database services.
* **Wireless Access:** Wi-Fi coverage for Canteen, Labs, and remote Workshop areas.
* **Security:** Perimeter security using **Cisco ASA Firewall**.
* **Inter-VLAN Routing:** Layer 3 Switching configurations.

## 🛠️ Technologies Used
* **Simulation Tool:** Cisco Packet Tracer (v8.2)
* **Hardware Models:**
    * Routers: Cisco 2911
    * Core/Dist Switches: Cisco 3650 (L3)
    * Access Switches: Cisco 2960 (L2)
    * Security: Cisco ASA 5506 Firewall
    * Wireless: Lightweight & Standalone APs


## 🔧 How to Run
1. Download `Integrated Faculty Network Infrastructure Simulation.pkt`.
2. Open with Cisco Packet Tracer.
3. Wait for STP convergence (or press Alt+D).
4. Test connectivity using Pings or the Web Browser on client PCs.

## 👤 Author
* **E.M.S. EKANAYAKE**
* Faculty of Technology, University of Sri Jayewardenepura
