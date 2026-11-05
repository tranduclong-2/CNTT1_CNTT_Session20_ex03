# Bài 3 : Quản lý rủi ro khi mất thiết bị xác thực 

### 1. Input (Đầu vào)
- Mã Backup Codes đã được tạo và lưu trữ từ trước.
- Người dùng bị mất điện thoại chứa Google Authenticator.
- Tài khoản AWS và thông tin đăng nhập hợp lệ.

### 2. Process (Xử lý)
1. Truy cập trang đăng nhập AWS và nhập tài khoản, mật khẩu.
2. Chọn phương thức xác thực bằng Backup Code.
3. Nhập một mã dự phòng chưa sử dụng để xác minh danh tính.
4. Sau khi đăng nhập thành công, hủy các mã dự phòng cũ còn lại.
5. Thiết lập lại Google Authenticator trên thiết bị mới.
6. Tạo bộ Backup Codes mới và lưu tại nơi an toàn.

### 3. Output (Đầu ra)
- Khôi phục quyền truy cập tài khoản AWS.
- Tài khoản được bảo vệ bằng phương thức xác thực mới.
- Các mã dự phòng cũ không còn sử dụng được.
- Hệ thống tiếp tục hoạt động an toàn.

### 4. Tại sao không được lưu Backup Codes dưới dạng ảnh trong thư viện điện thoại?
- Dễ bị đánh cắp: Khi mất điện thoại, người nhặt được có thể xem ảnh chứa mã dự phòng.
- Dễ bị đồng bộ: Ảnh có thể tự động tải lên Google Photos hoặc iCloud.
- Mất an toàn tài khoản: Kẻ xấu có thể sử dụng mã để vượt qua bước xác thực và truy cập AWS.
Giải pháp: Nên lưu Backup Codes trong trình quản lý mật khẩu an toàn hoặc in ra giấy và cất ở nơi riêng tư. Không lưu chung với thiết bị đăng nhập.
