#### 📌 Overview
This room builds on previous threat detection concepts by focusing on advanced analysis of Windows events and identifying more complex attack behaviors in a SOC environment.

---

#### 🧠 Key Concepts

- **Advanced Threat Detection**
  - Correlating multiple events  
  - Identifying attack chains  

- **Process Monitoring**
  - Tracking process creation and execution  
  - Detecting suspicious parent-child relationships  

- **Event Correlation**
  - Linking multiple Event IDs to identify attacks  

---

#### 🚨 Common Threat Indicators

- **Credential Abuse**
  - Multiple login attempts across accounts  
  - Lateral movement patterns  

- **Suspicious Process Activity**
  - Unknown processes running  
  - Unusual parent-child process relationships  

- **Persistence Mechanisms**
  - Scheduled tasks  
  - Registry modifications  

---

#### 🛡️ Detection Techniques

- Correlate logs across different sources  
- Monitor process creation events (e.g., Event ID 4688)  
- Analyze timelines of attacker activity  
- Use SIEM for alerting and correlation  

---

#### 🔍 SOC Analyst Notes

- Look for:
  - Process execution from unusual locations  
  - Repeated authentication across systems  
  - Suspicious scheduled tasks  

- Investigate:
  - Parent-child process chains  
  - Registry changes  
  - User behavior anomalies  

---

#### 🧪 Key Takeaway

Advanced threat detection requires correlating multiple events and understanding attacker behavior across the system.
