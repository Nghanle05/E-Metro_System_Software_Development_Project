# Dự án phát triển phần mềm E-Metro 
Thu thập và phân tích yêu cầu của một dự án giả định 

## 👨‍👩‍👧‍👦 CÁC THÀNH VIÊN ĐÓNG GÓP 
----------

| STT | MSSV | Họ tên | Email |
|:---:|:----------:|:-----------------:|:--------------------:|
| 1 | 23520430 | Lê Thị Ngọc Hân | 23520430@gm.uit.edu.vn |
| 2 | 23520285 | Lương Kiều Diễm | 23520285@gm.uit.edu.vn |

## 🧭 MÔ TẢ ĐỀ TÀI  
----------
Trong bối cảnh hiện đại hóa giao thông đô thị, hệ thống tàu điện ngầm và tàu điện trên cao đóng vai trò quan trọng trong việc giảm ùn tắc giao thông và ô nhiễm môi trường. Việc xây dựng một hệ thống phần mềm quản lý toàn diện cho hệ thống tàu điện không chỉ góp phần nâng cao tỷ lệ sử dụng phương tiện công cộng mà còn cải thiện đáng kể hạ tầng giao thông đô thị.

Dự án này tập trung vào thu thập và phân tích yêu cầu cho việc phát triển hệ thống phần mềm E-Metro. Dựa trên các yêu cầu thu thập được, hệ thống được thiết kế thông qua các mô hình và sơ đồ nghiệp vụ, bao gồm các chức năng chính như:
- Mua vé
- Quản lý vận hành
- Quản lý nhân sự
- Quản lý thông tin bảo trì
- Tạo và quản lý tài khoản người dùng
- Gửi thông báo
- Ghi nhận lịch sử hoạt động
- Cải thiện và nâng cao chất lượng dịch vụ

## 👥 CÁC ĐỐI TƯỢNG HƯỚNG ĐẾN 
----------
Hệ thống phục vụ cho 5 nhóm đối tượng chính, và chức năng của mỗi đối tượng trong hệ thống như sau: 
- **Nhóm quản trị viên:** Có quyền thực thi toàn quyền trên hệ thống, bao gồm:
  + Quản lý vận hành của ga, tàu, chuyến
  + Quản lý tài khoản người dùng
  + Xem báo cáo cuối tháng
  + Cấp quyền cho các nhóm đối tượng khác thông qua hệ thống
- **NHóm quản lý ga:** Có nhiệm vụ quản lý ga tàu, bao gồm:
  + Quản lý các thiết bị vận hành trên ga
  + Quản lý nhân sự hiện đang làm trong ga, gồm: nhân viên vé và nhân viên bảo trì
  + Theo dõi và cập nhật lịch trình bảo trì
  + Tổng hợp báo cáo mỗi cuối thánh thông qua hệ thống để gửi cho quản trị viên 
- **Nhóm nhân viên vé:** Có nhiệm vụ hỗ trợ hành khách đi tàu, bao gồm:
  + Mua, in, thay đổi vé tàu
  + Kiểm tra giao dịch thanh toán
  + Kiểm tra thông tin hành khách đi tàu
  + Xác minh thông tin vé đối với các vé được thanh toán trực tuyến 
- **Nhóm nhân viên bảo trì:** Có nhiệm vụ như sau:
  + Bảo trì các thiết bị tại ga, tàu theo lịch phân công của quản lý ga
  + Báo cáo, cập nhật kết quả lên hệ thống sau khi kết thúc công việc
- **Nhóm hệ thống tích hợp:** Bao gồm hệ thống thông báo và hệ thống thanh toán, có nhiệm vụ như sau:
  + Hỗ trợ hành khách thanh toán qua phần mềm
  + Xác minh giao dịch thanh toán, mua vé
  + Gửi các thông báo, sự cố đến các nhóm đối tượng khác
  + Lưu lại các thông tin lịch sử thông báo và giao dịch  

## 🧩 LƯỢC ĐỒ ERD 
----------
![ERD hệ thống](images/ERD.png)

## 🎯 KẾT QUẢ ĐẠT ĐƯỢC 
----------
Qua quá trình làm đồ án **"Thu thập và phân tích dự án giả định"** với đề tài **"Phát triển phần mềm E-Metro"**, nhóm đã hoàn thành các nội dung sau:
- Vận dụng các kiến thức trong môn học "Phân tích thiết kế phần mềm" để hoàn thành đồ án môn học
- Vận dụng các phương pháp, các cách khảo sát, hướng tiếp cận khác nhau để thu thập các yêu cầu, mong muốn thực tế đối với dự án phát triển phần mềm tàu điện từ nhiều nhóm đối tượng khác nhau
- Dựa vào các kết quả thu thập, khảo sát hay các bài báo để phân chia thành 5 nhóm đối tượng chính
- Phân tích nghiệp vụ, xác định rõ chức năng chính cho từng nhóm đối tượng theo yêu cầu chức năng và phi chức năng
- Làm rõ quy trình mà từng nhóm đối tượng sẽ thao tác trên hệ thống
- Xây dựng các mô hình, luồng quy trình thông qua các sơ đồ UML.
  
Thông qua đề tài, nhóm hiểu rõ hơn về cách thức khảo sát, thu thập yêu cầu, các quy trình phân tích nghiệp vụ, xác định từng nhóm đối tượng tham gia và xây dựng thành công các luồng quy trình mà từng nhóm sẽ thao tác trên hệ thống.

## ⚠️ ƯU VÀ NHƯỢC ĐIỂM CỦA ĐỒ ÁN 
----------
*1. Về ưu điểm:*
- Đề tài mang tính thực tiễn cao, có thể áp dụng cho các đô thị đang phát triển hệ thống điện ngầm
- Quá trình phân tích rõ ràng, bám sát các phương pháp kỹ thuật phần mềm hiện đại
- Phân chia nhóm đối tượng cụ thể, đáp ứng được nhu cầu thực tế của từng nhóm đối tượng
- Phương pháp tiếp cận toàn diện và cụ thể, từ khảo sát mong muốn, nhu cầu của các đối tượng, phân tích nghiệp vụ đến xây dựng từng quy trình hoạt động cụ thể
- Tính mở rộng và tích hợp được chú trọng ngay từ đầu, tạo điều kiện thuận lợi để phát triển trong tương lai 
  
*2. Về nhược điểm:*
- Một số chức năng nâng cao như chatbox, dự đoán lưu lượng hành khách, dự đoán thời gian chết của thiết bị, tàu chưa được triển khai mạnh
- Nhiều hệ thống giao thông lân cận chưa được tích hợp để hỗ trợ hành khách đưa ra con đường tối ưu, nhanh nhất.

## 🚀 HƯỚNG PHÁT TRIỂN TRONG TƯƠNG LAI
----------
- Phát triển và triển khai phần mềm vào thực tiễn, áp dụng các mô hình quy trình đã thiết kế
- Tích hợp trí tuệ nhân tạo (AI) như chatbot để hỗ trợ hành khách sử dụng hệ thống và giải đáp thắc mắc
- Kết nối với các hệ thống IoT trong ga để giám sát thiết bị theo thời gian thực
- Tích hợp với các hệ thống giao thông công cộng khác (xe buýt, phương tiện công cộng) nhằm tối ưu hóa lộ trình di chuyển cho hành khách
- Mở rộng đa nền tảng (web/app) để nâng cao trải nghiệm người dùng
- Tự động thu thập và phân tích dữ liệu (hành khách, sự cố, vận hành) nhằm hỗ trợ ra quyết định và cải thiện chất lượng dịch vụ
- Hỗ trợ đa ngôn ngữ để phục vụ khách du lịch quốc tế

## 🛠️ CÁC CÔNG CỤ SỬ DỤNG 
---------- 
- Excel: Tổng hợp các yêu cầu của nhóm đối tượng
- Draw.io: được sử dụng để xây dựng luồng quy trình thông qua UML 

## 📊 KHẢO SÁT
-----------
1. [Xây dựng sơ đồ Use Case cho e-shopping](https://www.studocu.vn/vn/document/dai-hoc-khoa-hoc-tu-nhien-dai-hoc-quoc-gia-thanh-pho-ho-chi-minh/software-design/e-metro-e-shopping-draw-use-case/115255211)
