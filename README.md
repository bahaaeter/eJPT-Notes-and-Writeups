# 🛡️ eLearnSecurity Junior Penetration Tester (eJPT) - Notes & Writeups

## 📖 Objective
This repository contains my structured notes, custom cheat sheets, and detailed machine writeups created while preparing for the **eJPT v2** certification. It serves as a working portfolio demonstrating my practical methodology for network enumeration, web application exploitation, and network pivoting. 

As a cybersecurity professional with a computer science background, I approach penetration testing systematically, focusing not just on the exploit, but on clear documentation and actionable remediation.

---

## 📂 Repository Structure

* 📌 **[`/Cheat-Sheets`](./Cheat-Sheets)** - My personal, quick-reference guides for Nmap, Metasploit, Privilege Escalation, and Network Pivoting.
* 📝 **[`/eJPT-Notes`](./eJPT-Notes)** - Condensed, chronological notes based on penetration testing phases (Recon, Web Apps, Post-Exploitation).
* 🎯 **[`/Machine-Writeups`](./Machine-Writeups)** - Step-by-step documentation of lab machines, formatted as professional penetration test reports.
* 🛠️ **[`/Custom-Scripts`](./Custom-Scripts)** - Python and Bash scripts I wrote to automate routine enumeration tasks.

---

## 🚀 Featured Writeups
*(Links will be added as machines are completed)*
1. **[TryHackMe Wreath Network](./Machine-Writeups/Wreath.md)** - Demonstrates network pivoting via Metasploit `autoroute` and compromising a multi-tiered network.
2. **[PortSwigger: SQL Injection Bypass](./Machine-Writeups/SQLi-Bypass.md)** - A manual exploitation of a web application login portal using UNION-based SQLi.
3. **[HackTheBox: Lame](./Machine-Writeups/HTB-Lame.md)** - A full walkthrough of exploiting an outdated SMB service to gain root access.

---

## 🔍 Assessment Methodology

My approach aligns closely with the core eJPT domains and standard industry frameworks:

1. **Information Gathering & Reconnaissance:** 
   * Thorough port scanning and service fingerprinting using `nmap`.
   * Directory brute-forcing and web architecture profiling with `gobuster` and Burp Suite.
2. **Vulnerability Assessment:** 
   * Manual verification of web vulnerabilities (SQLi, XSS, IDOR) before relying on automated scanners.
   * Identifying misconfigurations in AD, SMB, and FTP.
3. **Exploitation & Pivoting:** 
   * Leveraging Metasploit and manual payload generation (`msfvenom`).
   * Establishing persistence and routing traffic through compromised hosts to access internal subnets.
4. **Reporting & Mitigation:** 
   * Translating technical findings into clear business risks and providing developer-centric remediation advice.

---

## ⚖️ Legal Disclaimer
**All writeups, scripts, and techniques documented in this repository are for educational purposes only.** They are intended for use strictly in authorized, simulated lab environments (such as Hack The Box, TryHackMe, and the PortSwigger Web Security Academy). I do not condone, encourage, or participate in unauthorized access or illegal hacking activities.
