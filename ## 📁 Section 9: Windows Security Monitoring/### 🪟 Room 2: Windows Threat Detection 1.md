#### 📌 Overview
This room focuses on detecting threats in Windows environments by analyzing system and security logs. It introduces common attack patterns and how SOC analysts identify malicious activity.

---

#### 🧠 Key Concepts

- **Threat Detection**
  - Identifying malicious or suspicious activity  
  - Based on log analysis and behavior patterns  

- **Windows Event Monitoring**
  - Tracking login activity  
  - Monitoring process execution  
  - Observing system changes  

---

#### 🚨 Common Threat Indicators

- **Brute Force Attack**
  - Multiple failed login attempts (Event ID 4625)  

- **Suspicious Logins**
  - Logins at unusual times  
  - Logins from different locations  

- **Privilege Escalation**
  - Admin rights assigned (Event ID 4672)  

- **Unauthorized Processes**
  - Unknown or suspicious applications running  

---

#### 🛡️ Detection Techniques

- Analyze Windows Security Logs  
- Correlate events using SIEM (e.g., Splunk)  
- Identify abnormal user behavior  
- Monitor process creation events  

---

#### 🔍 SOC Analyst Notes

- Look for:
  - Repeated failed logins followed by success  
  - Sudden admin privilege assignment  
  - Unusual process execution  

- Investigate:
  - Source IP addresses  
  - User activity patterns  
  - Timeline of events  

---

#### 🧪 Key Takeaway

Effective threat detection in Windows relies on identifying abnormal patterns in logs and correlating multiple events to detect potential attacks.
