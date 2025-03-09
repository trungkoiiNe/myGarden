- Đăng nhập: đăng nhập bằng email trường, google trường ( bắt buộc)
- Quản lý các lớp học : 
	- Tạo lớp
		- Lớp riêng tư( cần set email hoặc tên đích danh để người đó có thể thấy được lớp này)
		- Lớp công khai ( ai cũng có thể thấy lớp này và join)
		- Mỗi lớp sẽ cần gắn nhãn để tăng độ nhận diện
	- Tham gia lớp:
		- TÌm kiếm lớp bằng tên
		- Tìm kiếm lớp bằng Mã tham gia
		- Đề xuất lớp phù hợp( dựa trên nhãn của lớp)
- Thông báo người dùng:
	- thông báo quan trọng từ các lớp
	- nhận các đề xuất lớp 
	- có thể tắt thông báo từ lớp chỉ định
- Nhắn tin:
	- Có thể nhắn tin với người trong lớp chung
	- Hạn chế tính năng tìm người lạ( tránh spam, làm phiền)
	- Chia sẻ file phương tiện
	- gọi điện thoại, xem lớp chung
	- Báo cáo spam ( báo cáo cho quản trị)
- Xem bài tập 
- Lịch trình 
- Cuộc họp: 
	- tạo cuộc họp
	- chia sẻ cuộc họp
	- chặn người dùng khỏi cuộc họp
	- tham gia cuộc họp( bằng mã )
	- Set quyền bật mic, bật cam của người tham gia
	- Chia sẻ màn hình
	- Nhắn tin
	- sẽ có các cuộc họp public( hiển thị trong các lớp của bản thân) bởi vì là lớp public nên ai cũng có thể tham gia và nằm ở trong danh sách lớp của mình 

|                                     |                                                                                                                    |           |                                     |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------ | --------- | ----------------------------------- |
| Giai đoạn                           | Công việc chính                                                                                                    | Thời gian | Người phụ trách                     |
| Giai đoạn 1: Khởi tạo               |                                                                                                                    | 1-2 tuần  |                                     |
| - Phân tích yêu cầu                 | Họp với các bên liên quan, xác định mục tiêu và yêu cầu chi tiết.                                                  | 1 tuần    | PM + UI/UX Designer                 |
| - Thiết kế mockup                   | Tạo bản thiết kế wireframe và giao diện cơ bản dựa trên Material Design.                                           | 1 tuần    | UI/UX Designer                      |
| Giai đoạn 2: Backend Setup          |                                                                                                                    | 3 tuần    |                                     |
| - Xây dựng hệ thống cơ sở dữ liệu   | Thiết kế và triển khai cơ sở dữ liệu (Firebase hoặc MongoDB) để lưu trữ thông tin người dùng, lớp học, và bài tập. | 1 tuần    | Backend Developer                   |
| - Authentication                    | Tích hợp đăng nhập với email trường và Google OAuth.                                                               | 1 tuần    | Backend Developer                   |
| - Notification Service              | Tích hợp hệ thống thông báo đẩy Firebase Cloud Messaging.                                                          | 1 tuần    | Backend Developer                   |
| Giai đoạn 3: Frontend Setup         |                                                                                                                    | 4 tuần    |                                     |
| - Đăng nhập                         | Tạo màn hình và logic đăng nhập.                                                                                   | 1 tuần    | React Native Developers             |
| - Quản lý lớp học                   | Xây dựng giao diện và chức năng tạo lớp, tham gia lớp (tìm kiếm lớp, nhập mã lớp).                                 | 2 tuần    | React Native Developers             |
| - Gắn nhãn lớp học                  | Tích hợp tính năng gắn nhãn và đề xuất lớp phù hợp.                                                                | 1 tuần    | React Native Developers             |
| Giai đoạn 4: Tính năng WebRTC       |                                                                                                                    | 6 tuần    |                                     |
| - Tích hợp WebRTC cơ bản            | Tạo chức năng cuộc họp, video call, chia sẻ màn hình.                                                              | 3 tuần    | WebRTC Developer                    |
| - Quản lý cuộc họp                  | Thêm quyền quản trị viên cho các cuộc họp: bật/tắt mic, camera, chặn người dùng.                                   | 2 tuần    | WebRTC Developer                    |
| - Phòng học cộng đồng               | Hiển thị danh sách các cuộc họp public trong lớp học chung.                                                        | 1 tuần    | WebRTC Developer + React Native Dev |
| Giai đoạn 5: Messaging              |                                                                                                                    | 3 tuần    |                                     |
| - Hệ thống nhắn tin cơ bản          | Tạo giao diện chat và tích hợp backend nhắn tin.                                                                   | 1 tuần    | React Native Developers             |
| - Chia sẻ file và media             | Tích hợp tính năng gửi file, ảnh, và media trong chat.                                                             | 1 tuần    | React Native Developers             |
| - Báo cáo spam                      | Thêm nút báo cáo tin nhắn hoặc người dùng gây rối.                                                                 | 1 tuần    | React Native Developers             |
| Giai đoạn 6: Bài tập và lịch trình  |                                                                                                                    | 3 tuần    |                                     |
| - Xem bài tập                       | Hiển thị danh sách bài tập từ lớp học (kết nối với backend).                                                       | 1 tuần    | React Native Developers             |
| - Quản lý lịch trình                | Tạo giao diện lịch trình học tập và sự kiện lớp.                                                                   | 2 tuần    | React Native Developers             |
| Giai đoạn 7: Kiểm thử và tối ưu hóa |                                                                                                                    | 4 tuần    |                                     |
| - Kiểm thử tính năng                | Test toàn bộ tính năng: đăng nhập, lớp học, WebRTC, nhắn tin, bài tập, thông báo.                                  | 2 tuần    | QA Tester                           |
| - Tối ưu hiệu năng                  | Tối ưu hóa tốc độ tải, dung lượng app, và xử lý sự cố.                                                             | 2 tuần    | Toàn bộ team                        |
| Giai đoạn 8: Triển khai             |                                                                                                                    | 2 tuần    |                                     |
| - Triển khai thử nghiệm             | Đưa ứng dụng lên TestFlight (iOS) và Google Play Console (Android).                                                | 1 tuần    | PM + QA Tester                      |
| - Triển khai chính thức             | Đưa ứng dụng lên các cửa hàng app chính thức.                                                                      | 1 tuần    | PM                                  |