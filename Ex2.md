# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## Date:

## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/d1d158c0-c4c4-4f39-a151-d867a28615d6)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/be5005b2-3038-47ca-b876-7d099eb518f3)

### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/a06870a3-12c0-49bb-8e3d-2e7b24265724)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/3fecaa8b-3207-40c9-9c3e-349e5bb17556)

### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/b06e944a-9855-4949-bac8-9436e7de0b0e)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/af8d0a5b-2984-4e17-aa3c-3414f338c531)

### Q5)	List the names of Clerks from emp table.


### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/5f905e11-5dd5-456e-8812-9ddadbbeaf30)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/0b00e35a-153d-4c94-afaa-68ff5d157d4b)


### Q6)	List the names of employee who are not Managers.


### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/f952b828-5117-465f-b7e1-382d21531f42)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/e58d897d-3498-401d-924d-a5af07f1be36)


### Q7)	List the names of employees not eligible for commission.


### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/ba83f3cf-33bd-407a-9093-d2a28bff4ede)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/d2936e63-9da9-40fd-9e6a-688d5956a2ef)


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/f1068827-0c3b-4f4e-9fa2-37e790f84fdb)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/4e9e693e-ccad-43d6-9ede-3fb3989746c6)


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/b4b88d5c-f490-4046-9109-ba6e206b8b2c)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/5d04d384-0765-4a9f-a34c-f03b4434d9ea)


### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/c6ee3498-b0ad-4e78-a07b-ff6703990a5c)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/cc4a4c64-567e-4dfc-9988-d20c49bb8c62)


### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/75f45745-f4aa-4549-9c45-55317762e282)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/d6123c23-0f20-45b1-853e-10cd0230deab)


### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/d0176374-d088-4c5f-85af-b04c9d85c22a)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/3025ae46-f5ad-4836-b63c-26f30f04b57e)

### Q13) Find number of rows in the table EMP

### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/568e7913-e09f-49c6-96df-7cb40f8acf43)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/318270c0-c1ab-4cee-b751-36f268246487)


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/702a0ff9-2d68-47c1-8e84-1fbd94ba4f3a)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/246f8fd2-48cb-46b6-8d6b-39a417ef22b9)


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/a49cae81-af00-4efd-a200-279b3fa322b6)


### OUTPUT:
![image](https://github.com/kanishka2305/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497357/31e1f84a-8e3f-47e6-83b2-6901dffabc29)

## Result:
Thus the Data Manipulation Language (DML) Commands and built in functions in SQL
