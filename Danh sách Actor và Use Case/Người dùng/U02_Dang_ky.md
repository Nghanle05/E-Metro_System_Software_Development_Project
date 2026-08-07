# U02 - Đăng ký 
## Chức năng

Người dùng đăng ký tài khoản mới để sử dụng các chức năng của hệ thống 

## Tiền điều kiện

Người dùng chưa từng sử dụng hệ thống

## Các luồng hoạt động 

| Bước | Mô tả | 
| --- | ---- |
| 1 | Người dùng truy cập vào hệ thống để tiến hành đăng ký |
| 2 | Người dùng chọn chức năng Đăng ký tài khoản | 
| 3 | Người dùng điền đầy đủ các thông tin như họ tên, số điện thoại, mật khẩu và nhấn Đăng ký  | 
| 4 | Hệ thống kiểm tra tính hợp lệ của số điện thoại và mật khẩu |
| 5 | Nếu hợp lệ thì hệ thống tạo tài khoản mới và lưu thông tin người dùng vào cơ sở dữ liệu |
| 6 | Hệ thống gửi SMS xác nhận tài khoản cho người dùng |
| 7 | Người dùng nhận thông báo là Đăng ký thành công và được chuyển hướng tới trang Đăng nhập tài khoản |

## Các luồng thay thế 

| Bước | Mô tả | 
| --- | ---- | 
| 5 | a. Nếu không hợp lệ thì hệ thống sẽ báo lỗi và người dùng phải nhập lại thông tin. <br> b. Nếu số điện thoại đã được đăng ký thì hệ thống sẽ thông báo và người dùng phải đăng nhập tài bằng số điện thoại đó hoặc đăng ký bằng số điện thoại khác |
## Hậu điều kiện 
Người dùng đăng ký tài khoản mới trên hệ thống thành công và có thể sử dụng các chức năng của hệ thống 
