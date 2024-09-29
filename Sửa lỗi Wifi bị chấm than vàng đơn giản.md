# Sửa lỗi Wifi bị chấm than vàng đơn giản

Trong quá trình sử dụng máy tính, [laptop](https://hacom.vn/laptop-may-tinh-xach-tay) hẳn không ít các bạn đã gặp phải tình trạng lỗi biểu tượng Wifi bị chấm than vàng và không thể truy cập vào mạng Internet được. Nếu bạn tìm thấy bài viết này trên đề xuất của google thì chắc hẳn bạn đang gặp phải tình trạng này và cảm thấy vô cùng khó chịu phải không? Và bạn đang muốn sửa lỗi này nhưng chưa biết phải làm thế nào? Vậy hãy cùng làm theo các cách sửa lỗi **Wifi bị chấm than vàng** dưới đây của Hanoicomputer dưới đây.

![img](https://hacom.vn/media/lib/30-09-2020/windows10-wifi-problems.jpg)

### **Reset lại các thiết bị mạng**

Bất kể bạn đang gặp phải sự cố nào liên quan đến mạng, khởi động lại các thiết bị mạng như modem hay [router wifi](https://hacom.vn/router-wifi) là cách đầu tiên mà các kỹ thuật viên tư vấn cho bạn. Và tất nhiên, nếu bạn gặp phải tình trạng [**Wifi bị chấm than vàng**](https://hacom.vn/sua-loi-wifi-bi-cham-than-vang-don-gian-trong-chop-mat) thì tại sao bạn không thử khởi động lại các thiết bị mạng. Thao tác vô cùng đơn giản, nếu thiết bị của bạn có công tắc nguồn - hãy tắt nguồn nó đi. Đối với những loại modem, router không có công tắc nguồn, hãy rút giắc nguồn của thiết bị ra chờ 1 - 2 phút rồi cắm lại sau đó kiểm tra thiết bị đã có thể kết nối lại wifi một cách bình thường chưa.

![img](https://hacom.vn/media/lib/30-09-2020/resetthietbimang.jpg)

Nếu vẫn chưa thể kết nối lại được mạng wifi, chúng ta chuyển sang cách thứ 2.

### **Đặt lại IP**

Nguyên nhân chính gây nên hiện tượng **Wifi bị chấm than vàng** đó là do các thiết bị cấp và sử dụng mạng bị xung đột IP. Hiện nay, hầu hết các thiết bị mạng dùng cho cá nhân và hộ gia đình đều được cấp IP động. Do đó, để đặt lại IP bạn có thể thực hiện thao tác dưới đây :

Đầu tiên bạn mở cửa sổ RUN lên bằng tổ hợp phím Windows + R > gõ lệnh cmd

```scss
ipconfig/release
ipconfig/renew
```

Sau khi cửa sổ DOS hiện ra, gõ lệnh `ipconfig/release` và ấn Enter để giải phóng địa chỉ IP cho tất cả các bộ tiếp hợp mạng được kết nối.

Sau khi quá trình giải phóng IP kết thúc, tiếp tục gõ lệnh `ipconfig/renew` và ấn Enter để cấp một địa chỉ IP mới cho máy.

![img](https://hacom.vn/media/lib/30-09-2020/tliip.png)

Sau khi lệnh renew được thực hiện, máy tính sẽ cấp mới địa chỉ IP cho laptop của bạn. Lúc này bạn thử kết nối mạng lại xem đã truy cập được Internet hay chưa.

### **Sử dụng tính năng Troubleshoot Problems**

Troubleshoot Problems là một tính năng được tích hợp trong Window giúp chuẩn đoán và tự động sửa chữa nhanh chóng các lỗi trong hệ điều hành Window bao gồm âm thanh, mạng và nhiều lỗi khác. Đây cũng là cách đơn giản cho những ai ít am hiểu về công nghệ hoặc lười thực hiện những thao tác rườm rà.

Thao tác rất đơn giản, bạn chỉ cần chuột phải vào biểu tượng **Wifi bị chấm than** **vàng** và chọn Troubleshoot Problems. Window sẽ tự phân tích lỗi và tự động sửa chữa cho bạn.

![img](https://hacom.vn/media/lib/30-09-2020/troubleshootwifi.png)

Ngoài ra, bạn cũng có thể mở tính năng Troubleshoot Problems để khắc phục các sự cố về mạng khác theo cách dưới đây :

1. Mở Settings.
2. Chọn Update & security.
3. Chọn Troubleshoot.
4. Chọn Network Adapter, và click vào Run the troubleshooter.
5. ![img](https://hacom.vn/media/lib/30-09-2020/network-adapter-troubleshoot-windows-10.jpg)
6. Chọn kết nối mạng mà bạn muốn sửa rồi ấn Next để bắt đầu.

![img](https://hacom.vn/media/lib/30-09-2020/wifi-network-adapter-fix.jpg)

### **Cài đặt lại Driver của card Wifi**

Ngoài vấn đề xung đột IP, khi driver [card wifi](https://hacom.vn/card-mang) bị lỗi thì biểu tượng wifi của bạn cũng sẽ được cảnh báo bằng một dấu chấm than vàng. Sau khi thực hiện các cách trên nhưng chưa hiệu quả, bạn có thể thực hiện cài đặt, update lại driver Wifi và kết nối lại xem có khắc phục được không nhé.

Đối với win 10, các bạn chuột phải vào biểu tượng cửa sổ Window sau đó chọn Device Manager.

![img](https://hacom.vn/media/lib/30-09-2020/devicemanager.png)

Trên màn hình xuất hiện cửa sổ Device Manager. Tại đây bạn tìm tùy chọn có tên Network adapters và mở rộng Network adapters bằng cách click vào mũi tên hướng xuống dưới. Kích chuột phải vào adapter mà bạn sử dụng, chọn tùy chọn Update driver.

![img](https://hacom.vn/media/lib/30-09-2020/updatedriver.png)

Tiếp theo, bạn chọn Search automatically for updated driver software và chờ để hoàn tất quy trình cập nhật.

![img](https://hacom.vn/media/lib/30-09-2020/updatedriver1.png)

Khi quá trình kết thúc, hãy đóng cửa sổ Device manager và khởi động lại PC của bạn.

Trên đây là những cách khắc phục lỗi **Wifi bị chấm than** vàng mà nhiều người thường gặp phải. [Hanoicomputer](https://hacom.vn/) chúc các bạn thành công, khắc phục được tình trạng lỗi gặp phải. Đừng quên chia sẻ những thông tin hữu ích này với bạn bè của mình nhé.