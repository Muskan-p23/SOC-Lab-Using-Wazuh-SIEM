# SOC-Lab-Using-Wazuh-SIEM
# 🛡️ Design and Implementation of a Security Operations Center (SOC) Lab Using Wazuh SIEM

A hands-on Security Operations Center (SOC) laboratory built using **Wazuh SIEM**, **Docker**, **Sysmon**, and a **Windows 10 Virtual Machine** to simulate real-world security monitoring, threat detection, and incident investigation.

---

## 📖 Project Overview

This project demonstrates the deployment of a Security Operations Center (SOC) using the open-source Wazuh SIEM platform. The lab was designed to provide practical experience in:

- Security monitoring
- Log collection and analysis
- Threat detection
- File Integrity Monitoring (FIM)
- Endpoint monitoring
- Incident investigation
- Custom detection rule creation

The project simulates real-world SOC analyst activities by generating and investigating security events from a Windows endpoint.

---

## 🎯 Project Objectives

- Deploy Wazuh SIEM using Docker
- Configure Windows 10 as the monitored endpoint
- Integrate Sysmon for enhanced event logging
- Monitor security events using the Wazuh Dashboard
- Detect suspicious PowerShell and process activity
- Configure File Integrity Monitoring (FIM)
- Create and validate custom Wazuh detection rules
- Perform ransomware-like activity simulation
- Analyze alerts using the MITRE ATT&CK Framework

---

## 🏗️ SOC Lab Architecture

```
Windows 10 VM
        │
        ▼
   Wazuh Agent
        │
        ▼
  Wazuh Manager
        │
        ▼
  Wazuh Indexer
        │
        ▼
 Wazuh Dashboard
        │
        ▼
   SOC Analyst
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Wazuh SIEM | Security monitoring & log analysis |
| Docker Desktop | Containerized deployment |
| Windows 10 VM | Endpoint monitoring |
| Sysmon | Advanced Windows event logging |
| PowerShell | Attack simulation |
| File Integrity Monitoring (FIM) | File change detection |
| OpenSearch Dashboard | Alert visualization |
| MITRE ATT&CK | Threat mapping |
| VirtualBox | Virtualization |

---

## 🔍 Security Scenarios Performed

- ✅ Wazuh deployment using Docker
- ✅ Windows Agent configuration
- ✅ Sysmon integration
- ✅ Process Creation Monitoring
- ✅ PowerShell Detection
- ✅ Windows Service Creation Detection
- ✅ File Integrity Monitoring (FIM)
- ✅ Custom Detection Rule (Rule ID 100100)
- ✅ Ransomware-like activity simulation
- ✅ Incident investigation and analysis

---

## 🚨 Detection Examples

During the project, the following security events were successfully detected:

- Process creation events
- PowerShell execution
- Windows service creation
- File creation and modification
- File Integrity Monitoring (Rule ID 554)
- Custom detection rule execution (Rule ID 100100)
- Suspicious endpoint activities
- Ransomware simulation alerts

---

## 🧠 Skills Demonstrated

- Security Information and Event Management (SIEM)
- Security Operations Center (SOC)
- Threat Detection
- Threat Hunting
- Incident Investigation
- Log Analysis
- Windows Event Monitoring
- Docker Deployment
- Endpoint Security Monitoring
- MITRE ATT&CK Mapping
- Custom Rule Development
- Digital Forensics Fundamentals

---

## 📄 Project Report

The complete project documentation is available in:

**SOC_Lab_Project_Report.pdf**

The report includes:

- Environment setup
- Installation
- Configuration
- Detection scenarios
- Incident analysis
- Screenshots
- Conclusions
- References

---

## 📚 References

- Wazuh Documentation
- Docker Documentation
- Microsoft Sysmon Documentation
- MITRE ATT&CK Framework
- Microsoft Windows Security Documentation

---

## 👩‍💻 Author

**Muskan Paraswani**

M.Sc. Cybersecurity & Digital Forensics

Institute of Advanced Research (IAR), Gandhinagar

---

## ⭐ Repository Purpose

This repository has been created as a personal cybersecurity portfolio project to demonstrate practical experience in:

- Security Operations Center (SOC)
- SIEM Implementation
- Threat Detection
- Incident Response
- Digital Forensics

---

If you found this project helpful, consider giving it a ⭐.
