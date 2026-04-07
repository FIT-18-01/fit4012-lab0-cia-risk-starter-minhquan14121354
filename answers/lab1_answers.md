# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Trần Minh Quân

**MSSV:** 1871020469

**Lớp/Nhóm:** CNTT 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Database
- Asset 2: Application Source Code
- Asset 3 (nếu có): Web Server

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Rò rỉ dữ liệu: Hacker đánh cắp mật khẩu, xem trộm hồ sơ khách hàng, công bố thông tin nội bộ. -> Confidentiality
- Sự cố B -> Sai lệch dữ liệu: Hacker thay đổi số dư tài khoản, sửa nội dung bài viết, thay đổi mã nguồn phần mềm. -> Integrity
- Sự cố C -> Tấn công hệ thống: Tấn công DDoS làm sập web, máy chủ bị rút điện, mạng bị nghẽn không thể truy cập. -> Availability

---

## 3. Phân tích sự cố B
- Threat: Hành động "Hacker thay đổi số dư" hay "sửa mã nguồn" chính là các mối đe dọa từ con người.
- Vulnerability: Việc hacker có thể "sửa nội dung bài viết" thường là do hệ thống bị lỗi phân quyền hoặc lỗi Broken Access Control.
- Mitigation: Giải pháp dùng Digital Signature (Chữ ký số) hoặc Hash (Mã băm) là cách tốt nhất để bảo vệ "mã nguồn phần mềm" không bị thay đổi trái phép.

---

## 4. Reflection
Viết 5-7 dòng.
- Hiểu rõ bộ ba nguyên tắc CIA: Bảo mật, Toàn vẹn và Sẵn sàng.
- Nhận thức được tầm quan trọng của việc xác định đúng tài sản (Assets).
- Biết cách phân loại các mối đe dọa (Threats) phổ biến hiện nay.
- Tự xác định được các lỗ hổng (Vulnerabilities) thường gặp trong hệ thống.
- Học được các biện pháp giảm nhẹ (Mitigation) như phân quyền và mã hóa.
- Nâng cao ý thức bảo mật khi thiết kế và vận hành các ứng dụng phần mềm.
- Đây là nền tảng quan trọng giúp em xây dựng các hệ thống an toàn hơn.


---

## 5. Bonus Flag
`FIT4012{A-C-B-I-C-A}`

