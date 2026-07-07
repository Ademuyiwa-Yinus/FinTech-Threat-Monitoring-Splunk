FinTech Threat Monitoring & Suspicious Transaction Investigation

---
Project Overview


This project demonstrates the use of Splunk Enterprise as a Security Information and Event Management (SIEM) platform to investigate suspicious financial transactions and identify indicators of fraudulent activity within a simulated FinTech environment.

The investigation focuses on detecting suspicious IP addresses, phishing-related account compromise, transaction structuring, and coordinated attack behavior through SPL queries and interactive dashboards.

---

Objectives

Investigate suspicious transaction activities.
Detect indicators of financial fraud.
Identify suspicious IP addresses.
Monitor high-risk users.
Visualize security events using Splunk dashboards.
Perform threat hunting using SPL queries.

---

Tools Used

Splunk Enterprise
Kali Linux
Oracle VirtualBox
Search Processing Language (SPL)
CSV Transaction Dataset

---

Lab Environment

Component	                      Technology
Operating System	              Kali Linux
SIEM Platform	                  Splunk Enterprise
Virtualization	                Oracle VirtualBox
Dataset                        	CSV Transaction Logs

---

Dataset Overview

The dataset includes transaction records containing:

User ID
IP Address
Device ID
Transaction Type
Transaction Status
Timestamp
Threat Flags
Analyst Notes

---

Dashboard Features

The Splunk dashboard provides visualizations for:

Attack Category Distribution
Transaction Type Distribution
Top 10 Active Users
Suspicious IP Addresses
Threat Activity Timeline
Threat Type Analysis
Top High-Risk Users
Repeated Suspicious IP Activity
Transaction Status Overview

---

Key Findings

The investigation identified:

Possible transaction structuring below reporting thresholds.
Repeated suspicious IP addresses.
Indicators of phishing-related account compromise.
Coordinated Midnight Swap attack activity.
High-risk users requiring further investigation.

---

Skills Demonstrated

SIEM Monitoring
Threat Hunting
SPL Query Development
Fraud Detection
Log Analysis
Dashboard Visualization
Detection Engineering
Incident Investigation
Threat Correlation
SOC Reporting

---

Recommendations
Configure real-time alerts for suspicious activities.
Enable Multi-Factor Authentication (MFA).
Investigate repeated suspicious IP addresses.
Monitor high-risk users continuously.
Improve transaction monitoring rules.
Update SPL detections to identify emerging attack techniques.

---

Screenshots



Future Improvements
Integrate additional threat intelligence feeds.
Automate alerting for critical threats.
Expand detection rules to cover more attack scenarios.
Develop advanced risk scoring for users and transactions.
Author

Ademuyiwa

Aspiring SOC Analyst | SIEM | Splunk | Threat Hunting | Cybersecurity
