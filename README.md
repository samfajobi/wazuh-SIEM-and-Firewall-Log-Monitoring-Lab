# SIEM-Log-Monitoring-with-Wazuh
# 🛡️ Wazuh SOC Home Lab  
### Building a Complete Security Operations Center (SOC) Environment Using Wazuh SIEM, Windows, Linux & Kali

This project demonstrates a full SOC (Security Operations Center) Home Lab designed to simulate real-world enterprise monitoring and detection using **Wazuh SIEM**.  
The setup includes a Wazuh Server, multiple monitored endpoints (Windows 10, Windows Server 2019, Ubuntu Server), and a Kali Linux attacker machine for adversary simulation.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Architecture Diagram](#architecture-diagram)
- [Lab Environment](#lab-environment)
- [Setup Guide](#setup-guide)
  - [Install Wazuh Server](#1-install-wazuh-server-ubuntu)
  - [Install Wazuh Agent on Windows 10](#2-install-wazuh-agent-on-windows-10)
  - [Install Wazuh Agent on Windows-server](#3-install-wazuh-agent-on-windows-server-2019)
  - [Install Wazuh Agent on Ubuntu](#4-install-wazuh-agent-on-ubuntu-server)
- [Attack Simulations](#attack-simulations)
- [Detection & Alerts](#detection--alerts)
- [What I Learned](#what-i-learned)
- [Repository Structure](#repository-structure)
- [Conclusion](#conclusion)

---

## 🧾 Overview
The purpose of this project is to build a production-style SOC lab environment using open-source tools.  
I deployed **Wazuh SIEM** on Ubuntu and installed agents on multiple operating systems to collect logs, detect threats, and simulate attacks using MITRE ATT&CK techniques.

This lab helps me practice:
- Endpoint detection & response
- Log analysis
- Incident detection & triage
- Linux auditd event monitoring
- Brute-force detection
- Threat hunting
- Windows & Linux security monitoring

---

## 🏗️ Architecture Diagram


