\#SQL Window Functions \& CTE Practice Queries

📌 Introduction

This repository contains a collection of SQL Window Function and CTE practice queries designed to improve understanding of advanced SQL analytical operations using a sample database consisting of:



Employees

Customers

Orders

The queries focus mainly on:



✅ SQL Window Functions ✅ Ranking Functions ✅ Running Totals \& Moving Averages ✅ LAG() \& LEAD() Analysis ✅ CTEs (Common Table Expressions) ✅ Recursive CTEs ✅ Interview-Oriented SQL Practice



🗂️ Database Schema

👨‍💼 Employees Table

Column Name	Description

employee\_id	Primary Key

employee\_name	Employee Name

department	Employee Department

manager\_id	Reporting Manager

salary	Employee Salary

hire\_date	Employee Hiring Date

👥 Customers Table

Column Name	Description

customer\_id	Primary Key

customer\_name	Customer Name

city	Customer City

🛒 Orders Table

Column Name	Description

order\_id	Primary Key

customer\_id	Foreign Key referencing Customers

employee\_id	Foreign Key referencing Employees

order\_date	Order Date

total\_amount	Total Order Amount

🔗 Database Relationships

Employees

&#x20;   ↑

&#x20;   |

&#x20; Orders

&#x20;   |

&#x20;   ↓

Customers

📚 SQL Concepts Covered

✅ ROW\_NUMBER()

Assign unique row numbers to rows.



✅ RANK()

Assign ranking with skipped ranks.



✅ DENSE\_RANK()

Assign ranking without skipping ranks.



✅ PARTITION BY

Perform calculations within groups.



✅ Running Totals

Calculate cumulative totals over ordered rows.



✅ Moving Averages

Calculate rolling averages over rows.



✅ LAG()

Access previous row values.



✅ LEAD()

Access next row values.



✅ NTILE()

Divide rows into equal buckets/groups.



✅ Common Table Expressions (CTEs)

Create temporary result sets for complex queries.



✅ Recursive CTEs

Handle hierarchical and recursive data operations.



📊 Topics Practiced

ROW\_NUMBER()

RANK()

DENSE\_RANK()

PARTITION BY

Running Totals

Moving Averages

LAG()

LEAD()

NTILE()

Aggregate Window Functions

CTEs

Recursive CTEs

Employee Ranking

Customer Sales Analysis

Department-wise Analytics



\#Technologies Used

MySQL

SQL

Window Functions

CTEs

Relational Database Concepts

\#Learning Outcomes

\-Window Functions in SQL 

\-Ranking and Analytical Queries 

\- Running Totals \& Moving Averages 

\- LAG() and LEAD() operations 

\- Common Table Expressions (CTEs) 

\- Recursive Queries 

\- Department-wise Analysis 

\- Real-world SQL Reporting 

\- SQL Interview Preparation





