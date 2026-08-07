# U03 - Quên mật khẩu
## Chức năng

Người dùng có nhu cầu đổi mật khẩu hoặc khi người dùng quên mật khẩu và phải đổi mật khẩu mới  

## Quan hệ phụ thuộc 

- Đăng nhập 

## Tiền điều kiện

Người dùng đã có tài khoản trên hệ thống 

## Các luồng hoạt động 

| Bước | Mô tả | 
| --- | ---- |
| 1 | Người dùng truy cập vào hệ thống để tiến hành đăng nhập |
| 2 | Người dùng nhập các thông tin số điện thoại và mật khẩu để đăng nhập | 
| 3 | Sau khi đăng nhập thành công, người dùng chọn chức năng “Đổi mật khẩu”  | 
| 4 | Người dùng nhập mật khẩu đang sử dụng để xác thực |
| 5 | Người dùng nhập mật khẩu mới | 
| 6 | Hệ thống xác thực thành công và lưu mật khẩu mới | 
| 7 | Hệ thống gửi thông báo " Đổi mật khẩu thành công" |

## Các luồng thay thế 

| Bước | Mô tả | 
| --- | ---- | 
| 3 | a. Người dùng đăng nhập sai mật khẩu <br> b. Hệ thống yêu cầu người dùng đăng nhập lại <br> c. Người dùng nhấn “Quên mật khẩu” <br> d. Hệ thống xác nhận yêu cầu “Quên mật khẩu” của người dùng và hiển thị trang "Đổi mật khẩu" <br> e. Hệ thống yêu cầu người dùng nhập số điện thoại và mật khẩu mới <br> f.  Người dùng nhập số điện thoại và mật khẩu mới <br> g. Hệ thống xác thực số điện thoại và mật khẩu mới của người dùng <br> h. Hệ thống gửi thông báo “Đổi mật khẩu thành công” <br> |
| 6 | a. Hệ thống thông báo “Mật khẩu chưa đáp ứng yêu cầu” hoặc “Mật khẩu chưa đủ mạnh” <br> b. Người dùng thay đổi mật khẩu theo gợi ý của hệ thống |

## Hậu điều kiện 
Người dùng đổi mật khẩu thành công
