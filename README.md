# Zepto Inventory Analysis Using SQL

## Project Overview
This project analyzes Zepto product and inventory data using SQL in MySQL Workbench. The goal is to understand product availability, pricing, discounts, stock status, and category-level patterns through practical SQL queries.

## Objectives
- Explore the dataset and understand its structure.
- Check product availability and out-of-stock status.
- Analyze MRP, selling prices, and discount percentages.
- Compare products across categories.
- Identify low-stock products and other useful inventory patterns.
- Practice SQL queries used in data analysis.

## Tools and Technologies
- **MySQL Workbench** — writing and executing SQL queries
- **SQL** — filtering, grouping, aggregation, sorting, and analysis
- **CSV** — source dataset
- **PDF** — project report and documented findings

## Dataset
The project uses a CSV dataset containing product-related fields such as:
- `sku_id`
- `category`
- `name`
- `mrp`
- `discountPercent`
- `availableQuantity`
- `discountSellingPrice`
- `weightInGms`
- `outOfStock`
- `quantity`

The dataset is intended for exploratory inventory and pricing analysis. The imported row count should be verified against the original CSV before drawing final conclusions.

## SQL Analysis
The project includes queries for:
1. Counting records and previewing the dataset
2. Checking missing values
3. Exploring product categories
4. Comparing in-stock and out-of-stock products
5. Identifying repeated product names
6. Analyzing prices and discounts
7. Calculating price per gram where applicable
8. Reviewing category-level product counts and average prices
9. Identifying products with low available inventory
10. Finding the heaviest products

## Key Skills Demonstrated
- SQL data exploration
- Filtering with `WHERE`
- Grouping with `GROUP BY`
- Aggregate functions such as `COUNT()` and `AVG()`
- Filtering groups with `HAVING`
- Sorting with `ORDER BY`
- Limiting results with `LIMIT`
- Data quality checks
- Translating data into practical business questions

## Repository Files
- **SQL script** — analysis queries
- **CSV dataset** — source data used for analysis
- **PDF report** — project documentation, query explanations, and result previews

## How to Run
1. Download or clone this repository.
2. Open MySQL Workbench and connect to your MySQL server.
3. Create or select the database and import the CSV into a table named `zepto`.
4. Open the SQL script in MySQL Workbench.
5. Confirm that the column names in the script match your table.
6. Execute the queries and review the results.

## Limitations
The results depend on the dataset and the way it was imported into MySQL. Verify the record count, column types, and query outputs before using the findings in business decisions.

## Author
**Prathamesh More**

This project was created for SQL practice and portfolio demonstration, with a focus on inventory and pricing analysis.
