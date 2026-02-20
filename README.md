# SQL Project – Online Book Store Database

## Project Overview
The **Online Book Store SQL Project** is a database design and analytics project that demonstrates the implementation of a relational database system for managing an online bookstore.  

This project focuses on designing structured database tables, importing real-world datasets, and performing analytical SQL queries to generate meaningful business insights.

The system simulates real-world bookstore operations such as managing books, customers, and orders while ensuring data consistency through relational modeling.

---

## Project Objectives
- Design a normalized relational database schema
- Implement primary and foreign key relationships
- Import structured data using CSV files
- Perform business analytics using SQL queries
- Extract actionable insights from transactional data

---

## Database Schema

The database consists of **three main tables**:

### 📖 Books
Stores detailed information about books:
- Book ID (Primary Key)
- Title
- Author
- Genre
- Published Year
- Price
- Stock Quantity

### Customers
Contains customer-related details:
- Customer ID (Primary Key)
- Name
- Email
- Phone Number
- City
- Country

### Orders
Tracks purchase transactions:
- Order ID (Primary Key)
- Customer ID (Foreign Key)
- Book ID (Foreign Key)
- Order Date
- Quantity
- Total Amount

Relational integrity is maintained using **primary and foreign key constraints**.

---

## Data Import Process
Data was imported using CSV datasets:
- `Books.csv`
- `Customers.csv`
- `Orders.csv`

The import process ensured:
- Correct column mapping
- Clean and structured data loading
- Data validation before analysis

---

## SQL Operations Performed

### ✅ Basic Queries
- Retrieve books by genre
- Filter customers by country
- View orders within specific date ranges

### 📊 Aggregate Analysis
- Total revenue calculation
- Available stock summary
- Genre-wise average book price
- Total books sold

### 🔗 Joins & Relational Analysis
- Best-selling books
- High-value customers
- Customer purchase patterns
- Remaining inventory after sales
- Genre-wise sales performance

### 🚀 Advanced Queries
- Top 3 most expensive fantasy books
- Customers with multiple orders
- Most frequently ordered book
- Customers exceeding spending thresholds

---

## Business Insights Generated
- Identification of top-selling books
- Revenue contribution analysis
- Customer purchasing behavior
- Sales distribution across genres
- Inventory tracking after transactions
- High-value customer segmentation

---

## Technologies Used
- **SQL (MySQL / SQL-based RDBMS)**
- Relational Database Design
- CSV Data Handling
- Data Analysis using SQL Queries

---

## Skills Demonstrated
- Database Design & Normalization
- Schema Creation
- Data Import & Validation
- SQL Query Optimization
- Joins (INNER JOIN, LEFT JOIN)
- GROUP BY & HAVING Clauses
- Aggregations & Analytical Queries
- Business Data Analysis

---


---

## How to Run the Project

1. Create a new database in MySQL.
2. Open the SQL file:
3. 3. Execute the script to:
- Create tables
- Define relationships
- Load data
4. Run the provided SQL queries to perform analysis.

---

## Use Case
This project demonstrates how SQL can be used for **real-world business analytics**, helping organizations understand sales trends, customer behavior, and inventory management in an online retail environment.

---

## 🚀 Future Enhancements
- Stored Procedures & Triggers
- Index Optimization
- Dashboard integration (Power BI / Tableau)
- Advanced customer segmentation
- Automated reporting queries

---

# 📬 Contact

👨‍💻 **Chanchal Vijay Bhangale**  
📧 Email: chanchalbhangale83@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/chanchal-vijay-bhangale  
💻 GitHub: https://github.com/Chanchal7136
