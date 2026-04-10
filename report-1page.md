# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

1.Mục tiêu bài lab
Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
Phân biệt Confidentiality, Integrity, Availability.
Xác định threat, vulnerability, mitigation.
Thực hành workflow GitHub cơ bản để nhận và nộp bài.
3. Cách làm
Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
Phân tích từng sự cố theo bộ ba CIA.
Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
Hoàn thiện bài làm trong repo và commit/push lên GitHub.
4. Kết quả chính

Assets:

Cơ sở dữ liệu điểm sinh viên
Tài khoản người dùng (giảng viên, sinh viên, admin)

CIA mapping:

Sự cố A → Confidentiality (lộ thông tin điểm)
Sự cố B → Integrity (bị sửa điểm trái phép)
Sự cố C → Availability (không truy cập được hệ thống)

Phân tích sự cố B:

Threat: Người dùng trái phép hoặc attacker thay đổi điểm số
Vulnerability: Hệ thống phân quyền yếu, không kiểm tra xác thực/ghi log đầy đủ
Mitigation: Áp dụng kiểm soát truy cập (RBAC), xác thực mạnh, ghi log và kiểm tra thay đổi dữ liệu
4. Kết luận ngắn

Qua bài lab, em hiểu rõ hơn cách áp dụng mô hình CIA vào thực tế và cách phân tích rủi ro cơ bản. Phần khó nhất là phân biệt rõ giữa threat và vulnerability. Bài lab giúp em biết cách xác định tài sản quan trọng và đánh giá mức độ ảnh hưởng khi có sự cố. Khi phân tích an toàn thông tin, cần xác định đúng vấn đề và đưa ra biện pháp phù hợp, không chung chung.
