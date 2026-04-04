---
title: "Worklog Tuần 6"
date: 2026-02-09
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:
* Lưu trữ và phân phối tài nguyên tĩnh (hình ảnh mỹ phẩm) hiệu quả thông qua Amazon S3.
* Tìm kiếm và thử nghiệm giải pháp hosting tối ưu cho phần Frontend của nền tảng.
* Giải quyết các sự cố triển khai trên môi trường thực tế (Production) bằng các dịch vụ bổ trợ.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | Upload hình ảnh sản phẩm lên Amazon S3, cấu hình quyền truy cập và tích hợp liên kết hiển thị ảnh lên hệ thống EC2. | 15/09/2025 | 15/09/2025 | AWS Documentation |
| 3 | Nghiên cứu tổng quan về các dịch vụ AWS sinh thái web/mobile như AWS Amplify, Amazon CloudFront và AWS AppSync. | 16/09/2025 | 16/09/2025 | AWS Training |
| 4 | Thử nghiệm AWS Amplify để triển khai (host) mã nguồn Frontend của trang web. | 17/09/2025 | 17/09/2025 | Amplify Docs |
| 5 | Xử lý các lỗi phát sinh trên môi trường Production của Amplify; nhận định vấn đề và chuyển hướng sang sử dụng CloudFront để giải quyết. | 18/09/2025 | 18/09/2025 | Cộng đồng AWS |
| 6 | Nghiên cứu chuyên sâu về Amazon CloudFront (CDN), thực hành thiết kế cấu hình Origins và thiết lập Cache Behaviors. | 19/09/2025 | 19/09/2025 | AWS Documentation |

### Kết quả đạt được tuần 6:

* **Tư duy kiến trúc hệ thống:** Hiểu được nguyên lý hoạt động cơ bản của nhiều dịch vụ AWS khác nhau (S3, EC2, Amplify, CloudFront) và cách chúng kết nối, giao tiếp với nhau để tạo thành một hệ thống hoàn chỉnh.
* **Quản lý tài nguyên tĩnh:** Tích hợp thành công S3 để lưu trữ hình ảnh, giúp giảm tải cho máy chủ EC2.
* **Kỹ năng giải quyết vấn đề:** Nhạy bén trong việc phát hiện giới hạn hoặc lỗi trên môi trường Production của một dịch vụ (Amplify), từ đó chủ động tìm hiểu và áp dụng dịch vụ khác phù hợp hơn (CloudFront) để đảm bảo tiến độ.