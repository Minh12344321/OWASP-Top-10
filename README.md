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

# Top 10 Lỗ hổng bảo mật trong Ứng dụng Di động (OWASP Mobile Application Security)
### Improper Platform Usage (Sử dụng nền tảng không đúng cách)
- Lợi dụng sai cách các API, thiết lập hoặc không bảo vệ các tính năng bảo mật có sẵn của hệ điều hành.

### Insecure Data Storage (Lưu trữ dữ liệu không an toàn)
- Lưu dữ liệu nhạy cảm như mật khẩu, token trong các bộ nhớ không an toàn như bộ nhớ cục bộ hoặc bộ nhớ ứng dụng.

### Insecure Communication (Giao tiếp không an toàn)
- Truyền dữ liệu không mã hóa hoặc bảo mật kém giữa ứng dụng và máy chủ, tạo cơ hội cho tấn công trung gian (MITM).

### Insecure Authentication (Xác thực không an toàn)
- Thiếu biện pháp xác thực người dùng an toàn, có thể bị lợi dụng để truy cập trái phép vào ứng dụng.

### Insufficient Cryptography (Mã hóa không đủ mạnh)
- Sử dụng thuật toán mã hóa yếu hoặc mã hóa không đúng cách, khiến dữ liệu nhạy cảm dễ bị giải mã.

### Insecure Authorization (Phân quyền không an toàn)
- Không xác thực người dùng hợp lệ hoặc không giới hạn quyền truy cập phù hợp, dẫn đến truy cập trái phép vào dữ liệu.

### Client Code Quality (Chất lượng mã nguồn khách hàng kém)
- Mã nguồn dễ bị lỗi hoặc có thể bị khai thác, bao gồm việc lưu các bí mật API trong mã nguồn ứng dụng.

### Code Tampering (Chỉnh sửa mã)
- Thiếu biện pháp bảo vệ để ngăn ngừa các cuộc tấn công sửa đổi mã ứng dụng, đặc biệt là khi mã được tải xuống thiết bị.

### Reverse Engineering (Phân tích ngược)
- Các kỹ thuật phân tích mã ứng dụng để tìm hiểu cách thức hoạt động và xác định điểm yếu có thể bị khai thác.

### Extraneous Functionality (Chức năng thừa)
- Các tính năng không cần thiết hoặc chế độ phát triển bị để lại trong ứng dụng có thể bị khai thác khi vào tay kẻ tấn công.
