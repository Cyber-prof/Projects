## Overview
This repository contains a SOC-style incident response analysis of an FTP compromise
identified through packet capture analysis using Wireshark.

The incident was evaluated using the NIST SP 800-61 Incident Response Framework
and mapped to standard security practices.

## Incident Summary
- Target Host: FTP Server (.101)
- Threat Actors: .102 (initial access) and .1 (brute-force)
- Attack Techniques:
  - Port scanning on TCP/21
  - Credential compromise
  - Brute-force attack
  - Unauthorized file deletion (DELE command)
- Impact: Unauthorized access and file deletion

## Tools Used
- Wireshark
- TCP Stream Analysis
- NIST SP 800-61 Framework
- CyBOK Incident Response Concepts

## Files
- `report/NIST_Incident_Response_Report.pdf` – Final incident response report
