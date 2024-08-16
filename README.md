# Cisco-Packet-Tracer

A glimpse of the virtual internship, I had completed for Cisco using Cisco Packet Tracer tool.

[**Part 1 Problem Statement**](#part-1) | [**Part 1 Proposed Solution**](#proposed-solution)

Cyber Shield: Defending the network

# Problem Statement:

## PART 1:
Analyse your existing university/college campus network topology. Map it out the using Cisco Packet Tracer and identify the security controls that are in place today. Consider and note how network segmentation is done. Observe what kind of intrusion detection systems, firewalls, authentication and authorization systems are in place. Apply the knowledge gained from the NetAcad cyber security course to conduct an attack surface mapping. Aim to identify potential entry points for cyber-attacks. Propose countermeasures to mitigate these risks.
Tasks:
1.	Campus Network Analysis: conduct an analysis of your college campus network topology, including the layout, devices, and connections.
2.	Network Mapping: Utilize Cisco Packet Tracer to map the network infrastructure, representing the placement and interconnectivity of routers, switches, firewalls, and other relevant network components.
3.	Attack Surface Mapping: Conduct an attack surface mapping exercise to identify potential vulnerabilities and weaknesses within the network architecture and design. Consider factors such as unauthorized access, data breaches, and network availability.
Deliverables:
1.	Network topology diagram depicting the existing infrastructure and attack surface findings.
2.	Security assessment report highlighting identified security risks, proposed solutions and countermeasures to mitigate attack surface risks

## Proposed Solution

To achieve a secure and efficient hybrid working environment, given below is the proposed network architecture that incorporates the following components:
1.	Core Layer: Several distribution switches are connected by a 2960 switch that serves as the core.
2.	Distribution Layer: Traffic distribution and VLAN segmentation are managed by several 2960 and 3650 switches.
3.	Access Layer: Access switches (2960), which link endpoints such as servers, PCs, laptops, and printers.
4.	Wireless Layer: Wireless clients are managed by a WLC 3504 wireless access point.

VLAN Segmentation:
Traffic is divided into segments by the network using VLANs, which are defined for VLANs 10, 20, 30, and 40. Although it offers some isolation, this basic type of network segmentation might not be enough for more complex security needs.

Potential Security Risks and Countermeasures
1.	Lack of Perimeter Security: Without a firewall, the network is vulnerable to outside attacks.
Countermeasure: Installing a firewall to filter traffic and stop illegal access at the network's edge.
2.	Inadequate Network segregation: VLANs offer some segregation, but more is required.
Countermeasure: Putting in place more detailed VLANs according to departments, user roles, or vital systems. To limit traffic flow, think about utilizing access control lists (ACLs) and VLAN tagging.
3.	Vulnerable Wireless Network: Attackers can target a wireless network without clear security measures.
Countermeasures: Using network access control (NAC) to limit access to the wireless network, turning on strong encryption (WPA3), and utilizing a reliable authentication method (802.1X).
4.	 Server and Device Vulnerability: Servers and devices without proper patching and configuration are vulnerable to attacks.
Countermeasures: Maintain up-to-date operating systems, applications, and firmware. Implement regular vulnerability scanning and patching.

Network Mapping
 
Part 1 networking architecture on Cisco Packet tracer

Part 1.pkt of the repository shows the proposed architecture for part 1 of the problem statement. The given picture includes two Routers named Router0 and Cloud Router, wherein Router0 serves as the main router connecting to the Multilayer Switch, the Cloud Router, and the Activity Centre. The activity center is like the sports center which is open to all kinds of sports and is the place where the Department of Student Services resides. The Multilayer Switch has the main architecture consisting of a switch connected 3 servers named Server0, Server1, and Server3, and a Wireless LAN Controller named Wireless LAN Controller0 which is used to manage wireless network access points that wireless devices connect to the network. Further, it expands its connection to Admin Block, Learning Center1, Learning Centre2, and Library having a PC, a Laptop, and a Printer to each network and is assigned to an IP address for configuration.
