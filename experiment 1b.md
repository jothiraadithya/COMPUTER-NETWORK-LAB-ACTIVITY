# Basic Peer-to-Peer Networking with Cisco Packet Tracer

This repository contains the setup and instructions for a basic network experiment using Cisco Packet Tracer, where two PCs are directly connected and tested for connectivity.

## Objective

To demonstrate basic peer-to-peer communication by:
- Connecting two PCs using a copper straight-through cable.
- Assigning IP addresses.
- Verifying connectivity using the ping command.

## Requirements
- Cisco Packet Tracer
- Two PC devices (PC0 and PC1)
- One Copper Straight-Through Cable

## Experiment Steps
   1. Create a New Network

Open Cisco Packet Tracer and create a new workspace.

   2. Add Devices

Drag and drop two PCs (PC0 and PC1) into the workspace.

   3. Connect the PCs

Use a copper straight-through cable to connect:
- PC0 → FastEthernet0
- PC1 → FastEthernet0

   4. Configure IP Addresses

Click each PC → Go to Desktop > IP Configuration and assign:

PC0:
- IP Address: 192.168.1.1
- Subnet Mask: 255.255.255.0

PC1:
- IP Address: 192.168.1.2
- Subnet Mask: 255.255.255.0

   5. Test the Connection

Open the Command Prompt on PC0 (Desktop > Command Prompt), then run:
<img width="1365" height="708" alt="Screenshot 2025-07-22 092214" src="https://github.com/user-attachments/assets/75fde8e3-01df-4bc6-b9e6-5981cbc09737" />

