# Phishing Email in Action

## Overview
This room provided hands-on experience in analyzing real-world phishing email scenarios. The focus was on applying investigative techniques to identify malicious intent, extract evidence, and determine whether an email represents a genuine threat.

The lab simulated practical SOC workflows used when handling phishing alerts.

---

## Key Learning Objectives

- Analyze real phishing email samples
- Identify social engineering tactics
- Extract and validate Indicators of Compromise (IOCs)
- Differentiate between legitimate and malicious emails
- Apply structured analysis methodology

---

## Core Investigation Areas

### 1. Email Content Analysis
- Reviewing subject lines for urgency or manipulation
- Identifying impersonation attempts
- Detecting grammatical inconsistencies
- Recognizing financial or credential harvesting attempts

### 2. Sender & Domain Verification
- Checking sender email structure
- Identifying spoofed or lookalike domains
- Comparing display name vs actual email address

### 3. URL Analysis
- Hovering over links to reveal real destinations
- Detecting URL obfuscation
- Identifying suspicious domains

### 4. Attachment Analysis
- Identifying risky file types
- Recognizing macro-enabled documents
- Understanding how attachments are used for malware delivery

---

## Indicators of Compromise (IOCs)

Common IOCs identified during analysis:
- Malicious URLs
- Suspicious domains
- Spoofed email addresses
- Potential payload delivery methods

---

## SOC Investigation Workflow Applied

1. Review alert and email details  
2. Inspect sender information  
3. Analyze email headers (if available)  
4. Extract links and attachments  
5. Validate artifacts using threat intelligence tools  
6. Determine malicious or false positive  
7. Document findings  

---

## Practical Skills Developed

- Real-world phishing email investigation
- Identifying social engineering techniques
- Evidence-based analysis approach
- Improved decision-making in alert triage

---

## Why This Matters for SOC Roles

Phishing investigations are one of the most frequent tasks in a SOC environment. The ability to quickly analyze emails, extract IOCs, and determine malicious intent is critical for reducing organizational risk and preventing credential compromise or malware infections.
