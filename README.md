# AMAZON_SALES_DATA_ANALYSIS

## PROJECT OVERVIEW

This project analyzes Amazon sales data to understand customer behavior, product performance, and sales trends. Using Python, the data is cleaned, processed, and transformed into meaningful insights through exploratory data analysis and visualization.

### TOOLS USED

 * Python (Pandas, NumPy)
 * Visualization Libraries (Seaborn, Matplotlib, Plotly)

### DATASET

The dataset contains detailed information about customer orders, products, and transactions across multiple regions. It includes both raw and engineered features used for analysis.

### Key Columns:
OrderID, OrderDate, CustomerID, CustomerName,
ProductID, ProductName, Category, Brand,
Quantity, UnitPrice, Discount, Tax, ShippingCost, TotalAmount,
PaymentMethod, OrderStatus, City, State, Country,
GrossSales, DiscountAmount, NetSales, EstimatedProfit,
Year, Month, MonthName

### DATASET INFORMATION

📌 Total Records: 100,000

📌 Total Columns: 27

📌 Data Types:

Datetime: 1 column

Numerical: 12 columns

Categorical: 14 columns

### STEPS FOLLOWED

1. #### Data Cleaning & Preparation

  * Used Pandas to handle missing values in Discount, Tax, and PaymentMethod

  * Removed duplicate records

  * Converted data types (OrderDate to datetime, numeric columns to proper format)

  * Ensured consistency in categorical fields

2. #### Defining Key Columns

  * Selected essential fields: Order ID, Customer, Product, Category, Country

  * Focused on important business metrics like Sales, Discount, and Profit

  * Structured dataset for analysis and reporting

3. #### Feature Engineering

  * Created GrossSales = Quantity × UnitPrice

  * Calculated DiscountAmount

  * Derived NetSales

  * Estimated Profit (NetSales - Tax - ShippingCost)

  * Extracted Year, Month, MonthName from OrderDate

4. #### Exploratory Data Analysis (EDA)

  * Performed descriptive statistics (mean, median, distribution)

  * Analyzed sales and quantity distributions

  * Identified patterns and trends across categories and regions

  * Detected outliers using boxplots and distribution plots

5. #### Visualization

  * Line plots: Monthly sales trends

  * Bar charts: Category and payment analysis

  * Pie charts: Country-wise sales distribution

  * Boxplots: Profit spread across categories

  * Histograms: Order value distribution

6. #### Interpretation & Insights

  * Identified top-performing categories and brands

  * Analyzed customer payment preferences

  * Detected seasonal sales trends

  * Evaluated country-wise performance

7. #### Documentation & Reporting

  * Summarized insights in structured format

  * Presented findings using charts and visualizations

  * Generated actionable business recommendations

### FILES INCLUDED

amazon_sales.csv

final_project.ipynb
