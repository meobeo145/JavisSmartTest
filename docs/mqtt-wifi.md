Chức năng này giúp cho người dùng có thể đưa công tắc Wifi vào trong bộ trung tâm JAVIS HC để có thể tạo automation, kịch bản…( mặc định công tắc Wifi kết nối vào ứng dụng JAVIS SMART chỉ có thể thao tác bật, tắt trên ứng dụng).

Bước 1: Cấu hình mqtt cho công tắc trên ứng dụng.

- Chọn “Cài đặt”/ “Thiết bị”/ “Chọn mã ID của công tắc WIFI mà bạn muốn cấu hình

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.049.png)![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.050.png)

- Chọn “Cấu hình MQTT”

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.051.png)![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.052.png)

+ Địa chỉ máy chủ: Địa chỉ ip bộ JAVIS HC
+ Cổng: 1883
+ Tên người dùng: javis
+ Mật khẩu: javis2020

Bước 2: Ghim địa chỉ ip Tĩnh cho công tắc WIFI (Tham khảo google ứng với từng mẫu    modem WIFI nhà bạn)

Bước 3: Mở menu “Công tắc MQTT” từ giao diện quản lý JAVIS HC

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.053.png)

- Địa chỉ IP nội mạng của công tắc: nhập địa chỉ IP đã lưu ở bước trên
- Sau đó bấm “Connect” để kết nối.
- Sau khi kết nối thành công tiến hành khởi động lại HC

Bước 4: Cập nhập công tắc MQTT vừa tạo vào ứng dụng JAVIS SMART

- Xem lại mục 10.

Lưu ý: khi cấu hình MQTT sẽ xuất hiện thêm các công tắc mới và những công tắc WIFI cũ sẽ không bị mất đi, khi tạo kịch bản, tự động hóa sẽ sử dụng những công tắc MQTT mới được tạo ra.
