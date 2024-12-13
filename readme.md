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

(query)

