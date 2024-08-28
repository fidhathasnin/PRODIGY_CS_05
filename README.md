# Network Packet Analyzer

## Overview

The `Network Packet Analyzer` is a Python tool for capturing and analyzing network packets. It provides valuable insights into network traffic by displaying details such as source and destination IP addresses, protocols, and payload data. This tool is intended for educational purposes to aid in understanding network traffic and packet analysis.

## Features

- **Captures Network Packets**: Monitors and collects packets in real-time.
- **Displays IP Addresses**: Shows source and destination IPs.
- **Protocol Identification**: Identifies and displays protocols like TCP, UDP, and ICMP.
- **Payload Preview**: Provides a snippet of packet payload data.

## Prerequisites

- Python 3.x
- Scapy library
- Npcap or WinPcap (for Windows users)

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/network-packet-analyzer.git
   ```

2. **Navigate to the Project Directory**:
    ```bash
    cd network-packet-analyzer
    ```
3. **Install Required Python Packages**:
   ```bash
   pip install scapy
   ```
4. **Install Npcap (Windows Users)**:
     **
    
    Download and install Npcap from [Npcap's official site](https://nmap.org/npcap/). During installation, select:
    
    *   "Install Npcap in WinPcap API-compatible Mode"
    *   "Install for all users (requires a reboot)"


    ## Usage

1. **Open a Terminal**:
   - For Windows, run the terminal as Administrator if needed.
   - For Linux/Mac, use `sudo` if required.

2. **Run the Packet Analyzer**:

   ```bash
   python packet_analyzer.py
   ```
 3. **View Output**:
        
     *   The script will display captured packets, including IP addresses, protocols, and payload snippets.
  
## Code
----

Here's the code for `packet_analyzer.py`:
    
    -------------------------------


