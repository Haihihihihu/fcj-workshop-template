---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9

* Chạy lại các kịch bản lưu lượng mạng sạch để làm lại dataset cho máy học.
* Cải thiện chất lượng và độ nhất quán của log lưu lượng sạch.
* Chạy lại các kịch bản tấn công tầng mạng để phục vụ training dataset.
* Kiểm tra log sinh ra và chuẩn bị dữ liệu cho các bước tiền xử lý, gắn nhãn sau đó.

### Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| Thứ 2 | - Chạy lại các kịch bản lưu lượng mạng sạch.<br>- Thu thập log clean traffic để xây dựng lại dataset cho máy học. | 15/06/2026 | 15/06/2026 | Ghi chú sinh lưu lượng sạch |
| Thứ 3 | - Tiếp tục chạy các luồng lưu lượng mạng sạch.<br>- Kiểm tra log sinh ra có ổn định và phù hợp để dùng cho dataset hay không. | 16/06/2026 | 16/06/2026 | Zeek logs / ghi chú dataset |
| Thứ 4 | - Hoàn thành thêm các lượt chạy benign traffic.<br>- Sắp xếp output của lưu lượng sạch để chuẩn bị cho bước tiền xử lý. | 17/06/2026 | 17/06/2026 | Ghi chú chuẩn bị dataset |
| Thứ 5 | - Chạy lại các kịch bản tấn công tầng mạng cho dataset máy học.<br>- Thu thập log attack traffic để so sánh với dữ liệu benign. | 18/06/2026 | 18/06/2026 | Ghi chú sinh attack traffic |
| Thứ 6 | - Tiếp tục chạy các kịch bản tấn công tầng mạng.<br>- Rà soát log tấn công và chuẩn bị dữ liệu cho bước gắn nhãn, tiền xử lý. | 19/06/2026 | 19/06/2026 | Zeek attack logs / ghi chú labeling |

### Kết quả đạt được tuần 9

* Xây dựng lại được các mẫu lưu lượng sạch cho dataset máy học.
* Cải thiện độ nhất quán của benign network logs thông qua nhiều lượt chạy traffic.
* Tạo được các mẫu tấn công tầng mạng mới phục vụ training và evaluation.
* Chuẩn bị dữ liệu benign và attack cho các bước tiền xử lý, gắn nhãn và trích xuất feature tiếp theo.
