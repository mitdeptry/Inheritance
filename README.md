So sánh Kế thừa và Đa hình
-Giống nhau:

Cả kế thừa và đa hình đều là tính chất của lập trình hướng đối tượng (OOP) giúp mã nguồn dễ bảo trì, mở rộng và tái sử dụng.
Đều giúp giảm sự trùng lặp mã và tối ưu hóa hiệu suất phát triển phần mềm.
Kế thừa là cơ sở cho đa hình động vì đa hình động thường dựa trên mối quan hệ kế thừa giữa các lớp.

-Khác nhau:

+Kế thừa:

Là mối quan hệ giữa các lớp, trong đó một lớp con (derived class) thừa hưởng các thuộc tính và phương thức từ lớp cha (base class).
Được sử dụng để chia sẻ các thuộc tính và phương thức chung giữa các lớp liên quan.
Chỉ có một lớp con kế thừa trực tiếp từ một lớp cha (trừ khi sử dụng interfaces).

+Đa hình:

Là khả năng của một phương thức hoặc đối tượng có thể hoạt động theo nhiều cách khác nhau dựa trên kiểu dữ liệu hoặc đối tượng.
Được phân thành hai loại: đa hình tĩnh (nạp chồng phương thức) và đa hình động (ghi đè phương thức).
Được sử dụng để mở rộng hoặc thay đổi hành vi của các phương thức trong lớp kế thừa hoặc thông qua interfaces.

Ứng dụng thực tế của Kế thừa và Đa hình
-Ứng dụng của Kế thừa:

Tái sử dụng mã nguồn: Các thuộc tính và phương thức dùng chung có thể được đặt trong lớp cha, và các lớp con có thể kế thừa và mở rộng các phương thức này mà không cần phải viết lại.
Mở rộng chức năng: Khi cần bổ sung chức năng mới, ta có thể tạo lớp con kế thừa từ lớp cha mà không cần thay đổi lớp cha gốc, giúp giữ mã nguồn ổn định.
Ví dụ: Trong một ứng dụng quản lý xe cộ, các lớp con như Car, Truck và Motorcycle có thể kế thừa từ lớp cha Vehicle, trong đó Vehicle chứa các thuộc tính chung như Color, Make, Model.

-Ứng dụng của Đa hình:

Ghi đè phương thức (Method Overriding): Được sử dụng trong việc thay đổi hoặc mở rộng hành vi của lớp con so với lớp cha mà không cần thay đổi mã nguồn của lớp cha.
Nạp chồng phương thức (Method Overloading): Giúp linh hoạt hơn trong việc tạo ra nhiều phiên bản của cùng một phương thức nhưng với tham số khác nhau, giúp tối ưu hóa mã nguồn.
Ví dụ: Trong một hệ thống thanh toán, các lớp con như CreditCardPayment, PaypalPayment có thể ghi đè phương thức ProcessPayment() của lớp cha Payment để thực hiện hành vi khác nhau cho mỗi loại thanh toán.
