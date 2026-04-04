---
title: "Worklog Tuần 7"
date: 2026-02-23
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:
* Tối ưu hóa hiệu suất truyền tải dữ liệu và tài nguyên tĩnh bằng mạng phân phối nội dung (CDN).
* Phân tích, đánh giá bài toán chi phí và rủi ro bảo mật của cấu trúc hệ thống hiện tại.
* Nghiên cứu các giải pháp kiến trúc thay thế linh hoạt và tiết kiệm hơn cho tương lai.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | Thiết lập kết nối giữa Amazon RDS và Frontend triển khai trên Amplify, định tuyến thông qua Amazon CloudFront. | 22/09/2025 | 22/09/2025 | AWS Documentation |
| 3 | Tích hợp Amazon S3 với CloudFront để tăng tốc độ truy xuất hình ảnh sản phẩm (fetch), tạo nền tảng cho các tính năng mở rộng sau này. | 23/09/2025 | 23/09/2025 | Tối ưu hóa AWS |
| 4 | Tổng hợp và phân tích dự toán chi phí (Cost Estimation) cho cụm dịch vụ AWS đang vận hành trong dự án. | 24/09/2025 | 24/09/2025 | AWS Pricing Calculator |
| 5 | Đánh giá tổng thể kiến trúc dự án dưới hai góc độ: Bảo mật dữ liệu người dùng (Security) và Khả năng chịu tải (Scalability). | 25/09/2025 | 25/09/2025 | AWS Well-Architected |
| 6 | Bắt đầu nghiên cứu về Amazon ECS (Elastic Container Service) và khái niệm container hóa ứng dụng. | 26/09/2025 | 26/09/2025 | AWS Documentation |

### Kết quả đạt được tuần 7:

* **Tối ưu trải nghiệm:** Hệ thống phân phối nội dung tĩnh nhanh hơn hẳn nhờ sự kết hợp chặt chẽ giữa S3 và CloudFront.
* **Tư duy hệ thống chuyên sâu:** Biết cách nhìn nhận dự án ở quy mô lớn hơn, đặt câu hỏi về tính an toàn và khả năng mở rộng khi lượng người dùng tăng đột biến.
* **Nhận thức về chi phí:** Rút ra kết luận quan trọng rằng việc duy trì máy chủ Amazon EC2 liên tục theo cách truyền thống có thể gây lãng phí tài nguyên và tốn kém ngân sách. Điều này tạo tiền đề để nhóm chuyển hướng sang tìm hiểu các giải pháp tối ưu hơn như ECS (Container).