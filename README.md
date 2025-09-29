# Wireshark-CMD-Ping-Packet-Capture-and-Analysis.
Wireshark packet capture of ICMP and DNS traffic generated via CMD ping. Demonstrates network packet analysis, protocol identification, and detailed packet inspection using Wireshark.

# Steps Performed:
1. Installed Wireshark and launched the application.
2. Selected the active network interface for capturing.
3. Generated network traffic using CMD: ping.google.com.
4. Captured packets in Wireshark for approximately one minute.
5. Stopped the capture and exported it as a .pcap file.
6. Filtered packets by protocol (ICMP, DNS, TCP) for analysis.
7. Examined detailed packet views to understand headers and protocol information.

# Findings:
ICMP: Ping requests and replies confirmed network connectivity.
DNS: Packets showed domain name resolution for google.com.
TCP: Background traffic illustrated multiple protocols operating simultaneously.
Packet details included source/destination IPs, protocol type, :flags, and response times.

# File Included:
.pcap – Complete packet capture file for analysis.

Learning Outcome:
This exercise improved understanding of:
Network protocols (ICMP, DNS, TCP)
Packet structure and detailed inspection
Using Wireshark for practical network analysis
