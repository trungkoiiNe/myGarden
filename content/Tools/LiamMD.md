# 5W1H về Công Cụ Liam ERD (https://liambx.com/)

Công cụ **Liam ERD** giúp tự động tạo sơ đồ thực thể (ER Diagram) từ cấu trúc cơ sở dữ liệu, mang lại sự tương tác cao và trực quan trong việc quản lý các dự án phần mềm. Dưới đây là phân tích 5W1H bằng tiếng Việt:

---

## 1. Ai? (Who?)
- **Nhà phát triển:** Được phát triển bởi đội ngũ tại **Liam HQ**.
- **Cộng đồng:** Là dự án mã nguồn mở với sự đóng góp của cộng đồng lập trình viên và các nhà phát triển trên GitHub.

---

## 2. Cái gì? (What?)
- **Định nghĩa:** Liam ERD là công cụ tự động tạo sơ đồ ER (Entity-Relationship Diagram) từ các file schema như SQL, `schema.rb`, `structure.sql`,…
- **Chức năng chính:**
  - Tạo sơ đồ trực quan và tương tác.
  - Hỗ trợ các tính năng như phóng to, thu nhỏ, lọc và đánh dấu mối liên hệ giữa các bảng.
  - Tích hợp cho các dự án công khai và riêng tư.

---

## 3. Khi nào? (When?)
- **Thời điểm sử dụng:** 
  - Trong quá trình phát triển cơ sở dữ liệu, khi cần làm rõ cấu trúc và mối quan hệ giữa các bảng.
  - Khi tích hợp vào quy trình CI/CD để đảm bảo tài liệu luôn cập nhật.
- **Lịch sử phát hành:** Được phát hành và liên tục cập nhật từ năm 2024 cho đến nay.

---

## 4. Ở đâu? (Where?)
- **Truy cập:** 
  - Trang web chính: [https://liambx.com/](https://liambx.com/)
- **Ứng dụng:**
  - Phiên bản web dành cho các kho lưu trữ công khai.
  - Thiết lập cục bộ hoặc tích hợp qua CI/CD pipeline cho các dự án riêng tư.

---

## 5. Tại sao? (Why?)
- **Tiết kiệm thời gian:** Tự động hóa quy trình tạo sơ đồ, giảm công việc thủ công và sai sót.
- **Tăng tính tương tác:** Giao diện trực quan với các tính năng tương tác (phóng to, thu nhỏ, lọc…) giúp dễ dàng khám phá và hiểu rõ cấu trúc dữ liệu.
- **Hỗ trợ hợp tác:** Tạo liên kết chia sẻ sơ đồ giúp các thành viên trong nhóm trao đổi và làm việc hiệu quả hơn.
- **Quản lý tài liệu:** Đảm bảo sơ đồ cơ sở dữ liệu luôn được cập nhật, hỗ trợ quản lý và phát triển dự án một cách chuyên nghiệp.

---

## 6. Như thế nào? (How?)
- **Phiên bản web:**
  - Chỉ cần thêm tiền tố `https://liambx.com/erd/p/` vào URL của file schema trên GitHub để xem sơ đồ.
- **CLI (Command Line Interface):**
  - Sử dụng lệnh: `npx @liam-hq/cli init` để thiết lập cho các dự án riêng tư.
- **Tính năng nổi bật:**
  - Cho phép phóng to, thu nhỏ, lọc dữ liệu, và đánh dấu mối liên hệ giữa các bảng.
  - Tích hợp liền mạch với các công nghệ như PostgreSQL, Prisma, Ruby on Rails, và nhiều nền tảng khác.
- **Triển khai:** 
  - Dễ dàng tích hợp vào quy trình CI/CD để tự động cập nhật sơ đồ khi có thay đổi trong cơ sở dữ liệu.

---

Với **Liam ERD**, việc quản lý và hiểu cấu trúc cơ sở dữ liệu trở nên dễ dàng, nhanh chóng và trực quan hơn bao giờ hết.
