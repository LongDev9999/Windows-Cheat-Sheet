# Cách kiểm tra ổ cứng SSD hay HDD chính xác & đơn giản nhất

## Một số cách kiểm tra ổ cứng SSD hay HDD đơn giản không dùng phần mềm

### Cách 01: Sử dụng công cụ chống phân mảnh của Windows

Đây cũng là cách kiểm tra ổ cứng SSD hay HDD đơn giản nhất mà Đỗ Bảo Nam Blog đã giới thiệu trong video ở trên. Bằng cách này, bạn có thể kiểm tra chính xác ổ cứng máy tính đang sử dụng ổ nào. Cách này áp dụng cho mọi phiên bản Windows, mọi loại máy tính như laptop, máy tính bàn. Các bước kiểm tra bạn làm như sau:

**Bước 01**: Click chuột phải vào ổ C (ổ cài Windows), chọn **Properties**

**Bước 02**: Một cửa sổ hiện ra bạn chuyển sang tab **tools**, chọn **optimize** (Ngoài ra, bạn có thể mở trực tiếp hộp thoại Optimize Drives bằng cách nhập **Defragment and Optimize Drive** vào ô tìm kiếm và mở nó).

![Cách kiểm tra ổ cứng SSD hay HDD chính xác & đơn giản nhất](https://dobaonamblog.com/wp-content/uploads/cach-kiem-tra-o-cung-ssd-hay-hdd-don-gian.jpg)Và tại bước này, bạn có thể kiểm tra xem máy tính đang dùng ổ cứng loại nào. Khi nhìn vào phần Media Type, bạn sẽ biết ổ cứng của mình là SSD hay HDD. Nếu máy tính của bạn có ổ SSD, công cụ sẽ liệt kê là Solid State Drive. Còn lại với ổ cứng cơ học thông thường sẽ được liệt kê là Hard Disk Drive.

### Cách 02: Kiểm tra ổ cứng SSD bằng công cụ PowerShell

Đây là công cụ được tích hợp sẵn trên Win 10. Do vậy bạn cũng không cần phải cài thêm bất kỳ phần mềm kiểm tra ổ cứng SSD nào cả. Thao tác thực hiện cũng rất đơn giản. Bạn chỉ cần thực hiện theo các bước sau:

**Bước 01:** Mở PowerShell với quyền admin. Bạn chỉ cần tìm kiếm PowerShell trong ô tìm kiếm, sau đó click chuột phải vào PowerShell, chọn Run as Administrator.

![Cách kiểm tra ổ cứng SSD hay HDD đơn giản không cần phần mềm -B01](https://dobaonamblog.com/wp-content/uploads/cach-kiem-tra-o-cung-ssd-hay-hdd-don-gian-c2.jpg)

**Bước 02:** Nhập câu lệnh **Get-PhysicalDisk** vào cửa sổ PowerShell và nhấn Enter. Sau đó bạn sẽ nhìn thấy nhiều thông tin về ổ cứng, trong đó có thông tin về ổ SSD hoặc HDD. Cũng giống như cách kiểm tra ổ cứng SSD hay HDD ở trên, bạn để ý cột Media Type. Nếu máy tính có ổ SSD, Media Type sẽ liệt kê là SSD.

![Cách kiểm tra ổ cứng SSD hay HDD đơn giản không cần phần mềm -B02](https://dobaonamblog.com/wp-content/uploads/cach-kiem-tra-o-cung-ssd-hay-hdd-don-gian-c2-b2.jpg)

Và như vậy trên đây là 02 cách kiểm tra ổ cứng SSD hay HDD vô cùng đơn giản mà không cần sử dụng phần mềm. Việc cài phần mềm chỉ để xem một thông tin nhỏ nào đó thực sự là không cần thiết. Và bạn hoàn toàn có thể xem những thông tin này ngay trên công cụ của Windows. Và theo Đỗ Bảo Nam Blog, bạn có thể sử dụng theo cách 01 là dễ nhất, bạn không cần phải nhập lệnh nào cả.