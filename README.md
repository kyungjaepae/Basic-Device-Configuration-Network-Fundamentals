Basic Device Configuration & Network Fundamentals Lab


Overview:
This lab focuses on fundamental networking concepts, including device configuration, IP addressing, subnetting, and basic connectivity testing using Cisco Packet Tracer.


Objectives:
- Set up a simple network with two PCs connected via a switch.
- Configure IP addresses and subnet masks.
- Verify network connectivity using ping.
- Document the network topology.


Network Topology:
Devices
- 2 PCs
- 1 Switch (Cisco 2960)

IP Addressing Scheme
- PC1: 192.168.1.10 / 255.255.255.0
- PC2: 192.168.1.20 / 255.255.255.0

Connections
- PC1 → Switch (FastEthernet 0/1)
- PC2 → Switch (FastEthernet 0/2)


Steps to Complete the Lab:
1. Set Up the Network in Packet Tracer
- Open Cisco Packet Tracer and create a new project.
- Add a Cisco 2960 switch to the workspace.
- Add two PCs and connect them to the switch using straight-through cables.

2. Configure IP Addresses
- Click on PC1, go to Desktop > IP Configuration, and assign:
- IP Address: 192.168.1.10
- Subnet Mask: 255.255.255.0

- Click on PC2, go to Desktop > IP Configuration, and assign:
- IP Address: 192.168.1.20
- Subnet Mask: 255.255.255.0

3. Verify Connectivity
- Open the Command Prompt on PC1.
- Run the following command:
```
ping 192.168.1.20
```
- If the ping is successful, connectivity is established.
- Repeat the ping test from PC2 to PC1.

4. Document the Network Diagram
- Use the "Place Note" tool in Packet Tracer to label devices.
- Save the project as .pkt file for future reference.
