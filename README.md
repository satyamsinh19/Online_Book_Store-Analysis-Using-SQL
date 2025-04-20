# 📚 Online Bookstore Data Analysis using SQL

🎯 **Project Title**: SQL Project – Online Bookstore  
🗂️ **Datasets Used**: Books.csv, Customers.csv, Orders.csv  
🎓 **Focus**: Data extraction, aggregation, and business insights through SQL  

---

## 🧾 Project Overview

This project is a comprehensive SQL case study based on an **Online Bookstore** scenario. It simulates real-world business analysis tasks using three relational datasets:
- 📘 `Books.csv`: Book inventory details
- 👥 `Customers.csv`: Customer profiles
- 🛒 `Orders.csv`: Book purchases and transactions

The goal is to gain insights into book sales, customer behavior, and inventory status using SQL queries in **PostgreSQL**.

---

## 🗃️ Database Schema (Key Columns)

| Books.csv      | Customers.csv   | Orders.csv        |
|----------------|-----------------|-------------------|
| Book_ID (PK)   | Customer_ID (PK)| Order_ID (PK)     |
| Title          | Name            | Book_ID (FK)      |
| Genre          | Email           | Customer_ID (FK)  |
| Author         | Country         | Quantity          |
| Year_Published | City            | Total_Amount      |
| Price          |                 | Order_Date        |
| Stock          |                 |                   |

---

## 🔍 List of SQL Queries Executed

### 🟢 Basic Queries
1. Retrieve all books in the **"Fiction"** genre  
2. Find books published **after the year 1950**  
3. List all customers from **Canada**  
4. Show orders placed in **November 2023**  
5. Retrieve the **total stock** of books available  
6. Find the **details of the most expensive book**  
7. Show all customers who ordered **more than 1 quantity** of a book  
8. Retrieve all orders where the **total amount exceeds $20**  
9. List all **genres available** in the Books table  
10. Find the book with the **lowest stock**  
11. Calculate the **total revenue generated** from all orders  

---

### 🔵 Advanced Queries
1. Retrieve the **total number of books sold** for each genre  
2. Find the **average price** of books in the **"Fantasy"** genre  
3. List customers who have placed **at least 2 orders**  
4. Find the **most frequently ordered book**  
5. Show the **top 3 most expensive books** in the **"Fantasy"** genre  
6. Retrieve the **total quantity of books sold** by each author  
7. List the **cities** where customers who spent over **$30** are located  
8. Find the customer who **spent the most on orders**  
9. Calculate the **stock remaining** after fulfilling all orders  

---

## 🛠 Tools & Technologies

- 💻 PostgreSQL (Database and query execution)
- 🧠 SQL (Joins, Aggregation, Subqueries, Filtering, Date Functions)
- 📊 CSV files for relational schema
- 📁 Git & GitHub for version control and deployment

---

## 📂 Repository Structure
| File | Description |
|------|-------------|
| 'OnlineBookStore Analysis.sql` | PostgreSQL queries for all given queries |
| `Books.csv` | Dataset used for query execution |
| `Customers.csv` | Dataset used for query execution |
| `Orders.csv` | Dataset used for query execution |
| `OnlineBookStore Analysis.pdf` | Final submitted queries (PDF) |
| `README.md` | This project documentation |

---

## 🎓 Learning Highlights

- Mastered real-world SQL operations using normalized datasets
- Practiced multi-table joins, subqueries, aggregation, and date-based filtering
- Simulated reporting and business analytics use-cases in an e-commerce setting
- Enhanced data-driven thinking for inventory and customer analytics

---

## 🔗 Connect with Me

👤 **Satyam Kumar**  
🌐 www.linkedin.com/in/satyam-kumar-5a229222b  
📬 satyamkv123@gmail.com



