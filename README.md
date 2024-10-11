# Yasserashraf1-Superstore-Sales-Analysis-Project-Using-Python-and-Tableau

## Project Overview
This project involves analyzing the "Superstore Sales Dataset" using Python for data cleaning, exploratory data analysis (EDA), and visualization. Tableau is then used to further visualize sales trends and insights. The project aims to uncover key patterns in sales performance, customer behavior, and product categories to support data-driven decision-making.

## Objectives
* Perform data importing, cleaning, and EDA using Python.
* Visualize sales patterns to identify trends in customer segments, product categories, and regions.
* Utilize Tableau for advanced interactive visualizations to gain insights into sales performance across different dimensions.
* Answer key business questions, such as which customer segments and products perform the best, and how sales vary across regions and time.

## Dataset
The dataset contains information about sales transactions, customers, products, and shipping details. Key columns include:
* **Order ID**: Unique identifier for each order.
* **Order Date and Ship Date**: Dates for when orders were placed and shipped.
* **Customer ID, Customer Name, Segment**: Customer-related details, including segmentation (e.g., Consumer, Corporate).
* Country, State, Region: Geographical information about customer locations.
* **Category and Sub-Category**: Classification of products sold.
* **Sales, Profit, and Quantity**: Metrics for evaluating sales performance.

## Project Steps
* **1. Data Importing and Cleaning**
* Imported the dataset and handled missing values by dropping nulls.
* Removed duplicated rows to ensure data quality.
* Converted date columns to a proper datetime format for temporal analysis.
* Dropped irrelevant columns such as 'Row ID' to streamline the data.
* **2. Exploratory Data Analysis (EDA)**
* Ship Mode and Customer Segments: Analyzed the distribution using pie charts to understand shipping preferences and segment contributions.
* Product Categories: Explored sales across different product categories and sub-categories to identify high-performing products.
* Geographical Analysis: Examined sales distribution across regions and states, with a focus on standout performers like California.
* Numerical Columns: Generated boxplots and histograms to understand the distribution and variability of numerical data such as Sales, Profit, and Discount.
* **3. Data Visualization in Python**
Visualized key insights using pie charts, boxplots, and histograms to identify patterns in sales and shipping preferences.
* **4. Advanced Visualizations in Tableau**
* Sales by Category: Technology contributes the most to sales (36.7%), followed by Furniture (32.1%) and Office Supplies (31.2%).
* Sales by Segment: Balanced sales across different customer segments, with Technology performing well across all segments.
* Regional Sales Distribution: The West region, particularly California, stands out in sales performance.
* Sales Over Time: A steady increase in sales over time, with notable spikes in Q4 each year.
* Mode Analysis: Standard Class is the most preferred shipping method, with Same Day shipping being the least popular.

## Key Findings
* **Sales Trends**: Technology dominates sales, but Furniture and Office Supplies also contribute significantly.
* **Geographical Insights**: The West region, especially California, leads in sales, followed by other regions with moderate performance.
* **Customer Preferences**: Standard Class is the most commonly used shipping mode, while Same Day shipping is less popular, likely due to higher costs.
* **Seasonal Trends**: Sales increase towards the end of each year, indicating potential seasonal promotions or demand surges.
  
## Conclusion
This project highlights the importance of understanding sales performance across various dimensions, such as customer segments, geographical regions, and product categories. By leveraging Python for data analysis and Tableau for visualizations, businesses can gain actionable insights to improve sales strategies, optimize product offerings, and enhance customer satisfaction.

## Files in the Repository
* Superstore Sales Dataset.csv: Original dataset used for analysis.
* Superstore_Sales_Cleaned.csv: Cleaned dataset after data preprocessing.
* Python Code.ipynb: Python script for data cleaning and EDA.
* Tableau Dashboard.twb: Tableau workbook containing the interactive sales dashboard.
