---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11

* Xây dựng AWS foundation cho phần triển khai dự án.
* Cấu hình các thành phần networking như VPC, Internet Gateway, route table và NAT Gateway.
* Thiết lập các dịch vụ pipeline chính gồm SQS, S3, Secrets Manager, KMS và IAM policies.
* Dựng các thành phần compute và access như EC2, IAM Roles, Security Groups, ALB và CloudFront.
* Refactor phần tích hợp Local Lab và kiểm tra flow backend trên EC2.

### Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| Thứ 2 | - Tạo AWS Foundation cho dự án.<br>- Bắt đầu thiết kế Network Foundation gồm VPC, Internet Gateway, route table và NAT Gateway. | 29/06/2026 | 29/06/2026 | Ghi chú AWS networking |
| Thứ 3 | - Cấu hình SQS và S3 cho cloud pipeline.<br>- Tạo Secrets Manager, KMS và IAM Policy cần thiết cho backend và worker. | 30/06/2026 | 30/06/2026 | Ghi chú AWS SQS / S3 / IAM |
| Thứ 4 | - Dựng EC2, IAM Roles và Security Groups.<br>- Thiết lập ALB và CloudFront cho kiến trúc ứng dụng. | 01/07/2026 | 01/07/2026 | Ghi chú AWS compute và networking |
| Thứ 5 | - Refactor phần Local Lab và `soc_shipper.py`.<br>- Kiểm tra flow đăng nhập dashboard sau khi thay đổi tích hợp. | 02/07/2026 | 02/07/2026 | Ghi chú Local Lab / dashboard |
| Thứ 6 | - SSH vào Backend EC2 để kiểm tra flow pipeline.<br>- Đọc source `main` của backend, phát hiện các phần còn thiếu như S3 `putObject` và SQS `sendMessage`. | 03/07/2026 | 03/07/2026 | Ghi chú Backend EC2 / source review |

### Kết quả đạt được tuần 11

* Chuẩn bị được AWS foundation và network foundation ban đầu cho dự án.
* Cấu hình các dịch vụ pipeline quan trọng như SQS, S3, Secrets Manager, KMS và IAM policies.
* Dựng các thành phần hạ tầng ứng dụng gồm EC2, IAM Roles, Security Groups, ALB và CloudFront.
* Refactor phần tích hợp Local Lab và kiểm tra hoạt động đăng nhập dashboard.
* Kiểm tra flow backend trên EC2 và xác định các điểm còn thiếu trong phần upload S3 và publish message lên SQS.
