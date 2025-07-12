Bài 1: Python là ngôn ngữ thông dịch hay biên dịch? Tại sao?
Bài 2:  Tìm hiểu trước kiến thức buổi 2 về :
Các kiểu dữ liệu trong Python
Các toán tử trong Python
Mệnh đề điều kiện và vòng lặp
Kiểu dữ liệu True, False

Bài 1: Python là ngôn ngữ thông dịch. Điều này có nghĩa là mã nguồn Python được thực thi bởi trình thông dịch (interpreter), chứ không được biên dịch thành mã máy như C/C++ trước khi chạy.

Vì:
+ Khi bạn viết một chương trình Python, bạn lưu nó dưới dạng file .py. Khi chạy, trình thông dịch Python sẽ đọc và chuyển từng dòng mã thành mã trung gian (bytecode), sau đó thực thi trực tiếp bằng máy ảo Python (Python Virtual Machine - PVM).
+ Python không tạo ra file thực thi (.exe) trừ khi dùng thêm công cụ đặc biệt như PyInstaller.
+ Do đó, bạn có thể chạy mã ngay lập tức mà không cần biên dịch trước – điều này giúp phát triển nhanh, dễ sửa lỗi và thử nghiệm.

Bài 2:

 1. Các kiểu dữ liệu trong Python

* `int`: số nguyên (vd: `5`, `-10`)
* `float`: số thực (vd: `3.14`, `-2.5`)
* `str`: chuỗi ký tự (vd: `"hello"`, `'Python'`)
* `bool`: giá trị đúng/sai (`True`, `False`)
* `list`: danh sách (vd: `[1, 2, 3]`)
* `tuple`: bộ giá trị không thay đổi (vd: `(1, 2)`)
* `dict`: từ điển (vd: `{"ten": "Phúc", "tuoi": 18}`)
* `set`: tập hợp không trùng lặp (vd: `{1, 2, 3}`)

2. Các toán tử trong Python

* Toán tử số học: `+`, `-`, `*`, `/`, `//` (chia lấy nguyên), `%` (chia lấy dư), `**` (lũy thừa)
* Toán tử so sánh: `==`, `!=`, `>`, `<`, `>=`, `<=`
* Toán tử logic: `and`, `or`, `not`
* Toán tử gán: `=`, `+=`, `-=`, `*=`, `/=`, ...
* Toán tử thành viên: `in`, `not in`
* Toán tử danh tính: `is`, `is not`

3. Mệnh đề điều kiện và vòng lặp

* Câu lệnh điều kiện:

  ```python
  if x > 10:
      print("Lớn hơn 10")
  elif x == 10:
      print("Bằng 10")
  else:
      print("Nhỏ hơn 10")
  ```

* Vòng lặp `for`:

  ```python
  for i in range(5):
      print(i)  # In từ 0 đến 4
  ```

* Vòng lặp `while`:

  ```python
  i = 0
  while i < 5:
      print(i)
      i += 1
  ```

4. Kiểu dữ liệu `True`, `False` (kiểu bool)

* Là **kiểu dữ liệu logic** trong Python, chỉ có hai giá trị: `True` và `False`

* Dùng nhiều trong kiểm tra điều kiện, ví dụ:

  ```python
  a = 5
  print(a > 3)  # True
  print(a == 10)  # False
  ```

* Một số giá trị được coi là `False` trong điều kiện:

  * `0`, `0.0`
  * `''` (chuỗi rỗng)
  * `[]`, `{}`, `()`
  * `None`
