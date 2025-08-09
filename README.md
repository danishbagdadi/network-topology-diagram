# network-topology-diagram

This repository contains a network diagram for an office setup.

## Diagram Overview

The attached diagram shows how devices in an office connect securely to the Internet. The design applies strong security with clear separation between different network parts using a firewall.

**Main components in the diagram:**
- **Internet:** The source for remote connections.
- **Router:** Receives and distributes Internet data to our network.
- **Firewall:** Protects all internal systems, filters unwanted traffic, and enforces security zones.
- **Switch:** Connects local devices like workstations, printers, and Wi-Fi access points.
- **Web Server:** Hosts our website.
- **Mail Server:** Handles our office emails.
- **VPN Server:** Allows secure connections for remote staff.
- **IDS/IPS:** Monitors traffic to detect and prevent threats.

**How the network works:**
1. The router brings in Internet traffic and sends it to the firewall.
2. The firewall splits traffic: only allowed connections proceed to servers and office devices.
3. The switch connects computers, printers, and our Wi-Fi access point for daily office use.
4. Servers (web, mail, VPN) sit behind the firewall for protection but are accessible as needed.
5. IDS/IPS monitors traffic between the firewall and servers for extra security.

## Author & Version Info

Created by [Danish Bagdadi]  
Version: 1.0  
Date: August 10, 2025

