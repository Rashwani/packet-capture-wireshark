# packet-capture-wireshark
Hands-on lab capturing and analyzing DNS and HTTP traffic using Wireshark.
# Wireshark Network Traffic Analysis Lab

## Overview
This lab demonstrates my ability to capture and analyze basic network traffic using Wireshark on Windows 11. I performed real-time packet capturing, filtered traffic for DNS and HTTP protocols, and documented key findings.

## Objectives
- Capture live network traffic using Wireshark.
- Generate and inspect DNS queries and HTTP requests.
- Apply filters to isolate specific traffic types.
- Interpret packet details, source/destination IPs, and protocol data.

## Steps Performed
1. Installed Wireshark with Npcap on Windows 11.
2. Selected the active Wi-Fi adapter to capture packets.
3. Visited websites and used `nslookup` to generate DNS traffic.
4. Stopped the capture and applied filters:
   - `dns` to inspect DNS queries and responses.
   - `http` to inspect HTTP GET requests and response headers.
5. Saved the capture file (`Wireshark_Lab1.pcapng`) and documented results.

## Key Findings
- Successfully captured and analyzed DNS requests for domain name resolution.
- Identified source and destination IP addresses and DNS response IPs.
- Observed HTTP GET requests in cleartext (using a non-HTTPS test site).

## Tools Used
- Wireshark
- Windows 11
- Command Prompt (`nslookup`)

## Skills Demonstrated
- Packet capture and filtering
- Basic network traffic analysis
- Understanding of DNS and HTTP protocols
- Practical use of industry-standard network monitoring tools

## Screenshots
- DNS query example
<img width="815" height="599" alt="Screenshot 2025-07-14 183423" src="https://github.com/user-attachments/assets/95c03765-59bf-4dce-8d7e-79212b3adee2" />
<img width="855" height="356" alt="Screenshot 2025-07-14 182610" src="https://github.com/user-attachments/assets/376633de-fea4-406d-91af-4cfb524cdf3c" />
 
- HTTP GET request example
  <img width="815" height="863" alt="Screenshot 2025-07-14 182906" src="https://github.com/user-attachments/assets/93d81482-0d6d-411a-b062-ccfe779bec29" />
<img width="1339" height="581" alt="Screenshot 2025-07-14 182649" src="https://github.com/user-attachments/assets/0003501b-a612-4b98-921b-0d4dc952af24" />


This lab lays the foundation for deeper packet analysis, IDS/IPS rules, and SOC monitoring tasks. Future labs will expand on more advanced traffic inspection and threat detection scenarios.



