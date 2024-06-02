# Pratikum

## **1**

### Kode Program
```mysql
SELECT orderdetails.OrderID, orderdetails.OrderDate, customerss.CompanyName,
    -> customerss.ContactName, customerss.Phone, employees.LastName, employees.Title
    -> FROM orderdetails, customerss, employees
    -> WHERE orderdetails.CustID = customerss.CustomerID AND orderdetails.EmpID = employees.Empld AND
    -> employees.FirstName = "Margaret";
```
### Hasil
![f.jpeg](asett/f.jpeg)

### Analisis 
-Select= untuk memili kolom mana saja yang ingin di tampilkan dan dari tabel         mana kolom tersebut diambil

-o.orderID, o.orderdate =kolom orderID dan orderdate dari tabel o (orders) dipilih untuk di tampilkan

-c.compnyname, c.contactrlame,c.phone =kolom companyname, contactname
-e.lastname, e.title= kolom lastname dan title dari table e (employees) di pilih untuk di tampilkan

-From order o , customers c , employees e= untuk memilih tabel mana saja kolomnya di pilih untuk di tampilkan . orderys atau adalah nama tabel yang dipilih untuk ditampilkan  costomers atau  c adalah nama tabel yang di pilih untuk di tampilkan . employees atau e adalah nama tabel yang di pilih untuk di tampilkan.

-where - kondisi yang harus di penuhi oleh satu kolom data agar bisa di tampilkan

-(o.custid = c.customerID) = data pada kolom custid dalam tabel o (orders) harus sama dengan data pada kolom costomersID dalam table c (costomers).

-AND= untuk menyeleksi dia data atau lebih pada perintah where.

-(e.empid= e.Empid) = data pada kolom firstname dalam tabel e employees harus berisi data "margaret" agar bisa tempil.


## **2**

### Kode Program
```mysql
select customers.CustomersID, customers.CompanyName, orders.OrdersID,
orders.OrdersDate, ordersdetails.ProductID, products.ProductName, ordersdetails.Quantity AS Qty, ordersdetails.UnitPrice
FROM customers, orders, ordersdetails, products
WHERE customers.CustomersID= orders.CustID AND orders.OrdersID= ordersdetails.OrdersID
AND products.ProductID = ordersdetails.ProductID
order by customers.CustomersID;
```
### Hasil
![hasil2.png](asett/hasil2.png)
### Analisis
-select = untuk memilih kolom mana saja yang ingin ditampilkan  dan dari tabel mana kolom tersebut diambil.

-c.customerID ,  c.companyname = kolom customerID  dan companyname dari tabel c (customers) dipilih untuk ditampilkan.

-o.orderID,  o,orderDate = kolom orderID dan orderDate dari tabel p (orders) dipilih untuk ditampilkan 

-od.productID, od.Quantity, od.unitprice  = kolom productID, Quantity dan unitprict dan tabel ad (orderdetails) di pilih untuk di tampilkan.

-P.Productname = kolom productname  merupakan kolom dari tabel p (Products) yang di pilih untuk di tampilkan 

-od.Quantity AS  Qty = kolom Quentity di tampilkan sebagai nama sementaranya yaitu Qty. AS untuk mengubah nama suatu kolom secara sementara.

-FROM customers c. orders o, orderdetails od, products p = untuk memilih dari tabel mana sata yang kolamnya dipilih untur ditampilkan, customers atv C adalah nama tabel Yang dipilih untuk ditampilkan, orders atau o sabah nama tabel Yang dipilih untuk ditampilkan orderdetails atau ad adalah nama tabel yang dipilih untuk ditampilkan. Products atau  P adalah nama) tabel yang dipilih untuk ditampilkan.

-WHERE = Kondisi yang harus dipenuhi oleh suatu kolom data adar bisa ditampilka le curterere) (c.customerID = O.CustID) = data Pada kolom customerID dari tabel customers atau a harus sama dengan data Pada kolom CustID dari tabel orders atau o.

-AND = Untuk menyeleksi dua data atau lebih foda perintah WHERE.  (o.orderTD=od.orderID)=data Pada kolom orderID dari tabel orders atau o harus sama dengan data Pada kolom orderId dari tabel orderdetails atau od.

-AND = untuk menyeleksi dua data atau lebih Pada Perintah WHERE. (Product) (P. ProductID = od. ProductID) =data Pada kolom ProductID dari tabel Products atau P harus sama dengan data Poda kolom ProductID dan tabel ordendetails atau d

-order By c.customerID = untuk mengurut data berdasarkan kolom CustomerID dari tabel customers.


## **3**

### Kode Program
```mysql
select customers.CustomersID,  customers.CompanyName, orders.OrdersID AS OrdiD, orders.ordersDate,
     concat(employees.LastName, ', ', employees.FirstName) AS EmployeeName, ordersdetails.ProductID, ordersdetails.Quantity AS Qty
     FROM customers, orders, ordersdetails, products, employees
     where customers.CustomersID = orders.CustID AND orders.OrdersID      = ordersdetails.OrdersID
     AND  products.ProductID = ordersdetails.ProductID AND employees.Empld order BY orders.ordersID;
```

### Hasil
![hasill1.png](asett/hasill1.png)
![hasill2.png](asett/hasill2.png)
![hasill3.png](asett/hasill3.png)
![hasill4.png](asett/hasill4.png)
### Analisis
SELECT = untuk memilih kolom mana saja yang ingin ditampilkan dan digabungkan serta dari tabel mana kolom tersebut dipilih.

c. customerID, C. companyName = kolom customerID dan company Name dari tabel c(customers) dipilih untuk ditampilkan.

- o.OrderID AS ordID, o.OrderDate = kolom orderID dan OrderDate dari tabel!  o(orders) dipilih untuk ditampilkan. As merupakan Perintah untuk mengubah nama Suatu kolom secara sementara. Dalam hal ini Kolom order ID diubah namanya sementara mentid ordID

- CONCAT(e.LastName,'.', e.FirstName) AS EmployeeName = CONCAT adalah Perintah untur menggabungkan beberala kolom data menjadi satu kolom data. (e.LastName", e. First Name) merupakan kolom-kalam Yang ingin digabungkan LastName dan FirstName merupakan kolom dari tabel e(employees) Yang ingin didabung. ('.') merupakan separator atau Pemisah dari kedua kolom Yang ingin digabungkan. As Employee Name untuk mengubah hasil concat tadi menjadi Employee (namanya) untuk sementara.

- od.ProductID AS ProdID, od. Quantity AS Qty = kolom ProductID dan Quantiy dari tabel od(orderdetails), dipilih untuk ditampilkan. kolom ProductID namanya diubah sementara Jadi ProdID. kolom Quantity namanya diubah Sementara Jadi Qty.

- P. ProductName = kolom ProductName dari tabel P(Products) dipilih untuk ditampilkan. 
- From customers corders o, orderdetails od, Products P, employees e = untuk memilih dari tabel mana saja yang kolomnya dipilih untuk ditampilkan customers atau C adalah nama tabel yang dipilih. orders atau o adalah nama tabel Yong dißlih order details od adalah nama tabel Yang dipilih. Products atau P adalah nama tabel yang dipilih. employees atau e adalah nama tabel Yand dipilih.

- WHERE kondisi Yang harus dipenuhi oleh suatu kolom data ag ar bisa ditampilkan.
- (c.custornerID=o. costID )= data Pada kolom customerID dari tabel c(customers) harus sama dengan data Pada kolom CustID dari tabel o(orders)

- AND = untuk menyeleksi dua data atau lebih Pada Perintah WHERE.

- (o.OrderID = od orderID) = data Pada kolom orderID dari tabel o (orders) harus Sama dengan data Pada kolom order ID dari tabel od (orderdetails).

- AND = untuk menyeleksi dua data atau lebih Pada Perintah WHERE.

- (P.ProductID=od. ProductID) = data Pada kolom ProductID dari tabel PCProductID) harus sama dengan data Pada kolom ProductID dari tabel od (orderdetails)

- AND = untuk menyeleksi dua data atau lebih Pada Perintah WHERE.

- (e. EmPID = o. EmpID) = data Pada kolom EmpID  dari tabel e(employees) harus sama dengan data Pada kolom EmPID dari tabel o(orders).

- order By o. orderID = untuk mengurut data berdasarkan kolom orderID dari tabel orders.


  


