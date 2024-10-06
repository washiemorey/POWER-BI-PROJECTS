This repository showcases a collection of Power BI dashboards and reports designed to provide valuable insights into various datasets. Each project demonstrates the use of data transformation, modeling, and visualization techniques to turn raw data into clear, actionable business insights.
# PROJECT 1( RETAIL X ANALYSIS REPORT)
This data contains sales records for the first 15 days of June 2024
You can download the dataset used in this analysis [here](https://docs.google.com/spreadsheets/d/1ZMHOlzxQUh4dIWcmA3hTK_iw097vDNDX/edit?usp=drive_link&ouid=104945955652080341592&rtpof=true&sd=true).
## SALES ANALYSIS OBJECTIVES
### 1 Identify Sales Trend
Understand flow of sales over time for the 15 days provided
### 2 Branch Performance Analysis 
Compare sales performance across different branches
### 3 Evaluate Product Performance 
Asses product sales performance and identify best selling products and categories as 
well as slow moving products
### 4 Revenue Growth Opportunities
Identify potential opportunities for revenue growth and improvemen

The data was preprocced using DAX in power Bi and various columns were added and Measures::
### Columns and Measures added in Transactions table
#### Profit = Transactions[Quantity] *(RELATED(Products[Price]) - RELATED(Products[Cost]))
#### Revenue = Transactions[Quantity] * RELATED(Products[Price])
#### Average Sales = SUM(Transactions[Quantity])/15
#### Margin = Products[Price] - Products[Cost]  was addesd in Products Table

### In my vusuals have brought out the following insights clearly
#### Revenue By Day: To understand how much revenue was made everyday and the variation
#### Sales Volume By Day: This helps understand how many sales were done each day,this can be used to explain variation in revenue since revenue depend on sales
#### Revenue By Branch : This is used to explain which branch makes least Revenue and which branch makes most revenue.
Have drilled it down for more and deeper understanding of Revenue at each branch by Category 
#### Revenue By Category : This helps understand how much percentage of total Revenue is being contributed by each Category
#### Top 5 Performing Products by Profit : To understand which products contribute most to profit made
#### Least 5 Performing Products By Profit : To understand which products are contributing least in profit for investigation how improvement can be done
#### Top Selling Products : To understand which products are bought most by customers in this Retail.
#### Slow Selling Products : To understand which products are bought least by customers in this Retail.
