# Các khái niệm trong lập trình hướng đối tượng với Python

Thực hiện: Thi Minh Nhựt - Email: thiminhnhut@gmail.com

Thời gian: Ngày 07 tháng 12 năm 2016

## Tài liệu tham khảo

* [Class trong python - Viblo](https://viblo.asia/le.cong.phuc/posts/znmMd0y4Mr69).

* [Khái niệm hướng đối tượng trong Python - Viet Jack](http://vietjack.com/python/khai_niem_huong_doi_tuong_trong_python.jsp).

* [Lập Trình Hướng Đối Tượng Trong Python - Phần 1: Cơ Bản - Studio](https://www.stdio.vn/articles/read/422/lap-trinh-huong-doi-tuong-trong-python-phan-1-co-ban).

## Các khái niệm

* `Class` (lớp): là kiểu dữ liệu do người dùng định nghĩa cho một đối tượng bao gồm 
các `attributes` (thuộc tính) đặc trưng cho tất cả các đối tượng của một `class`.

* `Attributes` (thuộc tính): bao gồm `data members` và `methods` được gọi thông qua 
ký hiệu dấu chấm `dot`.
	
	+ `Data members`: là biến chứa dữ liệu, gồm `class variable` và `instance variable`.
		
		- `Class variable`: là biến được dùng chung cho tất cả mọi đối tượng của một `class`, 
		không nằm trong `methods` nào cả và các biến này không sử dụng thường xuyên.
		
		- `Instance variable`: là biến được định nghĩa bên trong `methods` chỉ thuộc về `instance` 
		(đối tượng thực thể của một lớp).
	
	+ `Methods` (phương thức): là các hàm thực hiện một công việc nào đó được định nghĩa trong `class`.

* `Instance` (thực thể): là một hiện thực cụ thể của một `class`.

* `Instantiation`: là việc tạo ra một `instance` của một `class`.

* `Object` (đối tượng): là `instance` duy nhất chứa cấu trúc dữ liệu được định nghĩa bởi `class`. 
Một `object` bao gồm các `data members` và `methods`.

* `Function overloading`: là `methods` định nghĩa các phép toán gồm nhiều `instances` tham gia 
(ví dụ cộng 2 `instances`,...)

* `Operator overloading`: là phép toán cần nhiều `method` tham gia.

* `Inheritance`: là tính kế thừa của một `class` từ một `class` khác.
