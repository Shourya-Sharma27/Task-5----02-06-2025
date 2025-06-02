# Task-5----02-06-2025
This project demonstrates the basic use of **Wireshark** for capturing and analyzing network traffic on a Linux system.

Task Overview

The task involved the following steps:
1. Installing Wireshark
   - Commands used - 
     sudo apt update
     sudo apt install wireshark
2. Capturing Traffic
   - Started capture on an active network interface.
   - Generated traffic by pinging websites:  
     - `google.com`  
     - `gmail.com`  
     - `chatgpt.com`
3. Stopping Capture
   - The capture was stopped after enough traffic was recorded.
4. Protocol Filtering
   - Traffic was filtered and analyzed using different protocols:
     - DNS
     - ICMP
     - TCP
5. Protocol Identification
   - Identified and explained additional protocols:
     - HTTPS: Secure web traffic
     - ARP: Address resolution in the local network
     - TCP/ICMP/DNS: Standard web and ping interactions
6. Export
   - The capture file was saved in `.pcap` format for further analysis.

Summary
This project provides a practical introduction to using Wireshark for traffic analysis. It highlights how to initiate captures, generate relevant network activity, apply protocol filters, and interpret the data. The `.pcap` file offers a real-world snapshot of basic internet activity and protocol behavior, useful for beginners in network analysis and cybersecurity.
