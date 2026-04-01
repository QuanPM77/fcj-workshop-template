---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---
### 🎯 Week 10: AUTO SCALING ARCHITECTURE

**Objective:** _Automatically adjust the number of servers based on actual user demand._

---

#### 📅 Detailed Schedule

| Day of Week | Time Info | Task Description | Status |
| :---: | :---: | :--- | :---: |
| **Monday** | `2h` | Tạo Launch Template để định nghĩa cấu hình máy chủ mẫu. | ✅ |
| **Tuesday** | `1.5h` | Khởi tạo Auto Scaling Group (ASG) tích hợp cùng Load Balancer đã tạo. | ✅ |
| **Wednesday** | `1.5h` | Thiết lập Scaling Policies dựa trên chỉ số sử dụng CPU hoặc số lượng Request. | ✅ |
| **Thursday** | `1.5h` | Thực hành kiểm tra tính năng "Self-healing": Tắt một máy chủ và quan sát ASG tự động khởi tạo máy mới. | ✅ |
| **Friday** | `1h` | Tối ưu hóa chi phí bằng cách cấu hình số lượng máy chủ tối thiểu và tối đa (Desired/Min/Max). | ✅ |

---

{{% notice success "Completion & Results" %}}
**Completion Date:** 13/03/2026

**Learning Outcomes:** Successfully built an architecture capable of elastic scaling, optimizing both performance and cost.
{{% /notice %}}
