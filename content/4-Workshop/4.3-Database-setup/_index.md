---
title : "Sử dụng Prisma trong RDS"
date : 2026-04-02 
weight : 3
chapter : false
pre : " <b> 4.3. </b> "
---

#### Sử dụng Prisma trong RDS

Trong phần này, bạn sẽ thực hiện kết nối mã nguồn Node.js với **Amazon RDS** thông qua **Prisma ORM**. Việc sử dụng Prisma giúp tối ưu hóa thao tác truy vấn dữ liệu, đảm bảo an toàn kiểu dữ liệu (Type-safe) và quản lý cấu trúc bảng (Schema) một cách đồng bộ trên môi trường AWS Cloud.

#### Nội dung

- [Thiết lập Database trên RDS](4.3.1-setup-rds/)
- [Cấu hình Prisma Client](4.3.2-config-prisma/)
- [Thực thi Truy vấn & Lưu trữ](4.3.3-query-data/)

---
### Tại sao nội dung này quan trọng?
* **Khác biệt với DB local**: Khi dùng RDS, bạn phải quản lý chuỗi kết nối qua biến môi trường `.env` để bảo mật thông tin.
* **Đồng bộ hóa Schema**: Sử dụng lệnh `npx prisma db push` để đảm bảo bảng dữ liệu trên Cloud luôn khớp với định nghĩa trong mã nguồn của team.