# Multi-Layered SOC Lab: Threat Detection & Automated Malware Remediation

**By:** Olakunle Odesanya  
Entry-Level Cybersecurity Analyst  
May 2026  

Tech Stack: Wazuh (SIEM), Suricata (IDS), VirusTotal API, Ubuntu (Endpoint), Kali Linux (Manager), Diamorphine

## 1. Executive Summary
This project demonstrates the deployment of a functional Security Operations Center (SOC) designed to detect host-based, network-based, identity-based and file-based threats. By integrating Wazuh, Suricata, and VirusTotal, I created a unified visibility pipeline that identifies kernel-level obfuscation (rootkits), malicious network patterns, unauthorized access attempts, and automated malware remediation within a virtualized lab environment.

![Image](./Screenshots/SS_Wazuh_M&S.png)

## 2. Infrastructure Architecture
The lab environment was built using a private virtual network to simulate an enterprise internal LAN.
•	Wazuh Manager: Kali Linux (Centralized Intelligence).
•	Managed Endpoint: Agent Name: SOC_Lab_Endpoint (Ubuntu 22.04 LTS) 
•	Connectivity: The SOC_Lab_Endpoint agent communicates with the Manager over a dedicated virtual bridge. Connectivity was verified via the Wazuh Dashboard, showing the agent status as "Active." 


