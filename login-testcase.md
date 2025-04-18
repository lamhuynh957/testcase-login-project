# ✅ Test Case – Chức năng Đăng nhập

| STT | Tên test case          | Mô tả                          | Dữ liệu đầu vào                             | Kết quả mong đợi                        | Trạng thái |
|-----|------------------------|--------------------------------|---------------------------------------------|------------------------------------------|------------|
| TC01| Đăng nhập thành công   | Nhập đúng email & mật khẩu     | Email: user@gmail.com <br> Pass: 123456     | Chuyển tới trang Dashboard               | Pass       |
| TC02| Sai mật khẩu           | Nhập sai mật khẩu              | Email: user@gmail.com <br> Pass: abc123     | Thông báo “Sai mật khẩu”                 | Pass       |
| TC03| Email không hợp lệ     | Email thiếu @ hoặc .com        | Email: user@ <br> Pass: 123456              | Hiện thông báo “Email không hợp lệ”      | Pass       |
| TC04| Mật khẩu để trống      | Không nhập mật khẩu            | Email: user@gmail.com <br> Pass: (trống)    | Báo lỗi “Vui lòng nhập mật khẩu”         | Pass       |
| TC05| Email chưa đăng ký     | Email không có trong hệ thống  | Email: abc@gmail.com <br> Pass: 123456      | Thông báo “Tài khoản không tồn tại”      | Pass       |
