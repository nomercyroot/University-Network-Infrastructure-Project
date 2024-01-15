Project Description: University Network Infrastructure Project

In today's rapidly evolving educational landscape, institutions must harness the power of modern technology to provide the best education and effectively manage academic processes. Our project, named "University Network Infrastructure Project," is designed to offer a comprehensive solution to meet the communication and network management needs of universities.

Advantages of the Project:
Modular Infrastructure: University Network Infrastructure Project accommodates the size and complexity of university networks through a modular structure. This modular design provides a customizable and scalable solution tailored to the specific needs of each university.

Rapid Deployment:
The project streamlines network configuration in university environments through rapid deployment features. Automatic configuration and user-friendly interfaces save time for system administrators, accelerating academic processes.

Robust Security:
With a security-focused design, University Network Infrastructure Project prioritizes the safety of student information. Integrated security protocols and network monitoring capabilities effectively protect university networks against potential threats.

High Performance:
The project offers high performance and low latency, facilitating fast and seamless data transmission for students, faculty, and administrative staff over the network.

Scalability:
University Network Infrastructure Project is built with scalability in mind. It seamlessly integrates new students, devices, or departments to address future growth requirements.

Project Features:

Router Configuration: 
The project facilitates university network management through router configurations implemented on Cisco Packet Tracer.
VLAN-Based Network Structure:
University Network Infrastructure Project aims to manage network traffic effectively between different departments by providing a VLAN-based structure.
OSPF Protocol Integration: 
Effective routing is ensured through the integration of the Open Shortest Path First (OSPF) protocol among routers in the network. This contributes to a reliable and optimized communication infrastructure for university networks.
VLAN Management: 
The project focuses on creating and managing VLANs at switch points in university networks, enhancing control over network traffic.


Firewall and Access Control: 
University Network Infrastructure Project enhances network security by providing firewalls and access control, offering robust protection against unauthorized access.University Network Infrastructure Project aims to significantly contribute to the digital transformation of modern university management, fostering improved interaction and collaboration among students, faculty, and administrative staff.


Cisco Router and Switch Configurations

Fen-R:
On the Fen-R router, three separate VLANs (10, 11, 12) and corresponding subnets are configured.
Additionally, a trunk connection is established on VLAN 19, providing access to a subnet associated with this VLAN.

Ede-R:
The Ede-R router has a similar structure to Fen-R. Three separate VLANs (20, 21, 22) and subnets associated with VLAN 29 are configured.

BiM-R:
The BiM-R router has a slightly different structure. It is associated with four VLANs (100, 101, 102, and 109), each linked to a specific subnet.

FEN-OMG:
On the FEN-OMG switch, a port is configured for VLAN 19, providing access to the 192.168.19.0/24 subnet.

EDE-OMG:
On the EDE-OMG switch, a port is configured for VLAN 29, providing access to the 192.168.29.0/24 subnet.

BiM-OMG:
The BiM-OMG switch is configured with both trunk and access ports. It accommodates ports associated with VLANs 100, 101, 102, and 109.
F-Kat1, F-Kat2, F-Kat3:
These three switches respectively house ports associated with VLANs 10, 11, and 12.
E-Kat1, E-Kat2, E-Kat3:

These three switches respectively house ports associated with VLANs 20, 21, and 22.
Each configuration is tailored to the requirements of the respective network layout. Communication between VLANs and subnets is facilitated by the OSPF protocol running between routers. Additionally, VLAN information is distributed and synchronized among switches using the VLAN Trunking Protocol (VTP). To ensure the proper functioning of these configurations, it is essential to verify that the physical connections are accurately configured.

