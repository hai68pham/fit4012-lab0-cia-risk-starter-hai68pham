# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Phạm Hoàng Hải

**MSSV:** 1871020214

**Lớp/Nhóm:** CNTT 18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Tài khoản sinh viên
- Asset 2:Tài khoản giảng viên
- Asset 3 (nếu có):Hệ thống đăng nhập

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->Bảo mật (lộ dữ liệu)
- Sự cố B ->Toàn vẹn (bị sửa sai)
- Sự cố C ->Sẵn sàng (không dùng được)

---

## 3. Phân tích sự cố B
- Threat:Người dùng trái phép truy cập hệ thống
- Vulnerability:Không có phân quyền rõ ràng
- Mitigation:Bật xác thực 2 lớp (MFA)

---

## 4. Reflection
Viết 5-7 dòng.
Nếu em là quản trị viên hệ thống, em sẽ ưu tiên xử lý vấn đề phân quyền và xác thực trước. Vì nếu không kiểm soát được ai có quyền sửa điểm thì hệ thống rất dễ bị thay đổi dữ liệu trái phép. Sau đó, em sẽ triển khai ghi log để theo dõi các hành động chỉnh sửa. Điều này giúp phát hiện và truy vết khi có sự cố xảy ra. Cuối cùng, em sẽ áp dụng xác thực đa yếu tố để tăng cường bảo mật tài khoản.


---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:
Không đăng nhập được → A (Availability)
Điểm bị sửa (8.0 → 5.0) → I (Integrity)
Dữ liệu bị lộ → C (Confidentiality)
FIT4012{A-Availability-B-Integrity-C-Confidentiality}
