#### 📌 Overview
This room focuses on identifying and analyzing web-based attacks using logs and monitoring techniques. It helps understand how attackers interact with web applications and how to detect malicious activity.

---

#### 🧠 Key Concepts

- **Web Logs Analysis**
  - Logs store client requests to the server
  - Includes IP address, request type, URL, status code

- **Status Codes**
  - 200 → OK  
  - 404 → Not Found  
  - 500 → Server Error  

- **User Behavior Monitoring**
  - Normal vs abnormal request patterns  

---

#### 🚨 Indicators of Web Attacks

- **SQL Injection Indicators**
  - `' OR 1=1 --`
  - `UNION SELECT`

- **XSS Indicators**
  - `<script>alert(1)</script>`

- **Brute Force Indicators**
  - Multiple login attempts  
  - Same IP, repeated failures  

- **Directory Traversal**
  - `../` in URLs  

---

#### 🛡️ Detection Techniques

- Log analysis (Apache/Nginx logs)  
- SIEM tools (e.g., Splunk)  
- Pattern recognition  
- Alerting on unusual activity  

---

#### 🔍 SOC Analyst Notes

- Monitor:
  - High request volume from single IP  
  - Suspicious query strings  
  - Access to restricted files  

- Investigate:
  - Repeated failed logins  
  - Unexpected HTTP methods  

---

#### 🧪 Key Takeaway

Effective web attack detection relies on log analysis, recognizing attack patterns, and identifying abnormal behavior in web traffic.
