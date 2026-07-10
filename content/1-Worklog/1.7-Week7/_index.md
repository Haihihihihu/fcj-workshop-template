---
title: "Week 7 Worklog"
date: 2024-01-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Week 7 Objectives

* Design a direct data pipeline from Zeek logs to the Python backend.
* Finalize the RBAC model for project access control.
* Build the `soc_shipper.py` source structure for real-time log shipping.
* Implement parsers for Zeek `conn.log` and `http.log`.
* Normalize Zeek timestamps into ISO 8601 UTC format for downstream AI processing.

### Tasks to be carried out this week

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | --------------- | ------------------ |
| Monday | - Designed the direct data pipeline from Zeek to the Python backend.<br>- Finalized the RBAC model for permission control. | 01/06/2026 | 01/06/2026 | Data pipeline / RBAC design notes |
| Tuesday | - Initialized the source structure for `soc_shipper.py`.<br>- Researched and implemented a Python tail-file approach to track log file changes in real time. | 02/06/2026 | 02/06/2026 | Python file monitoring notes |
| Wednesday | - Developed a parser module for JSON data from Zeek `conn.log`.<br>- Extracted key fields for AI1 and AI2A, including connection duration, connection state, bytes sent, and bytes received. | 03/06/2026 | 03/06/2026 | Zeek conn.log parser notes |
| Thursday | - Extended the shipper to process application-layer `http.log` data in parallel.<br>- Extracted HTTP semantic fields for the AI2B web attack detection use case. | 04/06/2026 | 04/06/2026 | Zeek http.log parser notes |
| Friday | - Built an output timestamp formatting filter.<br>- Implemented automatic conversion from Zeek epoch timestamps to ISO 8601 UTC strings. | 05/06/2026 | 05/06/2026 | Timestamp normalization notes |

### Week 7 Achievements

* Designed the Zeek-to-Python-backend data pipeline and clarified the RBAC direction.
* Created the initial `soc_shipper.py` structure for real-time log collection.
* Implemented tail-file based monitoring to follow changes in Zeek log files.
* Built parsers for `conn.log` and `http.log` to extract features needed by AI modules.
* Standardized output timestamps into ISO 8601 UTC format for cleaner downstream processing.
