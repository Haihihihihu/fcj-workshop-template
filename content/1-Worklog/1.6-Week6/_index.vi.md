---
title: "Worklog Tuần 6"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6

* Ổn định môi trường giám sát Local Lab và xử lý sự cố Zeek quá tải/crash.
* Giả lập lưu lượng tấn công ở tầng mạng và tầng ứng dụng.
* Thu thập, phân tích log Zeek sinh ra từ nhiều kịch bản tấn công khác nhau.
* Chuẩn bị dữ liệu đã làm sạch và gắn nhãn cho các workflow phát hiện bằng AI.

### Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| Thứ 2 | - Xử lý sự cố Zeek quá tải/crash.<br>- Áp dụng chiến thuật copy trực tiếp từ thư mục spool để giữ lại dữ liệu log. | 25/05/2026 | 25/05/2026 | Ghi chú xử lý lỗi Zeek |
| Thứ 3 | - Giả lập lưu lượng tấn công SYN Flood phục vụ kiểm thử DoS/DDoS.<br>- Phân tích Zeek connection logs và trạng thái kết nối `S0`. | 26/05/2026 | 26/05/2026 | Zeek conn.log / ghi chú attack simulation |
| Thứ 4 | - Giả lập tấn công tầng ứng dụng bằng cách gửi payload SQL Injection qua HTTP.<br>- Thu thập và kiểm tra dữ liệu trong `http.log`. | 27/05/2026 | 27/05/2026 | Zeek http.log / ghi chú SQL Injection |
| Thứ 5 | - Giả lập thêm các luồng tấn công web như XSS và directory scanning.<br>- Sử dụng công cụ tự động để tạo lưu lượng tấn công có thể lặp lại. | 28/05/2026 | 28/05/2026 | Ghi chú web attack simulation |
| Thứ 6 | - Tiền xử lý dữ liệu cho workflow AI.<br>- Loại bỏ nhiễu và chuẩn hóa nhãn cho thuật toán Isolation Forest. | 29/05/2026 | 29/05/2026 | Ghi chú data engineering |

### Kết quả đạt được tuần 6

* Cải thiện độ ổn định của quy trình giám sát Zeek khi gặp lưu lượng lớn hoặc sự cố crash.
* Tạo được lưu lượng SYN Flood và nhận diện các mẫu kết nối `S0` liên quan trong Zeek logs.
* Thu thập được HTTP log từ kịch bản giả lập SQL Injection.
* Tạo thêm các mẫu tấn công web như XSS và directory scanning.
* Chuẩn bị dữ liệu sạch và nhãn nhất quán hơn để phục vụ huấn luyện mô hình AI và phát hiện bất thường.
