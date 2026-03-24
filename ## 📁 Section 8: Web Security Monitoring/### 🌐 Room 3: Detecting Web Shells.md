#### 📌 Overview
This room focuses on identifying web shells, which are malicious scripts uploaded by attackers to gain remote access and control over a web server.

---

#### 🧠 Key Concepts

- **Web Shell**
  - A malicious file (e.g., .php, .jsp, .aspx)
  - Allows attackers to execute commands on the server

- **Common File Types**
  - PHP → `.php`
  - Java → `.jsp`
  - ASP → `.aspx`

- **Attack Goal**
  - Persistent access  
  - Command execution  
  - Data exfiltration  

---

#### 🚨 Indicators of Web Shell Activity

- Suspicious file uploads  
- Unusual file names (e.g., `shell.php`, `cmd.php`)  
- Unexpected files in web directories  

- Abnormal HTTP requests:
  - POST requests with commands  
  - Encoded or obfuscated parameters  

---

#### 🛡️ Detection Techniques

- Monitor file upload activity  
- Analyze web server logs  
- Check for unusual scripts in web directories  
- Use file integrity monitoring (FIM)  

---

#### 🔍 SOC Analyst Notes

- Look for:
  - Repeated POST requests to a single file  
  - Commands in URL parameters  
  - Sudden spike in server activity  

- Investigate:
  - Unknown files in `/var/www/html` or similar directories  
  - Suspicious user-agent strings  

---

#### 🧪 Key Takeaway

Web shells provide attackers with persistent access, making early detection through log analysis and file monitoring critical for SOC operations.
