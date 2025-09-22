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
<img width="402" height="302" alt="image" src="https://github.com/user-attachments/assets/76a5e815-ec4f-4d11-af6f-6a7bd26218e0" />

