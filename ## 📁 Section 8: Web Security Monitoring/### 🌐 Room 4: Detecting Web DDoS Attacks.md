#### 📌 Overview
This room focuses on detecting Distributed Denial of Service (DDoS) attacks targeting web applications. These attacks aim to overwhelm a server with excessive traffic, making services unavailable to legitimate users.

---

#### 🧠 Key Concepts

- **DDoS Attack**
  - Large volume of traffic from multiple sources
  - Exhausts server resources (CPU, bandwidth)

- **Types of Web DDoS**
  - HTTP Flood → Massive GET/POST requests  
  - Slowloris → Keeps connections open  
  - Botnet-based attacks  

---

#### 🚨 Indicators of DDoS Attacks

- Sudden spike in traffic  
- High number of requests from multiple IPs  
- Repeated requests to the same endpoint  

- Abnormal patterns:
  - High GET/POST request rate  
  - Incomplete or slow connections  

---

#### 🛡️ Detection Techniques

- Monitor traffic volume and request rate  
- Analyze server performance (CPU, memory usage)  
- Use SIEM tools for alerting  
- Rate-limiting and traffic filtering  

---

#### 🔍 SOC Analyst Notes

- Look for:
  - Traffic spikes in a short time  
  - Multiple IPs targeting one resource  
  - Repeated identical requests  

- Investigate:
  - Access logs for request patterns  
  - Unusual geographic distribution of traffic  

---

#### 🧪 Key Takeaway

DDoS attacks disrupt availability, and early detection through traffic monitoring and log analysis is essential to maintain service uptime.
