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
ta Structure
The database contains a single main table: pizza_sales

The Columns include:

pizza_id	INT	    Unique identifier for each pizza in order

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

## Key Performance Indicators (KPIs)
### Calculated Metrics:
Total Revenue: $817,860.05

Average Order Value: $38.31

Total Pizzas Sold: 49,574

Total Orders: 21,350

Average Pizzas per Order: 2.32

## Analytical Insights
### Sales Trends:
Daily Pattern: Orders peak on Fridays (3,538 orders) and Saturdays (3,158 orders)

Monthly Pattern: Highest sales in July (1,935 orders) and January (1,845 orders)

Lowest Sales: September (1,661 orders) and October (1,646 orders)

### Product Category Performance:
Classic: 26.91% of total sales (14,579 pizzas)

Supreme: 25.46% of total sales (11,777 pizzas)

Chicken: 23.96% of total sales (10,815 pizzas)

Veggie: 23.68% of total sales (11,449 pizzas)

### Size Preference:
Large: 45.89% of sales (18,526 pizzas)

Medium: 30.49% of sales (15,385 pizzas)

Small: 21.77% of sales (14,137 pizzas)

XL/XXL: Combined <2% of sales

## Top Performers
### By Revenue:
The Thai Chicken Pizza - $43,434.25

The Barbecue Chicken Pizza - $42,768.00

The California Chicken Pizza - $41,409.50

The Classic Deluxe Pizza - $38,180.50

The Spicy Italian Pizza - $34,831.25

### By Quantity Sold:
The Classic Deluxe Pizza - 2,453 units

The Barbecue Chicken Pizza - 2,432 units

The Hawaiian Pizza - 2,422 units

The Pepperoni Pizza - 2,418 units

The Thai Chicken Pizza - 2,371 units

### By Order Frequency:
The Classic Deluxe Pizza - 2,329 orders

The Hawaiian Pizza - 2,280 orders

The Pepperoni Pizza - 2,278 orders

The Barbecue Chicken Pizza - 2,273 orders

The Thai Chicken Pizza - 2,225 orders

## Underperforming Products
### By Revenue:
The Brie Carre Pizza - $11,588.50

The Green Garden Pizza - $13,955.75

The Spinach Supreme Pizza - $15,277.75

The Mediterranean Pizza - $15,360.50

The Spinach Pesto Pizza - $15,596.00

### By Quantity Sold:
The Brie Carre Pizza - 490 units

The Mediterranean Pizza - 934 units

The Calabrese Pizza - 937 units

The Spinach Supreme Pizza - 950 units

The Soppressata Pizza - 961 units


### Analysis Type: Descriptive analytics with aggregation and grouping

 ##Query Categories:
Basic KPIs: Sums, averages, counts

Time-based Analysis: Daily and monthly trends

Category Analysis: Sales distribution by category and size

Product Performance: Top/bottom performers across metrics

## Business Recommendations
1. Inventory Optimization:
Increase stock of Classic category pizzas, especially Large sizes

Reduce inventory for Brie Carre and Mediterranean pizzas

Focus on chicken-based pizzas which show strong revenue performance

2. Staffing & Operations:
Schedule more staff on Fridays and Saturdays (peak days)

Prepare for higher demand in July and January

Optimize kitchen workflow for Large pizza production (45.89% of sales)

3. Marketing Strategy:
Promote weekend specials to capitalize on existing high demand

Create bundles around average order size (2.32 pizzas)

Highlight top-performing pizzas in marketing materials

Consider promotions for underperforming items to clear inventory

4. Menu Optimization:
Feature Thai Chicken, Barbecue Chicken, and Classic Deluxe prominently

Evaluate removing or reformulating consistently low-performing items

Create combo deals pairing popular items with slower sellers

## Stakeholders:
Business Owners: Strategic decision making

Operations Managers: Staffing and inventory planning

Marketing Teams: Campaign planning and product promotion

Data Analysts: Methodology and query reference

Investors: Performance evaluation

## Skills Demonstrated
SQL Querying: Complex aggregations, grouping, subqueries

Data Visualization: Power BI dashboard creation

Business Intelligence: KPI definition and calculation

Data Analysis: Trend identification and insight generation

Database Management: Connection and data extraction

Report Documentation: Clear communication of findings

### Requirements to Run Analysis
MySQL Database with pizzastore database loaded

Jupyter Notebook environment

Python packages: sqlalchemy, pymysql, ipython-sql

Power BI Desktop (for dashboard viewing/modification)
