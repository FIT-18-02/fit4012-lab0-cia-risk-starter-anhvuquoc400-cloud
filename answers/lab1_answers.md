# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** .....Vũ Quốc Anh..............................

**MSSV:** ...........1871020066..................................

**Lớp/Nhóm:** ..........18-02...............................

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Dữ liệu sinh viên (điểm số, thông tin cá nhân)
- Asset 2:Tài khoản đăng nhập hệ thống (username, password)
- Asset 3 (nếu có):

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->Confidentiality (Bảo mật)
- Sự cố B ->Integrity (Toàn vẹn)
- Sự cố C ->Availability (Sẵn sàng)

---

## 3. Phân tích sự cố B
- Threat:Hacker hoặc người dùng nội bộ sửa dữ liệu trái phép
- Vulnerability:Hệ thống không kiểm soát quyền truy cập chặt chẽ, thiếu xác thực
- Mitigation:Áp dụng phân quyền (role-based access)
Ghi log thay đổi dữ liệu
Sử dụng xác thực mạnh (2FA)

---

## 4. Reflection
Qua bài này, em hiểu rõ hơn về vai trò của mô hình CIA trong an toàn thông tin.
Mỗi yếu tố (Confidentiality, Integrity, Availability) đều rất quan trọng và liên kết chặt chẽ với nhau.
Chỉ cần một yếu tố bị vi phạm cũng có thể gây ảnh hưởng lớn đến toàn bộ hệ thống.
Việc xác định tài sản và phân tích mối đe dọa giúp em hiểu cách bảo vệ hệ thống tốt hơn.
Ngoài ra, em nhận ra rằng không chỉ hacker mà cả người dùng nội bộ cũng có thể là rủi ro.
Do đó, cần áp dụng nhiều biện pháp bảo mật khác nhau để giảm thiểu nguy cơ.



## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`
A = Confidentiality → C
B = Integrity → I
C = Availability → A

Flag của em:FIT4012{A-C-B-I-C-A}

