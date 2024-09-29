# PowerBI-Assign-1-DSML-D37
PowerBI first Assignment  of Entri DSML D37batch
# Global Superstore Sales Dataset Cleaning and Adding Calculated Columns

## Description
This project provides a comprehensive sales dataset cleaning for the Global Superstore dataset. The analysis includes data cleaning and adding four calculated columns in Power BI.

## Key Features
- Data Cleaning: Handling missing values, removing duplicates, and standardizing formats.
- Profit Margin Calculation: A calculated column to evaluate profit margins.
- Shipping Performance: Calculated column showing the number of days taken to ship products.

## Technologies Used
- Power BI for data cleaning
- DAX (Data Analysis Expressions) for calculated columns 
- GitHub for version control and collaboration

## Dataset
The dataset used for this project is the Global Superstore dataset, which contains information about sales transactions, customer details, and shipping information across various regions.

- **Orders Sheet**: Contains order details such as sales, profit, discounts, and customer information.
- **Returns Sheet**: Contains return information for products.
- **People Sheet**: Contains regional management information.

## Data Cleaning and Transformation
The following steps were taken to clean and transform the data:
- The first row was used as headers for the **Returns** and **People** tables.
- Corrected the data type for the **Postal Code** column to a whole number to ensure accurate analysis and prevent errors.
- Missing values were handled by replacing with default values for the **PIN CODE** column.
- Duplicate rows were identified and removed based on key columns (**Order ID**).
- Four Calculated columns were added to analyze **Profit Margin**, **Discount Percentage**, **Total Cost**, and **Shipping Times**.


## How to Use
To use this project, follow these steps:
1. Download the Power BI `.pbix` file from this repository.
2. Open the file in Power BI Desktop.
3. Interact with the report to explore the sales analysis, filter data by region, product category, and time period.
4. Modify the report to suit your specific requirements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
