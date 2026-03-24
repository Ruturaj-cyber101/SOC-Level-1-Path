### 🌐 Room 1: Web Security Essentials

#### 📌 Overview
This room introduces the fundamentals of web security, including how web applications function and common vulnerabilities attackers exploit.

---

#### 🧠 Key Concepts

- **Web Application Architecture**
  - Client (Browser) ↔ Server ↔ Database

- **HTTP vs HTTPS**
  - HTTP → Unencrypted
  - HTTPS → Encrypted (SSL/TLS)

- **HTTP Methods**
  - GET, POST, PUT, DELETE

---

#### 🚨 Common Web Attacks

- **SQL Injection (SQLi)** → Database exploitation  
- **Cross-Site Scripting (XSS)** → Injecting malicious scripts  
- **Cross-Site Request Forgery (CSRF)** → Unauthorized actions  
- **File Inclusion (LFI/RFI)** → Accessing sensitive files  

---

#### 🛡️ Defensive Measures

- Input validation & sanitization  
- HTTPS implementation  
- Authentication & authorization  
- Web Application Firewall (WAF)  

---

#### 🔍 SOC Analyst Notes

- Monitor web logs for:
  - Suspicious URLs  
  - Repeated failed requests  
  - Abnormal HTTP methods  

- Look for:
  - SQL keywords in traffic  
  - Script injection attempts  

---

#### 🧪 Key Takeaway

Understanding web fundamentals helps SOC analysts detect and investigate web-based attacks effectively.
