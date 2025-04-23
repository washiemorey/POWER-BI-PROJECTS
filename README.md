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

### The data was preprocced using DAX in power Bi and various columns were added and Measures::
#### Columns and Measures added in Transactions table
#### Profit = Transactions[Quantity] *(RELATED(Products[Price]) - RELATED(Products[Cost]))
#### Revenue = Transactions[Quantity] * RELATED(Products[Price])
#### Average Sales = SUM(Transactions[Quantity])/15
#### Margin = Products[Price] - Products[Cost]  was added in Products Table

### In my vusuals have brought out the following insights clearly
#### Revenue By Day: 
To understand how much revenue was made everyday and the variation
#### Sales Volume By Day: 
This helps understand how many sales were done each day,this can be used to explain variation in revenue since revenue depend on sales
#### Revenue By Branch : 
This is used to explain which branch makes least Revenue and which branch makes most revenue.
Have drilled it down for more and deeper understanding of Revenue at each branch by Category 
#### Revenue By Category : 
This helps understand how much percentage of total Revenue is being contributed by each Category
#### Top 5 Performing Products by Profit : 
To understand which products contribute most to profit made
#### Least 5 Performing Products By Profit : 
To understand which products are contributing least in profit for investigation how improvement can be done
#### Top Selling Products : 
To understand which products are bought most by customers in this Retail.
#### Slow Selling Products : 
To understand which products are bought least by customers in this Retail.

<img src="https://github.com/washiemorey/POWER-BI-PROJECTS/blob/main/Retail%20X%20sales.jpg" alt="Dashboard Preview" width="600"/>

# PROJECT 2(DATA PROFESSIONAL SURVEY)
This is data that was obtained by survey that was conducted online. The dataset is available 
[Here](https://docs.google.com/spreadsheets/d/1iZxgy2WHsbUk7GFwpZI9R5kr6LPew62B/edit?usp=sharing&ouid=104945955652080341592&rtpof=true&sd=true)

Performed various data cleaning and pre-processing before creating the visuals

## Objectives of the Analysis were:

### 1. To Find out Favourite Programming Language For data Professionals.
Which langage is used mostly and which one s used least.

### 2. To find out average salary of different data proffesionals 
Which proffesion earns highest and which one earns lowest on average .

### 3. To find out expectations on their new job.
Expectations of most data proffesuonals in new job 

### 4. To find out how difficult it is to break into data.

### 5. To find out whether most data proffesionals studied data at school or they switched into it later on

### 6. To find out current level of hapiness of data professionals with WorkLife Balance

### 7. To find out current level of hapiness of data professionals with Current Salary

### 8. To find out current level of hapiness of data professionals with Learning New Things

All these can be drilled down by country of residence for more insights.



