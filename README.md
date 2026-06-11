# Cloud Company Secure Network System

A comprehensive secure network infrastructure project designed for Cloud Company, a rapidly growing cloud solutions provider with approximately 600 employees across multiple departments.

---

## 📁 Project Files

This project contains the following documentation and design files:

| File | Description |
|------|-------------|
| **Cloud_Company_Secure_Network.md** | Project scenario, business requirements, network components, and IP address allocation |
| **designing and implementation of secure company network system.pkt** | Cisco Packet Tracer network simulation with complete topology and device configurations |
| **[Cloud_Company_Network_Documentation.pdf](Cloud_Company_Network_Documentation.pdf)** | Comprehensive network documentation and implementation guide |

---

## 🎯 Project Overview

**Organization:** Cloud Company - Cloud Solutions Provider  
**Employees:** ~600 across 3-floor office building  


### Key Network Components

- **Firewalls:** Cisco ASA 5500-X Series (dual redundant)
- **Core Switches:** Cisco Catalyst 3850 Multilayer Switches
- **Access Switches:** Cisco Catalyst 2960 Series
- **Wireless:** Cisco WLC with Lightweight Access Points
- **Routing:** OSPF with HSRP gateway redundancy
- **Internet:** Dual-ISP (SEACOM & Safaricom)

### Network Segmentation

| VLAN | Name | Network | Purpose |
|------|------|---------|---------|
| 10 | Management | 192.168.10.0/24 | Network administration |
| 20 | LAN | 172.16.0.0/16 | Employee workstations |
| 50 | WLAN | 10.20.0.0/16 | Wireless access |
| 70 | VoIP | 172.30.0.0/16 | Voice telephony |
| 199 | Blackhole | N/A | Null routing |

---

## 🚀 Quick Start

1. **Understand the Project:** Read [Cloud_Company_Secure_Network.md](Cloud_Company_Secure_Network.md)
2. **View the Network:** Open the Packet Tracer file in Cisco Packet Tracer
3. **Explore the Design:** Review network topology, security zones, and device configurations

---

## 📊 Key Features

✅ **High Availability** - Dual ISP connectivity, redundant firewalls, HSRP gateway failover  
✅ **Security** - Firewall zones (Inside, Outside, DMZ), ACLs, VLAN isolation  
✅ **Scalability** - Modular design supporting growth to 1,200+ employees  
✅ **Redundancy** - EtherChannel aggregation, dual core switches, VM cluster support  
✅ **Enterprise Services** - Active Directory, DHCP, DNS, RADIUS, VoIP, NAS

---

*Project Date: June 10, 2026*
