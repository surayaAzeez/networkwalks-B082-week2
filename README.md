# Networkwalks Cybersecurity Internship - Week 2

**Author:** Suraya Azeez  
**Program:** Networkwalks Cybersecurity & Ethical Hacking Internship  
**Batch:** B082  
**Date:** August 2026  

---

## 📌 Overview
This repository contains the documentation, technical reports, and command output evidence for **Week 2** of the Networkwalks Cybersecurity Internship. This week focused on two core operational phases of penetration testing: **Footprinting & Reconnaissance** (W2-PM1) and **Network Scanning with Zenmap** (W2-PM5).

---

## 📂 Modules Completed & Technical Evidence

### 🛠️ Module 1: Footprinting & Reconnaissance (W2-PM1)
Conducted passive reconnaissance against the target domain (`networkwalks.com`) using six Kali Linux command-line tools:

* **Task 1: Domain Registration (`whois`)**  
  Retrieved domain registration, creation/expiry dates, and primary name servers.  
  ![Task 1 - WHOIS Output](task1-whois.png)

* **Task 2: Web Technology Fingerprinting (`whatweb`)**  
  Identified web application server details, CMS version (WordPress), and active plugins.  
  ![Task 2 - WhatWeb Output](task2-whatweb.png)

* **Task 3: Domain IP Resolution (`nslookup`)**  
  Resolved the public domain name to its corresponding public IP address.  
  ![Task 3 - Nslookup Output](task3-nslookup.png)

* **Task 4: HTTP Header Inspection (`curl -I`)**  
  Analyzed server response headers and identified exposed REST API endpoints.  
  ![Task 4 - cURL Output](task4-curl.png)

* **Task 5: WAF Detection (`wafw00f`)**  
  Identified active Web Application Firewall protection (ModSecurity WAF).  
  ![Task 5 - Wafw00f Output](task5-wafw00f.png)

* **Task 6: DNS Record Enumeration (`dnsrecon`)**  
  Enumerated DNS infrastructure, including NS, MX, SOA, and SPF records.  
  ![Task 6 - DNSRecon Output](task6-dnsrecon.png)

---

### 🌐 Module 2: Network Scanning with Zenmap (W2-PM5)
Executed active network discovery on the local area network (LAN):

* **Task 1–6: Local Host & Subnet Discovery (`nmap -sn`)**  
  Identified local network range via Windows `ipconfig` and ran a Ping Scan using Zenmap (Nmap GUI) to discover active IP/MAC addresses.  
  ![Task 7 - Zenmap Ping Scan](task7-zenmap-scan.png)

* **Task 7: Network Topology Mapping**  
  Generated and exported the local subnet visual network topology map.  
  ![Task 7 - Zenmap Topology Map](task7-zenmap-topology.png)

---

## 📄 Key Deliverables
* **Penetration Testing Report:** Formal summary covering recon methodology, risk evaluations, and defensive mitigations.
* **Evidence Collection:** Screenshot evidence for all terminal and graphical outputs.

---

## ⚠️ Liability Disclaimer
All footprinting, scanning, and security assessment activities documented in this repository were conducted strictly for educational purposes within authorized lab scopes and local test networks.
