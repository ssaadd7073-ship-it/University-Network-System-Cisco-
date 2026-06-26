# University-Network-System-Cisco-
University Network System using Cisco packet tracer
# University Campus Network System using Cisco Packet Tracer

## Overview

This project demonstrates the design and implementation of a University Campus Network using Cisco Packet Tracer. The network is divided into multiple departments connected through VLANs, Inter-VLAN Routing, and WAN connectivity. Various network services such as DHCP, DNS, Web Server, FTP Server, and Email Server are configured to simulate a real university environment.

---

## Objectives

- Design a scalable campus network.
- Separate departments using VLANs.
- Enable communication between VLANs.
- Provide automatic IP addressing using DHCP.
- Configure DNS, Web, Email, and FTP services.
- Secure the network using Access Control Lists (ACLs).
- Verify network connectivity using Ping and Traceroute.

---

## Technologies Used

- Cisco Packet Tracer
- Cisco Routers
- Cisco Switches
- VLAN
- Inter-VLAN Routing
- Static Routing
- DHCP
- DNS
- HTTP
- FTP
- Email Server
- ACL (Access Control List)

---

## Network Topology

The university network consists of four departments:

- Administration
- Human Resources (HR)
- Finance
- Computer Science Department

Each department is connected through managed switches and assigned a separate VLAN. A central router performs Inter-VLAN Routing, allowing secure communication between departments.

---

## Features

- VLAN Configuration
- Inter-VLAN Routing
- DHCP Server Configuration
- DNS Server Configuration
- Web Server
- FTP Server
- Email Server
- Static Routing
- Access Control Lists (ACLs)
- Network Testing using Ping and Traceroute

---

## Network Services

### DHCP

Automatically assigns IP addresses to client devices.

### DNS

Resolves domain names to IP addresses.

### Web Server

Hosts the university website for internal users.

### FTP Server

Provides centralized file sharing.

### Email Server

Allows communication through university email accounts.

---

## Security

The following security features are implemented:

- VLAN Segmentation
- Access Control Lists (ACLs)
- Department Isolation
- Controlled Inter-VLAN Communication

---

## Project Structure

```
University-Campus-Network/
│
├── UniversityNetwork.pkt
├── README.md
├── screenshots/
│   ├── topology.png
│   ├── vlan_configuration.png
│   ├── routing.png
│   ├── ping_test.png
│   ├── web_server.png
│   └── email_server.png
└── documentation/
    └── Project_Report.pdf
```

---

## Configuration Highlights

### VLANs

| VLAN | Department |
|------|------------|
| 10 | Administration |
| 20 | Human Resources |
| 30 | Finance |
| 40 | Computer Science |

---

### Routing

- Inter-VLAN Routing
- Static Routing

---

### Services

- DHCP
- DNS
- HTTP
- FTP
- Email

---

## Testing

The following tests were successfully performed:

- PC to PC Communication
- Inter-VLAN Communication
- DHCP Address Assignment
- DNS Name Resolution
- Website Accessibility
- FTP File Transfer
- Email Communication
- Traceroute Verification

---

## Learning Outcomes

Through this project, the following networking concepts were implemented and understood:

- VLAN Design
- IP Addressing
- Routing
- Switching
- DHCP
- DNS
- Email Services
- FTP Services
- Network Security
- Troubleshooting
- Cisco Packet Tracer Simulation

---

## Future Improvements

- OSPF Dynamic Routing
- NAT Configuration
- Firewall Integration
- Wireless Network
- IPv6 Support
- VPN Connectivity
- Redundant Links
- Network Monitoring using SNMP

---

## Author

**Saad Bin Rashid**

Bachelor of Computer Science

University of Central Punjab

LinkedIn:
https://www.linkedin.com/in/saad-rashid-b5801b412

---

## License

This project is intended for educational purposes.
