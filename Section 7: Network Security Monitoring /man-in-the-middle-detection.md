# Man-in-the-Middle Detection

## Overview
This room focuses on detecting Man-in-the-Middle (MITM) attacks, where an attacker intercepts communication between two parties to steal or manipulate data.

## Key Concepts
- MITM attacks occur when an attacker positions themselves between a user and a system.
- Attackers can eavesdrop, modify, or inject malicious data into communication.
- These attacks often target insecure or unencrypted connections.

## Common Techniques
- ARP spoofing
- DNS spoofing
- Session hijacking
- SSL stripping

## Indicators of Suspicious Activity
- Unexpected changes in network traffic patterns
- Duplicate IP or MAC addresses
- Unusual ARP requests or responses
- Certificate warnings or HTTPS issues

## SOC Analyst Perspective
SOC analysts monitor network traffic and logs to detect signs of interception attacks. Identifying anomalies such as spoofing or abnormal communication patterns helps detect MITM attacks early.

## Key Takeaways
- MITM attacks can compromise sensitive data.
- Monitoring network anomalies is key to detection.
- Encryption (HTTPS) helps prevent such attacks.
