---
title: "Week 6 Worklog"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Week 6 Objectives

* Stabilize the Local Lab monitoring setup and handle Zeek overload issues.
* Simulate network-layer and application-layer attack traffic.
* Collect and analyze Zeek logs generated from different attack scenarios.
* Prepare cleaned and labeled data for AI-based detection workflows.

### Tasks to be carried out this week

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | --------------- | ------------------ |
| Monday | - Handled Zeek overload/crash issues.<br>- Applied a direct copy strategy from the spool directory to preserve log data. | 25/05/2026 | 25/05/2026 | Zeek troubleshooting notes |
| Tuesday | - Simulated SYN Flood attack traffic for DoS/DDoS testing.<br>- Analyzed Zeek connection logs and reviewed `S0` connection states. | 26/05/2026 | 26/05/2026 | Zeek conn.log / attack simulation notes |
| Wednesday | - Simulated an application-layer attack by sending SQL Injection payloads through HTTP.<br>- Collected and reviewed `http.log` output. | 27/05/2026 | 27/05/2026 | Zeek http.log / SQL Injection notes |
| Thursday | - Simulated additional web attack flows such as XSS and directory scanning.<br>- Used automated tools to generate repeatable web attack traffic. | 28/05/2026 | 28/05/2026 | Web attack simulation notes |
| Friday | - Preprocessed data for AI workflows.<br>- Removed noisy records and normalized labels for the Isolation Forest algorithm. | 29/05/2026 | 29/05/2026 | Data engineering notes |

### Week 6 Achievements

* Improved the stability of the Zeek monitoring workflow when handling heavy traffic or crash scenarios.
* Generated SYN Flood traffic and identified relevant `S0` connection patterns in Zeek logs.
* Captured HTTP logs from SQL Injection attack simulation.
* Created additional web attack samples such as XSS and directory scanning traffic.
* Prepared cleaner and more consistent labeled data for later AI model training and anomaly detection.
