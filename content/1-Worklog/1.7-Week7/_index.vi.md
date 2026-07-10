---
title: "Worklog Tuần 7"
date: 2024-01-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7

* Thiết kế data pipeline trực tiếp từ log Zeek đến Python backend.
* Chốt mô hình phân quyền RBAC cho dự án.
* Xây dựng cấu trúc mã nguồn `soc_shipper.py` để ship log theo thời gian thực.
* Lập trình parser cho Zeek `conn.log` và `http.log`.
* Chuẩn hóa timestamp của Zeek sang định dạng ISO 8601 UTC để phục vụ xử lý AI phía sau.

### Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| Thứ 2 | - Thiết kế data pipeline trực tiếp từ Zeek qua Python Backend.<br>- Chốt mô hình phân quyền RBAC cho hệ thống. | 01/06/2026 | 01/06/2026 | Ghi chú Data Pipeline / RBAC |
| Thứ 3 | - Khởi tạo cấu trúc mã nguồn cho `soc_shipper.py`.<br>- Nghiên cứu và triển khai giải pháp đọc đuôi file theo thời gian thực bằng Python để theo dõi biến động log. | 02/06/2026 | 02/06/2026 | Ghi chú Python file monitoring |
| Thứ 4 | - Lập trình module parser dữ liệu JSON từ Zeek `conn.log`.<br>- Trích xuất các trường đặc trưng cho AI1 và AI2A như thời lượng kết nối, trạng thái kết nối, byte gửi và byte nhận. | 03/06/2026 | 03/06/2026 | Ghi chú Zeek conn.log parser |
| Thứ 5 | - Mở rộng shipper để xử lý đồng thời luồng log ứng dụng `http.log`.<br>- Bóc tách dữ liệu ngữ nghĩa HTTP phục vụ bài toán phát hiện tấn công Web của AI2B. | 04/06/2026 | 04/06/2026 | Ghi chú Zeek http.log parser |
| Thứ 6 | - Xây dựng bộ lọc định dạng thời gian cho dữ liệu đầu ra.<br>- Lập trình hàm tự động quy đổi timestamp epoch của Zeek sang chuỗi ISO 8601 UTC. | 05/06/2026 | 05/06/2026 | Ghi chú chuẩn hóa timestamp |

### Kết quả đạt được tuần 7

* Thiết kế được data pipeline từ Zeek đến Python backend và làm rõ hướng phân quyền RBAC.
* Tạo cấu trúc ban đầu cho `soc_shipper.py` phục vụ thu thập log theo thời gian thực.
* Triển khai cơ chế tail-file để theo dõi thay đổi của các file log Zeek.
* Xây dựng parser cho `conn.log` và `http.log` để trích xuất feature cần thiết cho các module AI.
* Chuẩn hóa timestamp đầu ra sang ISO 8601 UTC, giúp dữ liệu sạch và nhất quán hơn cho các bước xử lý tiếp theo.
