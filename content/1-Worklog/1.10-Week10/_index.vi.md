---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---

### TUẦN 10: TỰ ĐỘNG MỞ RỘNG KIẾN TRÚC (AUTO SCALING)

**Mục tiêu:** Tự động điều chỉnh số lượng máy chủ dựa trên nhu cầu thực tế của người dùng.

**Chi tiết nội dung & Thời gian:**
- **Thứ 2 (2h):** Tạo Launch Template để định nghĩa cấu hình máy chủ mẫu.
- **Thứ 3 (1.5h):** Khởi tạo Auto Scaling Group (ASG) tích hợp cùng Load Balancer đã tạo.
- **Thứ 4 (1.5h):** Thiết lập Scaling Policies dựa trên chỉ số sử dụng CPU hoặc số lượng Request.
- **Thứ 5 (1.5h):** Thực hành kiểm tra tính năng "Self-healing": Tắt một máy chủ và quan sát ASG tự động khởi tạo máy mới.
- **Thứ 6 (1h):** Tối ưu hóa chi phí bằng cách cấu hình số lượng máy chủ tối thiểu và tối đa (Desired/Min/Max).

**Ngày hoàn thành:** 13/03/2026.

**Kết quả học tập:** Xây dựng thành công kiến trúc có khả năng co giãn linh hoạt, tối ưu cả về hiệu năng và chi phí.
