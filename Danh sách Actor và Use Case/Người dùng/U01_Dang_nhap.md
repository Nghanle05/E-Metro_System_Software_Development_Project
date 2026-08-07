# U01 - Đăng nhập 
## Chức năng

Người dùng đăng nhập vào tài khoản để thực hiện các chức năng của hệ thống 

## Quan hệ phụ thuộc 

- Đăng xuất
- Quên mật khẩu
- Xem thông tin cá nhân
- Cập nhật thông tin mới
- Xem thông tin chuyến tàu
- Xem lịch sử giao dịch

## Tiền điều kiện

Người dùng đã từng đăng ký tài khoản trên hệ thống này 

## Các luồng hoạt động 

| Bước | Mô tả | 
| --- | ---- |
| 1 | Người dùng truy cập vào hệ thống để tiến hành đăng nhập |
| 2 | Người dùng nhập các thông tin số điện thoại và mật khẩu để đăng nhập | 
| 3 | Hệ thống đối chiếu thông tin tài khoản và mật khẩu với cơ sở dữ liệu | 
| 4 | Nếu hợp lệ, hệ thống thông báo đăng nhập thành công và chuyển hướng đến trang chủ hệ thống |

## Các luồng thay thế 

| Bước | Mô tả | 
| --- | ---- | 
| 4 | a. Nếu không hợp lệ thì hệ thống sẽ báo lỗi và người dùng phải đăng nhập lại. <br> b. Nếu người dùng quên mật khẩu có thể tự cập nhật lại trên hệ thống hoặc liên hệ với nhân viên vé để được hỗ trợ đổi mật khẩu |
## Hậu điều kiện 
Người dùng sử dụng được các chức năng của hệ thống 
