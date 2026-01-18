# EternalBlue (MS17-010) Vulnerability Exploitation

## Overview
EternalBlue is a critical vulnerability in Microsoft SMBv1 that allows remote code execution.
This CTF focused on identifying and exploiting MS17-010 on a vulnerable Windows system.

## Vulnerability Details
- Name: EternalBlue
- CVE: MS17-010
- Protocol: SMBv1
- Impact: Remote Code Execution

## Tools Used
- Nmap
- Metasploit Framework
- SMB Enumeration scripts

## Exploitation Steps
1. Performed SMB service discovery using Nmap
2. Identified vulnerable SMB version
3. Used Metasploit MS17-010 module
4. Successfully gained shell access
5. Navigated system to locate the flag

## Learning Outcome
- Understanding SMB vulnerabilities
- Practical exploitation using Metasploit
- Post-exploitation navigation
- Importance of timely patching

## Mitigation
- Disable SMBv1
- Apply MS17-010 security patch
- Use network segmentation
