Retail Sales Analysis Using SQL

📘 Project Description

** This project focuses on performing a comprehensive retail sales analysis using SQL.
It covers the complete workflow — from database creation, data cleaning, and exploratory analysis, to answering key business questions based on sales data.

** The main objective is to extract actionable insights that can help businesses improve sales strategy, understand customer behavior, and identify top-performing categories and time periods.

🧾 Project Summary

. Domain: Retail / Data Analytics

. Tools Used: MySQL / SQL Server / PostgreSQL

. Dataset: Retail transactions dataset with 11 attributes

. Objective: Analyze customer transactions and derive business insights through SQL queries

📊 Dataset Details

| Column Name      | Description                         |
| ---------------- | ----------------------------------- |
| `transaction_id` | Unique ID for each sale transaction |
| `sale_date`      | Date on which the sale occurred     |
| `sale_time`      | Time of transaction                 |
| `customer_id`    | Unique customer identifier          |
| `gender`         | Gender of the customer              |
| `age`            | Customer’s age                      |
| `category`       | Product category                    |
| `quantity`       | Quantity sold                       |
| `price_per_unit` | Price of each item                  |
| `cogs`           | Cost of goods sold                  |
| `total_sale`     | Total sale amount per transaction   |

🧠 Objectives of the Analysis

1. Create and manage a retail sales database.

2. Clean and validate sales data.

3. Perform exploratory analysis to understand customer and sales patterns.

4. Solve real-world business queries using SQL.

5. Identify key sales trends across time, gender, and category.

⚙️** Project Workflow**

1. **Database and Table Creation**

    A. Created a new schema named retail_schema.
  
    B. Defined a table retail_sales with appropriate data types and constraints.
  
    C. Imported raw transactional data.

2. **Data Cleaning**

    A. Checked for NULL or missing values in all columns.
  
    B. Removed or filtered incomplete transactions.

3. **Exploratory Analysis**
  
    A. Performed descriptive queries to:
  
    B. Count total sales and customers
  
    C. Identify unique product categories
  
    D. Explore customer demographics

4. **Business Questions Solved**

  -- Data Analysis & Business Key Problems & Answers

  -- My Analysis & Findings

  -- Q.1 Write a SQL query to retrieve all columns for sales made on '2022-11-05

  -- Q.2 Write a SQL query to retrieve all transactions where the category is 'Clothing' and the quantity sold is more than 10 in the month of Nov-2022

  -- Q.3 Write a SQL query to calculate the total sales (total_sale) for each category.

  -- Q.4 Write a SQL query to find the average age of customers who purchased items from the 'Beauty' category.

  -- Q.5 Write a SQL query to find all transactions where the total_sale is greater than 1000.

  -- Q.6 Write a SQL query to find the total number of transactions (transaction_id) made by each gender in each category.

  -- Q.7 Write a SQL query to calculate the average sale for each month. Find out best selling month in each year

  -- Q.8 Write a SQL query to find the top 5 customers based on the highest total sales 

  -- Q.9 Write a SQL query to find the number of unique customers who purchased items from each category.

  -- Q.10 Write a SQL query to create each shift and number of orders (Example Morning <=12, Afternoon Between 12 & 17, Evening >17)
