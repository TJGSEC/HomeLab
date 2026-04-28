# HomeLab
HomeLab Enviroment 
## Overview
Isolated virtual lab built in virtual box to practise offensive and defensive security techniques in a controlled enviroment.
## Environment
| Machine | OS | Role |
|---|---|---|
| Attacker | Kali Linux | Offensive testing |
| Target | Metasploitable 2 | Vulnerable target |
| DNS Filter | Pi-hole (Ubuntu VM) | Network defence |

Machines are isolated on an internal virtual network with 
no internet exposure.

## What I Practised

**Reconnaissance**
- Network scanning with Nmap to enumerate open ports, 
  running services, and OS fingerprinting

**Exploitation**
- Exploited vsftpd 2.3.4 backdoor via Metasploit — 
  achieved root-level shell
- Command injection leading to remote code execution 
  and file extraction

**Web Application Attacks**
- SQL injection to extract and dump database credentials
- Cross-Site Scripting (XSS) to demonstrate client-side 
  vulnerabilities

**Password Cracking**
- Cracked MD5 hashes using John the Ripper with rockyou.txt

**Network Defence**
- Deployed Pi-hole as a DNS-level filter to block malicious 
  and tracking domains

## Tools Used
Nmap · Metasploit Framework · John the Ripper · VirtualBox · Pi-hole

## Purpose
Built to develop hands-on skills ahead of entry-level SOC and 
security analyst roles. Documented to demonstrate practical 
ability alongside certifications.
