# Retail Sales Analysis (PostgreSQL)

## Project Overview

This project demonstrates **SQL-based data analysis** using a retail sales dataset.
It covers the **end-to-end workflow**: creating a database, cleaning data, exploring customer transactions, and answering **key business questions** with SQL queries.

The goal is to analyze customer behavior, sales trends, and product category performance in order to extract actionable insights.

---

## Project Structure

1. **Database & Table Setup**

   * Create `sql_project` database
   * Define schema for `retail_sales` table

2. **Data Cleaning**

   * Handle missing or null values
   * Remove incomplete rows

3. **Exploratory Analysis**

   * Total number of sales
   * Unique customers
   * Product categories

4. **Business Analysis (Q\&A)**

   * Sales by date, category, and customer
   * Customer demographics
   * Top customers and best-selling months
   * Shift-based sales distribution

---

## Key Business Questions Answered

1. Retrieve all sales on a given date (`2022-11-05`).
2. Find all clothing transactions with quantity > 4 in Nov-2022.
3. Calculate total sales by category.
4. Average age of customers in the Beauty category.
5. Transactions with total sales > 1000.
6. Number of transactions by gender and category.
7. Average monthly sales & best-selling month per year.
8. Top 5 customers by sales.
9. Unique customers by category.
10. Orders by shift (Morning, Afternoon, Evening).

---

## Example Insights

* **Top Customers**: Identified the 5 highest contributors to sales.
* **Category Trends**: Clothing & Beauty segments drove majority sales.
* **Best Month**: Seasonal patterns emerged (e.g., holiday spikes in November/December).
* **Customer Demographics**: Beauty category attracted younger customers.
* **Shift Performance**: Evenings saw the highest number of orders.

---

## How to Run

1. Clone this repository
2. Launch PostgreSQL
3. Run the provided SQL script step by step

   ```sql
   \i retail_sales_analysis.sql
   ```
4. Query results will provide business insights

