# Static Routing & Subnetting Network Simulation

## Overview
[cite_start]This project is a complete network topology simulation built using Cisco Packet Tracer[cite: 9, 11]. It demonstrates practical skills in network design, IP address planning, and manual routing configuration to achieve full end-to-end connectivity.

## Topology Architecture
The simulated network consists of:
* [cite_start]**3 Routers** connected via Serial interfaces (`Se0/1/0`, `Se0/1/1`)[cite: 12, 13, 14, 15].
* [cite_start]**3 Switches** connecting the local area networks to the routers via FastEthernet interfaces (`Fa0/0`, `Fa0/1`)[cite: 7, 8, 18, 19, 20].
* [cite_start]**6 End Devices (PCs)** distributed across three distinct subnets[cite: 31].

## Key Concepts & Implementation
* [cite_start]**IP Addressing & Subnetting:** Calculated and distributed appropriate IP addresses across the network[cite: 31]. [cite_start]This includes determining subnet masks and classifying addresses (Classful/Classless, Public/Private)[cite: 35, 36].
* [cite_start]**Interface Configuration:** Assigned IPs to both router interfaces and end devices, ensuring correct default gateway settings for each PC[cite: 31, 37].
* [cite_start]**Static Routing:** Implemented static routing commands across all routers to establish full communication between non-adjacent networks[cite: 41].
* [cite_start]**Network Verification:** Tested and analyzed connectivity pre- and post-routing configuration using standard verification tools, including inspection of the routers' routing tables[cite: 38, 39, 42].

## Tools & Technologies
* [cite_start]Cisco Packet Tracer [cite: 9]
* Networking Protocols (IPv4, Static Routing)

## How to Run
1. Clone this repository to your local machine.
2. Open the `.pkt` file using Cisco Packet Tracer.
3. Access the CLI of any PC and use the `ping` command to test connectivity to devices in different subnets.
4. Access the Routers' CLI and use `show ip route` to inspect the routing tables.
