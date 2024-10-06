# CAPSTONE-PROJECT-WESTWILD-2.0
"Walkthrough of the 'Westwild: 2' boot2root challenge from VulnHub, demonstrating penetration testing techniques and privilege escalation methods. Includes detailed steps for enumeration, exploitation, and flag capture."

# Westwild: 2 - Boot2Root Walkthrough

## Overview
This repository contains a detailed walkthrough of the "Westwild: 2" boot2root challenge available on VulnHub. The challenge focuses on penetration testing techniques like enumeration, exploitation, and privilege escalation.

## Challenge Level: Intermediate

- **Author:** Hashim Alsharef
- **Target IP:** 192.168.1.105 (example, can vary)
- **Tools Used:**
  - Netdiscover
  - Nmap
  - Dirb
  - BurpSuite
  - Metasploit
  - LinEnum
  - wget

## Walkthrough
The following steps are taken to successfully breach the target system and capture the flag:

1. **Network Scanning:** Using Netdiscover and Nmap to identify open ports and services.
2. **Enumeration:** Exploring HTTP services and brute-forcing directories using Dirb.
3. **Exploiting:** Brute-forcing CMS login credentials with BurpSuite and exploiting the Showtime2 plugin using Metasploit.
4. **Privilege Escalation:** Gaining root access by exploiting SUID binaries and modifying the `/etc/passwd` file.

## Flag Capture
"Ding-dong! We captured the flag and completed the challenge."

## License
This repository is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International License](LICENSE).

## Disclaimer
This content is for educational purposes only. Unauthorized penetration testing or exploitation of systems is illegal.

