# Hướng dẫn cách đổi tên thư mục tài khoản trong Windows 10

https://www.youtube.com/watch?v=ZOFczBroouk



Tên thư mục "User" trong ổ C được tạo ra cùng với tên tài khoản đăng nhập khi cài đặt hệ điều hành Windows 10. 

Một ngày đẹp trời bạn không thích cái tên thư mục này nữa, muốn đổi sang tên khác "ngầu" hơn. Tuy nhiên tên thư mục này không thể đổi theo các Rename thông thông . Laptop K1 sẽ **[hướng dẫn cách đổi tên thư mục tài khoản](https://laptopk1.com.vn/huong-dan-cach-doi-ten-thu-muc-tai-khoan-trong-windows-10)** trong windows 10 này nhé

**1.** Click mở **Start** menu.

**2.** Gõ tìm kiếm “**cmd**” và mở **Command Prompt**.

![img](https://file.hstatic.net/1000345160/file/doi_ten_1_grande.png)

**3.** Copy và dán dòng sau vào Command Prompt:

```css
wmic useraccount get name,SID
```

![img](https://file.hstatic.net/1000345160/file/doi_ten_2_grande.png)

**4.** Cửa sổ lệnh sẽ hiển thị danh sách các tài khoản có trên hệ điều hành. Ghi nhớ SID tài khoản muốn đổi tên thư mục.

**5.** Mở Start menu, gõ vào tìm kiếm “**regedit**“. Click mở **Regedit**.

![img](https://file.hstatic.net/1000345160/file/doi_ten_3_grande.png)

**6.** Trong cửa sổ Registry Editor tìm tới thư mục sau:

```css
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList\SID
```

**SID** chính là dòng bạn đã nhớ ở bước 4.

![img](https://file.hstatic.net/1000345160/file/doi_ten_4_grande.png)

**7.** Click đúp vào **ProfileImagePath**, đặt tên mới cho thư mục ở đây.

![img](https://file.hstatic.net/1000345160/file/doi_ten_5_grande.png)

**8.** Tới đây vẫn chưa xong, tên thư mục user vẫn chưa được đổi. Bạn cần đăng xuất khỏi tài khoản hiện tại: Click vào **Start** menu, click vào tài khoản hiện tại và chọn **Sign out**.

![img](https://file.hstatic.net/1000345160/file/doi_ten_6_grande.png)

**9.** Sau khi bạn đăng nhập lại, do tên thư mục đã bị đổi nên những gì được lưu trong tài khoản sẽ không hiển thị, bao gồm màn hình desktop, taskbar, các đăng nhập phần mềm… Màn hình sẽ hiển thị thông báo không thể đăng nhập vào tài khoản của bạn. Click **Dismiss** để bỏ qua.

![img](https://file.hstatic.net/1000345160/file/doi_ten_7_grande.png)**10.** Bây giờ bạn hãy truy cập vào thư mục tài khoản cần đổi tên và thực hiện đổi. Nhấp tổ hợp phím **Windows + E** để mở File Explorer rồi tìm tới thư mục đó. Bây giờ bạn đã có thể click chuột phải và chọn **Rename** để thực hiện đổi tên. Viết lại tên y hệt như ở bước 7, nếu không sẽ bị lỗi và phải đổi lại. 

Chúc các bạn thành công !

![img](https://file.hstatic.net/1000345160/file/doi_ten_8_grande.png)