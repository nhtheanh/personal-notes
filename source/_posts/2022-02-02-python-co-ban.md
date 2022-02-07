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

## 18. Toán tử so sánh trong python

## 19. Vòng lặp trong python

## 20. Mảng trong python

## 21. Các phương thức cơ bản với mảng

## 22. Hàm trong python (function)

# Bài tập
1. Dịch bài viết dưới đây


> https://programmingwithmosh.com/python/python-exercises-and-questions-for-beginners/


2. Sau đó trả lời hết câu hỏi và làm hết bài tập trong đó

# References

[1][https://www.youtube.com/watch?v=_uQrJ0TkZlc](https://www.youtube.com/watch?v=_uQrJ0TkZlc)
