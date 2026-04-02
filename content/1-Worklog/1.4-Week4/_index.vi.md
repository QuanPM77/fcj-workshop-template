---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---
###  TUẦN 4: NỀN TẢNG MẠNG VÀ VPC (PHẦN 2: CÁCH LY VÀ BẢO MẬT)

**Mục tiêu:** _Thiết lập vùng mạng riêng tư và cơ chế kiểm soát lưu lượng chuyên sâu._

---

####  Lịch trình chi tiết

| Ngày trong tuần | Đầu tư | Nội dung công việc | Trạng thái |
| :---: | :---: | :--- | :---: |
| **Thứ 2** | `1.5h` | Triển khai các Private Subnets để chứa các tài nguyên nhạy cảm (Database, Backend). | ✅ |
| **Thứ 3** | `2h` | Cấu hình NAT Gateway để cho phép Private Subnet truy cập Internet một chiều (chỉ để tải bản cập nhật). | ✅ |
| **Thứ 4** | `1.5h` | Phân biệt và thực hành cấu hình Security Groups (tầng instance) và Network ACLs (tầng subnet). | ✅ |
| **Thứ 5** | `1.5h` | Thiết lập Bastion Host (Jump Box) để truy cập an toàn vào các máy chủ trong Private Subnet. | ✅ |
| **Thứ 6** | `1h` | Tổng kết sơ đồ kiến trúc mạng mạng đa tầng (Multi-tier Architecture). | ✅ |

---

{{% notice success "Hoàn thành & Kết quả" %}}
**Ngày hoàn thành dự kiến:** 30/01/2026.

**Kết quả học tập:** Xây dựng hoàn chỉnh môi trường mạng an toàn, đảm bảo tính riêng tư cho dữ liệu nội bộ.
{{% /notice %}}
