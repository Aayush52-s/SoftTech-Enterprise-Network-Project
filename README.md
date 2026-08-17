
# SOFT.TECH — Enterprise Network Project

## Project Overview

This project demonstrates the design and implementation of a multi-site enterprise network connecting Headquarters (HQ), Branch 1, and Branch 2 using Cisco Packet Tracer.

## Technologies Used

- OSPF
- DHCP
- VLAN
- Inter-VLAN Routing
- Router-on-a-Stick
- Extended ACL
- Wireless Networking
- Cisco IOS
- Cisco Packet Tracer

## Network Topology

![Complete Enterprise Topology](images/full-enterprise-topology.png)

## HQ Network

![HQ Topology](images/hq-topology.png)

## Branch 1 Network

![Branch 1 Topology](images/branch-1-topology.png)

## Branch 2 Network

![Branch 2 Topology](images/branch-2-topology.png)

## Key Implementations

- Configured OSPF for dynamic routing between routers.
- Implemented DHCP for automatic IP address assignment.
- Configured VLANs for department segmentation.
- Implemented Inter-VLAN Routing using Router-on-a-Stick.
- Applied Extended ACLs to control inter-network traffic.
- Integrated wireless connectivity using access points.

## Network Verification

The following Cisco IOS commands were used for network verification:

```text
show ip interface brief
show ip route
show ip ospf neighbor
show ip protocols
show ip dhcp binding
show vlan brief
show interfaces trunk
show access-lists
