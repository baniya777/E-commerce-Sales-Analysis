# E-commerce Sales Analysis with Python
Analyze Amazon sales data to uncover trends in revenue, categories, cities, and fulfillment methods using Python. The analysis aims to support strategic decision-making for marketing, logistics, and fulfillment optimization in the e-commerce domain.

## Dataset
- `amazon_sales_dataset.csv`: CSV containing sales transaction data

## Steps
1. Cleaned missing and irrelevant data
2. Filtered only shipped, valid orders
3. Parsed dates and created time-based fields
4. Standardized categories and fulfillment types

## Exploratory Data Analysis:
1. Monthly Sales Trend
Monthly revenue and quantity were calculated using groupby.
A bar chart was plotted showing monthly sales revenue trends.
This helps identify peak and off-peak months in sales performance.

2. Category-wise Sales
Sales were aggregated by product category.
A bar plot highlights which product categories generate the most revenue.

3. Top Shipping Cities
City-wise revenue was calculated and visualized using a bar chart.
The top 10 cities with the highest total sales were identified.

4. Fulfillment Method Analysis
Cleaned and analyzed the Fulfilment column.
Pie chart was used to show the revenue distribution between different fulfillment types (e.g., Amazon vs Seller).

5. Total Sales and Orders
The script computed total revenue and total unique orders from the dataset.

## Install dependencies: 
```bash
pip install pandas matplotlib seaborn
