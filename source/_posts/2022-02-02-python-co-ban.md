---
title: "Python Cơ Bản"
date: 2022-02-02
---

# Python Căn Bản

## 1. Phần mềm là gì?

> Phần mềm là tập hợp của 1 file hoặc nhiều file, được tạo ra để giải quyết một bài toán nào đó.

## 2. Ngôn ngữ lập trình là gì?

- Người Việt nói tiếng việt.
- Người Mỹ nói tiếng anh.
- Máy tính có ngôn ngữ riêng của nó gọi là mã máy.

> Để nói chuyện được với máy tính (để sử dụng được tài nguyên của máy tính: Ram, CPU, Disk), ta phải dùng ngôn ngữ lập trình, bằng một cách nào đó ngôn ngữ lập trình sẽ được biên dịch sang **mã máy**, từ mã máy ta có thể ra lệnh cho máy tính.

```
File Python -> Mã Máy -> Được Biên Dịch

Ruby -> Code C/C++ -> Mã máy -> Được Biên Dịch

```

## 3. Giao diện dòng lệnh (Terminal / Command Line) là gì?

- macOS: Terminal
- window: Command Line
- Linux: Terminator

> Mục đích là để chạy các lệnh để máy tính thực hiện

## 4. Code Editor là gì?

Ví dụ như **VSCode**:
- Soạn thảo mã nguồn (để code)
- **Nhưng code editor không thể chạy code**
- VSCode thì có tích hợp thêm terminal vào

## 5. IDE là gì?

Ví dụ như **Visual Studio**:
- Dùng để soạn thảo mã nguồn (để code)
- **Có thể chạy được code**
- Không phải là ngôn ngữ nào nó cũng chạy được.

Ví dụ:
Visual Studio: chỉ chạy code .Net, C#, C, C++...
NetBean: chỉ chạy được code Java.
Android Studito: Code app cho android.
Xcode: Code app cho iOS

## 6. Các ngôn ngữ lập trình phổ biến

> Javascript > Java > .Net > Python

Backend: Ruby, Python, Java, Golang, Javascript, .Net...
Frontend Web: Javascript
iOS: swift, Javascript
Android: Kotlin, Java, Javascript

## 7. Ngôn ngữ lập trình python có thể dùng làm gì?

- Làm backend
- Làm AI

## 8. Hello world với python

```python
print("Hello world\n")
```

## 9. Cách chạy một chương trình python

```
python ten_file.py

python chuot.py

python source/_posts/chuot.py

python test.py
```

## 10. Biến trong python (variables)

```python
# Tên biến đặt như nào cũng được
# Nhưng nên đặt làm sao cho dễ hiểu
# Đặt a, b, c là vô nghĩa?

so_nguyen = 10
so_thap_phan = 0.0001
so_am = -10

# Kiểu chuỗi
ten = "nguyen the anh"

# Giá trị boolean
# Boolean luôn nhanh nhất
# Trong các ngôn ngữ khác thì là true, false
# Tuy nhiên trong python phải là True, False (với chữ đầu viết hoa).
true_value = True # đồng nghĩa là đúng
false_value = False # đồng nghĩa là sai
```

> Không thể gán 1 biến cho nhiều hơn 1 giá trị, một biến ứng với 1 giá trị
> Trong python có 3 loại giá trị cơ bản là: **số**, **chuỗi** và **boolean**

## 11. Nhận giá trị từ terminal trong python

```python
name = input('what is your name?')

# Nhận giá trị từ bàn phím và gán vào biến name.
```

## 12. Chuyển đổi dạng giá trị trong python

**int()**: Chuyển chuỗi sang số.
**str()**: Chuyển số sang chuỗi.

## 13. Chuỗi trong python (String)

```python
thong_diep_nam_moi = '''
Nam moi con chuc ba suc khoe, nhieu tien
Nam moi con chuc cau suc khoe, thu nhap tang gap doi
Chuot
'''

print(thong_diep_nam_moi)

# Sẽ ra được như này:
# Nam moi con chuc ba suc khoe, nhieu tien
# Nam moi con chuc cau suc khoe, thu nhap tang gap doi
# Chuot
```

## 14. Một số phương thức với chuỗi trong python

> Python hỗ trợ nhiều phương thức với chuỗi

Ví dụ: `len()` là hàm để tính độ dài 1 chuỗi.

## 15. Các phép toán trong python

> + là cộng
> - là trừ
> * là nhân
> / là chia


> "1" + "1" sẽ bằng "11" vì cộng chuỗi chỉ đơn thuần là ghép ký tự lại với nhau

> Chuyển đổi chuỗi sang số nguyên với hàm **int()**

## 16. Các phép toán cao cấp trong python

```python
diem_tong_ket = 8.9

print(round(diem_tong_ket))

# In ra màn hình số 9, vì 8.9 đã được hàm round() làm tròn.
```

**abs()**: là để lấy giá trị tuyệt đối của 1 số.
**round()**: để làm tròn 1 số.

```python
nam = input('nhap nam?')
nam_sinh = input('nhap nam sinh?')

tuoi = int(nam) - int(nam_sinh)
cau_tra_loi = "nam sinh cua ban la "

print(cau_tra_loi + str(tuoi))
```

## 17. Điệu kiện trong python

1. Câu điều kiện đơn giản

```python
tuoi = input('ban bao nhieu tuoi?')
tuoi_so_nguyen = int(tuoi)

if (tuoi_so_nguyen == 27):
  print("day la tuoi cua cau")
else:
  print("day la tuoi cua chuot")
```

2. Câu điều kiện phức tạp

```python
tuoi = input('ban bao nhieu tuoi?')
tuoi_so_nguyen = int(tuoi)

if (tuoi_so_nguyen == 27):
  print("======> day la tuoi cua cau <=======")
elif (tuoi_so_nguyen == 14):
  print("======> day la tuoi cua chuot <=======")
elif (tuoi_so_nguyen == 12):
  print("======> day la tuoi cua hanh <=======")
else:
  print("======> day khong phai la tuoi cua ai ca. <=======")
```

## 18. Toán tử so sánh trong python

1. So sánh bằng thì dùng **==**

Ví dụ:

```python
# So sánh tuổi

tuoi = 10

# So sánh tuoi với 100, xem tuoi có bằng 100 hay không?

tuoi == 100

# Nếu đúng thì nó trả về True
# Nếu sai thì nó trả về False
```

2. So sánh lớn hơn thì dùng **>**

Ví dụ:

```python
x = 10

x > 15

# Câu so sánh trên sẽ trả về False, vì x nhỏ hơn 15.

x > 9

# Câu so sánh này thì trả về True, vì x lớn hơn 9
```

3. So sánh nhỏ hơn thì dùng **<**

Ví dụ:

```python
x = 10
x < 10

# Sai, vì x bằng 10 nên, 10 không thể nhỏ hơn 10
```

4. So sánh lớn hơn hoặc bằng **>=**

Ví dụ:

```python
x = 10

x >= 10

# câu so sánh này đúng vì x = 10, thỏa mãn điều kiện
```

5. So sánh nhỏ hơn hoặc bằng **<=**

Ví dụ:

```python
x = 10

x <= 10

# Câu so sánh này đúng vì x = 10, thỏa mãn điều kiện
```

6. So sánh khác **!=**

Ví dụ:

```python
x = 10

x != 10

# câu này sai vì x = 10
```

## 19. Vòng lặp trong python

![vong lap while](/../images/vong_lap_while.webp)

```python
# in số từ 1 đến 20 ra màn hình

# ta gọi x là biến chạy
x = 1

# Điều kiện dừng là x > 20
while x <= 20:
  # Đoạn logic xử lý, làm gì với biến chạy cũng được
  print(x)

  # Điều kiện để tăng giá trị của biến chạy
  x = x + 1
```

**Cách lặp 1 mảng**

```python
mang_chieu_cao = [163, 180, 155]

for y in mang_chieu_cao:
  print(y)

# Nó sẽ in ra lần lượt: 163, 180, 155
# Biến y sẽ lần lượt được gán với giá trị từng phần
# tử của mảng mang_chieu_cao theo thứ tự trái sang phải
```

## 20. Mảng trong python

1. Khai báo 1 mảng

```python
mang_chieu_cao = [163, 180, 155]

mang_ten = ["Nguyen The anh", "Tuyen Son", "Quang Luong"]

mang_thi_hoc_sinh_gioi_co_giai = [True, False, False]

mang_diem_tong_ket = [8.6, 8.4, 1.0]
```

## 21. Các phương thức cơ bản với mảng

1. Lấy phần tử ở vị trí trong mảng

```python
mang_chieu_cao = [163, 180, 155]

# Cách lấy giá trị theo thứ tự
print(mang_chieu_cao[2])
```

## 22. Hàm trong python (function)

```python
# Đây là hàm tính tuổi, tên hàm là "tinh_tuoi"
# Hàm này nhậm 1 tham số truyền vào là năm sinh
def tinh_tuoi(nam_sinh):
  # Tất cả logic liên quan đến tính tuổi vào đây
  tuoi = 2022 - nam_sinh
  print("so tuoi cua ban la: " + str(tuoi))

mang_nam_sinh = [1995, 2008, 2010]

tinh_tuoi(mang_nam_sinh[0])
tinh_tuoi(mang_nam_sinh[1])
tinh_tuoi(mang_nam_sinh[2])
```

```python
def tong_5_so_nguyen(a,b,c,d,e):
  tong = a + b + c + d + e
  print("tong cua 5 so la: " + str(tong))

so_thu_nhat = input('nhap so thu nhat?')
so_thu_nhat_int = int(so_thu_nhat)

so_thu_hai = input('nhap so thu hai?')
so_thu_hai_int = int(so_thu_hai)

so_thu_ba = input('nhap so thu ba?')
so_thu_ba_int = int(so_thu_ba)

so_thu_tu = input('nhap so thu tu?')
so_thu_tu_int = int(so_thu_tu)

so_thu_nam = input('nhap so thu nam?')
so_thu_nam_int = int(so_thu_nam)

tong_5_so_nguyen(so_thu_nhat_int, so_thu_hai_int, so_thu_ba_int, so_thu_tu_int, so_thu_nam_int)
```

# Bài tập
1. Dịch bài viết dưới đây


> https://programmingwithmosh.com/python/python-exercises-and-questions-for-beginners/


2. Sau đó trả lời hết câu hỏi và làm hết bài tập trong đó

# References

[1][https://www.youtube.com/watch?v=_uQrJ0TkZlc](https://www.youtube.com/watch?v=_uQrJ0TkZlc)
