#### 📌 Overview
This room focuses on Windows logging and how logs are used in Security Operations Centers (SOC) to monitor, detect, and investigate security events.

---

#### 🧠 Key Concepts

- **Windows Event Logs**
  - Record system, security, and application events  
  - Stored in Event Viewer  

- **Log Categories**
  - Security Logs → Login activity, authentication  
  - System Logs → OS-related events  
  - Application Logs → Application activity  

- **Event ID**
  - Unique identifier for each event  
  - Helps in detecting specific activities  

---

#### 🚨 Important Event IDs

- **4624** → Successful login  
- **4625** → Failed login  
- **4634** → Logoff  
- **4672** → Admin privileges assigned  

---

#### 🛡️ Logging Importance

- Detect unauthorized access  
- Identify brute force attacks  
- Monitor privilege escalation  
- Track user activity  

---

#### 🔍 SOC Analyst Notes

- Monitor:
  - Multiple failed login attempts (4625)  
  - Logins at unusual times  
  - Admin privilege usage (4672)  

- Investigate:
  - Suspicious login locations  
  - Repeated authentication failures  

---

#### 🧪 Key Takeaway

Windows logs are a critical data source for SOC analysts to detect and investigate security incidents effectively.
