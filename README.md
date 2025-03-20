# Data-Analysis-with-SQL-Inform-a-Business-Decision


This project demonstrates how a data analyst uses SQL to inform business decisions. 

## Project Overview
In this project, I worked on analyzing sales data from the Northwind database using SQL queries. The primary objective was to calculate sales for each order and summarize them in a way that can inform business decisions. 
The tasks involved joining multiple tables, calculating sales per order, and displaying the data in a format that can help make business decisions.

## Steps Taken

### 1. **A Look at the Business Question and the Suggested Solution**
  
   - Our Business Question/Problem: To increase future sales, the company has decided to give employees bonuses for exemplary performance in sales.
     Bonuses will be awarded to employees responsible for the five highest order amounts. 

How can we identify those employees? Proposed Solution: A list of employees who have orders with the five highest sales amounts
   - Explored tables in the database

### 2. Determine which tables and fields will be needed
   - [4397]()
   - [4398]()
   - [4399]()
   - [4300]()
   - [4401]()

### 3. **Joining Tables Together in SQL to Obtain Data for Analysis**
   - To retrieve the necessary data, I joined multiple tables in SQL, including the `Employees`, `Orders`, `OrderDetails`, and `Products` tables and used ORDER BY
   - [4405]()

### 4. **Calculate and Summarize Sales for Each Order**
   - In this query, I calculated the total sales amount for each order by joining the Employees, Orders, OrderDetails, and Products tables
     and used GROUP BY to group the results by employee name and order ID.
   - [4406]()
  

### 5. **Displaying the Top Results**
   - To focus on the top sales performers, I used the `SELECT TOP 5` query to retrieve the top 5 employees with the highest sales.
   - [4409]()


## Conclusion
This project gave me a comprehensive understanding of how SQL can be used to perform data analysis that supports business decisions. 
By joining multiple tables, calculating sales data, and organizing the results, I was able to display the key insights in a format that would be useful for business stakeholders.


