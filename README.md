# Amazon-sales-analysis
Project Overview-
This project focuses on performing Exploratory Data Analysis (EDA) and Sales Forecasting on Amazon sales data using Python. The goal is to understand sales trends, customer behavior, product performance, and generate useful business insights that can help in decision-making.
The project also includes a basic machine learning model (Linear Regression) to forecast future sales trend.
Objectives-
Clean and preprocess raw Amazon sales data
Perform exploratory data analysis (EDA)
Identify sales trends and patterns
Analyze category-wise and state-wise performance
Study customer purchasing behavior
Build a simple forecasting model for future sales
Data Cleaning-
The following data preprocessing steps were performed:
Removed unnecessary columns (Unnamed: 22, index)
Handled missing values in Amount, currency, etc.
Converted Date column to datetime format
Removed duplicate records
Created new features like Month and Day
Exploratory Data Analysis (EDA)-
1. Sales Trend Analysis
Monthly sales trends were analyzed to understand business growth over time.
Visualization shows how sales change across different months.
2. Category-wise Analysis
Identified top-performing product categories.
Found which categories generate the highest revenue.
3. State-wise Sales Analysis
Analyzed top states contributing to total sales.
Helped identify high-demand regions.
4. Order Status Analysis
Studied order distribution (Delivered, Cancelled, Returned).
Helped understand fulfillment performance.
5. Customer Behavior
Analyzed quantity purchased per order.
Studied B2B vs B2C sales distribution.
6. Promotion Impact
Checked whether promotions affect sales volume.
 Sales Forecasting
Approach:
Grouped data by Month
Calculated total monthly sales
Trained regression model
Predicted future sales for next months

A simple Linear Regression model was used to forecast future
