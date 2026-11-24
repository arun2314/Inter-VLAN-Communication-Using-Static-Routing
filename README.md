# VLAN-Based-Network-Design
Cisco Packet Tracer project demonstrating VLAN segmentation, IP addressing, switches, routers, and inter-network connectivity.
# Inter-VLAN Communication Using Static Routing

## Project Overview

This project demonstrates communication between multiple VLANs and different IP networks using Static Routing in Cisco Packet Tracer.

The network consists of two routers, two switches, and multiple PCs divided into six VLANs representing different departments.

The main objective is to establish end-to-end communication between devices belonging to different VLANs across two interconnected networks.

## Network Topology

![Network Topology](images/network-topology.png)

## Network Architecture

The network is divided into two sections:

**Network 1 – Router 0**
- VLAN 10 – DEV
- VLAN 20 – HR
- VLAN 30 – Sales

**Network 2 – Router 1**
- VLAN 50 – Admin
- VLAN 60 – OPS
- VLAN 70 – Testing

Both routers are connected to each other to enable communication between the two network sections.

## VLAN and IP Addressing

| Department | VLAN ID | Network Address |
|---|---:|---|
| DEV | 10 | 172.16.10.0/24 |
| HR | 20 | 192.168.10.0/24 |
| Sales | 30 | 10.10.10.0/24 |
| Admin | 50 | 10.10.20.0/24 |
| OPS | 60 | 172.16.20.0/24 |
| Testing | 70 | 192.168.20.0/24 |

## Network Components

- 2 Cisco Routers
- 2 Network Switches
- Multiple PCs
- VLAN Segmentation
- IPv4 Addressing
- Static Routing

## Technologies Used

- Cisco Packet Tracer
- Virtual LAN (VLAN)
- Static Routing
- IPv4 Addressing
- Inter-VLAN Communication

## Routing Configuration

Static routing is used to enable communication between the networks connected to Router 0 and Router 1.

Each router requires routes to reach the remote VLAN networks through the other router.

## Connectivity Testing

Ping tests were performed between devices belonging to different VLANs to verify network connectivity.

**Test result:** Successful communication was verified between different VLANs.

## Project Objectives

- Create multiple VLANs for different departments.
- Assign separate IP networks to each VLAN.
- Configure routing between different VLANs.
- Establish communication between two interconnected routers.
- Verify end-to-end connectivity using the ping command.

## Learning Outcomes

- Understanding VLAN segmentation.
- Configuring IP addressing and subnetting.
- Understanding static routing.
- Learning inter-VLAN communication.
- Troubleshooting network connectivity.
- Understanding communication between multiple networks.

## Project Files

- `images/` – Network topology diagram.
- `packet-tracer/` – Cisco Packet Tracer project file.
- `configurations/` – Router and switch configurations.
- `README.md` – Project documentation.

## Author

Arunkumar

Arunkumar
