---
title: "Worklog Tuần 11"
date: 2026-03-23
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:
* Đánh giá và rà soát lại các thành phần Trí tuệ nhân tạo (AI Model, Chatbot).
* Tăng cường lớp bảo mật ứng dụng với tường lửa (WAF).
* Hoàn thiện tài liệu kiến trúc hệ thống và đánh giá giới hạn kỹ thuật của toàn bộ nền tảng.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | Rà soát lại luồng hoạt động của Chatbot và kiểm tra hiệu suất, độ chính xác của Mô hình AI. | 23/03/2026 | 23/03/2026 | Nội bộ nhóm |
| 3 | Tìm hiểu cơ chế của AWS WAF (Web Application Firewall) và tiến hành tích hợp WAF vào Amazon ECS để tăng cường bảo mật. | 24/03/2026 | 24/03/2026 | AWS Security |
| 4 | Cập nhật và vẽ lại sơ đồ kiến trúc hệ thống (Architecture Diagram) một cách chuyên nghiệp để chuẩn bị nộp báo cáo. | 25/03/2026 | 25/03/2026 | Draw.io / AWS Icons |
| 5 | Nghiên cứu các tiêu chuẩn thiết kế kiến trúc; phân tích và giải thích cặn kẽ lý do (logic) đằng sau mỗi quyết định kết nối các dịch vụ. | 26/03/2026 | 26/03/2026 | AWS Well-Architected |
| 6 | Kiểm thử tổng thể website; ghi nhận các tính năng còn thiếu, rà soát các điểm dễ phát sinh lỗi (edge cases) và xác định giới hạn chịu tải (limit) của hệ thống. | 27/03/2026 | 27/03/2026 | Thực hành cá nhân |

### Kết quả đạt được tuần 11:

* **Hoàn thiện tài liệu kỹ thuật:** Đã hệ thống hóa toàn bộ dự án thành bản vẽ kiến trúc rõ ràng, hiểu sâu sắc lý do tại sao các thành phần lại được thiết kế và liên kết với nhau theo cách hiện tại.
* **Đảm bảo an toàn hệ thống:** Nắm được cách bảo vệ ứng dụng thực tế khỏi các lỗ hổng web phổ biến thông qua việc triển khai WAF.
* **Bài học thực tiễn:** Nhìn nhận thực tế rằng quá trình triển khai dự án gặp khá nhiều thách thức, đặc biệt là trong việc quản lý, tối ưu chi tiêu đám mây và xử lý hiệu quả các luồng request trả về. Đây là những kinh nghiệm vô cùng quý giá cho các dự án sau này.