# Bank-Database-Management-System

## Project Overview
This project is a Bank Database Management System designed to keep track of customer transactions, employee details, branch information, and loan data. It demonstrates the use of MySQL operations such as CREATE, READ, UPDATE, and DELETE to manage and maintain banking operations efficiently.

## 🏆 Abstract
The Bank Database Management System project aims to create a structured system for handling customer and employee data, transactions, and loans within a bank. It supports operations such as account creation, balance checking, deposits, withdrawals, and updating customer details. The system ensures smooth and secure financial operations using MySQL.

## 🎯 Objective
Build an organized and interactive system for managing customer and employee details.

Track customer accounts, balances, and deposits.

Provide insight into loans taken by customers.

Enable customers to update personal information like address and contact details.

Ensure efficient and secure handling of financial operations.


## 📌 Features
✅ Employee Registration

✅ Customer Account Creation

✅ Credit and Debit Transactions

✅ Balance Inquiry

✅ Loan Management (Approval and Tracking)

✅ Branch Transfers

✅ Online Data Updates


## 📊 ER Diagram
The project uses a relational model with the following entities:

Customer – Contains customer details such as ID, name, address, mobile number, etc.

Account – Stores account information like balance, type, and status.

Branch – Holds branch-specific details including branch ID, location, and name.

Loan – Manages loan data including type, amount, and issue date.

## 🏦 Database Structure
## 1. ACCOUNT
Column	Data Type	Description

Acc_id	INT	Unique account ID

Cust_id	INT	Associated customer ID

Balance	FLOAT	Account balance

Acc_type	VARCHAR	Type of account (e.g., savings, current)

Acc_status	VARCHAR	Status of the account (active/inactive)

## 2. BRANCH
Column	Data Type	Description

Branch_id	INT	Unique branch ID

Branch_name	VARCHAR	Branch name

Location	VARCHAR	Branch location

## 3. LOAN
Column	Data Type	Description

Loan_id	INT	Unique loan ID

Cust_id	INT	Associated customer ID

Loan_amount	FLOAT	Loan amount

Loan_type	VARCHAR	Type of loan

Date_issued	DATE	Date of loan approval

## 4. CUSTOMER
Column	Data Type	Description

Cust_id	INT	Unique customer ID

First_name	VARCHAR	Customer's first name

Last_name	VARCHAR	Customer's last name

Address	VARCHAR	Customer's address

Mob_no	VARCHAR	Customer's mobile number


## 🔎 Key SQL Operations
## ➡️ Basic Queries
Add new customer details

Update customer records

Delete customer details

## ➡️ JOINS
LEFT JOIN – Display records of customers with an associated account 

RIGHT JOIN – Display records of accounts without matching customers

INNER JOIN – Display details of customers with an account

CROSS JOIN – Create a cross-relationship between customer and account

## ➡️ Aggregate Functions
Average, Minimum, Maximum, and Sum of account balances

Count of customer records

## ➡️ Filtering & Sorting
ORDER BY – Sort records by name or balance

DISTINCT – Remove duplicate records

LIMIT – Return a specific number of records

## ➡️ Advanced Operations
LIKE – Search customers by partial name

HAVING – Filter records based on aggregated data

Subqueries – Display customers with loan amounts above average

## 🚀 Usage
Open MySQL Workbench or terminal.

Load the schema.

Execute provided SQL queries to perform banking operations.


## 📝 Conclusion
This project successfully implements a Bank Database Management System using MySQL, allowing for secure handling of customer and employee data. The project efficiently manages financial transactions, customer updates, and loan records, ensuring smooth and secure banking operations.

