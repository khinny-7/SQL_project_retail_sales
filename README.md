# Retail Sales Analysis SQL Project Tutotial

## Project Overview


## Objectives

1. **Set up a retail sales database**: Create and populate a retail sales database with the provided sales data.
2. **Data Cleaning**: Identify and remove any records with missing or null values.
3. **Exploratory Data Analysis (EDA)**: Perform basic exploratory data analysis to understand the dataset.
4. **Business Analysis**: Use SQL to answer specific business questions and derive insights from the sales data.

## Project Structure

### 1. Database Setup

- **Database Creation**: The project starts by creating a database named `p1_retail_db`.
- **Table Creation**: A table named `retail_sales` is created to store the sales data. The table structure includes columns for transaction ID, sale date, sale time, customer ID, gender, age, product category, quantity sold, price per unit, cost of goods sold (COGS), and total sale amount.


### 2. Data Exploration & Cleaning

- **Record Count**: Determine the total number of records in the dataset.
- **Customer Count**: Find out how many unique customers are in the dataset.
- **Category Count**: Identify all unique product categories in the dataset.
- **Null Value Check**: Check for any null values in the dataset and delete records with missing data.


### 3. Data Analysis & Findings

The SQL queries were developed to answer the following business questions:

- Retrieve all columns for sales made on '2022-11-05.

- Retrieve all transactions where the category is 'Clothing' and the quantity sold is more than 4 in the month of Nov-2022.

- Calculate the total sales (total_sale) for each category.

- Find the average age of customers who purchased items from the 'Beauty' category.

- Find all transactions where the total_sale is greater than 1000.

- Find the total number of transactions (transaction_id) made by each gender in each category.

- Calculate the average sale for each month. Find out best selling month in each year.

- Find the top 5 customers based on the highest total sales.

- Find the number of unique customers who purchased items from each category.

- Create each shift and number of orders (Example Morning <12, Afternoon Between 12 & 17, Evening >17).
    

## Findings

- Customer Overview: The data includes customers of different ages who purchased items across categories like Clothing and Beauty.
- Big Purchases: Some transactions were over 1000, showing that high-value purchases were made.
- Sales Patterns: Sales change from month to month, helping to spot busy and slow seasons.
- Top Customers & Categories: The analysis highlights the highest-spending customers and the most popular product types.


## This project was developed as a part of the 'Beginner and Advanced Guide for Aspiring Data Analysts' by the YouTube Creator 'Zero Analyst'.


