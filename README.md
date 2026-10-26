# Bookstore SQL Analysis
## Overview
A PostgreSQL project focused on managing and analyzing bookstore data using SQL queries, relational tables, and data aggregation.
## Database Tables
- **Books:** Book titles, authors, genres, publication years, prices, and stock.
- **Customers:** Customer names, contact information, cities, and countries.
- **Orders:** Customer orders, book references, order dates, quantities, and total amounts.
## Key SQL Concepts
- DDL: Creating and managing tables
- Data Import: Loading CSV files into PostgreSQL
- Filtering and Sorting: WHERE, ORDER BY, LIMIT
- Aggregations: SUM, AVG, COUNT
- Joins: Combining books, customers, and orders
- Grouping: GROUP BY and HAVING
- Subqueries and analytical queries
- Inventory and revenue analysis
## Business Questions Answered
- Which books are the most expensive?
- What is the total sales revenue?
- Which genres sell the most books?
- Which customers place multiple orders?
- Which books are ordered most frequently?
- Which customers spend the most?
- How much stock remains after fulfilling orders?
## Tools & Technologies
- PostgreSQL
- SQL
- pgAdmin
- CSV datasets
## Project Structure
- `bookstore_analysis.sql` — Table creation, data import statements, and analytical queries.
- `data/books.csv` — Book records.
- `data/customers.csv` — Customer records.
- `data/orders.csv` — Order records.
## How to Run
1. Install PostgreSQL and open pgAdmin.
2. Create a database named `bookstore_db`.
3. Open `bookstore_analysis.sql` in the SQL editor.
4. Update the CSV file paths in the COPY statements to match your local environment.
5. Execute the table creation statements first.
6. Import the CSV files into their corresponding tables.
7. Run the analytical queries and review the results.
## Objective
To develop practical SQL skills and extract meaningful insights about bookstore sales, customer purchasing behavior, and inventory management.
