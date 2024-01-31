# Python Socket Programming

This repository provides a set of Python scripts demonstrating various aspects of socket programming, particularly focusing on TCP protocol and client-server interactions. Each example is crafted to illustrate key network programming concepts, ranging from simple data transmissions to complex protocol implementations like Reliable Data Transfer (RDT) 3.0.

## Contents

### 1. **TCP Server-Client JSON Communication**
   - **Description**: These scripts demonstrate a TCP server and client exchanging data in JSON format. The client sends a JSON request for specific operations (e.g., squaring a number), and the server responds in JSON. This example is excellent for learning structured data exchange in network programming.

### 2. **TCP Date-Time Server**
   - **Description**: This example features a TCP server that sends the current date and time to the client. It's a straightforward implementation showing data transmission over TCP.

### 3. **Reliable Data Transfer (RDT) 3.0 Implementation**
   - **Description**: These scripts implement the RDT 3.0 protocol, which ensures reliable data transfer over an unreliable network layer. This example is critical for understanding how higher-level protocols like TCP manage reliable communication over the inherently unreliable IP layer.

### 4. **TCP Chat Client**
   - **Description**: A TCP client designed to send messages to an echo server and receive responses. This script demonstrates bi-directional communication and continuous data exchange in a networked application.

### 5. **DNS Resolver**
   - **Description**: A simple code for getting the IP_address

## Usage Instructions

- Python 3.x is required.
- Run the server script first, then the client script.
- For scripts involving both server and client, use separate terminals or machines but within the same network.

## Requirements

- Python 3.x
- Basic understanding of networking concepts
- Network access for socket communication

## Disclaimer

These scripts are intended for educational purposes, illustrating basic to intermediate concepts in socket programming with Python. They are not suited for production environments without modifications and testing.


