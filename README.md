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
  ![WHOIS Output](image_5bc8c3.png)

* **Task 2: Web Technology Fingerprinting (`whatweb`)**  
  Identified web application server details, CMS version (WordPress), and active plugins.  
  ![WhatWeb Output](image_5bc8df.png)

* **Task 3: Domain IP Resolution (`nslookup`)**  
  Resolved the public domain name to its corresponding public IP address.  
  ![Nslookup Output](image_5bc920.png)

* **Task 4: HTTP Header Inspection (`curl -I`)**  
  Analyzed server response headers and identified exposed REST API endpoints.  
  ![cURL Output](image_5bc926.png)

* **Task 5: WAF Detection (`wafw00f`)**  
  Identified active Web Application Firewall protection (ModSecurity WAF).  
  ![Wafw00f Output](image_5bcc27.png)

* **Task 6: DNS Record Enumeration (`dnsrecon`)**  
  Enumerated DNS infrastructure, including NS, MX, SOA, and SPF records.  
  ![DNSRecon Output](task6-dnsrecon.png)

---

### 🌐 Module 2: Network Scanning with Zenmap (W2-PM5)
Executed active network discovery on the local area network (LAN):

* **Task 1–6: Local Host & Subnet Discovery (`nmap -sn`)**  
  Identified local network range via Windows `ipconfig` and ran a Ping Scan using Zenmap (Nmap GUI) to discover active IP/MAC addresses.  
  ![Zenmap Ping Scan](image_5bd083.png)

* **Task 7: Network Topology Mapping**  
  Generated and exported the local subnet visual network topology map.  
  ![Zenmap Topology Map](image_5bd06a.png)

---

## 📄 Key Deliverables
* **Penetration Testing Report:** Formal summary covering recon methodology, risk evaluations, and defensive mitigations.
* **Evidence Collection:** Screenshot evidence for all terminal and graphical outputs.

---

## ⚠️ Liability Disclaimer
All footprinting, scanning, and security assessment activities documented in this repository were conducted strictly for educational purposes within authorized lab scopes and local test networks.
