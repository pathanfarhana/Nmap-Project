Network Reconnaissance and Vulnerability Assessment Using Nmap

🧾 Project Description

This project focuses on performing network reconnaissance and security assessment using Nmap (Network Mapper). Nmap is a powerful open-source tool used to discover live hosts, open ports, running services, and operating systems in a network. The project was conducted in a controlled lab environment using Kali Linux and a target machine to analyze network exposure and potential security risks.

🛠 Tools & Technologies

Kali Linux

Nmap

Metasploitable / Target Machine

Local Network

🎯 Objectives

To identify active hosts in a network

To discover open ports and running services

To perform OS and service version detection

To analyze network security weaknesses

🔍 Methodology

Identified the target IP address using netdiscover.

Performed basic and full port scans using Nmap.

Used TCP SYN scans, TCP connect scans, and UDP scans.

Conducted service and version detection using -sV.

Performed OS fingerprinting using -O.

Used aggressive scanning -A to gather detailed information.

Documented all scan results for analysis.

🧪 Key Nmap Scans Used

Basic scan: nmap <IP>

Full port scan: nmap -p- <IP>

Service detection: nmap -sV <IP>

OS detection: nmap -O <IP>

Aggressive scan: nmap -A <IP>

TCP SYN scan: nmap -sS <IP>

⚠ Security Findings

The scans revealed open ports and active services that could be targeted by attackers. Service version detection helped identify outdated or vulnerable services, which could be exploited if not properly secured.

🔐 Conclusion

This project helped in understanding how attackers and security professionals use Nmap for network discovery and vulnerability assessment. It improved practical knowledge of penetration testing, reconnaissance, and network security analysis.
