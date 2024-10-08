
# Dynamic Routing simulation in a Network Using Cisco Packet Tracer

## Network Design
<p align="middle">
  <img src="DynamicRouting_ss.png" alt="Network Topology"/>
</p>


## Overview
This project involves the configuration of a dynamic routing network using RIP Version 1 (Routing Information Protocol) across multiple subnets. The setup is simulated in Cisco Packet Tracer and includes three different subnetworks interconnected via routers. The goal is to ensure seamless communication between all devices within and across the subnetworks while optimizing the network design with minimal resources.

## Network Topology
The network consists of three primary routers connected to multiple PCs through switches, with each router representing a different subnet:

* Router 0 (192.168.1.1): Connects three PCs within the 192.168.1.x subnet.
* Router 1 (192.168.2.1): Manages connections for three PCs in the 192.168.2.x subnet.
* Router 2 (192.168.3.1): Handles connections for three PCs in the 192.168.3.x subnet.
* Each router is linked to a switch, which in turn connects to multiple PCs, creating isolated subnets within the larger network.

## Configuration Details:
* Static IP Assignment: Each PC within the subnets was assigned a static IP address corresponding to its router’s subnet.
Routing Information Protocol (RIP) Version 1: RIP v1 was implemented on each router to dynamically exchange routing information. This protocol helps in automatically updating routing tables, allowing for efficient data transfer between different subnets.
* Inter-Router Connections: The routers are interconnected through serial links using a dedicated network (10.0.0.0/24). This setup facilitates communication between the different subnets by routing data through the appropriate paths.

## Project Highlights:
Dynamic Routing: RIP v1 enables dynamic updates of the routing table, reducing the need for manual configuration as the network grows or changes.
This project demonstrates the effective use of RIP v1 for dynamic routing in a multi-subnet environment. The configuration not only allows for seamless communication across all devices within the network but also optimizes resource usage, making it ideal for scalable network setups. The successful simulation in Cisco Packet Tracer showcases the practical application of RIP v1 in managing complex network topologies.

## How to run
Install Cisco Packet Tracer and then simply open the [Dynamic_Routing.pkt](Dynamic_Routing.pkt). The whole network is in working condition. You can check it by sending a packet from one system to another or through using the PING command in the Cisco Packet Tracer.
Install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) and then simply open the [Dynamic_Routing.pkt](Dynamic_Routing.pkt). The whole network is in working condition. You can check it by sending a packet from one system to another or through using the PING command in the Cisco Packet Tracer.








