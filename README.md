# VLAN-Segmentation-and-Trunking
# VLAN Segmentation & Trunking Project (Cisco Packet Tracer)

## Overview
This project simulates a segmented switched network using VLANs to separate traffic by department/function, with trunk links configured between switches to carry multiple VLANs across the topology. Dynamic Trunking Protocol (DTP) was used to negotiate trunk links between switches.

## Objectives
- Design a switched network topology with multiple VLANs to logically separate traffic
- Configure access ports and assign end devices to the correct VLANs
- Configure trunk links between switches to carry tagged VLAN traffic
- Use DTP to negotiate trunking mode between connected switches
- Verify VLAN configuration and trunk status across the topology

## Topology
- **Devices used:** [e.g. 2–3 Cisco switches, end devices/PCs — update to match your topology]
- **VLANs configured:** [list your VLAN IDs and names, e.g. VLAN 10 – Sales, VLAN 20 – IT, VLAN 30 – Management]
- **Trunk links:** Configured between switches to carry all/selected VLANs, with DTP set to negotiate trunking mode automatically

## Key Configurations
- Created VLANs and assigned names on each switch
- Assigned access ports to their respective VLANs
- Configured trunk ports and verified DTP negotiation between switches
- Verified VLAN membership and trunk status using `show vlan brief` and `show interfaces trunk`

## Tools Used
- Cisco Packet Tracer

## How to Open
1. Download and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) (free with a Cisco Networking Academy account)
2. Open `VLANS_lab_1.pkt` in Packet Tracer to view and interact with the topology

## Learning Outcomes
This project helped build practical, hands-on experience with VLAN segmentation, trunking, and DTP negotiation — core building blocks for managing traffic and structure in switched network infrastructure.
