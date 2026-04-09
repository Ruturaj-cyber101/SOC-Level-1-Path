# SOC Level 1 Path – TryHackMe

This repository documents my hands-on progress through the TryHackMe **SOC Level 1** learning path.  
The focus of this path is defensive security, SIEM analysis, alert triage, incident response, and threat detection.

---

## 🎯 Objective

To build practical blue team skills required for a **SOC Analyst (Level 1)** role by working through structured labs and applying real-world security concepts.

---

# 📚 Section 1 – Blue Team Introduction

- Junior Security Analyst Intro
- SOC Role in Blue Team
- Humans as Attack Vectors
- Systems as Attack Vectors

**Skills Gained:**
- Understanding SOC structure
- Blue team responsibilities
- Attack surfaces (human & system)
- Security monitoring basics

---

# 🛡️ Section 2 – SOC Team Internals

- SOC L1 Alert Triage
- SOC L1 Alert Reporting
- SOC Workbooks & Lookups
- SOC Metrics & Objectives

**Skills Gained:**
- Alert investigation workflow
- Incident documentation
- Escalation process
- KPIs & SOC performance metrics

---

# 🧰 Section 3 – Core SOC Solutions

- Introduction to EDR
- Introduction to SIEM
- Splunk: The Basics
- Elastic Stack: The Basics
- Introduction to SOAR

**Skills Gained:**
- Log ingestion & correlation
- SIEM searching and analysis
- EDR monitoring concepts
- Security automation with SOAR

---

# 🔍 Section 4 – Cyber Defence Frameworks

- Pyramid of Pain
- Cyber Kill Chain
- Unified Kill Chain
- MITRE ATT&CK

**Skills Gained:**
- Threat modelling
- Mapping attacker behaviour
- Understanding adversary tactics & techniques
- Detection strategy improvement

---

# 🧠 Core Competencies Developed

- Alert triage & investigation
- Log analysis
- Threat detection
- Incident response fundamentals
- SIEM querying (Splunk & Elastic)
- Framework-based threat mapping (MITRE ATT&CK)
# 🎣 Section 5 – Phishing Analysis

- Phishing Analysis Fundamentals  
- Phishing Emails in Action  
- Phishing Analysis Tools  
- Phishing Prevention  
- The Greenholt Phish  

**Skills Gained:**
- Identifying phishing emails
- Email header analysis
- Using phishing investigation tools
- Understanding social engineering techniques
- Phishing detection and prevention

---

# 🌐 Section 6 – Network Traffic Analysis

- Network Traffic Basics  
- Wireshark: The Basics  
- Wireshark: Packet Operations  
- Wireshark: Traffic Analysis  
- NetworkMiner  

**Skills Gained:**
- Understanding network traffic behaviour
- Packet analysis using Wireshark
- Identifying suspicious network activity
- Investigating network communications
- Network forensic analysis

# 🛡 Section 7 – Network Security Monitoring

- Network Security Essentials  
- Network Discovery Detection  
- Data Exfiltration Detection  
- Man-in-the-Middle Detection  
- IDS Fundamentals  
- Snort  

**Skills Gained:**
- Network monitoring and threat detection
- Identifying scanning and reconnaissance activity
- Detecting data exfiltration techniques
- Understanding MITM attacks
- Working with IDS tools like Snort
- Analyzing network-based alerts

## 📁 Section 8: Web Security Monitoring

---

### 🌐 Room 1: Web Security Essentials

#### 📌 Overview
This room introduces the fundamentals of web security, including how web applications function and common vulnerabilities attackers exploit.

#### 🧠 Key Concepts
- Web Application Architecture (Client ↔ Server ↔ Database)  
- HTTP vs HTTPS (Encryption using SSL/TLS)  
- HTTP Methods (GET, POST, PUT, DELETE)  

#### 🚨 Common Web Attacks
- SQL Injection (SQLi)  
- Cross-Site Scripting (XSS)  
- Cross-Site Request Forgery (CSRF)  
- File Inclusion (LFI/RFI)  

#### 🛡️ Defensive Measures
- Input validation & sanitization  
- HTTPS implementation  
- Authentication & authorization  
- Web Application Firewall (WAF)  

#### 🔍 SOC Analyst Notes
- Monitor suspicious URLs and repeated requests  
- Detect SQL keywords and script injections  

#### 🧪 Key Takeaway
Understanding web fundamentals helps in detecting and analyzing web-based attacks.

---

### 🌐 Room 2: Detecting Web Attacks

#### 📌 Overview
Focuses on identifying web attacks through log analysis and monitoring techniques.

#### 🧠 Key Concepts
- Web logs (IP, request, status codes)  
- Status codes (200, 404, 500)  
- User behavior analysis  

#### 🚨 Indicators
- SQLi → `' OR 1=1 --`, `UNION SELECT`  
- XSS → `<script>`  
- Brute force → Multiple login attempts  
- Directory traversal → `../`  

#### 🛡️ Detection Techniques
- Log analysis (Apache/Nginx)  
- SIEM tools (Splunk)  
- Pattern recognition  

#### 🔍 SOC Analyst Notes
- High traffic from single IP  
- Suspicious query strings  
- Failed login attempts  

#### 🧪 Key Takeaway
Detection relies on recognizing patterns and abnormal behavior.

---

### 🌐 Room 3: Detecting Web Shells

#### 📌 Overview
Covers detection of malicious scripts (web shells) used for persistent server access.

#### 🧠 Key Concepts
- Web shells (.php, .jsp, .aspx)  
- Remote command execution  
- Persistence  

#### 🚨 Indicators
- Suspicious file uploads  
- Unknown files in web directories  
- Repeated POST requests  

#### 🛡️ Detection Techniques
- File monitoring  
- Log analysis  
- File Integrity Monitoring (FIM)  

#### 🔍 SOC Analyst Notes
- Commands in URL parameters  
- Unusual activity in `/var/www/html`  
- Suspicious user-agents  

#### 🧪 Key Takeaway
Early detection of web shells is critical to prevent long-term compromise.

---

### 🌐 Room 4: Detecting Web DDoS Attacks

#### 📌 Overview
Focuses on detecting DDoS attacks that overwhelm web servers with high traffic.

#### 🧠 Key Concepts
- DDoS (high traffic from multiple sources)  
- HTTP Flood, Slowloris, Botnets  

#### 🚨 Indicators
- Sudden traffic spikes  
- Multiple IPs targeting same endpoint  
- High request rate  

#### 🛡️ Detection Techniques
- Traffic monitoring  
- SIEM alerts  
- Rate limiting  

#### 🔍 SOC Analyst Notes
- Repeated identical requests  
- Unusual traffic patterns  
- Geographic anomalies  

#### 🧪 Key Takeaway
Monitoring traffic patterns is key to detecting and mitigating DDoS attacks.

---

 ## 📁 Section 9: Windows Security Monitoring

---

### 🪟 Room 1: Windows Logging for SOC

#### 📌 Overview
This room focuses on Windows logging and how logs are used in SOC environments to monitor and investigate security events.

#### 🧠 Key Concepts
- Windows Event Logs (Security, System, Application)  
- Event Viewer usage  
- Event IDs for tracking activity  

#### 🚨 Important Event IDs
- 4624 → Successful login  
- 4625 → Failed login  
- 4634 → Logoff  
- 4672 → Admin privileges assigned  

#### 🔍 SOC Analyst Notes
- Monitor failed login attempts  
- Detect unusual login times  
- Track admin privilege usage  

#### 🧪 Key Takeaway
Windows logs are essential for detecting unauthorized access and suspicious activity.

---

### 🪟 Room 2: Windows Threat Detection 1

#### 📌 Overview
Focuses on detecting basic threats using Windows logs and identifying suspicious behavior.

#### 🧠 Key Concepts
- Threat detection using logs  
- Monitoring login and process activity  

#### 🚨 Indicators
- Multiple failed logins (brute force)  
- Suspicious login patterns  
- Privilege escalation  

#### 🔍 SOC Analyst Notes
- Repeated failed logins followed by success  
- Sudden admin privilege assignment  
- Unusual processes  

#### 🧪 Key Takeaway
Detection is based on identifying abnormal behavior in logs.

---

### 🪟 Room 3: Windows Threat Detection 2

#### 📌 Overview
Introduces advanced detection techniques using event correlation and process monitoring.

#### 🧠 Key Concepts
- Event correlation  
- Process monitoring (Event ID 4688)  
- Attack pattern analysis  

#### 🚨 Indicators
- Credential abuse  
- Suspicious process execution  
- Persistence activity  

#### 🔍 SOC Analyst Notes
- Unusual parent-child processes  
- Repeated authentication attempts  
- Registry and scheduled task changes  

#### 🧪 Key Takeaway
Advanced detection requires correlating multiple events.

---

### 🪟 Room 4: Windows Threat Detection 3

#### 📌 Overview
Focuses on detecting advanced threats like persistence and lateral movement.

#### 🧠 Key Concepts
- Attack lifecycle  
- Persistence mechanisms  
- Lateral movement  

#### 🚨 Indicators
- Scheduled tasks and registry changes  
- Activity across multiple systems  
- Suspicious services  

#### 🔍 SOC Analyst Notes
- Multiple endpoint activity  
- Unusual service installations  
- Cross-system login patterns  

#### 🧪 Key Takeaway
Understanding attacker behavior is key to detecting advanced threats.

--- 
  
## 🔟 Linux Security Monitoring

🐧 Room 1: Linux Logging for SOC  
📌 Overview  
This room focuses on Linux logging and how logs are used in SOC environments to monitor and investigate system and security events.  

🧠 Key Concepts  
Linux log files (/var/log/)  
System logs and authentication logs  
Log analysis using command-line tools  

🚨 Important Logs  
/var/log/syslog → General system activity  
/var/log/auth.log → Authentication (SSH, sudo)  
/var/log/kern.log → Kernel logs  
/var/log/dpkg.log → Package activity  

🔍 SOC Analyst Notes  
Monitor failed SSH login attempts  
Track sudo (privilege escalation) usage  
Identify unusual login activity  
Use grep and tail for quick analysis  

🧪 Key Takeaway  
Linux logs are critical for detecting unauthorized access and system anomalies.  

---

🐧 Room 2: Linux Threat Detection 1  
📌 Overview  
Focuses on detecting basic threats in Linux systems using logs and system monitoring commands.  

🧠 Key Concepts  
Threat detection basics  
Monitoring processes and user activity  
Understanding normal vs abnormal behaviour  

🚨 Indicators  
Multiple failed login attempts  
Unusual user activity  
Unknown running processes  
Suspicious login locations  

🔍 SOC Analyst Notes  
Use `ps`, `top` to monitor processes  
Check login history using `last`  
Investigate failed logins in auth.log  
Watch for unauthorized access  

🧪 Key Takeaway  
Threat detection starts with identifying unusual system behaviour.  

---

🐧 Room 3: Linux Threat Detection 2  
📌 Overview  
Introduces advanced detection techniques including process, network, and file activity analysis.  

🧠 Key Concepts  
Process and network monitoring  
Event correlation  
Identifying persistence mechanisms  

🚨 Indicators  
Suspicious network connections  
Unknown open ports  
Hidden or background processes  
Unexpected file changes  

🔍 SOC Analyst Notes  
Use `lsof` and `ss` for network analysis  
Check cron jobs for persistence  
Monitor active processes carefully  
Look for unusual outbound connections  

🧪 Key Takeaway  
Advanced detection requires analysing multiple system components together.  

---

🐧 Room 4: Linux Threat Detection 3  
📌 Overview  
Focuses on detecting advanced threats such as persistence, privilege escalation, and compromised accounts.  

🧠 Key Concepts  
Persistence techniques  
Privilege escalation detection  
User and account monitoring  

🚨 Indicators  
New or suspicious user accounts  
Modified cron jobs or startup scripts  
Unauthorized SSH access  
Changes in system configurations  

🔍 SOC Analyst Notes  
Check `/etc/passwd` for new users  
Review command history  
Investigate privilege changes  
Monitor scheduled tasks  

🧪 Key Takeaway  
Understanding attacker techniques helps detect and respond to advanced threats.  

---

---

# 🏆 Status

✔ Completed SOC Level 1 Path  
✔ Hands-on lab experience  
✔ Practical blue team workflow understanding  

---

# 🚀 Career Goal

Aspiring SOC Analyst (Level 1) focused on defensive security, monitoring, and threat detection.
