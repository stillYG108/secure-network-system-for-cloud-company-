# Cloud Company Secure Network

## Scenario
Cloud Company is a rapidly growing cloud solutions provider serving clients worldwide. Due to business expansion, the company is relocating to a new three-floor office building that will accommodate approximately 600 employees across multiple departments.

The departments include:

- Sales and Marketing
- Human Resources and Logistics
- Finance and Accounts
- Administration and Public Relations
- ICT Department
- Server Room

The ICT department consists of Software Developers, Cloud Engineers, Cybersecurity Engineers, Network Engineers, System Administrators, IT Support Specialists, Business Analysts, and Project Managers.

To support business operations, a new secure network infrastructure must be designed and implemented. The network should provide high performance, scalability, redundancy, availability, and strong security while supporting both internal and external communications.

To enhance security, the organization will deploy Cisco ASA firewalls with Inside, Outside, and DMZ security zones. Internal infrastructure services such as Active Directory, DHCP, DNS, and RADIUS servers will reside within the protected internal network, while public-facing services such as Web, FTP, Email, Application, and NAS servers will be hosted in the DMZ.

The company will also utilize cloud computing services to provide access to resources and services for clients and employees worldwide.

---

## Network Components
The proposed network infrastructure includes:

### Internet Connectivity

- Two Internet Service Providers (ISPs) for redundant Internet access.
- ISP-1 (SEACOM)
- ISP-2 (Safaricom)

### Security Infrastructure

- Two Cisco ASA 5500-X Series Firewalls
- Inside, Outside, and DMZ Security Zones
- Security Policies and Access Control

### Routing Infrastructure

- Core Multilayer Switches
- Dynamic Routing using OSPF
- Inter-VLAN Routing

### Switching Infrastructure

- Cisco Catalyst 3850 Core Switches
- Cisco Catalyst 2960 Access Switches
- Hierarchical Network Design

### Server Infrastructure

- Physical Servers supporting Virtualization
- Multiple Virtual Machines providing enterprise services

### Wireless Infrastructure

- Cisco Wireless LAN Controller (WLC)
- Lightweight Access Points (LAPs)
- Centralized Wireless Management

### VoIP Infrastructure

- Cisco Voice Gateway
- IP Telephony Services

---

## Network Requirements
The network must satisfy the following requirements:

1. Implement a hierarchical enterprise network design.
2. Establish connectivity to two Internet Service Providers.
3. Deploy a Wireless LAN Controller and Wireless Access Points for centralized Wi-Fi management.
4. Implement VLAN segmentation using:VLAN 10 – Management
5. VLAN 20 – LAN
6. VLAN 50 – WLAN
7. VLAN 70 – VoIP
8. VLAN 199 – Blackhole VLAN
9. Configure EtherChannel using LACP.
10. Implement VoIP services using a Cisco Voice Gateway.
11. Configure STP PortFast and BPDU Guard.
12. Apply subnetting to allocate address space efficiently.
13. Configure device security including passwords, banners, SSH access, and password encryption.
14. Enable Inter-VLAN Routing using multilayer switches.
15. Configure DHCP services for dynamic IP address allocation.
16. Implement HSRP for gateway redundancy and failover.
17. Configure static addressing for servers.
18. Use OSPF as the dynamic routing protocol.
19. Configure standard ACLs to restrict SSH access to authorized administrators.
20. Configure Cisco ASA firewalls with appropriate security policies and routing.
21. Perform comprehensive testing to verify connectivity, security, and redundancy.

---

## IP Address Allocation
NetworkAddress RangeManagement Network192.168.10.0/24WLAN Network10.20.0.0/16LAN Network172.16.0.0/16VoIP Network172.30.0.0/16DMZ Network10.11.11.0/27ISP-1 Public Network105.100.50.0/30ISP-2 Public Network197.200.100.0/30
---

## Project Goal
Design and implement a secure, scalable, and highly available enterprise network infrastructure capable of supporting approximately 600 users, providing secure access to cloud services, internal resources, wireless connectivity, VoIP communication, and redundant Internet connectivity while maintaining strong security and operational reliability.
