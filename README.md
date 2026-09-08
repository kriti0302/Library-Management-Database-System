# Library Management Database System

## 📌 Project Overview

The Library Management Database System is a MySQL-based database project developed to manage library books, members, employees, branches, and book issue/return transactions.

The system demonstrates relational database concepts such as primary keys, foreign keys, constraints, SQL joins, stored procedures, views, and analytical queries.

## 🎯 Objectives

- Manage library books and their availability.
- Maintain member records.
- Manage library branches and employees.
- Record book issue and return transactions.
- Identify overdue books.
- Generate issued and available book reports.
- Perform SQL-based library analytics.
- Demonstrate stored procedures and database views.

## 🛠️ Technologies Used

- MySQL
- MySQL Workbench
- SQL
- EER Diagram / ER Modeling

## 🗄️ Database Structure

Database name:

`library_management`

### Main Tables

1. `branches`
2. `employees`
3. `members`
4. `books`
5. `transactions`

### Relationships

- Employees are associated with library branches.
- Transactions are associated with books.
- Transactions are associated with members.

## 🔑 Key Features

### Book Management
Stores book information including:

- ISBN
- Title
- Category
- Author
- Publisher
- Publication year
- Rental price
- Availability status

### Member Management
Maintains:

- Member ID
- Member name
- Email
- Phone
- Address
- Membership date

### Issue and Return Management

The system provides stored procedures for:

- Issuing books
- Returning books

Book availability is updated automatically during issue and return operations.

### Overdue Book Analysis

The system identifies books whose due dates have passed and calculates the number of overdue days.

### Reports

Two database views are included:

- `issued_books_report`
- `available_books_report`

These provide quick access to current library status.

## 📊 SQL Queries and Analysis

The project demonstrates queries for:

- Available books
- Issued books
- Overdue books
- Books by category
- Availability statistics
- Members who never issued books
- Most frequently issued books
- Rental value analysis
- Employees by branch

## 📁 Project Files

- `library_management.sql` — Complete database script
- `PROJECT_REPORT.pdf` — Project report
- `README.md` — Project documentation
- `screenshots/` — Project execution and work evidence

## ▶️ How to Run

1. Install MySQL and MySQL Workbench.
2. Open `library_management.sql`.
3. Connect to your MySQL server.
4. Execute the complete SQL script.
5. The `library_management` database and required tables will be created automatically.
6. Run the sample queries to view the results.

## 📸 Project Evidence

Screenshots demonstrate:

- Successful database execution
- Library reports
- Overdue book analysis
- Book return operation
- Return verification
- EER diagram

## 👩‍💻 Author

**Your Name**

## 🔗 Project Link

GitHub Repository:  
Add your GitHub repository link here.

## 📄 License

This project was developed for educational/internship purposes.
