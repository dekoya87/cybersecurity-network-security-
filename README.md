# Cybersecurity & Network Security Administration Portfolio

## Overview
Entry-level Cybersecurity professional with an **AAS in Cybersecurity (Network Security Administration emphasis)** from **Dallas College**. This portfolio demonstrates hands-on experience aligned with **SOC Analyst and Network Security Intern** roles, including packet analysis, firewall configuration, log investigation, and SIEM monitoring.

---

## 1. Network Traffic Analysis (Wireshark)

**Objective:**  
Analyze network traffic to distinguish normal behavior from suspicious activity.

**Tools:**  
Wireshark, Windows 10

**Summary:**  
Captured live network traffic and applied protocol filters (TCP, DNS, HTTP). Identified normal browsing patterns, TCP handshakes, and DNS queries. No malicious or abnormal traffic detected.

**Skills Demonstrated:**  
Packet analysis, protocol filtering, network troubleshooting

📁 Evidence: `wireshark-analysis/screenshots/`

---

## 2. Firewall Configuration & Access Control

**Objective:**  
Restrict unauthorized traffic while allowing approved network services.

**Tools:**  
Linux iptables, Windows Defender Firewall

**Summary:**  
Created inbound and outbound firewall rules to block unused ports and allow HTTP/HTTPS traffic. Verified rule effectiveness through connectivity testing.

**Skills Demonstrated:**  
Firewall policy creation, access control, traffic filtering

📁 Evidence: `firewall-configuration/screenshots/`

---

## 3. Log Analysis & Security Monitoring

**Objective:**  
Investigate system and security events to identify potential security issues.

**Tools:**  
Windows Event Viewer

**Summary:**  
Reviewed security logs and identified failed login attempts (Event ID 4625). Correlated timestamps and user accounts to confirm non-malicious activity.

**Skills Demonstrated:**  
Log analysis, event correlation, basic incident investigation

📁 Evidence: `log-analysis/event-viewer-screenshots/`

---

## 4. SIEM Lab – Splunk (SOC Readiness)

**Objective:**  
Use a SIEM to detect and analyze authentication-related security events.

**Tools:**  
Splunk Free / Trial

**Summary:**  
Ingested Windows security logs into Splunk. Created search queries to identify failed login attempts and reviewed results for escalation indicators.

**Sample Query:**

