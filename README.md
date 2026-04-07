# 🚨 SIEM Alert Triage & Incident Investigation (Splunk & ELK)

🔗 **Live Repo:** [github.com/Matt-Solo/siem-tryhackme-lab](https://github.com/Matt-Solo/siem-tryhackme-lab)

## 🎯 Project Overview

This project demonstrates a **Security Operations Center (SOC) investigation** involving detection and analysis of suspicious authentication activity using SIEM tools.

The objective was to identify potential brute-force attack behaviour, analyse security logs, correlate events, and recommend appropriate response actions.

---

## 🧪 Environment

* SIEM Platforms: Splunk / ELK
* Data Source: Windows Event Logs
* Log Types: Authentication Events (Event ID 4625 & 4624)

---

## 🔍 Investigation Process

### 1. Alert Detection

* Identified abnormal spikes in failed login attempts
* Observed repeated authentication failures within a short timeframe

---

### 2. Log Analysis

* Filtered logs using Event ID 4625 (failed logins)
* Identified a pattern of repeated login attempts from a single IP address

---

### 3. Event Correlation

* Correlated failed login attempts with successful login events (Event ID 4624)
* Determined potential account compromise behaviour

---

### 4. Threat Mapping

* Mapped observed activity to:

  * **MITRE ATT&CK: T1110 (Brute Force Attack)**

---

## 📊 Key Findings

* High volume of failed login attempts detected
* Repeated login attempts from a single source IP
* Successful login following multiple failed attempts
* Indicators consistent with brute-force attack activity

---

## ⚠️ Security Impact

* Risk of unauthorized access
* Potential account compromise
* Exposure of sensitive systems and data

---

## 🛡️ Response Recommendations

* Enforce account lockout policies
* Block or monitor suspicious IP address
* Enable Multi-Factor Authentication (MFA)
* Implement continuous monitoring for similar activity

---

## 🛠️ Skills Demonstrated

* SIEM alert triage and investigation
* Log analysis and event correlation
* Threat detection and analysis
* MITRE ATT&CK mapping
* Incident documentation and reporting

---

## 📸 Investigation Evidence (https://github.com/Matt-Solo/siem-tryhackme-lab)

Screenshots included in this repository demonstrate:

* SIEM queries and log filtering
* Failed login patterns
* Event correlation analysis

---

## 🎯 Conclusion

This project demonstrates the ability to **detect, analyse, and respond to security incidents** using SIEM tools and structured SOC workflows, reflecting real-world Tier 1 SOC analyst responsibilities.


--- 


✅ *Lab Completed on TryHackMe*  
🔗 [Visit TryHackMe](https://tryhackme.com)


