# Rekall Corp Penetration Test

**Author**: Andrew Boschini  
**Role**: Penetration Tester  
**Date**: April 2025  
**Certs in Progress**: Security+, Splunk Core Certified Power User

---

## Project Overview

This repo documents a simulated penetration test conducted against Rekall Corporation. The engagement involved identifying and exploiting multiple vulnerabilities across both Linux and Windows hosts, culminating in full domain compromise.

The purpose of this engagement was to evaluate Rekall’s internal and external security posture by simulating a real-world attacker using reconnaissance, exploitation, lateral movement, and post-exploitation techniques.

---

## Scope & Objectives

- Compromise multiple systems
- Escalate privileges
- Locate and exfiltrate sensitive information
- Document all steps and provide remediation

---

## Tools Used

- Nmap
- Nikto
- Burp Suite
- Metasploit
- Hydra
- Mimikatz
- Windows Exploit Suggester
- BloodHound
- WinPEAS
- Enum4linux

---

## Files Included

- attack-path.md – Step-by-step attack narrative from recon to domain takeover
- rekall-penetration-test-report.pdf – Full professional report with findings, evidence, and remediation
- screenshots/ – Terminal output, payloads, shells, and UI vulnerabilities
- exploits/ – Payload samples and Metasploit RC files

---

## Key Achievements

- SQL Injection leading to login bypass
- Reflected XSS and Local File Inclusion exploitation
- Remote Code Execution via Shellshock and Tomcat Manager
- Domain Admin hash captured through post-exploitation (Mimikatz, LSASS dump)
- Lateral movement and privilege escalation from compromised foothold

---

## Skills Demonstrated

- Vulnerability discovery and validation
- Exploitation of misconfigured web applications
- Post-exploitation and credential harvesting
- Attack chain documentation and remediation strategy
