# Wireshark Packet Capture and Analysis

## Objective:
To analyze live network traffic using Wireshark by capturing packets, applying filters, identifying protocols, and exporting data.

## Steps Performed:

1. Installed Wireshark from the official website.
2. Opened Wireshark and started capturing on the active network interface (Wi-Fi).
3. Generated network traffic by:
   - Visiting https://www.google.com
   - Running `ping google.com` in Command Prompt/Terminal
4. Stopped the capture after approximately one minute.
5. Applied filters in Wireshark to isolate specific protocols 

## Protocols Identified:

1. **DNS** – Used to resolve domain names like google.com to IP addresses.
2. **TCP** – Transport protocol used for reliable communication 
3. **HTTP** – Application protocol used for web browsing 

## Summary of Findings:

- Number of packets captured: 253
- DNS queries and responses were visible when accessing websites.
- TCP handshake (SYN, SYN-ACK, ACK) and data transfer packets were captured.
- HTTP GET requests and responses were seen when browsing the web.
- The communication showed IP addresses of both local and remote systems.


## Conclusion:

Wireshark effectively captured real-time traffic, making it easy to inspect how devices communicate using different protocols. This exercise helped understand network operations and protocol behaviors in practice.
