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

  
  


---

# 🏆 Status

✔ Completed SOC Level 1 Path  
✔ Hands-on lab experience  
✔ Practical blue team workflow understanding  

---

# 🚀 Career Goal

Aspiring SOC Analyst (Level 1) focused on defensive security, monitoring, and threat detection.
