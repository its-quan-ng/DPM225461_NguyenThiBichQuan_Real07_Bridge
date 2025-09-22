# DPM225461_NguyenThiBichQuan_Real07_Bridge
Một dự án thực tế minh họa cho việc sử dụng Bridge pattern. Lớp abtract CustomersBase tách rời khỏi lớp implementation DataObject. Ta có thể thay đổi, tùy chỉnh DataObject mà không thay đổi bất kỳ Client.

Abstraction   (CustomersBase)
RefinedAbstraction   (Customer)
Implementor   (DataObject)
ConcreteImplementor   (CustomersData)

Ban đầu ta có một danh sách khách hàng gồm:
 `Mavis Hong
 Twinkle Kan
 Chris Fon
 Joey Law
 Freeda Cheung`
 
ở client:
 `customers.Data = new CustomersData("Hong Kong");` ---add city của các customers
 `customers.Add("Irene Bae");` -- add một customer mới Irene Bae


 Ta có kết quả như sau:
<img width="494" height="402" alt="image" src="https://github.com/user-attachments/assets/fb0c87cd-a59d-42fa-ab85-50f3597a40f2" />
