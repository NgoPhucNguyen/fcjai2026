---
title : "Thực thi truy xuất dữ liệu từ prisma"
date : 2026-04-02 
weight : 3
chapter : false
pre : " <b> 4.3.3 </b> "
---

### 4.3.3 Thực thi Truy vấn & Lưu trữ Dữ liệu

Ví dụ 1 phần mô tả cách thức hệ thống Backend tương tác với Database để xử lý các luồng nghiệp vụ chính.

#### 1. Luồng đăng ký và quản lý người dùng
Khi có người dùng mới, hệ thống sẽ thực hiện kiểm tra tính duy nhất của Email. Nếu hợp lệ, thông tin sẽ được ghi xuống bảng `Customer` trên RDS. Prisma đảm bảo rằng các ràng buộc về dữ liệu (như tính duy nhất của email) luôn được thực thi nghiêm ngặt.

![user-flow](/images/4-Workshop/4.3-DB-setup/user-management-ui.png)

#### 2. Truy xuất lịch sử phân tích
Người dùng có thể xem được mình đã thanh toán những cái nào. Hệ thống sẽ hiển thị đầy đủ thông tin.

![history-view](/images/4-Workshop/4.3-DB-setup/history-ui.png)

---