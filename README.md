# CN_project

# Computer Network Topology with VLAN, NAT, Subnetting, EIGRP, OSPF, RIP

**Overview**
The Computer Network Topology project aims to create a comprehensive and scalable computer network topology using various networking concepts such as VLANs, NAT, subnetting, EIGRP, OSPF, RIP, and more. This project provides a practical and hands-on approach to network design, allowing users to understand and implement key networking protocols and technologies. The goal is to create a functional and secure network infrastructure with specific requirements.

# Features
The network is divided into three blocks, each utilizing different routing protocols and VLAN configurations:
# Dynamic Routing Protocols:

## First Block:
**EIGRP (Enhanced Interior Gateway Routing Protocol):**
Implement EIGRP for efficient routing within the network.

## Second Block:
**OSPF (Open Shortest Path First):**
Configure OSPF for dynamic routing and link-state advertisement.
OSPF with Area 1.

## Third Block:
**RIP (Routing Information Protocol):**
Use RIP for simple and straightforward routing.

## Last Block:
OSPF with Area 0.

# InterConnection
## Redistribution
Implemented on Router8 and Router21 to connect OSPF with OSPF and OSPF with RIP.

# Network Address Translation (NAT):
Configure NAT to allow private network devices to access the internet using a single public IP address.

- Implemented on a router with Network G.
- Used the provided Public IP Address for NAT.

# IP Address Assignment
## DHCP Server
Provides IP addresses to hosts in OSPF Area 1, RIP, and EIGRP.
## DHCP Server for VLAN's
Provides IP addresses to hosts in OSPF Area 0.

# VLAN Implementation:
Design and implement Virtual LANs (VLANs) to logically segment the network and enhance performance and security.

## VLAN Configuration
VTP (VLAN Trunking Protocol)
3560 switch acts as a server. Other switches act as clients.
## VLAN Routing
- Implemented using router-on-a-stick technique.
- VLANs hosts can communicate within the same VLAN.
- Inter-VLAN communication is established between VLAN 20 and VLAN 40.
- 
# Access Control
Access control is implemented between various hosts and servers based on the specified requirements.

# Restrictions and Special Configurations
Specific restrictions are applied as mentioned in the scenario, such as TFTP server access, Data server access, etc.

# Address Table
A comprehensive address table outlining all IP configurations for the network is provided in the attached document.
**Subnetting:**
Divide the network into subnets to optimize IP address utilization and manage network traffic efficiently.


# Technology Stack
**Network Simulation Tool:** Cisco Packet Tracer
**Routing Protocols:** EIGRP, OSPF, RIP
**VLAN Configuration:** Cisco 3 layered switches
**NAT Implementation:** Cisco routers
**Subnetting:** IPv4 addressing


# How to Run
To simulate the Computer Network Topology, follow these steps:

Select Network Simulation Tool: Choose a network simulation tool compatible with the project requirements (e.g., Cisco Packet Tracer).

Import Topology File: Load the provided topology file or manually configure devices, connections, and settings based on the project specifications.

Start Simulation: Run the simulation and observe the behavior of VLANs, NAT, subnetting, and routing protocols within the network.







