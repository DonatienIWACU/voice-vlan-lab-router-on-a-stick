🧩 Cisco Voice and Data VLAN Lab

This project demonstrates a Cisco lab setup for configuring Voice and Data VLANs using Router-on-a-Stick inter-VLAN routing.
The setup includes IP Phones and PCs sharing the same switch port, trunking, subinterface configuration, and ping test validation using Cisco Packet Tracer.

🚀 Overview

This lab simulates a real-world small office network where both Voice (IP Phones) and Data (PCs) traffic share a single switch port while maintaining network segmentation through VLANs.
The configuration ensures proper routing, QoS readiness, and reliable connectivity between devices across VLANs.

🧱 Lab Components

Cisco Switch (Layer 2)

Cisco Router (for Router-on-a-Stick setup)

IP Phones

PCs

Cisco Packet Tracer (for simulation)

⚙️ Configuration Highlights
🔸 VLAN Setup

VLAN 10 – Data VLAN

VLAN 20 – Voice VLAN

🔸 Switch Configuration

Access ports configured with both Data and Voice VLANs

Trunk ports for router connection

Voice VLAN assignment using switchport voice vlan command

🔸 Router Configuration

Subinterfaces for each VLAN (e.g., Gig0/0.10 and Gig0/0.20)

802.1Q encapsulation for VLAN tagging

Default gateways for both VLANs

🔸 QoS-Ready Design

Network design supports future Quality of Service (QoS) configuration for prioritizing voice traffic.

🧪 Validation

Ping tests between VLANs confirm successful inter-VLAN routing.

Voice and data devices communicate independently while sharing the same physical port.
