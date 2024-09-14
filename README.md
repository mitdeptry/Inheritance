#Polymorphism
Đa hình là một tính chất trong lập trình hướng đối tượng (OOP) cho phép một đối tượng có thể hành xử theo nhiều cách khác nhau. Cụ thể, một phương thức hoặc hành vi có thể có nhiều hình thức khác nhau tùy thuộc vào ngữ cảnh hoặc đối tượng cụ thể sử dụng nó. Trong C#, đa hình giúp mã nguồn trở nên linh hoạt hơn, dễ bảo trì hơn và tối ưu hóa quá trình tái sử dụng mã.

-Phân biệt giữa Đa hình tĩnh và Đa hình động

+Đa hình tĩnh (Compile-time Polymorphism):
Còn gọi là Nạp chồng phương thức (Method Overloading).
Phương thức có thể có nhiều phiên bản với cùng tên nhưng khác nhau về số lượng hoặc kiểu tham số.
Quyết định phương thức nào sẽ được gọi xảy ra tại thời gian biên dịch.
Thường sử dụng cho các tình huống khi cần thực hiện nhiều hành động khác nhau tùy thuộc vào kiểu và số lượng tham số truyền vào.

+Đa hình động (Run-time Polymorphism):
Còn gọi là Ghi đè phương thức (Method Overriding).
Xảy ra khi một lớp con cung cấp cách triển khai riêng cho một phương thức được khai báo trong lớp cha.
Quyết định phương thức nào sẽ được gọi xảy ra tại thời gian chạy.
Được thực hiện bằng cách sử dụng từ khóa virtual và override.
