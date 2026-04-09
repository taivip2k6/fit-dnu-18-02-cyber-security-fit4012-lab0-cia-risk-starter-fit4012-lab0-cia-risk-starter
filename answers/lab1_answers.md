# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Bùi Ván Tài

**MSSV:** 1871020515

**Lớp/Nhóm 18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Dữ liệu nhạy cảm
- Asset 2:Hạ tầng hệ thống và Thiết bị
- Asset 3 (nếu có):

---

## 2. Mapping CIA
Ghép các sự cố phổ biến với từng mục tiêu bảo mật:

Sự cố A (Rò rỉ dữ liệu) -> Confidentiality (Tính bảo mật)

Ví dụ: Hacker đánh cắp danh sách mật khẩu người dùng hoặc thông tin thẻ tín dụng.

Sự cố B (Sửa đổi dữ liệu) -> Integrity (Tính toàn vẹn)

Ví dụ: Hacker xâm nhập hệ thống ngân hàng để thay đổi số dư tài khoản hoặc sửa điểm sinh viên.

Sự cố C (Tấn công từ chối dịch vụ) -> Availability (Tính khả dụng)

Ví dụ: Tấn công DDoS làm sập trang web hoặc Ransomware mã hóa dữ liệu khiến người dùng không thể truy cập.

---

## 3. Phân tích sự cố B
Giả sử sự cố B là việc hacker thay đổi cơ sở dữ liệu của một phần mềm quản lý (như dự án Java bạn từng làm):

Threat (Mối đe dọa): Tin tặc (Hacker) hoặc nhân viên nội bộ có ý đồ xấu muốn thay đổi thông tin để trục lợi.

Vulnerability (Lỗ hổng): Hệ thống thiếu kiểm soát truy cập (Access Control) chặt chẽ, không có cơ chế kiểm tra tính toàn vẹn (Hashing), hoặc tồn tại lỗ hổng SQL Injection.

Mitigation (Biện pháp giảm thiểu): Sử dụng các thuật toán băm (SHA-256) để kiểm tra tính toàn vẹn, thiết lập quyền truy cập tối thiểu (Least Privilege) và thực hiện sao lưu (Backup) định kỳ để khôi phục khi cần.

## 4. Reflection
Qua việc tìm hiểu về an ninh mạng và an toàn thông tin, em nhận thấy bảo mật không chỉ đơn thuần là cài đặt phần mềm diệt virus mà là một hệ thống phòng thủ đa tầng (Defense-in-depth). Tam giác CIA là kim chỉ nam giúp xác định mục tiêu bảo vệ, trong đó tính bảo mật, toàn vẹn và khả dụng luôn phải cân bằng. Đặc biệt, con người thường là mắt xích yếu nhất, vì vậy việc tuân thủ các chính sách và quy trình là cực kỳ quan trọng. Hiểu rõ các lỗ hổng giúp em có tư duy lập trình an toàn hơn trong các dự án phần mềm sau này.
## 5. Bonus Flag
`Dựa trên thứ tự sắp xếp phổ biến trong giáo trình (C-I-A), Flag của bạn sẽ là:

Flag của em: FIT4012{A-Confidentiality-B-Integrity-C-Availability}

