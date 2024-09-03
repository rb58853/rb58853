# Distributed FTP System

## Overview

This project focuses on designing and implementing a distributed file transfer protocol (FTP) system using Python. It emphasizes leader coordination through the Bully algorithm, addressing key challenges in distributed systems.

### Key Components

- Distributed File Transfer Protocol
- Bully Algorithm for Leader Election
- Network Communication
- Data Persistence

### Technologies Used

- Python

### Skills Demonstrated

- Distributed Systems Design
- Network Programming
- Fault-Tolerant Systems
- Concurrent Programming

### Description

The distributed FTP system is designed to allow secure file transfers between nodes in a network. It is built to be resilient and scalable, capable of handling multiple simultaneous transfer requests without compromising performance.

#### Bully Algorithm Integration

The Bully algorithm is central to this project, playing a crucial role in leader coordination among system nodes. This algorithm ensures that there is always an active and available node to coordinate FTP operations, even in case of failures or disconnections of some nodes.

#### Failure Management and Recovery

The system includes mechanisms to detect and handle node failures, ensuring the continuity of FTP service. When a node fails, the Bully algorithm activates a selection process to designate a new leader, minimizing service interruption.

### Keywords

- Bully Algorithm
- Distributed FTP
- Data Persistence