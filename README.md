# Java Core

## Avariable in java
Trong lập trình java có ba loại biến:
  1. ***Biến instance:*** là biến khai báo trong class và ngoài method. có phạm vi sử dụng bên trong class. được lưu trong bộ nhớ head. Nó được tạo khi một đối tượng được tạo trong từ khoá new và sẽ bị phá huỷ khi đối tượng bị phá huỷ. bạn cần cung cấp một access modifier khi khai báo biến instance.mặt định thì giá trị của biến instance là default.
  2. ***Biến local:*** biến local là biến khai báo trong method và có phạm vi sử dụng bên trong method đó. không có access modifier. nó sẽ lưu trên bộ nhớ stack. cần phải đặt giá trị mặt định của biến local trước khi sử dụng nó.
  3. ***Biến Static:*** là biến được khởi tạo một lần lúc class đó load. biến sẽ được sử dụng cho tấc các đối tượng chứ không phải cho một đối tượng riêng biệt.Biến static được lưu trữ trong bộ nhớ riêng
  
## Data type
Trong java có hai loại kiểu dữ liệu:
1. Kiểu dữ liệu nguyên thuỷ: byte(8 bit), int (32bit), float(32bit) char(16bit) boolean(1bit), double(32bit), short(16bit), long(64bit)
2. Kiểu dữ liệu đối tượng: Array, class, interface.

## Discription Object orriented Programming in java:
có 4 tính chất của java trong OOP: 
  1. ***Tính đói gọi:*** là kỹ thuật ẩn giấu thông tin liên quan và hiển thị thông tin liên quan.Mục đích giảm mứa độ phức tạp của phần mềm.Thể hiện qua từ khoá private và dùng method getter và setter lúc khởi tạo class.
  2. ***Tính kế thừa:*** là lớp con có thể thừa hưởng tấc cả các thuộc tính và phương thức từ lớp cha với điều kiện access modifier của thuộc tính và phương thức phải là public hoặc là protected.
  * có ba loại kế thừa: đơn kế thừa, kế thừa nhiều cấp và đa kế thừa
  3. ***Tính da hình:*** dùng Bike bike = new Honda() hoặc Bike bike = new Yamaha()
  
  ## Các khái niệm về đối tượng
  
  1. ***Class:*** là một nhóm các đối tượng có chung thuộc tính và phương thức. nó là mẫu thiết kế của các đối tượng tạo ra.
  2.***Object:*** là thể hiện của class. Một thực thể có các trạng thái hành vi gọi là đối tượng.
  3. ***So sánh sự khác nhau và giống nhau giữa class và object:*** 

|Class||Object|
|-||-|
|- Là khuân mẫu để tạo ra các đối tượng| |- Là thể hiện của một class|

|- Là nhóm các đối tượng tương tự nhau| |- Là thự thể của class ở thể giới thực|
