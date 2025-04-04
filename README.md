# network-programming-projects
Python implementations of networking concepts including HTTP servers, packet analysis, routing algorithms, DNS tools, and port scanning. These projects demonstrate fundamental networking principles through hands-on code examples for educational purposes.

# Python Network Concepts and Programming Assignments

## Overview

This repository contains Python implementations for various network concepts and programming assignments. The projects cover a wide range of networking topics including HTTP protocols, TCP/IP stack, routing algorithms, packet analysis, network configuration, and network security tools, all implemented in Python.

## Assignments

### Web Technologies
- **Project 5: HTTP Client and Server**  
  Python implementation of basic HTTP client and server applications demonstrating the HTTP protocol, request/response formats, and proper header handling using libraries like `socket`, `http.client`, and `http.server`.

- **Project 9: A Better Web Server**  
  Enhanced Python web server with support for multiple concurrent connections, virtual hosting, proper MIME type detection, and basic caching mechanisms. Implements threading or asynchronous I/O for improved performance.

### Time Protocols
- **Project 12: Atomic Time**  
  Python client application that synchronizes with NTP (Network Time Protocol) servers to obtain high-precision time information using the `ntplib` module.

### Application Protocols
- **Project 13: The Word Server**  
  Simple network service written in Python that processes word-related queries (definitions, synonyms, etc.) using a client-server architecture with socket programming.

### Packet Analysis
- **Project 16: Validating a TCP Packet**  
  Python utility that parses and validates TCP packet structures, including header fields, checksums, and flags using libraries like `scapy` or `dpkt`.

- **Project 23: Sniff ARP Packets with WireShark**  
  Documentation and analysis of ARP (Address Resolution Protocol) traffic captured using WireShark, with Python scripts to process PCAP files using `pyshark` or `scapy`.

### Network Addressing
- **Project 19: Computing and Finding Subnets**  
  Python tools for subnet calculation, including subnet mask operations, CIDR notation conversion, and IP address range determination using the `ipaddress` module.

### Routing
- **Project 22: Routing with Dijkstra's Algorithm**  
  Python implementation of Dijkstra's algorithm for finding optimal network routes based on link costs and topology information using data structures from the `networkx` library.

### Network Configuration
- **Project 25: Packet Tracer: Connect Two Computers**  
  Packet Tracer lab with Python scripts to analyze and validate the configuration of direct computer-to-computer connections.

- **Project 26: Packet Tracer: Using a Switch**  
  Packet Tracer lab showing switch-based local area network configuration with Python tools to test connectivity and analyze network behavior.

- **Project 27: Packet Tracer: Using a Router**  
  Packet Tracer lab illustrating inter-network routing with Python scripts to test and validate router configurations.

### Advanced Socket Programming
- **Project 30: Using Select**  
  Python implementation of non-blocking I/O using the `selectors` module (modern alternative to `select`) for efficient handling of multiple socket connections.

### Domain Name System
- **Project 34: Digging DNS Info**  
  Python tools for DNS query and analysis, including record lookups, zone transfers, and DNS hierarchy exploration using the `dnspython` module.

### Network Security
- **Project 38: Port Scanning**  
  Python implementation of port scanning techniques to discover open ports and services on remote hosts, using libraries like `socket` and `scapy`.

## Project Structure

Each project is contained in its own directory with the following structure:

```
project-name/
├── src/        
├── tests/
├── requirements.txt 
├── docs/  
│   └── report.md   
└── README.md 
```

## Prerequisites

- Python 3.8+ 
- Required Python packages (listed in each project's requirements.txt file)
- WireShark for packet analysis projects
- Cisco Packet Tracer for network simulation projects
- Basic understanding of networking protocols and Python programming

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/python-network-assignments.git
   cd python-network-assignments
   ```

2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install common dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. For project-specific dependencies:
   ```bash
   cd project-directory
   pip install -r requirements.txt
   ```

## Running the Projects

Each project contains its own run instructions in its respective README.md file. Generally, you can run projects using:

```bash
cd project-directory
python src/main.py
```

## Documentation

Each project includes:
- Implementation details
- Design decisions
- Testing procedures
- Results and analysis
- References to relevant RFCs or specifications

## Common Python Libraries Used

- `socket` - Low-level networking interface
- `requests` - HTTP client library
- `scapy` - Packet manipulation library
- `asyncio` - Asynchronous I/O
- `threading` - Thread-based parallelism
- `ipaddress` - IP address manipulation
- `dnspython` - DNS toolkit
- `pyshark` - Python wrapper for WireShark
- `networkx` - Network analysis and algorithms

## Learning Outcomes

Through these projects, you will gain hands-on experience with:
- Socket programming in Python
- Network protocol analysis and implementation
- Network configuration and troubleshooting
- Routing algorithms and subnetting
- Network security fundamentals
- Performance optimization techniques
- Using Python's networking libraries effectively

## References

- [Python Socket Programming Documentation](https://docs.python.org/3/library/socket.html)
- [Requests Library Documentation](https://docs.python-requests.org/)
- [Scapy Documentation](https://scapy.readthedocs.io/)
- [Python Standard Library Networking Modules](https://docs.python.org/3/library/ipc.html)
- [Beej's Guide to Network Programming](https://beej.us/guide/bgnet/)
- Relevant RFCs for implemented protocols
- [WireShark Documentation](https://www.wireshark.org/docs/)
- [Cisco Packet Tracer Resources](https://www.netacad.com/courses/packet-tracer)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Matt M
