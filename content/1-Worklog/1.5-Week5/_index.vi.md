---
title: "Worklog Tuần 5"
date: 2026-02-02
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:
* Triển khai và quản trị cơ sở dữ liệu đám mây với Amazon RDS.
* Áp dụng các chiến lược tối ưu hóa chi phí lưu trữ cơ sở dữ liệu cho dự án.
* Tích hợp thành công công cụ ORM để đồng bộ dữ liệu giữa môi trường phát triển và máy chủ.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | Thiết lập và kiểm tra kết nối trực tiếp từ máy tính cục bộ (local machine) đến Amazon RDS. | 08/09/2025 | 08/09/2025 | Thực hành cá nhân |
| 3 | Nghiên cứu các chiến lược giảm thiểu chi phí cho RDS, quyết định không cấu hình Multi-AZ để phù hợp với ngân sách giai đoạn thử nghiệm. | 09/09/2025 | 09/09/2025 | AWS Cost Optimization |
| 4 | Cài đặt và cấu hình Prisma ORM trên môi trường local; thực hiện kiểm thử các luồng truy vấn dữ liệu người dùng. | 10/09/2025 | 10/09/2025 | Prisma Documentation |
| 5 | Đưa Prisma lên môi trường máy chủ EC2; thiết lập mạng và bảo mật để kết nối thành công giữa EC2 và RDS. | 11/09/2025 | 11/09/2025 | AWS Documentation |
| 6 | Bắt đầu tìm hiểu về dịch vụ lưu trữ đối tượng Amazon S3 để chuẩn bị cho việc lưu trữ tài nguyên tĩnh (hình ảnh sản phẩm mỹ phẩm, file hệ thống). | 12/09/2025 | 12/09/2025 | AWS Documentation |

### Kết quả đạt được tuần 5:

* **Quản trị Database hiệu quả:** Xây dựng được quy trình kết nối và tương tác với Amazon RDS một cách hợp lý, tối ưu hóa được hiệu suất làm việc.
* **Tối ưu chi phí:** Nắm rõ tác động tài chính của các tùy chọn cấu hình (như Multi-AZ) và biết cách loại bỏ các cấu hình không cần thiết để tiết kiệm ngân sách.
* **Chuẩn hóa luồng làm việc:** Việc cấu hình thành công Prisma ORM và thiết lập kết nối EC2 - RDS rõ ràng đã tạo ra một quy trình chuẩn, dễ hiểu, giúp bất kỳ thành viên nào trong nhóm cũng có thể tham gia thao tác và tiếp quản.