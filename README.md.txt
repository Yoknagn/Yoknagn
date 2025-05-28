# ReLog: Cyclist Dashboard & Analytics

ReLog là một ứng dụng Java cung cấp cái nhìn sâu sắc về dữ liệu đi xe đạp, phân tích hành vi người dùng, các mô hình đi xe và hiển thị các biểu đồ trực quan để hỗ trợ quyết định.

## Các tính năng

- **CSV Watcher**: Theo dõi sự thay đổi của các tệp CSV và cập nhật bảng điều khiển khi có thay đổi.
- **Bảng điều khiển**: Hiển thị các biểu đồ tương tác dựa trên dữ liệu đi xe đạp, bao gồm loại người dùng, thời gian đi trung bình, hoạt động theo giờ, v.v.
- **Phân tích dữ liệu**: Thực hiện các kỹ thuật phân tích dữ liệu, so sánh người dùng thường xuyên và thành viên, giờ cao điểm và các tuyến đường phổ biến.

## Yêu cầu

Đảm bảo bạn đã cài đặt các phần mềm sau:
- **Java 11+**
- **Apache Maven** (tùy chọn, nếu bạn muốn xây dựng dự án bằng Maven)
- **Thư viện JFreeChart** (được sử dụng để tạo biểu đồ)
- **Thư viện BCrypt** để băm mật khẩu

## Cài đặt

1. **Clone (Sao chép) repository về máy**:
   ```bash
   git clone https://github.com/username/ReLog.git
   cd ReLog
