HỌC VIỆN CÔNG NGHỆ BƯU CHÍNH VIỄN THÔNG TP.HCM
KHOA CÔNG NGHỆ THÔNG TIN 2

BÁO CÁO ĐỊNH KỲ THỰC TẬP TỐT NGHIỆP
-	Họ tên sinh viên: NGUYỄN VĂN DU
-	Lớp: L16CQCP01-N
-	Mã số sinh viên: N6LDCN001
-	Tên đề tài: Thiết kế hệ thống điều khiển và giám sát thiết bị điện trong nhà thông qua internet
-	Giáo viên hướng dẫn: Nguyễn Xuân Sâm 



GIỚI THIỆU NỘI DUNG ĐỀ TÀI 
-	Tên đề tài : Thiết kế hệ thống điều khiển và giám sát thiết bị điện trong nhà thông qua internet
Thiết kế hệ thống điều khiển và giám sát thiết bị điện trong nhà thông qua internet có các chức năng:
 Điều khiển thiết bị từ xa qua Internet;
Điều khiển thiết bị thông qua tin nhắn SMS

 NỘI DUNG ĐÃ THỰC HIỆN ĐƯỢC
1.	Lý thuyết:
Tìm hiểu phần mềm Arduino
Lịch Sử ra đời của Arduino ?
Arduino ra đời tại thị trấn Ivrea, nước Ý và được đặt theo tên một vị vua vào thế kỷ thứ 9 là King Arduin
Nó chính thức được đưa ra giới thiệu vào năm 2005 như là một công cụ cho sinh viên học tập của giáo sư Massimo Banzi, một trong những người phát triển Arduino tại trường Interaction Design Instistute Ivrea (IDII). Dù hầu như không có một sự tiếp thị hay quảng cáo nào nhưng tin tức về Arduino vẫn lan truyền với tốc độ chóng mặt nhờ vô vàn lời truyền miệng tốt đẹp của những người dùng đầu tiên.
Hiện nay Arduino nổi tiếng trên toàn thế giới đến nỗi có người đã tìm đến thị trấn Ivrea chỉ để tham quan nơi đã sản sinh ra nền tảng thú vị này. 

Arduino là một nền tảng mà mọi thiết bị phần cứng đều được làm sẵn và chuẩn hóa, người dùng chỉ việc chọn những thứ mình cần, ráp lại là có thể chạy được. Bạn muốn làm xe điều khiển từ xa ? Arduino cung cấp cho bạn module điều khiển động cơ có sẵn, mạch điều khiển có sẵn, mạch thu phát sóng không dây có sẵn,… Bạn sẽ không cần phải động não thiết kế mạch điện cho chiếc xe bởi đơn giản là mọi thứ đều có sẵn.
Giống như một con người với “thể xác” đã được xây dựng sẵn, một hệ thống Arduino phải có “tâm hồn” để có thể “sống”. Và tôi gọi việc tạo ra “tâm hồn” ấy là “Lập trình”. Tuy nhiên bạn sẽ không phải lập trình từ A đến Z. Mỗi thứ phần cứng gắn mác “Arduino” đều có những đoạn lệnh đã được viết sẵn (gọi là thư viện) do cộng đồng người dùng Arduino cùng phát triển. Bạn chỉ việc bưng vào và xào nấu lại theo ý muốn của mình. Tới đây, bạn đã giải quyết được vấn đề thứ 2. Đừng lo nếu bạn không biết gì về lập trình bởi chúng chỉ giống như những bài tập Tin học lớp 11 lặt vặt ở trường thôi.
Arduino có thể kết nối với những gì ?
Một hệ thống Arduino có thể cung cấp cho bạn rất nhiều sự tương tác với môi trường xung quanh với:
•	Hệ thống cảm biến đa dạng về chủng loại (đo đạc nhiệt độ, độ ẩm, gia tốc, vận tốc, cường độ ánh sáng, màu sắc vật thể, lưu lượng nước, phát hiện chuyển động, phát hiện kim loại, khí độc,…),…
•	Các thiết bị hiển thị (màn hình LCD, đèn LED,…).
•	Các module chức năng (shield) hỗ trợ kêt nối có dây với các thiết bị khác hoặc các kết nối không dây thông dụng (3G, GPRS, Wifi, Bluetooth, 315/433Mhz, 2.4Ghz,…), …
•	Định vị GPS, nhắn tin SMS,…

Tìm hiểu về vi xử lý ESP8266
Kít ESP8266 là kít phát triển dựa trên nền chíp Wifi SoC ESP8266 với thiết kế dễ dàng sửa dụng vì tích hợp sẵn mạch nạp sử dụng chíp CP2102 trên borad. Bên trong ESP8266 có sẵn một lõi vi sử lý vì thế bạn có thể trực tiếp lập trình cho ESP8266 mà không cần thêm bất kì con vi sử lý nào nữa. Hiện tại có hai ngôn ngữ có thể lập trình cho ESP8266, sử dụng trực tiếp phần mềm IDE của Arduino để lập trình với bộ thư viện riêng hoặc sử dụng phần mềm node MCU

Thông số kĩ thuật
•	Ic chính ESP8266 Wifi SoC
•	Chip nạp CP2102
•	Nguồn cấp 5vdc
•	GPIO giao tiếp mức logic 3.3v 

Thực hành:
 	Đã in được mạch.
