# Mẹo xem nhanh tất cả tài khoản người dùng trên Windows

## **Kiểm tra tất cả tài khoản bằng Computer Management**

Công cụ quản lý máy tính Computer Management là một tiện ích quản lý Windows mà bạn có thể sử dụng để thực hiện các tác vụ quản trị như quản lý tài khoản người dùng và truy cập các công cụ như Device Manager, Event Viewer… Bạn cũng có thể sử dụng nó để xem tất cả các tài khoản người dùng trên máy tính của mình. Dưới đây là các bước để làm điều đó:

*Lưu ý:* Chúng tôi sẽ phải truy cập tùy chọn Local Users and Groups của công cụ Computer Management để xem tài khoản người dùng. Nhưng tùy chọn này chỉ khả dụng trong phiên bản Windows Pro. Nếu đang sử dụng Windows 11 Home, bạn có thể xem các phương pháp khác trong bài viết này.

**Bước 1:** Kích vào biểu tượng ***Windows*** để mở menu Start, nhập ***Computer Management*** vào thanh tìm kiếm và nhấn ***Enter.***

**Bước 2:** Kích đúp vào tùy chọn ***Local Users and Groups*** trong khung bên trái.

![Mẹo xem nhanh tất cả tài khoản người dùng trên Windows 11 (7)](https://cdn2.fptshop.com.vn/unsafe/Uploads/images/tin-tuc/158062/Originals/win_list_users.jpg)

**Bước 3:** Tiếp theo kích vào thư mục ***Users*** ở thanh bên trái trong menu phụ xổ xuống.

Quan sát khung bên phải, bạn sẽ thấy tất cả các tài khoản người dùng được hiển thị trong Computer Management.

## **Kiểm tra tất cả tài khoản bằng Command Prompt** 

[Windows PowerShell](https://fptshop.com.vn/tin-tuc/thu-thuat/cach-su-dung-powershell-quet-phan-mem-doc-hai-tren-windows-10-134830) và [Command Prompt](https://fptshop.com.vn/tin-tuc/danh-gia/command-prompt-la-gi-cach-chay-command-prompt-136652) là hai trong số các công cụ dòng lệnh phổ biến nhất của Windows. Bạn có thể sử dụng hai công cụ này để thực hiện các tác vụ nâng cao, tuy nhiên bạn cũng có thể sử dụng chính hai công cụ này xem tất cả tài khoản người dùng trên máy tính chạy Windows 11 của bạn.

Dưới đây là cách sử dụng Command Prompt để xem danh sách tất cả tài khoản người dùng trên Windows 11:

**Bước 1:** Kích vào biểu tượng ***Windows*** để mở menu Start, nhập ***Command Prompt*** vào thanh tìm kiếm và kích tùy chọn ***Run as administrator*** trong khung bên phải. 

**Bước 2:** Từ cửa sổ dòng lệnh, hãy nhập vào lệnh dưới đây và nhấn ***Enter:***

```css
net user
```

![Mẹo xem nhanh tất cả tài khoản người dùng trên Windows 11 (8)](https://cdn2.fptshop.com.vn/unsafe/Uploads/images/tin-tuc/158062/Originals/Profile-list-in-CMD.png)

Kết quả là bạn sẽ thấy tất cả các tài khoản người dùng trên máy tính của mình.

Nếu bạn muốn kiểm tra tài khoản người dùng bằng Windows PowerShell, hãy làm theo các bước sau:

**Bước 1:** Kích vào biểu tượng ***Windows*** để mở menu Start, nhập ***Windows PowerShell*** vào thanh tìm kiếm và kích tùy chọn ***Run as administrator*** trong khung bên phải. 

**Bước 2:** Nhập lệnh sau vào cửa sổ PowerShell và nhấn ***Enter.***

```css
Get-LocalUser
```

![Mẹo xem nhanh tất cả tài khoản người dùng trên Windows 11 (9)](https://cdn2.fptshop.com.vn/unsafe/Uploads/images/tin-tuc/158062/Originals/Profile-list-in-Windows-PowerShell.png)

Trên đây là những cách khác nhau để xem danh sách tất cả tài khoản người dùng trên Windows 11. Hãy cho chúng tôi biết bạn thấy phương pháp nào dễ nhất. Ngoài ra nếu bạn biết thêm cách nào khác để kiểm tra tài khoản người dùng hiện có trong Windows 11, hãy chia sẻ với chúng tôi nhé. 