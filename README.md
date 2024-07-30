# Sales and Product Analysis of Chocolate Shop

## Project Objective

- Understand the key statistics of the company's sales and profits.
- Analyze the top-performing and best-selling products in the shop (Top 10 Products).
- Identify products that need to be discontinued (Bottom 10 Products).
- Determine underperforming salespersons.
- Analyze sales by country.
- Create an interactive sales dashboard.

## Data Sourcing

- Sample data collected from the internet.

## Data Preparation

- Data cleaning
- Data formatting
- Data profiling

## Dataset

The dataset consists of two sheets:
1. **Sales data:** Includes salespersons, geography, product name, sales, and quantity sold.
2. **Product data:** Includes product name and cost per unit.

## Understanding Quick Statistics of Sales and Profits

Using the available sales and product data:
- Calculated sales per unit using the formula: `=IFERROR([@Sales]/[@[Units Sold]], 0)`
- Calculated profit per unit using the cost per unit and sales per unit with the formula: `=IFERROR([@[Sales per Unit]]-[@[Cost per Unit]], 0)`
- Calculated the product cost using the formula: `=[@[Units Sold]]*[@[Cost per Unit]]`
- Used conditional formatting for quick data visualization.

## Detailed Analysis

- Created a summarized report using VLOOKUP, SUMIFS, drop-down lists, and COUNTIF.
- Conducted profit analysis using pivot tables to determine the profit percentage of each product relative to the total profit, with a slicer for custom filtering by geography.
- Analyzed sales by country, salesperson, top 10 products, and bottom 10 products.

## Identifying Products for Discontinuation

- Based on the bottom three products generating less profit than others.

## Sales Dashboard

- Created a Power BI dashboard.
  
  ![image](https://github.com/user-attachments/assets/9fd51625-6e6a-4259-a177-4d12c857cb60)

