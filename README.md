# Wireshark-Network-Traffic-Analysis
Hands-on project on analyzing network traffic using Wireshark to detect anomalies and suspicious activity.


## Objective
The aim of this project was to understand and analyze network traffic using Wireshark to identify potential security threats, suspicious activities, and gain hands-on experience in packet-level investigation — an essential skill for a SOC Analyst.

## Tools Used
- Wireshark – For capturing and analyzing network packets.
- Kali Linux / Ubuntu – Operating system environment for running Wireshark.
- TryHackMe (Wireshark: The Basics) – Lab environment for practice.

## Methodology
1. Installed and configured Wireshark  
2. Used TryHackMe "Wireshark: The Basics" lab  
3. Applied filters (`http`, `tcp.port == 80`, `ip.addr == X.X.X.X`)  
4. Analyzed packets (TCP handshake, DNS queries, suspicious activity)  
5. Captured evidence with screenshots  

## Findings
- Detected unusual DNS requests to suspicious domains.  
- Observed multiple failed TCP connection attempts indicating possible scanning activity.
- Noticed unencrypted HTTP traffic, making data vulnerable to sniffing. 

## Conclusion
This project provided practical exposure to network traffic analysis, a core SOC analyst skill. By completing this exercise, I developed the ability to filter and analyze packets, detect anomalies, and document security incidents effectively.
