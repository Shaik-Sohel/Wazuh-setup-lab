# Wazuh Setup Lab

## Project Overview
This project demonstrates the setup and configuration of Wazuh SIEM for security monitoring, log analysis, and threat detection in a virtual lab environment. The lab includes Windows and Kali Linux systems integrated with Wazuh for monitoring security events and suspicious activities.

---

## Tools and Technologies
- Wazuh SIEM
- Windows 10
- Kali Linux
- Sysmon
- VirtualBox / VMware
- Wireshark
- Nmap

---

## Objectives
- Configure Wazuh SIEM for centralized log monitoring
- Monitor Windows security events
- Detect brute-force attacks and suspicious activities
- Integrate Sysmon logs with Wazuh
- Perform basic threat detection and analysis

---

## Lab Architecture
- Wazuh Server
- Windows Endpoint with Wazuh Agent
- Kali Linux Attacker Machine
- Virtual Network Environment

---

## Features Implemented
- Installed and configured Wazuh Manager
- Connected Windows agent to Wazuh dashboard
- Integrated Sysmon for advanced log monitoring
- Monitored authentication and security events
- Created alerts for suspicious activities
- Performed network scanning detection
- Analyzed logs and security alerts

---

## Attack Simulations

### 1. Brute Force Attack Detection
- Simulated multiple failed login attempts
- Monitored Windows Event ID 4625
- Generated alerts in Wazuh dashboard

### 2. Nmap Scan Detection
- Performed network scanning using Nmap
- Detected suspicious scanning activities

### 3. Sysmon Monitoring
- Monitored process creation events
- Tracked PowerShell execution logs
- Analyzed security-related events

---

## Log Analysis
- Windows Security Event Monitoring
- Authentication Log Analysis
- Suspicious Activity Detection
- Alert Investigation and Correlation

---

## Screenshots Included
- Wazuh Dashboard
- Agent Connectivity Status
- Sysmon Event Logs
- Brute Force Detection Alerts
- Nmap Scan Detection

---

## Skills Gained
- SIEM Monitoring
- Threat Detection
- Log Analysis
- Windows Event Monitoring
- Incident Investigation
- Security Alert Analysis
- Basic Threat Hunting

---

## Commands Used

### Check Wazuh Agent Status
```bash
systemctl status wazuh-agent
```

### Nmap Scan
```bash
nmap -sS 192.168.1.0/24
```

### Windows Event ID for Failed Login
```text
4625
```

---

## Future Improvements
- Integrate Suricata IDS
- Configure Email Alerts
- Add Active Directory Monitoring
- Implement Threat Intelligence Integration
- Configure Custom Detection Rules

---

## Author
Shaik Sohel
Cybersecurity Enthusiast | SOC Analyst Aspirant
