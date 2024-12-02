# Top 10 Lỗ hổng bảo mật trong Ứng dụng Web (OWASP Web Application Security)
### Broken Access Control (Lỗi kiểm soát truy cập)
- Người dùng có thể truy cập tài nguyên mà họ không có quyền.
  
### Cryptographic Failures (Thất bại mã hóa)
- Không mã hóa hoặc mã hóa không đúng cách dữ liệu nhạy cảm, khiến dữ liệu dễ bị lộ.
  
### Injection (Tấn công Injection)
- Bao gồm SQL, NoSQL, OS và LDAP injection, nơi kẻ tấn công có thể chèn dữ liệu độc hại vào hệ thống.

### Insecure Design (Thiết kế không an toàn)
- Thiếu các biện pháp bảo mật ngay từ giai đoạn thiết kế, gây rủi ro bảo mật.

### Security Misconfiguration (Cấu hình bảo mật sai)
- Cấu hình sai máy chủ, hệ điều hành hoặc ứng dụng có thể tạo lỗ hổng bảo mật.

### Vulnerable and Outdated Components (Thành phần lỗi thời và dễ bị tổn thương)
- Sử dụng thư viện hoặc framework lỗi thời có thể tạo lỗ hổng bảo mật.

### Identification and Authentication Failures (Lỗi xác thực và nhận diện)
- Gồm các lỗi liên quan đến đăng nhập, mật khẩu yếu, và quản lý phiên (session management).

### Software and Data Integrity Failures (Lỗi tích hợp dữ liệu và phần mềm)
- Không xác minh tính toàn vẹn của dữ liệu hoặc phần mềm có thể tạo ra lỗ hổng, như các cuộc tấn công qua cập nhật phần mềm.

### Security Logging and Monitoring Failures (Thiếu ghi log và giám sát bảo mật)
- Không có hoặc không đủ nhật ký bảo mật khiến các cuộc tấn công không bị phát hiện.

### Server-Side Request Forgery (SSRF) (Giả mạo yêu cầu phía máy chủ)
- Kẻ tấn công gửi yêu cầu từ máy chủ ứng dụng đến một hệ thống khác mà không có xác thực hợp lệ.
