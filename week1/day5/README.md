\#SQL Window Functions \& Advanced Analytics Practice

📌 Introduction

This repository contains a collection of SQL Window Function and Analytical Queries designed to improve understanding of advanced SQL concepts using a sample academic database consisting of:



Students

Departments

Staff

Subjects

Marks

The queries focus mainly on:



\-Window Functions 

\- Ranking Functions 

\- Running Totals \& Moving Averages 

\- Analytical SQL Queries 

\- Department-wise \& Subject-wise Analysis 

\- Interview-Oriented SQL Practice



🗂️ Database Schema

👨‍🎓 Student Table

Column Name	Description

student\_id	Primary Key

student\_name	Student Name

department\_id	Foreign Key referencing Department

cgpa	Student CGPA

admission\_year	Year of Admission

city	Student City

🏢 Department Table

Column Name	Description

department\_id	Primary Key

department\_name	Department Name

👨‍🏫 Staff Table

Column Name	Description

staff\_id	Primary Key

staff\_name	Staff Name

department\_id	Foreign Key referencing Department

salary	Staff Salary

hire\_date	Staff Hiring Date

📘 Subject Table

Column Name	Description

subject\_id	Primary Key

subject\_name	Subject Name

staff\_id	Foreign Key referencing Staff

📝 Mark Table

Column Name	Description

mark\_id	Primary Key

student\_id	Foreign Key referencing Student

subject\_id	Foreign Key referencing Subject

exam\_type	Exam Type

exam\_date	Exam Date

marks	Student Marks

🔗 Database Relationships

Departments

&#x20;   ↑

&#x20;   |

&#x20; Students

&#x20;   |

&#x20;   ↓

&#x20;  Marks

&#x20;   ↑

&#x20;   |

&#x20; Subjects

&#x20;   ↑

&#x20;   |

&#x20;  Staff

📚 SQL Concepts Covered

\- ROW\_NUMBER()

Assign unique row numbers to records.



\- RANK()

Assign ranking with skipped ranks for duplicates.



\- DENSE\_RANK()

Assign ranking without skipping ranks.



\- NTILE()

Divide rows into equal groups/buckets.



\- PERCENT\_RANK()

Calculate percentage ranking of rows.



\- CUME\_DIST()

Calculate cumulative distribution of rows.



\- LAG()

Access previous row values.



\- LEAD()

Access next row values.



\- Running Totals

Calculate cumulative sums.



\- Moving Averages

Calculate cumulative averages over ordered data.



\- Analytical Reporting

Generate advanced reports using window functions.



📊 Topics Practiced

ROW\_NUMBER()

RANK()

DENSE\_RANK()

LAG()

LEAD()

NTILE()

PERCENT\_RANK()

CUME\_DIST()

Running Totals

Moving Averages

Department-wise Analysis

Subject-wise Analytics

Ranking Queries

Cumulative Calculations



🛠️ Technologies Used

MySQL

SQL

Window Functions

Relational Database Concepts



🎯 Learning Outcomes

By completing these analytical SQL queries, you will gain practical understanding of:



\- Window Functions in SQL 

\- Ranking and Distribution Functions 

\- Analytical SQL Reporting 

\- Running Totals \& Moving Averages 

\- Department-wise Data Analysis 

\- Advanced SQL Problem Solving

\- Real-world SQL Analytics 

\- SQL Interview Preparation





