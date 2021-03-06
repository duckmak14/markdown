# Cách sử dụng ngôn ngữ Markdown

Ta có thể sử dụng được một số câu lệnh trong HTML vào markdown 

[ 1.Phần tiêu đề](#phantieude)

[ 2.Nhấn mạnh văn bản](#nhanmanh)

[ 3.Danh sách](#danhsanh)

[ 4.Chèn link](#chenlink)

[ 5.Chèn ảnh](#chenanh)

[ 6.Đánh dấu và cách viết code](#code)

[ 7.Bảng](#bang)

[ 8.Tạo chú thích](#chuthich)

[ 9.Dấu Ngang](#daungang)

<a name="phantieude">

# 1.Phần tiêu đề

```
# H1
```

# H1

``` 
## H2

```
## H2

```
### H3

```
### H3

Tương tự như vậy các tiêu đề cấp sau thì thêm nhiều dấu `#` hơn

<a name="nhanmanh">

# 2.Nhấn mạnh

Có nhiều cách để nhấn mạnh

- In nghiêng ta dùng `* Từ cần in nghiêng *` nó sẽ ra được * Từ cần in nghiêng *

- Để in đậm ta dùng `** Từ cần in đậm **` nó sẽ được ** Từ cần in đậm **

- Để gạch thêm nhấn mạnh bằng cách gạch ngang chữ ta dùng ` ~~ Từ gạch ~~` sẽ ra ~~ Từ gạch ~~

- Khi ta viết văn bản vào hai dấu thăng thì văn bản sẽ được giữ nguyên những gì ta viết 

<a name="danhsanh">

# 3.Danh sách

thì kết quả sẽ là 

1. Mục 1

2. Mục 2

 * Muc 2.1
 
 * Mục 2.2
     
     - Mục 2.2.1

3. Mục 3

<a name="chenlink">

# 4.Chèn link



Có nhiều cách để chèn link

`[ link đến google](https://www.google.com)`

[ link đến google](https://www.google.com)

nếu không muốn để đường link ở sau

```
[link][mô tả link]

[mô tả link]: https://www.google.com
```

Phần mô tả ta cũng có thể đặt là số

Ta cũng có thể đặt link trực tiếp luôn 

`https://www.google.com`

https://www.google.com

<a name="chenanh">

# 5.Chèn ảnh

Chèn ảnh ta có hai cách để chèn ảnh 

cách 1: chèn ảnh trực tiếp bằng một hàng
 
![alt text](https://github.com/duckmak14/anh/blob/master/Screenshot_1.png)

cách 2: chèn ảnh bằng cách tham chiếu xuống môt link ảnh

![alt text][logo]

[logo]:  https://github.com/duckmak14/anh/blob/master/Screenshot_2.png "Logo Title Text 2"

<a name="code">

# 6.Đánh dấu code và cú pháp

Để bo chữ ta dùng kí tự ` ` chữ cần bo` `

` chữ cần bo`

Để bo cả một đoạn

ta dùng ` ``` `

```

```
đoạn 1

đoạn 2
```
```

```
đoạn 1

đoạn 2
```

<a name="bang">

# 7. Bảng

```
| dòng | cột 1 | cột 2 | Cột 3 |
| ----- |-----|------|-----|
|dòng 1 | 1 | 2 | 3 |
|Dòng 2 | 4 | 5 | 6 |
```

| dòng | cột 1 | cột 2 | Cột 3 |
| ----- |-----|------|-----|
|dòng 1 | 1 | 2 | 3 |
|Dòng 2 | 4 | 5 | 6 |

<a name="chuthich">

# 8.Tạo dòng chú thích

```

Cái này có nghĩa là:

> ý nghĩa 1
> ý nghĩa 2
```

Cái này có nghĩa là:

> ý nghĩa 1
> ý nghĩa 2

<a name="daungang">

# 9.Tạo ra dấu gạch ngang 

ta có thể dùng 3 dấu gạch ngang

---

hấu sao

***

hay 3 dấu gạch dưới

___



