# week2-footprinting-reconnaissance
Week 2 Project: Footprinting and Reconnaissance on networkwalks.com using Kali Linux tools
# Week 2 Project: Footprinting & Reconnaissance Report

**Author:** Sangamithra.P
**Date:** September 2026
**Domain Target:** networkwalks.com

---

## 📖 Overview
This repository contains the complete report for my Week 2 project on Footprinting and Reconnaissance. The objective was to gather publicly available information about a target domain and its infrastructure using a variety of industry-standard tools within Kali Linux.

## 🛠️ Tools Used
| Tool | Purpose |
| :--- | :--- |
| **whois** | Domain registration details |
| **whatweb / curl** | Web server fingerprinting |
| **nslookup / dnsrecon** | DNS enumeration |
| **wafw00f** | Web Application Firewall detection |
| **Zenmap (Nmap GUI)** | Network host discovery |
| **Maltego** | Visual infrastructure mapping |
| **theHarvester** | Public information gathering |

## 🔍 Key Findings
*   **Domain Registrar:** GoDaddy.com, LLC
*   **Web Server:** Apache (running WordPress 7.1)
*   **Security:** Protected by ModSecurity (SpiderLabs) WAF
*   **Network:** Discovered 2 live hosts on the `10.0.0.0/24` subnet (`10.0.0.1` and `10.0.0.2`)
*   **Critical Finding:** An exposed webcam interface at a public IP address

## 📄 Full Report
The complete report with all screenshots and detailed analysis is available in the PDF file included in this repository.

## 📚 References
*   Nmap Documentation
*   Maltego Documentation
*   OWASP WAF Documentation
*   DNSRecon Documentation
*   WAFW00F Documentation
