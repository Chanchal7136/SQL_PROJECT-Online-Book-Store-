# SQL_PROJECT-Online-Book-Store-
Project Overview : 
This project demonstrates the design and implementation of a complete SQL database system for an Online Bookstore. It includes creating relational tables, importing data from CSV files, and performing analytical SQL queries to extract meaningful business insights.
The project is ideal for showcasing SQL skills such as schema design, joins, grouping, data import, and reporting.

#  Database Structure

## The system contains three main tables

🔹 Books

Stores book information such as:

Title

Author

Genre

Published Year

Price

Stock

🔹 Customers

Contains customer details:

Name

Email

Phone

City

Country

🔹 Orders

Tracks all purchases:

Customer ID (Foreign Key)

Book ID (Foreign Key)

Order Date

Quantity

Total Amount
      
Primary and foreign keys ensure data consistency and clean relationships between tables.



# Data Import

The dataset was manually uploaded using CSV files for:

Books

Customers

Orders

This approach helped ensure correct column mapping and clean data import.




# Key SQL Operations :

## Basic Queries

Retrieve books by genre

Filter customers by country

View orders for specific dates

## Aggregate Functions

Total stock available

Total revenue generated

Average book price (genre-wise)

## Joins & Analysis

Best-selling books

Most valuable customers

Cities of customers who spent more than a specific amount

Stock remaining after sales

Genre-wise number of books sold

## Advanced Queries

Top 3 most expensive Fantasy books

Customers with at least 2 orders

Most frequently ordered book




# Business Insights Generated 

Which books sell the most

Which customers buy most frequently

Total sales revenue

Stock availability after fulfilling orders

Sales distribution across genres

Customer spending patterns



# Skills Demonstrated 

SQL database design

Normalization and relationships

Importing and validating CSV data

Writing analytical SQL queries

Joins (INNER, LEFT JOIN)

GROUP BY and HAVING

Sorting and filtering data

Real-world problem-solving with SQL




