# Enterprise Network Simulation

## Overview

This project demonstrates the design and implementation of a simulated enterprise network using Cisco Packet Tracer.

The network includes VLAN segmentation, dynamic routing, DHCP services and access control to emulate a small enterprise environment.

---

## Technologies

- Cisco Packet Tracer
- Cisco IOS
- VLAN
- Inter-VLAN Routing
- OSPF
- DHCP
- ACL

---

## Network Topology

![Topology](./screenshots/Topology.png)

---

## Key Features

- Multi-VLAN enterprise network
- Dynamic routing using OSPF
- DHCP address allocation
- Access Control Lists (ACL)
- Router-on-a-Stick configuration
- Network troubleshooting and verification

---

## Verification

Example verification commands:

show ip route
![routing-table](./screenshots/routing-table.png)
show vlan brief
![vlan](./screenshots/vlan.png)
show ip ospf neighbor
![ospf-neighbor](./screenshots/ospf-neighbor.png)
ping
![Ping-test](./screenshots/ping-test.png)
