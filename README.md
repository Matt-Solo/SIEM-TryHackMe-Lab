# 🛡️SOC WORKFLOW

🔗 **Live Repo:** [github.com/Matt-Solo/siem-tryhackme-lab](https://github.com/Matt-Solo/siem-tryhackme-lab)

This repository documents my hands-on experience with the **"Introduction to SIEM"** lab on TryHackMe. The lab provided a guided, interactive experience using Security Information and Event Management (SIEM) tools in a simulated SOC environment.


## 📂 Repository Content

- `walkthrough.md` – Detailed step-by-step notes  
- `splunk-queries.txt` – Useful SPL queries  
- `screenshots/` – Key snapshots from the lab  
- `ioc-report.md` – Indicators of compromise (IOCs) documented  

---

## 🔑 Key Skills & Lessons Learned

- ✅ Gained foundational knowledge of **SIEM tools and architecture**
- ✅ Analyzed real-world security events using **Splunk**
- ✅ Investigated suspicious logins and brute-force activity via **Event IDs**
- ✅ Practiced writing **SPL (Search Processing Language)** queries
- ✅ Understood how SIEM platforms support **threat detection and incident response**

---

## 🛠️ Tools & Technologies Used

- 🧠 **Splunk**  
- 🖥️ **Windows Event Logs**  
- 🧪 **TryHackMe Virtual SOC Lab**

---

## 🧭 Lab Walkthrough (Steps Taken)

1. ✅ Launched a virtual SOC environment with Splunk pre-installed  
2. 📥 Collected and explored **Windows Security Event Logs**  
3. 🔍 Searched for **Event ID 4625** (failed logins) and **4688** (process creation)  
4. 🧠 Analyzed user login patterns and detected brute-force attempts  
5. 🧩 Correlated events across log sources using **SPL queries**  
6. 📊 Created basic dashboards and visualizations in Splunk  
7. 📝 Completed incident response questions based on live log data  

---

## 🔍 Investigation Highlights

- Detected multiple **account lockouts** and suspicious login attempts  
- Identified **process executions** tied to potential malicious behavior  
- Filtered logs based on IP, user, and timestamp to **pinpoint threats**  
- Mapped attacker behavior patterns using **event correlation**

---

## 🎯 Why This Lab Matters

This lab simulated the daily tasks of a **SOC Analyst**, allowing me to:

- Think critically when analyzing log data  
- Use **SPL** to uncover hidden security threats  
- Understand how SIEM tools contribute to **threat detection and response**  
- Build confidence in handling structured investigations using enterprise tools

It’s another practical step in my journey to becoming a **job-ready SOC Analyst**.

--- 


✅ *Lab Completed on TryHackMe*  
🔗 [Visit TryHackMe](https://tryhackme.com)


