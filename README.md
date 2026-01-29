<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=Network+Reconnaissance+with+Nmap;Vulnerability+Assessment+Lab;Offensive+Security+Project&font=Fira+Code&center=true&width=950&height=45&color=00BFFF&vCenter=true&pause=1000" />
</p>

<h1 align="center">🛰️ Network Reconnaissance & Vulnerability Assessment Using Nmap</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Nmap-blue?style=for-the-badge&logo=nmap" />
  <img src="https://img.shields.io/badge/Category-Network%20Pentesting-red?style=for-the-badge&logo=kalilinux" />
  <img src="https://img.shields.io/badge/Environment-Lab%20Based-success?style=for-the-badge" />
</p>

---

## 🧾 Project Overview

This project demonstrates **network reconnaissance and vulnerability assessment** using **Nmap (Network Mapper)** — one of the most essential tools in penetration testing and SOC investigations.

The assessment was performed in a **controlled lab environment** using **Kali Linux** and a deliberately vulnerable target machine. The objective was to **discover hosts, identify open ports, detect services, fingerprint operating systems, and analyze potential security risks**.

> ⚠️ This project is conducted strictly for **educational and ethical security research purposes**.

---

## 🛠 Tools & Technologies

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux" />
</p>

| Tool | Purpose |
|-----|--------|
| 🐉 **Kali Linux** | Penetration testing platform |
| 🛰️ **Nmap** | Network discovery & port scanning |
| 🎯 **Metasploitable / Target VM** | Vulnerable test machine |
| 🌐 **Local Network** | Testing environment |

---

## 🎯 Objectives

- Identify **active hosts** in a network
- Discover **open ports** and exposed services
- Perform **service & version detection**
- Fingerprint **operating systems**
- Analyze **network security weaknesses**
- Understand attacker reconnaissance techniques

---

## 🔍 Methodology

### 1️⃣ Host Discovery
- Identified live hosts using **netdiscover**
- Confirmed reachable targets within the local network

### 2️⃣ Port Scanning
- Conducted basic and full TCP port scans
- Identified exposed services and attack surface

### 3️⃣ Service & Version Detection
- Used Nmap scripting and probes to identify service versions
- Flagged outdated or vulnerable services

### 4️⃣ OS Fingerprinting
- Detected target operating system using TCP/IP stack behavior

### 5️⃣ Aggressive Enumeration
- Combined OS detection, version detection, scripts, and traceroute
- Collected maximum intelligence in a single scan

### 6️⃣ Documentation
- Recorded open ports, services, and versions
- Analyzed findings from an attacker and defender perspective

---

## 🧪 Key Nmap Scans Used

```bash
# Basic Scan
nmap <IP>

# Full Port Scan
nmap -p- <IP>

# Service & Version Detection
nmap -sV <IP>

# OS Detection
nmap -O <IP>

# Aggressive Scan
nmap -A <IP>

# TCP SYN Scan (Stealth)
nmap -sS <IP>
````

---

## ⚠️ Security Findings & Analysis

🚨 The reconnaissance phase revealed:

* Multiple **open ports** exposing network services
* **Service versions** that may contain known vulnerabilities
* Increased **attack surface** due to unnecessary exposed services

Such information can be leveraged by attackers for:

* Exploitation
* Lateral movement
* Privilege escalation
* Persistent access

---

## 🔐 Defensive Insights (Blue Team View)

🛡️ Based on findings, recommended mitigations include:

* Close unused ports and services
* Apply timely **patching and updates**
* Implement **network segmentation**
* Use **firewalls and IDS/IPS**
* Monitor scans via **SOC alerting**

---

## 📁 Project Outcome

✅ Learned real-world network reconnaissance techniques
✅ Understood how attackers map networks
✅ Improved Nmap command proficiency
✅ Enhanced network security analysis skills

This project strengthened my **foundational penetration testing and SOC investigation capabilities**.

---

## ⚠️ Legal & Ethical Disclaimer

> All scans were conducted in a **controlled lab environment** on systems owned by me or explicitly permitted for testing.
> Unauthorized scanning of live networks is illegal.

---
⭐ **If this repository helped you, consider starring it!**
🛡️ *Reconnaissance is the first step to both attack and defense.*
