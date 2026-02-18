# Enterprise Multi-Site Network Infrastructure (Cisco)

A simulated enterprise network designed and implemented in Cisco Packet Tracer representing a company with headquarters and multiple international branches.

The project focuses on real-world network services, segmentation, routing, redundancy, and security controls.

## Network Architecture

Locations:
* Hong Kong (HQ)
* Tokyo
* Beijing
* Singapore
* Kuala Lumpur
* Seoul (Wireless branch)

The network supports inter-site communication while enforcing segmentation and controlled access between departments.

## Implemented Technologies
### Layer 2 & Segmentation
* VLAN creation and trunking
* InterVLAN routing
* Switch management VLAN
* Wireless WPA2 secured network

### Routing
* OSPF dynamic routing (Area 0)
* Static routing
* Floating default routes (failover)
* IPv4 and IPv6 verification

### Network Services
* DHCP (local + remote relay)
* DNS name resolution
* HTTPS-only internal web server
* Syslog logging
* NTP time synchronization

### Security Controls
* Standard ACLs for network access restriction
* VTY access restrictions
* NAT (PAT overload & Static NAT)
* Client network isolation between branches

## Key Engineering Concepts Demonstrated
* VLSM subnet planning across multiple sites
* Redundant internet routing using floating static routes
* Secure internal service deployment
* Network monitoring and logging
* Troubleshooting inter-VLAN connectivity

## Verification & Testing
* The network was validated using operational checks including:
* Routing table verification (show ip route)
* NAT translation monitoring
* ACL traffic blocking tests
* Cross-site connectivity tests
* Secure HTTPS access validation
* Screenshots are provided in /screenshots.

## Purpose
This project demonstrates practical understanding of how enterprise networks are segmented, routed, secured, and monitored, beyond basic connectivity configuration.

## How to Open
* Install Cisco Packet Tracer
* Open .pka file
* Use Simulation mode to observe traffic flow