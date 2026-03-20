# Data Exfiltration Detection

## Overview
This room focuses on detecting data exfiltration, where attackers attempt to steal sensitive information from a network. Identifying such activity is critical for preventing data breaches.

## Key Concepts
- Data exfiltration is the unauthorized transfer of data outside an organization.
- Attackers may use normal protocols to hide malicious activity.
- Monitoring outbound traffic is essential to detect exfiltration.

## Common Techniques
- Large data transfers to external IP addresses
- Use of encrypted channels (HTTPS, DNS tunneling)
- Unusual file transfers
- Data uploads to cloud services or unknown servers

## Indicators of Suspicious Activity
- High volume of outbound traffic
- Communication with unknown or suspicious external hosts
- Data transfers at unusual times
- Repeated connections to the same external destination

## SOC Analyst Perspective
SOC analysts monitor network traffic and logs to identify unusual outbound activity. Detecting exfiltration early helps minimize data loss and respond quickly to incidents.

## Key Takeaways
- Data exfiltration is a critical security threat.
- Monitoring outbound traffic is
