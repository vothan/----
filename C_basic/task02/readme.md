





**1. Thẻ tiêu đề**

Markdown sử dụng kí tự # để bắt đầu cho các thẻ tiêu đề, có thể dùng từ 1 đến 6 ký tự # liên tiếp. Mức độ riêu đề giảm dần từ 1 đến 6

Tùy mục đích và ý thích bạn có thể sử dụng cách này để thể hiện các chỉ mục khác nhau.

**Ví dụ:**

#1.Tiêu đề cấp 1
#1.Tiêu đề cấp 1

##2.Tiêu đề cấp 2
##2.Tiêu đề cấp 2

######6.Tiêu đề cấp 6
######6.Tiêu đề cấp 6


**2. Chèn link, chèn ảnh**

Để chèn hyperlink bạn chỉ cần paste luôn linh đó vào file .md

https://www.google.com.vn
https://www.google.com.vn

Hoặc bạn cũng có thể sử dụng cú pháp sau để thu ngắn đường dẫn của link

[Google](https://www.google.com.vn)
Kết quả là:

Google

Để chèn ảnh thì sử dụng cú pháp sau:

<img src="link_anh_cua_ban">

<img src="https://imgur.com/a/s2GYuzb">

Tôi thường sử dụng công cụ Lightshot để chụp ảnh màn hình và up hình đó lên trang http://i.imgur.com/ để lấy đường dẫn ảnh đưa vào Github

Hai công cụ này khá dễ sử dụng, bạn chỉ cần chụp màn hình bằng Lightshot ấn Ctrl + C để copy và Ctrl + V để paste vào trình duyệt tại trang web http://i.imgur.com/


3. Ký tự in đậm, in nghiêng
Để in đậm một đoạn text bạn chỉ cần làm như sau:
**từ cần in đậm**
từ cần in đậm

Để in nghiên một đoạn text bạn chỉ cần làm như sau:
*từ cần in nghiêng*
từ cần in nghiêng


4. Trích dẫn, bo chữ
Để bo một đoạn text thì bạn chỉ cần sử dụng cú pháp sau:

`đoạn cần bo`
Kết quả là: đoạn cần bo

Để làm nổi bật một đoạn, chẳng hạn như một đoạn shell hay file cấu hình bạn có thể sử dụng cú pháp như ví dụ sau:

```sh
auto eth0
iface eth0 inet static
ipaddress 10.10.10.10
netmask 255.255.255.0
gateway 10.10.10.1
dns-nameservers 8.8.8.8
```
Kết quả như sau:

auto eth0
iface eth0 inet static
ipaddress 10.10.10.10
netmask 255.255.255.0
gateway 10.10.10.1
dns-nameservers 8.8.8.8

5. Gạch đầu dòng
Để sử dụng gạch đầu dòng bạn chỉ cần sử dụng cú pháp sau:

- Gạch đầu dòng thứ nhất
  <ul>
  <li>Thụt với đầu dòng 1</li>
  <li>Thụt với đầu dòng 1</li>
  </ul>
- Gạch đầu dòng thứ hai
  <ul>
  <li>Thụt với đầu dòng 2</li>
  <li>Thụt với đầu dòng 2</li>
  </ul>
Gạch đầu dòng thứ nhất
Thụt với đầu dòng 1
Thụt với đầu dòng 1
Gạch đầu dòng thứ hai
Thụt với đầu dòng 2
Thụt với đầu dòng 2

6. Tạo bảng
Bạn có thể sử dụng cú pháp sau để tạo bảng:

| Cột 1 Hàng 1 | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |
Kết quả:

Cột 1 Hàng 1	Cột 2	Cột 3	Cột 4
Hàng 2	2 x 1	2 x 2	2 x 3
Hàng 3	3 x 1	3 x 2	3 x 3
Hàng 4	4 x 1	4 x 2	4 x 3
- - -
