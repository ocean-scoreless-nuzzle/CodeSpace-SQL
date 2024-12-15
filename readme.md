#SQL Practical

question 1

select employee_id, employee_name, department_id, hire_date, salary from Employee

! [question 1 image result](/img/question_1.png)

question 2

select department_name from Department

![question 2 image result](/img/question_2.png)

question 3

select employee_name, salary from Employee order by salary desc
![question 3 image result](/img/question_3.png)

question 4

select product_id, product_name, price, stock_quantity from Product where price >= 100 and price <= 500
![question 4 image result](/img/question_4.png)

question 5

select Purchase.order_id, Purchase.order_date, Employee.employee_name
from Purchase 
INNER JOIN Employee on Purchase.employee_id = Employee.employee_id
where Employee.department_id = 4

![question 5 image result](/img/question_5.png)

question 6

select product_id, product_name, price, stock_quantity
from Product
where product_name like '%chair%'

![question 6 image result](/img/question_6.png)

question 7

select order_id, employee_id, product_id, order_date, quantity
from Purchase
where employee_id in ('1','3','5')

![question 7 image result](/img/question_7.png)

question 8

select order_id, 

![question 8 image result](/img/question_8.png)

question 9

select order_id,

![question 9 image result](/img/question_9.png)

question 10

select order_id, 

![question 10 image result](/img/question_10.png)