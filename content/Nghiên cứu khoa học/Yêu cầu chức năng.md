
1. **Đăng nhập/Đăng ký:**
	* **Phương thức Đăng nhập:**
		* Đăng nhập bằng tài khoản Google trường (OAuth  mail có đuôi @student.tdmu.edu.vn hoặc @tdmu.edu.vn)
		* Đăng nhập bằng Facebook (sau khi đã liên kết tài khoản Google)
	* **Quy trình Đăng ký:**
		* Đăng ký bằng Google trường:
		* Tự động lấy thông tin từ tài khoản Google
		* Bổ sung thông tin còn thiếu (lấy từ firebase )
	* **Tính năng bổ sung:**
		* 2FA (tùy chọn):
			* Xác thực qua ứng dụng Google Authenticator
			* Xác thực qua SMS
		* Quản lý phương thức đăng nhập:
			* Liên kết/hủy liên kết tài khoản Facebook
			* Thêm/xóa số điện thoại ( fetch từ firebase auth)
		* Xem lịch sử đăng nhập (bảo mật )
	* **Phân quyền người dùng:**
		* **Sinh viên** ( mail có đuôi @student.tdmu.edu.vn:
			* Truy cập các tính năng cơ bản
			* Tham gia lớp học
			* Có thể tạo lớp học public
		* **Giảng viên** (mail có đuôi @tdmu.edu.vn):
			* Tạo và quản lý lớp học private và public
			* Tạo bài tập và chấm điểm
		* **Quản trị viên(** mail phải được gán từ admin):
			* Quản lý tài khoản người dùng
			* Xem báo cáo hoạt động
			* Cấu hình hệ thống
	* **Giao diện:**
		* **Responsive** design cho các thiết bị (Android, **Web**, có thể phát triển **Windows** trong tương lai )
		* **Dark**/Light mode
		* Hỗ trợ đa ngôn ngữ (Việt/Anh)
		* Tùy chỉnh thông tin hiển thị
2. **Thống kê và Báo cáo**
	* **Dashboard** hiển thị:
		* Số lớp đang tham gia
		* Bài tập sắp đến hạn (tất cả deadline chưa xong đều là bài tập sắp đến hạn)
		* Thông báo mới (deadline dài thì còn 3 ngày đến hạn thì thông báo hoặc deadline ngắn hơn 3 ngày thì thông báo nếu còn 1/2 thời gian)
		* Lịch học/họp trong tuần (lời nhắc lịch học sắp diễn ra)
	* Xuất báo cáo (**report**):
		* Kết quả học tập **(theo tháng, học kỳ, năm, .**..)
		* **Lịch sử hoạt động** (nhật ký tương tác với hệ thống)
		* **Thống kê** tham gia ( tham gia những **tag** nào, thời gian tham gia phòng học,...)
3. **Tích hợp Trợ lý AI (có thể đề xuất sử dụng API free hoặc rẻ nhất có thể)**
	* Hỗ trợ học tập: Trợ lý ảo có thể trả lời câu hỏi, cung cấp thông tin và **đề xuất tài liệu** học tập.
	* Tương tác tự nhiên: Người dùng có thể giao tiếp với trợ lý AI thông qua giao diện chat.
	* Cá nhân hóa: Trợ lý AI có thể học từ hành vi người dùng để đưa ra gợi ý phù hợp hơn.
4. **Học Nhóm**
	* **Tạo nhóm học tập:** Cho phép người dùng tạo và quản lý các nhóm học tập.
	* **Chia sẻ tài liệu:** Thành viên nhóm có thể tải lên và chia sẻ tài liệu học tập.
	* **Thảo luận:** Tích hợp chat nhóm để thảo luận và làm bài tập chung.
5. **Thư viện Tài Liệu (đề xuất sử dụng thư viện online (API) hoặc upload sách thủ công hoặc fetch từ một source google drive)**
	* Tìm kiếm: Hỗ trợ tìm kiếm tài liệu **theo từ khóa, chủ đề, hoặc người đăng tải.**
	* **Tải lên** và chia sẻ: Người dùng có thể tải lên tài liệu và chia sẻ với cộng đồng.( limit dung lượng tránh quá tải)
	* Đánh giá và bình luận: Cho phép người dùng **đánh giá và bình luận về tài liệu.**
6. **Theo Dõi Tiến Độ Học Tập**
	* Lịch sử học tập: Hiển thị **lịch sử học tập và tiến độ** của người dùng.
	* Thông báo sự kiện: Nhắc nhở người dùng về các **sự kiện quan trọng** và **hạn nộp bài** tập.
	* **Báo cáo tiến độ:** Cung cấp báo cáo tiến độ học tập theo tuần, tháng, học kỳ.
7. **Gamification**
   **Yếu tố trò chơi hóa:**
	- Hệ thống điểm thưởng: Người dùng nhận điểm thưởng khi hoàn thành nhiệm vụ hoặc đạt thành tích (study streak) 
	- Bảng xếp hạng: Xếp hạng người dùng dựa trên điểm thưởng. 
	* Huy hiệu: Trao huy hiệu cho người dùng khi đạt được các mốc quan trọng **(thưởng kim cương để customize khung avatar, hiệu ứng, study streak...)**
8. **Cá Nhân Hóa Học Tập**
	* Đề xuất khóa học: Dựa trên dữ liệu học tập, **đề xuất các khóa học** phù hợp( dựa trên các tag thuộc các room mà user đã join)
	* Tài liệu và bài tập: Gợi ý tài liệu và bài tập **phù hợp với trình độ và sở thích cá nhân** (bài tập public như kiểu 300 cài code thiếu nhi, ...)
9. **Hỗ Trợ Học Tập Ngoại Tuyến**
	* Tải xuống tài liệu: Cho phép người dùng **tải xuống tài liệu** và bài giảng để học offline.
	* Đồng bộ hóa: Tự động đồng bộ hóa tiến độ học tập khi có kết nối internet.( có thể nộp bài khi không có internet và **tự động upload khi có internet)**
10. **Tích Hợp và Tương Tác**
	* **Webhook Notifications:** Cung cấp thông báo tức thời qua webhook để tích hợp với các ứng dụng khác.
	* **Single Sign-On:** Hỗ trợ đăng nhập một lần với hệ thống trường.
	* **Google Calendar Integration:** Tích hợp với Google Calendar để quản lý lịch học và sự kiện.