# 🌐 Network Analysis Resources 🌐

Understanding how data moves across networks is a foundational skill in cybersecurity. Whether you're analyzing DNS traffic, investigating HTTP headers, or inspecting raw packets, these tools and resources will help you sharpen your network analysis abilities. 🕵️‍♂️

---

## 💡 Tools & Tutorials

| Resource Name                          | Description                                                                                      |
|---------------------------------------|--------------------------------------------------------------------------------------------------|
| **Wireshark**                         | The most popular open-source packet analyzer. Ideal for live captures and deep packet inspection. |
| **tshark**                            | Command-line version of Wireshark – great for scripting and automation.                          |
| **tcpdump**                           | Lightweight packet capture tool available on most Unix systems.                                  |
| **NetworkMiner**                      | Network forensic analysis tool (NFAT) for extracting files, credentials, and metadata.           |
| **Brim**                              | Modern interface for analyzing Zeek logs and PCAPs efficiently.                                  |
| **Zeek (formerly Bro)**              | A powerful network analysis framework that turns traffic into logs for deeper inspection.        |
| **Suricata**                          | High-performance network IDS, IPS, and network security monitoring engine.                       |
| **PCAP Analyzer**                     | Tools and web interfaces to visualize PCAPs like pcapr.net or CapAnalysis.                       |
| **DNSDumpster**                       | OSINT tool for passive DNS recon and subdomain enumeration.                                      |
| **PacketTotal**                       | Upload and analyze PCAP files online with insights and community tags.                           |
| **Xplico**                            | Extracts and reconstructs application-level data (e.g., emails, HTTP, VoIP) from network traffic. |
| **Ettercap**                          | Comprehensive suite for man-in-the-middle attacks and traffic sniffing.                          |
| **Netcat (nc)**                       | Swiss-army knife for network debugging and penetration testing.                                  |
| **Fiddler**                           | HTTP debugging proxy to analyze browser traffic.                                                 |
| **Charles Proxy**                     | Web proxy for inspecting HTTP(S) requests/responses in web and mobile apps.                      |
| **MITMf**                             | Man-in-the-Middle Framework for traffic manipulation and credential harvesting.                  |
| **PacketWhisperer**                   | Covert data exfiltration using DNS tunneling and other stealthy techniques.                      |
| **Wireshark Display Filters Cheatsheet** | Quick reference for building powerful Wireshark filters.                                       |
| **PCAP Sample Repositories**          | Public PCAPs for practice ([Contagio](http://contagiodump.blogspot.com), [Malware-Traffic-Analysis.net](https://www.malware-traffic-analysis.net)) |
| **CyberChef**                         | Web-based data transformation tool to decode, analyze, and inspect payloads.                     |
| **HTTP Headers Cheat Sheet**          | List of HTTP headers used in network analysis and web security.                                  |
| **ipinfo.io**                         | API and web tool to geolocate and gather data on IP addresses.                                   |

---

## 🧠 Concepts & Techniques

Use these resources to understand and apply network analysis fundamentals:

- Capture and analyze traffic using packet sniffers (Wireshark, tcpdump)
- Filter specific protocol traffic (DNS, HTTP, TLS, ICMP, etc.)
- Inspect DNS records and query behaviors
- Reconstruct files and sessions from PCAPs
- Identify malicious payloads, beaconing behavior, or exfiltration attempts
- Interpret HTTP headers and request patterns
- Understand TCP/IP models and flow behavior
- Investigate SSL/TLS handshakes and certificate info
- Monitor real-time traffic using IDS like Zeek or Suricata

---

## ⚠️ Ethical Reminder

Only analyze network traffic on systems and networks you own or have explicit permission to inspect. Unauthorized monitoring or sniffing of data is illegal and unethical.

🛡️ Stay curious, stay legal, and happy packet hunting! 📡
