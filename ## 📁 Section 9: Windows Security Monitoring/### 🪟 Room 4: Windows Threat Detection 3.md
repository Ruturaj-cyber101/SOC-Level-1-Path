#### 📌 Overview
This room focuses on advanced threat detection techniques in Windows environments, emphasizing identifying sophisticated attack patterns, persistence mechanisms, and attacker behavior.

---

#### 🧠 Key Concepts

- **Attack Lifecycle Awareness**
  - Initial access → Execution → Persistence → Privilege escalation  

- **Persistence Techniques**
  - Scheduled tasks  
  - Registry run keys  
  - Startup programs  

- **Lateral Movement**
  - Attackers moving across systems within a network  

---

#### 🚨 Common Threat Indicators

- **Persistence Activity**
  - New scheduled tasks created  
  - Registry modifications  

- **Lateral Movement**
  - Multiple systems accessed by same user  
  - Remote logins across hosts  

- **Suspicious Services**
  - Unknown services installed or running  

---

#### 🛡️ Detection Techniques

- Monitor registry and scheduled task changes  
- Track logins across multiple systems  
- Analyze service creation events  
- Correlate logs using SIEM  

---

#### 🔍 SOC Analyst Notes

- Look for:
  - Activity across multiple endpoints  
  - Unusual service installations  
  - Repeated access attempts on different machines  

- Investigate:
  - Timeline of attacker movement  
  - Registry and startup changes  
  - Service execution behavior  

---

#### 🧪 Key Takeaway

Detecting advanced threats requires understanding attacker techniques such as persistence and lateral movement, along with correlating events across systems.
