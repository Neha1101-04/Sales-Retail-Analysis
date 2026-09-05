# Sales/Retail Analysis

## Project Overview
This project analyzes retail sales data to uncover key business insights around revenue performance, top-selling products, regional trends, and customer behavior. It was built as a beginner-level data analytics project using Python and Pandas.

## Objective
The goal was to answer practical business questions such as:
- What is the total revenue and average order value?
- Which product categories, sub-categories, and regions generate the most revenue?
- How does revenue trend across months and years?
- Are customers repeat buyers?
- Who are the top customers by revenue?

## Dataset
The dataset used is a version of the popular "Sample Superstore" dataset, containing 9,800 rows and 18 columns of retail transaction data, including Order ID, Order Date, Customer details, Product Category/Sub-Category, Region, and Sales.

*Note: This dataset does not include Quantity, Discount, or Profit columns, so the analysis is based on revenue (Sales) only.*

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Analysis Performed
- Data cleaning: checked for missing values and duplicates, converted date columns to proper datetime format
- Exploratory analysis: total sales, average order value, unique orders/customers, average orders per customer
- Business questions: sales broken down by category, region, sub-category, month, and top customers
- Visualizations: bar and line charts for category, region, monthly trend, top sub-categories, and top customers

## Key Insights
1. Technology is the top-performing category by revenue.
2. West is the strongest-performing region.
3. November shows a strong seasonal sales peak, likely tied to Black Friday and Christmas shopping.
4. There is a large revenue gap between top (Phones) and bottom (Fasteners) performing sub-categories.
5. Customers place an average of 6.2 orders each, indicating strong repeat-purchase behavior.

## Conclusion
This analysis provides a foundational understanding of sales performance across categories, regions, and time. While limited to revenue data (no cost/profit figures were available), it highlights actionable opportunities in inventory planning, regional investment, seasonal marketing, and customer retention strategies.
