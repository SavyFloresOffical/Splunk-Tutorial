# 🔎 TryHackMe: Splunk Tutorial  

## 📖 Overview  
This room introduced me to **Splunk**, one of the leading **SIEM (Security Information and Event Management)** platforms. The focus was on navigating log data, building queries, and understanding how Splunk supports **Blue Team** operations for monitoring, detection, and incident response.  

Splunk is widely used because it can ingest and analyze massive amounts of machine-generated data in real time, making it an essential tool for Security Operations Centers (SOCs).  

---

## 🏗 Splunk Architecture  
- **Indexes** – Store all ingested event data for fast searches.  
- **Search Head** – The analyst’s interface to query, filter, and visualize data.  
- **Forwarders** – Lightweight agents that collect and send log data from endpoints/servers into Splunk.  

This architecture ensures scalability and efficiency in enterprise log management.  

---

## 🔍 Log Navigation & Filtering  
I practiced working with **VPN logs** to explore Splunk’s search functionality and filtering.  

Key takeaways:  
- Filtering by **username, IP, or country** helps analysts quickly identify patterns.  
- Using search queries is far more effective than manually parsing large log files.  
- Even outside of Splunk’s GUI, I practiced parsing raw logs to answer questions — a useful skill when analysts must work directly with log files.  

---

## 🔐 Blue Team Application  
Splunk is invaluable for defenders because it enables:  
- **Real-time monitoring** of system and user activity.  
- **Incident investigation** by filtering logs linked to suspicious IPs, accounts, or failed login attempts.  
- **Correlation of multiple events** to detect anomalies that might otherwise go unnoticed.  

### 📊 Practical Exercise  
From a dataset of **2,862 VPN log entries**, I investigated country-specific login attempts:  

- **Events from France:** 48  
- **Events from all other countries:** 2,814  

This reinforced the importance of **efficient log filtering** and showed how Splunk enables quick identification of geographic patterns in network traffic.  

---

## 💡 Reflection  
This room demonstrated how Splunk acts as a **force multiplier** for Blue Team analysts. Instead of manually sifting through thousands of logs, Splunk’s search and filtering capabilities streamline threat detection and response.  

> **Logs tell a story — Splunk helps Blue Teams read that story faster and respond to threats more effectively.**  

---

## ✅ Skills Gained  
- Navigating Splunk interface and architecture  
- Querying and filtering large log datasets  
- Understanding Splunk’s role in SIEM and Blue Team operations  
- Applying log analysis to real-world scenarios  

---

## 🚀 Next Steps  
- Apply Splunk skills to hands-on detection labs.  
- Explore how alerts and dashboards can be automated for SOC workflows.  

---
