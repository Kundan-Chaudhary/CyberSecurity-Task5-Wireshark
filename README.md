# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective
The objective of this task was to capture live network traffic and analyze different network protocols using Wireshark.

## Tool Used
- Wireshark
- Npcap (for packet capturing)

## Procedure Followed

1. Installed Wireshark along with Npcap.
2. Launched Wireshark and selected the active Wi-Fi network interface.
3. Started live packet capture.
4. Generated network traffic by browsing websites such as Google and YouTube.
5. Captured traffic for approximately 2 minutes.
6. Stopped the capture.
7. Applied display filters to analyze specific protocols.
8. Exported the captured file as Capture.pcap`.

## Protocols Identified and Analysis

### 1. DNS (Domain Name System)
- DNS packets were observed when accessing websites.
- These packets resolved domain names into IP addresses.
- Both DNS query and response packets were captured.

### 2. TCP (Transmission Control Protocol)
- TCP packets were identified in the capture.
- Observed TCP three-way handshake process.
- Ensures reliable and ordered data transmission.

### 3. HTTPS (TCP Port 443)
- HTTPS traffic was identified using filter: `tcp.port == 443`.
- It represents secure communication between client and server.
- The traffic was encrypted, which means payload data could not be directly read.

## Key Concepts Learned
- Packet capture and live traffic monitoring
- Protocol filtering using display filters
- Understanding TCP/IP communication
- Basic network troubleshooting techniques

## Conclusion
In this task, I successfully captured and analyzed live network traffic using Wireshark. I identified multiple protocols including DNS, TCP, and HTTPS. This task helped me understand how data travels across networks and how different protocols interact during communication. It also improved my practical knowledge of packet analysis and network troubleshooting.
