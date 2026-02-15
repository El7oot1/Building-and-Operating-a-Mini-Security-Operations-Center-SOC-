# 🛡️ Building and Operating a Mini Security Operations Center (SOC)

## 📋 Project Information
* **Group Name:** ONL4_ISS6_S2
* **Project Focus:** Cybersecurity / Defensive Security Operations

## 📌 Project Overview
This project demonstrates the design, deployment, and operation of a **Mini Security Operations Center (SOC)**. It aims to provide a practical environment for monitoring network traffic, detecting cyber threats, and analyzing logs using industry-standard tools. The project simulates real-world attack scenarios to test the efficiency of defensive measures and incident response.

## 👥 Team Members
We are a dedicated team of engineers working together to build and secure this environment:
1. **Mohamed Mostafa Elhoot**
2. **Islam Esam**
3. **Mohamed Ashraf**
4. **Ameen Yasser**
5. **Hussien Ahmed**


---

## 🚀 Key Features
* **Centralized Log Management:** Collecting and normalizing logs from multiple endpoints.
* **Real-time Threat Detection:** Implementing rules to identify malicious activities like Brute Force, Port Scanning, and Malware execution.
* **Security Dashboards:** Visualizing security events for better situational awareness.
* **Incident Response:** Simulating attacks and documenting the detection-to-mitigation workflow.

## 🛠️ Tech Stack
* **Virtualization:** VMware / VirtualBox
* **SIEM/XDR:** (e.g., Wazuh, ELK Stack, or Splunk)
* **IDS/IPS:** (e.g., Suricata, Snort)
* **Operating Systems:** Kali Linux (Attacker), Ubuntu/Windows (Victims & Monitoring)

## 🏗️ Architecture
1. **Endpoints:** Monitored assets (Windows/Linux servers).
2. **SOC Manager:** The brain of the operation where logs are analyzed.
3. **Visualization:** Dashboards used for monitoring and reporting.

## 📊 Getting Started
1. **Prerequisites:** Ensure you have at least 16GB RAM for the virtual environment.
2. **Deployment:** Install the SIEM manager and deploy agents to the endpoints.
3. **Simulation:** Run a test attack from Kali Linux and monitor the alerts on the SOC dashboard.

---
