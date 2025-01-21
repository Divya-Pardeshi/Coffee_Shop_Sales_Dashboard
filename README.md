# Coffee Shop Sales Dashboard

## Project Overview
This project involves analyzing sales and transaction data from a fictitious coffee shop in New York City. The goal is to build an interactive dashboard to explore trends, patterns, and insights in the data, enabling the coffee shop to make data-driven decisions to enhance operations and improve customer experience.

## Objectives
### Objective 1: Data Preparation
1. **Data Familiarization**:
   - Analyze the dataset to understand the number of transactions, the period covered, and the products/product categories sold.

2. **New Calculated Fields**:
   - Create a column for Revenue using the formula `Revenue = Price * Quantity`.
   - Add columns for Month and Day of the Week, formatted as text (e.g., "Jan", "Feb", "Mon", "Tue").
   - Extract the Hour from the transaction time.

### Objective 2: Data Exploration with PivotTables
1. Create PivotTables to analyze the following:
   - Revenue by Month.
   - Number of transactions by Day of the Week and Hour of the Day.
   - Number of transactions by Product Category, sorted in descending order.
   - Top 15 products by transactions, showing both transaction count and revenue.

### Objective 3: Dashboard Design
1. **Visualization**:
   - Create PivotCharts to display:
     - Revenue by Month (Line Chart).
     - Transactions by Day of the Week and Hour of the Day (Column Charts).
     - Transactions by Product Category (Bar Chart).
   
2. **Dashboard Layout**:
   - Assemble the charts into a clean, interactive dashboard layout.
   - Include a table for the Top 15 products by transactions and revenue.
   
3. **Interactivity**:
   - Add a slicer for store location and connect it to all PivotTables on the dashboard.

4. **Polishing**:
   - Adjust formatting and alignment for a professional look.
   - Hide raw PivotTables and remove worksheet gridlines.

## Dashboard Screenshot

Below is a screenshot of the dashboard for quick reference:
![Coffee Shop Sales Dashboard](https://github.com/user-attachments/assets/fc1df3fe-5091-49d8-95f2-74a54e912d06)

## Insights and Recommendations
1. **Best-Performing Month**:
   - The month of June had the highest revenue followed by the month of May and April. 
     
2. **High-Performing Products**:
   - Brewed Chai Tea and Gourmet Brewed Coffee are the top revenue generators. Consider increasing inventory or promoting these products.

2. **Time-Based Trends**:
   - Morning hours between 8:00 AM to 10:00 AM are the busiest hours, suggesting a preference for morning purchases. We should allocate more staff and resources during this period.

3. **Category Focus**:
   - Coffee, Tea, and Bakery items dominate sales. We could explore introducing new products in these categories to sustain interest.

4. **Weekend Strategies**:
   - Transactions dip on weekends. We can launch weekend-specific promotions or events to attract more customers.

## Tools Used
- **Microsoft Excel**: For data cleaning, PivotTables, and dashboard creation.

## How to Use the Dashboard
1. Open the Excel file.
2. Use the slicer to filter data by store location.
3. Explore charts and tables for detailed insights into sales and transactions.

## Files
- `Coffee_Shop_Sales_Dashboard.xlsx`: Contains the final dashboard and all supporting PivotTables.

## Acknowledgments
Thanks to Maven Analytics for providing this project template and dataset.
