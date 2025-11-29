# Scalable-ISP-Routing-Simulation
A comprehensive Cisco Packet Tracer simulation modeling a three-tier Internet Service Provider (ISP) core and distribution network. This project demonstrates core routing and service distribution principles necessary for a robust, production-ready environment.
# Key Technical Features:
# Dynamic Routing (OSPF): 
Implemented OSPF as the Interior Gateway Protocol (IGP) across the ISP core and customer edge routers for dynamic route advertisement and scalability. 
#Network Address Translation (NAT/PAT): 
Configured Port Address Translation (NAT Overload) on all customer routers to allow multiple private IP devices to share a single public ISP address, conserving IPv4 space and providing security. 
# Centralized DHCP Relay: 
Utilized the ip helper-address command on all customer routers to centralize IP address management on a single DHCP server, proving a scalable solution for dynamic IP assignment. 
# Advanced Customer Segments: 
Includes configurations for complex customer requirements, such as Router-on-a-Stick VLANs (Business Park) and Wireless Access Points for public connectivity (Shopping Mall).

<ul>
  <li> 
  Architecture: 
    Connects three distinct customer areas (Housing, Organization, Mall) to a central ISP HQ via a scalable 200.0.0.0/24 backbone.
  </li>
</ul>
