**Các bước thực hiện:**

- Tại màn hình chính của ứng dụng chọn "Tự động"/ "Tự động hóa" / "Chọn dấu +"

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.020.png)

- Chọn 1 trong số những tự động hóa có sẵn và tiến hành đặt tên, chọn hành động, thiết bị thực hiện tương ứng.

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.021.png)

## Hẹn giờ 

### Hẹn giờ với công tắc Wifi (không dùng bộ trung tâm JAVIS HC)

Tính năng này cho phép người dùng hẹn giờ bật, tắt thiết bị Wifi có trong hệ . Ví dụ: hẹn 5h bật bình nóng lạnh và tự động tắt 30 phút.

- Chọn “Hẹn giờ” => Chọn mã ID của công tắc muốn thiết lập hẹn giờ (hình công tắc 3 nút màu trắng).

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.022.png)

- “Thời gian thực hiện”: Chọn thời gian bạn muốn hẹn giờ.
- “Ngày lặp lại”: Chọn những ngày trong tuần mà bạn muốn hẹ giờ
- “Chọn hành động”: Chọn hành động mà bạn muốn thiết bị thực hiện có sẵn trong danh sách.
- “Chọn thiết bị thực hiện”: Chọn những thiết bị có sẵn trong danh sách để thực hiện ứng với hành động bạn chọn ở bên trên.

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.023.png)

### Hẹn giờ khi dùng bộ trung tâm JAVIS HC

Tính năng này cho phép người dùng hẹn giờ bật, tắt 1 thiết bị có trong hệ thống hoặc kích hoạt 1 kịch bản đã được tạo sẵn. Ví dụ: hẹn 10h kích hoạt kịch bản “Đi ngủ”.

- Chọn “Hẹn giờ” => Chọn mã ID của bộ trung tâm JAVI HC (hình ngôi nhà màu xanh).

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.024.png)

- “Tên hẹn giờ”: Điền tên bạn muốn đặt.
- “Thời gian thực hiện”: Chọn thời gian bạn muốn hẹn giờ.
- “Ngày lặp lại”: Chọn những ngày trong tuần mà bạn muốn hẹ giờ
- “Chọn hành động”: Chọn hành động mà bạn muốn thiết bị thực hiện có sẵn trong danh sách.
- “Chọn thiết bị thực hiện”: Chọn những thiết bị có sẵn trong danh sách để thực hiện ứng với hành động bạn chọn ở bên trên.

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.023.png)

## Đồng bộ trạng thái

Tính năng này cho phép người dùng đồng bộ trạng thái của 2 công tắc hoặc đèn khác nhau có trong hệ thống. Ví dụ dùng để đồng bộ 2 công tắc đảo chiều đèn cầu thang.

- “Tên đồng bộ”: Đặt tên đồng bộ tương ứng.
- “Kiểu đồng bộ”: 
+ Đồng bộ một chiều: Thiết bị 1 điều khiển thiết bị 2, nhưng thiết bị 2 không thể điều khiển thiết bị 1.
+ Đồng bộ hai chiều: Thiết bị 1 điều khiển thiết bị 2 và ngược lại.
- “Thiết bị 1”, “Thiết bị 2”: Chọn 2 thiết bị mà bạn muốn đồng bộ trạng thái.

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.025.png)

## Tự động nhà vệ sinh

Tính năng này cho phép bật tắt tự động đèn và các thiết bị trong nhà vệ sinh dựa theo cảm biến cửa và cảm biến chuyển động. 

Yêu cầu: cần lắp đặt công tắc thông minh, 1 cảm biến cửa và 1 cảm biến chuyển động ứng với nhà Vệ sinh cần thiết lập tự động.

**Các trường hợp tự động nhà vệ sinh:**

\1. Trường hợp cửa vệ sinh luôn đóng (đi ra hoặc đi vào đều đóng lại)

1.1. Mở cửa thì đèn bật ngay lập tức

1.2. Sau đó đóng cửa lại thì đèn KHÔNG tắt (cứ bật mãi) dù ngồi im không cử động.

1.3. Mở cửa đi ra ngoài đèn tắt ngay lập tức

\2. Trường hợp cửa vệ sinh luôn mở (đi ra không đóng kín cửa)

2.1. Mở cửa vào đèn sẽ bật (chậm hơn 1.1 khoảng 1~2s)

2.2. Nếu đóng cửa lại và ở trong đó thì đèn sẽ KHÔNG tắt( trong vòng 30p) dù ngồi im không cử động

2.3. Nếu đi vào và KHÔNG đóng cửa, sau đó ngồi im thì đèn sẽ tắt khi không có chuyển động 1-2p

2.4. Đi ra ngoài KHÔNG đóng cửa đèn sẽ tắt sau 1-2p

**Những trường hợp chạy không chính xác (các trường hợp không phổ biến):**

- Trường hợp 2 người cùng vào nhà vệ sinh và đóng cửa lại, sau đó 1 người thứ 3 mở cửa vào hoặc 1 người ở trong mở cửa ra thì tính năng tự động chạy không đúng.
- Trường hợp 1 người vừa mở cửa ra không đóng lại (đèn đã tắt) nhưng quay lại ngay đèn sẽ không bật mà phải tầm 2p kịch bản tự bật mới có hiệu lực. Nguyên nhân do cảm biến chuyển động sau 2p mới cập nhật trạng thái từ có chuyển động sang không có chuyển động.
- Trường hợp 3: đi vào và không đóng cửa ngay. Sau đó đi ra lại đóng cửa lại.

**Các bước thiết lập tự động Vệ sinh trên ứng dụng Javis Smart:**

- “Tên tự động”: Điền tên tự động tương ứng
- “Thời gian hiệu lực”: mặc định sẽ hoạt động cả ngày, nếu muốn giới hạn thời gian hoạt động có thể điều chỉnh tương ứng.
- “Cảm biến cửa”: Chọn cảm biến cửa WC
- “Cảm biến chuyển động”: Chọn cảm biến chuyển động WC
- “Thời gian tắt đèn sau khi cửa mở mà không có chuyển động”: Thời gian cài đặt tự động tắt đèn trong trường hợp cửa Wc mở, người sửa dụng WC nhanh sau đó đi ra thì sau thời gian cài đăth đèn sẽ tự động tắt.
- “Các thiết bị sẽ bật, tắt tự động”: Chọn đến các thiết bị trong WC mà bạn muốn bật tắt tự động (Đèn, quạt).

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.026.png)

## Bật tắt theo trạng thái cửa

Mục đích của tính năng này cho phép thiết lập tự động bật hoặc tắt đèn khi cửa mở.

- “Tên tự động”: Đặt tên tự động
- Có thể chọn hành động “Mở cửa bật đèn” hoặc “Đóng cửa tắt đèn”
- ‘Cảm biến cửa”: Chọn cảm biến cửa bạn muốn thiết lập tự động
- “Các thiết bị sẽ bật tự động”: Chọn thiết bị mà bạn muốn bật, tắt tự động theo trạng thái cửa
- “Thời gian hiệu lực”: chỉnh sửa thời gian phù hợp
- “Độ trễ”: thời gian thiết bị sẽ bật, tắt sau khi cửa được đóng, mở
- Khi thiết lập xong nhấn “Lưu” để lưu lại.

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.027.png)

## Bật tắt theo chuyển động

Mục đích của tính năng này cho phép thiết lập tự động bật hoặc tắt đèn khi có chuyển động. Ví dụ thiết lập tự bật đèn khi có chuyển động trong phòng khách trong khoảng thời gian từ 23h đến 6h sáng.

- “Tên tự động”: Đặt tên tự động
- Có thể chọn hành động “Có chuyển động bật đèn” hoặc “Không có chuyển động tắt đèn”
- ‘Cảm biến chuyển động”: Chọn cảm biến chuyển động bạn muốn thiết lập tự động
- “Các thiết bị sẽ bật tự động”: Chọn thiết bị mà bạn muốn bật, tắt tự động theo trạng thái cảm biến chuyển động
- “Thời gian hiệu lực”: chỉnh sửa thời gian phù hợp
- “Độ trễ”: thời gian thiết bị sẽ bật, tắt sau khi có hoặc không có chuyển động
- Khi thiết lập xong nhấn “Lưu” để lưu lại.

![](../assets/Hướng%20dẫn%20cài%20đặt%20JAVIS%20HC\_V2.028.png)

Video hướng dẫn:

<https://javishome.vn/huong-dan-thiet-lap-tu-dong-hoa-trong-ung-dung-javis-smart>

## Thiết bị thay đổi trạng thái

Mục đích của tính năng này cho phép thiết lập nhiều tự động hóa phức tạp (có thể nói là tổng hợp tất cả các tính năng tự động hóa ở phía trên).

### 8.6.1

- “Mở cửa, đóng cửa” 

- “Có chuyển động, không chuyển động” 

- “Cảm biến bật, cảm biến tắt” 

- “Công tắc bật, công tắc tắt”

- “Đèn bật, đèn tắt”

- “Tivi bật, tivi tắt”

- “Rèm mở, Rèm đóng”

Với các mục trên có thể setup các tự động hóa tương ứng với tiêu đề để thực hiện các hành động tương ứng.

Ví dụ: “Cửa mở”

- Chọn mục “Cửa mở”
- “Tên tự động”: đặt tên cho tự động hóa
- “Cảm biến cửa”: chọn cảm biến cửa mà bạn muốn khi cửu đó được mở sẽ thực hiện hành động tương ứng.
- “Thời gian hiệu lực”: là thời gian Automation có thể hoạt động, nếu muốn Automation hoạt động cả ngày thì để mặc định.
- “Độ trễ”: thời gian chờ để thực hiện hành động sau khi cửa được mở.
- “Hành động”: chọn một trong  những hành động mà bạn muốn thực hiện có trong danh sách.

### “Remote, nút kịch bản”

Chức năng này cho phép thiết lập nút kịch bản, remote để thực hiện các hành động tương ứng.Ví dụ: ấn nút về nhà thì bật đèn, mở rèm, bật điều hòa...Ấn nút “Ra ngoài” thì tắt toàn bộ thiết bị, đóng rèm…

- “Tên tự động”: Đặt tên cho tự động hóa
- “Remote, Nút kịch bản”: Chọn thiết bị tương ứng
- “Trạng thái kích hoạt”: Chọn trạng thái mà bạn muốn thiết lập với nút kịch bản hoặc remote đó.
- “Thời gian hiệu lực”: thời gian cho phép Automation hoạt động
- “Độ trễ”: Thời gian chờ để thực hiện hành động tương ứng khi kích hoạt nút kịch bản hoặc remote.
- “Hành động”: chọn hành động thực hiện mà bạn muốn thiết lập.