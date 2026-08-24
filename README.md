# Networkwalks Cybersecurity Internship - Week 2

**Author:** Suraya Azeez  
**Program:** Networkwalks Cybersecurity & Ethical Hacking Internship[cite: 2]  
**Batch:** B082[cite: 2]  
**Date:** August 2026[cite: 2]  

---

## 📌 Overview
This repository contains the documentation, technical reports, and command output evidence for **Week 2** of the Networkwalks Cybersecurity Internship[cite: 2]. This week focused on two core operational phases of penetration testing: **Footprinting & Reconnaissance** (W2-PM1) and **Network Scanning with Zenmap** (W2-PM5)[cite: 2].

---

## 📂 Modules Completed & Technical Evidence

### 🛠️ Module 1: Footprinting & Reconnaissance (W2-PM1)
Conducted passive reconnaissance against the target domain (`networkwalks.com`) using six Kali Linux command-line tools[cite: 2, 3]:

* **Task 1: Domain Registration (`whois`)**  
  Retrieved domain registration, creation/expiry dates, and primary name servers[cite: 2, 3].  
  ![WHOIS Output](screenshots/task1-whois.png)

* **Task 2: Web Technology Fingerprinting (`whatweb`)**  
  Identified web application server details, CMS version (WordPress), and active plugins[cite: 2, 3].  
  ![WhatWeb Output](screenshots/task2-whatweb.png)

* **Task 3: Domain IP Resolution (`nslookup`)**  
  Resolved the public domain name to its corresponding public IP address[cite: 2, 3].  
  ![Nslookup Output](screenshots/task3-nslookup.png)

* **Task 4: HTTP Header Inspection (`curl -I`)**  
  Analyzed server response headers and identified exposed REST API endpoints[cite: 2, 3].  
  ![cURL Output](screenshots/task4-curl.png)

* **Task 5: WAF Detection (`wafw00f`)**  
  Identified active Web Application Firewall protection (ModSecurity WAF)[cite: 2, 3].  
  ![Wafw00f Output](screenshots/task5-wafw00f.png)

* **Task 6: DNS Record Enumeration (`dnsrecon`)**  
  Enumerated DNS infrastructure, including NS, MX, SOA, and SPF records[cite: 2, 3].  
  ![DNSRecon Output](screenshots/task6-dnsrecon.png)

---

### 🌐 Module 2: Network Scanning with Zenmap (W2-PM5)
Executed active network discovery on the local area network (LAN)[cite: 2]:

* **Task 1–6: Local Host & Subnet Discovery (`nmap -sn`)**  
  Identified local network range via Windows `ipconfig` and ran a Ping Scan using Zenmap (Nmap GUI) to discover active IP/MAC addresses[cite: 1, 2].  
  ![Zenmap Ping Scan](screenshots/zenmap-scan.png)

* **Task 7: Network Topology Mapping**  
  Generated and exported the local subnet visual network topology map[cite: 1, 2].  
  ![Zenmap Topology Map](screenshots/zenmap-topology.png)

---

## 📄 Key Deliverables
* **Penetration Testing Report:** Formal summary covering recon methodology, risk evaluations, and defensive mitigations[cite: 2].
* **Evidence Collection:** Screenshot evidence for all terminal and graphical outputs[cite: 2, 3].

---

## ⚠️ Liability Disclaimer
All footprinting, scanning, and security assessment activities documented in this repository were conducted strictly for educational purposes within authorized lab scopes and local test networks[cite: 2].
