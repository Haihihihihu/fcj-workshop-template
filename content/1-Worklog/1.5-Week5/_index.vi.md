---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5

* Chuyển hướng dự án sang môi trường Local Lab phục vụ giám sát an ninh mạng.
* Thiết lập kiến trúc mạng trên VMware để tạo và giám sát lưu lượng.
* Cấu hình pfSense làm firewall, gateway và thành phần định tuyến nội bộ.
* Cài đặt và cấu hình Zeek để giám sát lưu lượng mạng.
* Tạo lưu lượng sạch và lưu lượng tấn công, sau đó bóc tách dữ liệu hữu ích từ file log.

### Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| Thứ 2 | - Chuyển hướng dự án sang môi trường Local Lab.<br>- Bắt đầu thiết kế kiến trúc mạng trên VMware cho lab. | 18/05/2026 | 18/05/2026 | Ghi chú VMware / Local Lab |
| Thứ 3 | - Cấu hình pfSense làm firewall và gateway.<br>- Thiết lập WAN và định tuyến nội bộ cho hệ thống lab. | 19/05/2026 | 19/05/2026 | pfSense documentation |
| Thứ 4 | - Cài đặt và cấu hình trạm giám sát Zeek.<br>- Chuẩn bị Zeek để thu thập và phân tích log lưu lượng mạng. | 20/05/2026 | 20/05/2026 | Zeek documentation |
| Thứ 5 | - Xây dựng kịch bản giả lập lưu lượng mạng.<br>- Chạy lưu lượng HTTPS sạch để tạo baseline log. | 21/05/2026 | 21/05/2026 | Ghi chú traffic simulation |
| Thứ 6 | - Thực thi kịch bản tấn công brute-force đa luồng.<br>- Bóc tách và kiểm tra dữ liệu từ các file log được tạo ra. | 22/05/2026 | 22/05/2026 | Zeek logs / ghi chú attack simulation |

### Kết quả đạt được tuần 5

* Xác định hướng Local Lab và chuẩn bị kiến trúc mạng VMware ban đầu.
* Cấu hình pfSense để đảm nhiệm firewall, gateway, WAN và định tuyến nội bộ.
* Cài đặt và cấu hình Zeek làm thành phần giám sát lưu lượng mạng.
* Tạo lưu lượng HTTPS sạch làm dữ liệu baseline để so sánh về sau.
* Giả lập lưu lượng brute-force và bóc tách thông tin hữu ích từ log của Zeek.
