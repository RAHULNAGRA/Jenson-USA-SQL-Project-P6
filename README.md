# Jenson-USA-SQL-Analysis-Project-P6

## Overview

This project focuses on analyzing Jenson USA's dataset to extract insights on customer behavior, staff performance, inventory management, and store operations through SQL queries. The analysis aims to inform strategic decisions and enhance operational efficiency.

## Dataset Link: 
https://drive.google.com/drive/folders/1feFkClnYME7Be3kjmz-TD2PV1uVkXNAN



The dataset includes information about products, customers, orders, staff, and sales.

## Queries

The analysis involves executing the following SQL queries:

1. Find the total number of products sold by each store along with the store name.
2. Calculate the cumulative sum of quantities sold for each product over time.
3. Find the product with the highest total sales (quantity * price) for each category.
4. Find the customer who spent the most money on orders.
5. Find the highest-priced product for each category name.
6. Find the total number of orders placed by each customer per store.
7. Find the names of staff members who have not made any sales.
8. Find the top 3 most sold products in terms of quantity.
9. Find the median value of the price list. 
10. List all products that have never been ordered.(use Exists)
11. List the names of staff members who have made more sales than the average number of sales by all staff members.
12. Identify the customers who have ordered all types of products (i.e., from every category).


## MySQL Features Used

The following MySQL features were utilized to execute the queries:

- **SELECT Statement**: To retrieve specific columns and data from the database.
- **JOIN Operations**: To combine rows from different tables based on related columns for comprehensive analysis.
- **GROUP BY**: To aggregate data for calculations like totals and averages.
- **HAVING Clause**: To filter groups based on aggregate functions, ensuring accurate analysis.
- **COUNT() Function**: To count the number of records or rows that meet specified criteria.
- **SUM() Function**: To calculate the total sales and quantities.
- **CROSS JOIN and EXISTS**: To handle queries that require checking for conditions across multiple tables.
- **MEDIAN Calculation**: To determine the middle value in a set of prices.
- **Subqueries**: To execute complex queries that depend on results from other queries.

## Technologies Used

- **SQL**: For querying and analyzing data.
- **Google Drive**: For dataset storage and access.
- **GitHub**: For version control and collaboration.

## Installation

To run the SQL queries locally, follow these steps:

1. Download the dataset from the provided link.
2. Import the dataset into your SQL database management system.
3. Execute the SQL queries to perform the analysis.

