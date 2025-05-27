# 📚 Online Bookstore SQL Project

This project is a comprehensive SQL-based analysis of an **Online Bookstore** using **PostgreSQL**. It involves designing a relational schema, importing datasets, and executing various SQL queries to extract meaningful insights from the data.

---

## 📂 Dataset Overview

The project uses three CSV files representing core entities of an online bookstore:

- **Books.csv** – Contains book details:  
  `Books(Book_ID, Title, Author, Genre, Published_Year, Price, Stock)`

- **Customers.csv** – Stores customer information:  
  `Customers(Customer_ID, Name, Email, Phone, City, Country)`

- **Orders.csv** – Captures order records:  
  `Orders(Order_ID, Customer_ID, Book_ID, Order_Date, Quantity, Total_Amount)`

These datasets were imported into PostgreSQL using `COPY` or `\copy`.

---

## 🧾 SQL Queries

### ✅ Basic Queries
1. Retrieve all books in the **"Fiction"** genre  
2. Find books published **after the year 1950**  
3. List all customers from **Canada**  
4. Show orders placed in **November 2023**  
5. Retrieve the **total stock** of books available  
6. Find details of the **most expensive book**  
7. Show all customers who ordered **more than 1 quantity** of a book  
8. Retrieve all orders where the **total amount exceeds $20**  
9. List all **genres** available in the Books table  
10. Find the book with the **lowest stock**  
11. Calculate the **total revenue** generated from all orders  

---

### 🚀 Advanced Queries
1. Retrieve the **total number of books sold per genre**  
2. Find the **average price** of books in the **"Fantasy"** genre  
3. List customers who have placed **at least 2 orders**  
4. Find the **most frequently ordered book**  
5. Show the **top 3 most expensive books** of the **"Fantasy"** genre  
6. Retrieve the **total quantity** of books sold by each **author**  
7. List the **cities** of customers who spent **over $30**  
8. Find the customer who **spent the most** on orders  
9. Calculate the **remaining stock** after fulfilling all orders  

---

## 🛠️ Tools & Technologies

- **PostgreSQL** (Database engine)
- **pgAdmin 4** (GUI client for PostgreSQL)
- **CSV** (Comma-separated values for data import/export)

---

## 📌 Key Takeaways

- Practical experience with SQL data import and relational schema design
- Real-world querying using `SELECT`, `JOIN`, `GROUP BY`, `ORDER BY`, subqueries, aggregate functions, and conditional filtering
- Demonstrated ability to perform both analytical and operational data tasks

---

## 📁 Repository Structure

📦 Online-Bookstore-SQL-Project
├── 📄 Books.csv
├── 📄 Customers.csv
├── 📄 Orders.csv
├── 📄 Basic_Queries.sql
├── 📄 Advanced_Queries.sql
└── 📄 README.md

