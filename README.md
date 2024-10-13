# PowerBI-Assign-1-DSML-D37
PowerBI first and second Assignment  of Entri DSML D37batch
# Global Sales and Shipping Performance Dashboard

This repository contains a Power BI dashboard that provides an overview of global sales and shipping performance. The dashboard enables stakeholders to visualize and analyze key business metrics related to sales, shipping methods, and profitability across different regions and markets.

## Dashboard Features

### 1. Shipping Performance
- Displays the percentage of shipping by different ship modes (Standard Class, Second Class, First Class, Same Day).
- Breakdown of sales by regions and markets (Africa, APAC, Canada, EMEA, EU, LATAM).

### 2. Sales Overview
- Visualizes total sales by country and market.
- Provides insights into sales performance across various regions, including the top countries by sales.

### 3. Profitability Analysis
- Illustrates profit margin by market.
- Compares total sales against total profit for each market to identify the most profitable regions.

### 4. Sales Over Time
- Tracks monthly sales trends, allowing users to identify seasonal patterns and peak sales periods.

### 5. Top Performing Cities
- Highlights the top-performing cities based on total sales and profit, providing insights into the best markets and areas of improvement.

## Data Cleaning and Transformation

### 1. Handling Missing Values
- Replaced missing values in key columns, such as the `PIN CODE` column, to ensure data completeness.

### 2. Removing Duplicates
- Identified and removed duplicate rows based on key columns like `Order ID` to ensure accuracy in reporting.

### 3. Standardizing Formats
- Corrected data types, including converting the `Postal Code` column to a whole number for accurate analysis.

## Key Calculations

### 1. Profit Margin Calculation
- A calculated column was added using DAX (Data Analysis Expressions) to evaluate profit margins for each transaction. This helps in understanding profitability across various regions.

### 2. Shipping Performance
- Another calculated column was created to analyze shipping performance by calculating the number of days taken to ship products, allowing for more efficient shipping analysis.

## Data Sources
The dashboard uses data from fictional or simulated global sales records, including the following fields:

- **Country**
- **Region**
- **Market**
- **Sales**
- **Profit**
- **Shipping Mode**

## Key Metrics
- **Total Sales**: The total revenue generated by region and market.
- **Profit**: The net earnings after all costs, broken down by market and city.
- **Profit Margin**: The percentage of profit in relation to total sales, helping to evaluate the profitability of different regions.
- **Shipping Mode Performance**: Breakdown of shipping methods used across markets.

## How to Use the Dashboard
1. Open the Power BI file.
2. Use the filters available in the dashboard to drill down into specific regions, countries, or shipping methods.
3. Analyze key performance indicators (KPIs) across different time frames and geographic regions.

## Conclusion
This Power BI dashboard serves as a tool for business leaders to monitor global sales performance and optimize shipping operations. It helps identify top-performing regions, shipping modes, and cities, as well as areas with potential for improvement in profitability.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
