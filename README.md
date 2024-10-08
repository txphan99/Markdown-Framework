## Markdown Framework, Git and Github for sysadmin

### Mục lục

[I. Mở đầu](#Modau)

[II. Ngôn ngữ Markdown](#ngonngumarkdown)
- [1. Thẻ tiêu đề](#thetieude)
- [2. Chèn link, chèn ảnh](#chenlinkchenanh)
- [3. Ký tự in đậm, in nghiêng](#kytuindaminnghieng)
- [4. Trích dẫn, bo chữ](#trichdanbochu)
- [5. Gạch đầu dòng](#gachdaudong)
- [6. Tạo bảng](#taobang)

=========================
<a name="Modau"></a>
### I. Mở đầu
Markdown là ngôn ngữ đánh dấu văn bản được tạo ra bởi John Gruber, sử dụng cú pháp khá đơn giản và dễ hiểu, dễ nhớ. Nếu nắm vững các cú pháp của Markdown bạn có thể trình bày bài viết của mình một cách mạch lạc, ấn tượng mà không mất nhiều thời gian. Bài viết dưới đây sẽ hướng dẫn để bạn có thể hiểu và sử dụng được ngay những cú pháp đó.

<a name="ngonngumarkdown"></a>
### II. Ngôn ngữ Markdown

<a name="tieude"></a>
### 1. Thẻ tiêu đề
Markdown sử dụng kí tự # để bắt đầu cho các thẻ tiêu đề, có thể dùng từ 1 đến 6 ký tự # liên tiếp. Mức độ riêu đề giảm dần từ 1 đến 6

Tùy mục đích và ý thích bạn có thể sử dụng cách này để thể hiện các chỉ mục khác nhau.
 
 Ví dụ: 
 ```
 # 1. Tiêu đề cấp 1 
 ```
 # 1. Tiêu đề cấp 1

 ```
 ## 2. Tiêu đề cấp 2 
 ```
 ## 2. Tiêu đề cấp 2

 ... đến tiêu đề cấp 6

 <a name="chenlinkchenanh"></a>
 ### 2.Chèn link, chèn ảnh
Để chèn hyperlink bạn chỉ cần paste luôn linh đó vào file .md
```
https://github.com
```
https://github.com

Hoặc bạn cũng có thể sử dụng cú pháp sau để thu ngắn đường dẫn của link
```
[Github](https://github.com)
```
Kết quả là:
[Github](https://github.com)

Để chèn ảnh thì bạn sử dụng cú pháp sau:
```
<img src="link_cua_anh">
```
Ví dụ: 
<img src="Image\453249115_122129834864307168_7372820565617487837_n.jpg">

Hoặc:
```
![Description of image](Image/n.jpg)
```
Ví dụ:

![Description of image](Image/453249115_122129834864307168_7372820565617487837_n.jpg)

<a name=kytuindaminnghieng></a>
### 3. Ký tự in đậm, in nghiêng

- Để in đậm một đoạn text  bạn chỉ cần làm như sau:

 ```
**từ cần in đậm**
```

**từ cần in đậm**
- Để in nghiên một đoạn text  bạn chỉ cần làm như sau:

```
*từ cần in nghiêng*
```

*từ cần in nghiêng*
- Để vừa in nghiêng vừa bôi đậm bạn chỉ cần làm như sau:
```
***từ vừa in nghiên vừa in đậm***
```
***từ vừa in nghiên vừa in đậm***
- Để nhấn mạnh, hightlight bạn chỉ cần làm như sau:

```
```php
echo ("highlight code");
```

```php
echo ("highlight code");
```
- Để viết inlide code bạn chỉ cần làm như sau:
```
`inline code`
```
`inline code`

<a name="trichdanbochu"></a>
### 4. Trích dẫn, bo chữ

Để bo một đoạn text thì bạn chỉ cần sử dụng cú pháp sau:

```
`đoạn cần bo`
```

Kết quả là: `đoạn cần bo`

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

```sh
auto eth0
iface eth0 inet static
ipaddress 10.10.10.10
netmask 255.255.255.0
gateway 10.10.10.1
dns-nameservers 8.8.8.8
```

