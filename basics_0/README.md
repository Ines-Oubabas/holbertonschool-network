# Network Basics Project

## Project Overview

This project focuses on basic networking concepts, protocols, and tools. By completing these tasks, you'll gain a deeper understanding of how networks operate, including the OSI model, types of networks, IP addresses, MAC addresses, and essential network protocols like TCP, UDP, and ICMP. You'll also work with Bash scripts to interact with networks and network devices.

## Learning Objectives

At the end of this project, you should be able to explain, without using external resources, the following concepts:

- **OSI Model**: 
  - What it is, how it is organized, and the seven layers.
- **LAN (Local Area Network)**: 
  - Typical usage and geographical size.
- **WAN (Wide Area Network)**: 
  - Typical usage and geographical size.
- **The Internet**: 
  - How it functions as a global network.
- **IP Addresses**:
  - The role of public and private addresses.
  - IPv4 and IPv6.
- **Localhost**:
  - What it is and why it’s important.
- **Subnet**:
  - The concept of subnets and subnet masks.
- **TCP and UDP**:
  - Differences between these two protocols.
  - The purpose of ports.
  - Important ports: SSH (22), HTTP (80), HTTPS (443).
- **Ping/ICMP**:
  - How it’s used to check network connectivity.
  
## Project Structure

- Each task involves either answering theoretical questions or writing Bash scripts to perform specific network-related operations.
- The Bash scripts must adhere to strict guidelines, including passing `shellcheck` without errors.

## Tasks

### 0. **OSI Model**

- Understand the OSI model and its 7 layers.
- Write a file answering questions about the OSI model.

### 1. **Types of Network**

- Differentiate between LAN, WAN, and the Internet.
- Write a file answering questions about the types of networks.

### 2. **MAC and IP Address**

- Understand the role of MAC and IP addresses.
- Write a file answering questions about MAC and IP addresses.

### 3. **UDP and TCP**

- Compare UDP and TCP protocols.
- Write a file answering questions about these protocols and their usage.

### 4. **TCP and UDP Ports**

- Learn about the role of ports in network communication.
- Write a Bash script that displays listening ports and their associated PIDs and programs.

### 5. **Is the Host on the Network?**

- Use the `ping` command to check network connectivity.
- Write a Bash script that pings an IP address passed as an argument, or displays usage instructions if no argument is passed.

## Requirements

- All Bash script files must be executable.
- The first line of each Bash script should be `#!/usr/bin/env bash`.
- The second line should be a comment explaining what the script does.
- All scripts should pass `shellcheck` without errors.

## Commands & Tools

- **ping**: Used to check if a host is reachable over the network.
- **netstat** or **ss**: Used to display network connections, routing tables, interface statistics, masquerade connections, and more.
- **shellcheck**: A static analysis tool for shell scripts, used to identify and correct issues.

## Example

Example of how to use the `5-is_the_host_on_the_network` script:

```bash
./5-is_the_host_on_the_network 8.8.8.8

