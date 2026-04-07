# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Cơ sở dữ liệu điểm số: Đây là tài sản quan trọng nhất, chứa kết quả học tập của sinh viên.
- Thông tin xác thực (Username/Password): Tài khoản của giảng viên và quản trị viên có quyền nhập/sửa điểm.

**CIA mapping:**
- Sự cố A -> Confidentiality Ví dụ: Danh sách điểm bị rò rỉ ra ngoài trước khi công bố chính thức.
- Sự cố B -> Integrity Ví dụ: Điểm số bị thay đổi trái phép, từ 5 điểm sửa thành 10 điểm.
- Sự cố C -> Availability Ví dụ: Hệ thống bị sập đúng lúc giảng viên cần nhập điểm cuối kỳ.

**Phân tích sự cố B:**
- Threat: Học sinh cố tình dùng tài khoản của giảng viên hoặc dùng công cụ tấn công để tự nâng điểm cho mình.
- Vulnerability: Hệ thống quản lý phiên làm việc (Session) yếu hoặc không có cơ chế xác thực hai lớp (2FA) cho giảng viên.
- Mitigation: Triển khai cơ chế phân quyền chặt chẽ (RBAC) và lưu nhật ký (Log) chi tiết mọi hành động chỉnh sửa điểm số để truy vết.

### 4. Kết luận ngắn
Qua bài lab em đã học cách áp dụng mô hình CIA để đánh giá rủi ro cho hệ thống lưu điểm.
Phần khó nhất là phân biệt rõ threat và vulnerability khi phân tích các sự cố thực tế.
Em nhận ra tầm quan trọng của phân quyền và lưu nhật ký (logging) để đảm bảo tính toàn vẹn của dữ liệu.
Sao lưu định kỳ và cơ chế khôi phục giúp đảm bảo tính sẵn sàng và khả năng phục hồi khi có sự cố.
Bài lab giúp em phát triển tư duy phòng thủ khi xây dựng và bảo trì hệ thống thông tin.
