# SQL-
Create and Inserting data
Create Database SQLTUTORIAL;
USE SQLTUTORIAL;

Creating Table
CREATE TABLE EmployeeDemographics
(
EmployeeID INT,
FirstName Varchar(50).
LastName Varchar(50),
Age INT,
Gender Varchar(50);

CREATE TABLE EmployeeSalary
(
EmployeeID INT,
JobTitle Varchar(50).
Salary INT;

----Inserting values into the table----
INSERT INTO EmployeeDemographics Values(1001,'Jim', 'Halpert',30,'Male'),
(1002,'Pam', 'Beasley',30,'Female'),
(1003,'Dwight', 'Schrute',29,'Male'),
(1004,'Angela', 'Martin',31,'Female'),
(1005,'Toby', 'Flenderson',32,'Male'),
(1006,'Michael', 'Scott',35,'Male'),
(1007,'Meredith', 'Plamer',32,'Female'),
(1008,'Stanley', 'Hudson',38,'Male'),
(1009,'Kevin', 'Malone',31,'Male');

Select * from EmployeeDemographics;

INSERT INTO EmployeeSalary Values (1001, 'Salesman', 45000),
(1002, 'Reciptionist', 36000),
(1003, 'Salesman', 63000),
(1004, 'Accountant', 47000),
(1005, 'HR', 50000),
(1006, 'Regional Manager', 65000),
(1007, 'Supplier realtions', 41000),
(1008, 'Salesman', 48000),
(1009, 'Accountant', 42000);

Select * from Employeesalary;

