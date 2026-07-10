---
title: "Week 11 Worklog"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives

* Build the AWS foundation for the project deployment.
* Configure networking components such as VPC, Internet Gateway, route tables, and NAT Gateway.
* Set up core pipeline services including SQS, S3, Secrets Manager, KMS, and IAM policies.
* Deploy compute and access components such as EC2, IAM Roles, Security Groups, ALB, and CloudFront.
* Refactor local lab integration and verify backend pipeline flow on EC2.

### Tasks to be carried out this week

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | --------------- | ------------------ |
| Monday | - Created the AWS foundation for the project.<br>- Started the network foundation design, including VPC, Internet Gateway, route tables, and NAT Gateway. | 29/06/2026 | 29/06/2026 | AWS networking notes |
| Tuesday | - Configured SQS and S3 for the cloud pipeline.<br>- Created Secrets Manager, KMS, and IAM policies required by the backend and worker components. | 30/06/2026 | 30/06/2026 | AWS SQS / S3 / IAM notes |
| Wednesday | - Deployed EC2 resources, IAM Roles, and Security Groups.<br>- Set up ALB and CloudFront components for the application architecture. | 01/07/2026 | 01/07/2026 | AWS compute and networking notes |
| Thursday | - Refactored the Local Lab integration and `soc_shipper.py`.<br>- Checked the dashboard login flow after integration changes. | 02/07/2026 | 02/07/2026 | Local Lab / dashboard notes |
| Friday | - Connected to the backend EC2 instance through SSH to verify the pipeline flow.<br>- Reviewed the backend `main` source code and identified missing S3 `putObject` and SQS `sendMessage` logic. | 03/07/2026 | 03/07/2026 | Backend EC2 / source review notes |

### Week 11 Achievements

* Prepared the initial AWS foundation and network foundation for the project.
* Configured key pipeline services such as SQS, S3, Secrets Manager, KMS, and IAM policies.
* Deployed core application infrastructure including EC2, IAM Roles, Security Groups, ALB, and CloudFront.
* Refactored Local Lab integration and verified the dashboard login behavior.
* Checked backend EC2 flow and identified missing implementation points for S3 upload and SQS message publishing.
