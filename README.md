# Music Store Data Analysis Project using SQL

## Overview

This project focuses on analyzing a digital music store database using SQL queries. The objective is to solve real-world business problems related to customers, sales, artists, genres, invoices, and employee data.

The project demonstrates practical SQL skills such as:

* Data filtering and sorting
* Aggregate functions
* Joins and subqueries
* Common Table Expressions (CTEs)
* Business insights generation
* Advanced SQL analysis

## Project Files

* `Music_Store_Query.sql` → Contains all SQL queries used for analysis.
* `album2.csv` → Dataset file used in the project.

## Database Concepts Used

* SELECT Statements
* WHERE Clause
* GROUP BY & ORDER BY
* Aggregate Functions (`SUM`, `COUNT`, `AVG`)
* INNER JOIN
* Subqueries
* Common Table Expressions (CTEs)
* LIMIT

## Business Questions Solved

### Easy Level Queries

* Find the senior most employee based on job title.
* Identify countries with the highest number of invoices.
* Find top invoice totals.
* Determine the city generating maximum revenue.
* Identify the best customer based on spending.

### Moderate Level Queries

* Find Rock music listeners.
* Identify top Rock music artists.
* Find tracks longer than average song duration.

### Advanced Level Queries

* Calculate customer spending on artists.
* Analyze artist-wise revenue generation.
* Generate deeper customer and sales insights.

## Tools & Technologies

* SQL
* MySQL / PostgreSQL / SQLite
* CSV Dataset
* GitHub

## Key Learnings

Through this project, I improved my understanding of:

* Writing optimized SQL queries
* Handling relational databases
* Extracting business insights from raw data
* Using joins and subqueries efficiently
* Performing advanced data analysis using SQL

## Sample SQL Query

```sql
SELECT customer.customer_id, first_name, last_name, SUM(total) AS total_spending
FROM customer
JOIN invoice ON customer.customer_id = invoice.customer_id
GROUP BY customer.customer_id
ORDER BY total_spending DESC
LIMIT 1;
```

## Project Outcome

This project helped in strengthening practical SQL and data analysis skills by solving business-oriented problems using structured query language.

## Author

**Yash Chauhan**

## Connect With Me

LinkedIn:www.linkedin.com/in/yashchauhan06







