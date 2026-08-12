# SYN-Flood-Incident-Analysis 
Analysis of a TCP SYN Flood Denial-Of-Service Attack Using Wireshark Network Traffic.

## Overview
This project analyzes a denial-of-service (DoS) incident involving a TCP SYN flood against a web server.

## Tools Used
- Wireshark

## Skills Demonstrated
- Network traffic analysis
- Wireshark Monitoring
- TCP/IP
- TCP three-way handshake
- SYN flood identification
- Denial-of-service analysis
- HTTPS / Port 443
- Incident response

## Findings
Packet analysis showed an unusually large number of TCP SYN requests being sent from an unfamiliar IP address to the web server on port 443.

The abnormal volume of connection requests overwhelmed the server and prevented legitimate users from reliably establishing connections.

## Incident Response
The affected server was temporarily taken offline to recover, and the source IP address was blocked at the firewall.

Because IP blocking alone is not a permanent solution, additional protections would be necessary to mitigate future SYN flood attacks.

## Project File
The complete cybersecurity incident report is included in this repository.
