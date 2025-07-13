Mobilink Secure Network Solution
This repository contains the design, configurations, and documentation for a secure, scalable, and efficient enterprise network for Mobilink Pakistan, developed to meet specific organizational requirements.

📋 Project Overview
The project implements:

VLAN segmentation for departmental isolation.

ACLs to enforce communication policies.

DHCP & DNS services from NOC for all users.

Secure switch configurations with port security.

Spanning Tree Protocol (STP) validation.

Multi-area OSPF with route summarization.

Optimized IPv4 addressing to minimize wastage.

Varied serial link bandwidths to avoid conflicts.

📝 Requirements Addressed
✔ IT department staff can ping and Telnet all users;
✔ Other users can only ping IT staff and nothing else;
✔ Only ICMP, DNS, DHCP, and HTTP traffic allowed to NOC, rest filtered;
✔ IT department switches secured with port security, shutting down on violation;
✔ STP enabled & observed in SMT network;
✔ VLANs configured for SMT postpaid & prepaid users in Area 1;
✔ OMD cannot connect to SMT postpaid users or NOC webserver;
✔ PB department cannot access Prepaid Subscriber Management team;
✔ DHCP server in NOC allocates IPv4 to all departments;
✔ DNS properly configured and accessible where not restricted;
✔ Multi-area OSPF with summarization implemented;
✔ IP addresses allocated with minimal wastage;
✔ Unique bandwidth assigned to each serial link.

🗂 Repository Structure
PacketFile (Cisco Packet Tracer)
Report.doc
LICENSE
README.md

⚙️ Technologies & Protocols
VLANs

ACLs

DHCP

DNS

STP

OSPF (multi-area with summarization)

Telnet & ICMP

🔒 License
This project is licensed under the  Apache 2.0 License.

👨‍💻 Author
  University Porject
  Muhammad Talha Ali Butt (MuhammadTalha988516)
