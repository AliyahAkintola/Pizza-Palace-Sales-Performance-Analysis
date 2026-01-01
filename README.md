# Pizza-Palace-Sales-Performance-Analysis
This project is a comprehensive sales performance analysis for a pizza restaurant (Pizza Palace) covering the entire year of 2015. The analysis includes both data visualization (Power BI) and SQL-based data exploration (Jupyter Notebook), providing actionable business insights through data-driven decision making.

## Project Goals
1. Analyze 2015 sales performance across multiple dimensions

2. Identify best and worst-performing pizza products

3. Understand customer ordering patterns (time, category, size preferences)

4. Calculate key business metrics for performance monitoring

5. Provide data foundation for business strategy and inventory planning

## Project Components
1. Power BI Interactive Dashboard
Visual Summary: High-level KPIs and trends for 2015

Interactive Elements: Date filters, category selectors

Key Visualizations: Daily and Monthly Order Trends, Sales Distribution by Pizza Category and Size, Best/Worst Sellers by Revenue, Quantity, and Orders

2. SQL Analysis Notebook (PizzaStore.ipynb)
Database Connection: MySQL database with full 2015 sales data

Comprehensive SQL Queries: 15+ analytical queries

Data Exploration: Raw data preview and structure understanding

## Data Structure
The database contains a single main table: pizza_sales

Schema:
Column	Type	Description
pizza_id	INT	Unique identifier for each pizza in order
order_id	INT	Order identifier
pizza_name_id	VARCHAR	Short code for pizza type and size
quantity	INT	Number of pizzas in the line item
order_date	DATE	Date of order
order_time	TIME	Time of order
unit_price	DECIMAL	Price per pizza
total_price	DECIMAL	Line item total (quantity × unit_price)
pizza_size	CHAR	Size code (S, M, L, XL, XXL)
pizza_category	VARCHAR	Category (Classic, Supreme, Chicken, Veggie)
pizza_ingredients	TEXT	Comma-separated ingredients list
pizza_name	VARCHAR	Full pizza name
Total Records: 49,574 pizzas sold across 21,350 orders
