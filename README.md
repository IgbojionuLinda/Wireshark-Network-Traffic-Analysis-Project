
# Wireshark-Network-Traffic-Analysis-Detecting Unencrypted Traffic.

SOC Analyst project analyzing live network traffic using Wireshark to detect unencrypted communication and security risks.

## Project Overview.
This project demonstrates the practical application of network traffic analysis using Wireshark. The objective was to capture and analyse live network traffic to identify security risks such as unencrypted communication and observable DNS activity.

This project simulates tasks performed by a Security Operations Centre (SOC) analyst during network monitoring and investigation.

## Project Problem Statement.
Many users assume all internet traffic is secure. However, some communication still occurs without encryption, which may expose sensitive information to attackers monitoring network traffic.

This project investigates how network traffic behaves and identifies potential security weaknesses.

## Tools Used
-Wireshark.
-Windows Laptop.
-Wi-Fi Network Connection.
-Web Browser.

## Methodology
1 I captured live traffic using Wireshark.
2 Selected active Wi-Fi network interface.
3 Generated traffic by browsing websites.
4 Applied protocol filter:

  Live Traffic
## This screenshot shows Live Traffic capture.
![Live Traffic](Screenshots/Live_Network_Capture.png)

  DNS
## This capture shows DNS queries captured during live traffic monitoring.
![DNS Traffic](Screenshots/DNS_Query_Packets.png)

  TLS
## This screenshot demonstrates encrypted HTTPS communication using TLS protocol.
![TLS Traffic](Screenshots/TLS_Handshake_Packet.png)

5 Analysed packet behaviour and security implications.

## Analysis performed
### DNS Traffic Analysis
DNS packets revealed domain resolution requests showing how systems translate domain names into IP addresses.

### TLS Traffic Analysis
TLS packets confirm encrypted communication and protect transmitted data.

### Live Traffic Observation
I observed data transmission without encryption, demonstrating potential exposure risks.

## Key Findings
-DNS traffic exposes browsing activity.
-Live traffic is vulnerable to interception.
-HTTPS encrypts communication and improves security posture.

## Security Recommendations
-Monitor DNS activity for suspicious domains.
-Implement continuous network monitoring.
-Enforce HTTPS-only communication.

## Skills Demonstrated
-Packet capture and analysis
-Protocol filtering
-Network traffic investigation
-Security risk identification
-SOC analyst fundamentals

## Author
Security Operations (SOC) analysis through a hands-on project.

## Project updated

