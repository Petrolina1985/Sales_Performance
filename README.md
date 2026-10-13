# RADOPIN SUPERMARKET SALES DASHBOARD
## SALES PERFORMANCE ANALYSIS


# PROJECT OVERVIEW

### This project analyzes the sales performance of Radopin Supermarket Awka Anambra State, over a three-year period from 2013 to 2015.
The dataset contains 444 sales transactions, covering four regions, five salespersons and four product categories. I used Microsoft Excel to clean, organize, analyze and visualize the sales data through PivotTables, charts and an interactive dashboard.
The analysis recorded total sales of approximately ₦3.25 million, with 2,322,594 units sold across 444 orders.

The analysis indicates that:

1. Central Region generation the highest sales.
2. Ice cream was the highest-performing product category.
3. Parker recorded the highest sales among the salespersons.
4. 2014 recorded the highest annual sales.
5. April recorded the highest sales among the months represented in the dataset.
6. Sales increase from 2013 to 2014 but declined slightly in 2015.

# BUSINESS PROBLEM

Radopin Supermarket has accumulated sales records across different years, regions, products and salespersons.
However, raw transactional data alone does not immediately provide management with an understanding of:

- Where sales are strongest.
- Which product generate most sales.
- Which salespersons contribute most to sales
- How sales have change over time.
- Which months record stronger sales performance.

The purpose of this analysis is therefore to transform the raw sales records into meaningful information that can support management's understanding of sales performance.


# PROJECT OBJECTIVES

The objective of this analysis were to:

1. Determine the total sales generated during the period.
2. Determine the total number of units sold.
3. Determine the total number of orders.
4. Analyze sales performance by region.
5. Analysis sales performance salesperson.
6. Analyze annual sales trends.
7. Analyze monthly sales performance.
8. Analyze sales performance by product.
9. Present the finding through an interactive Excel dashboard.
10. Provide management with actionable observations from the available sales data.

# DATASET DESCRIPTION
The dataset contains 444 sales transactions covering the period 2013–2015.

### DATASET FIELDS

|FIELD|DESCRIPTION|
------|-----------|
Year|year in which the occured|
Month|Month in which the sale occurrd|
Type|Product category|
Salesperson|Employee responsible for the sale|
Region|Sales region|
Sales|Monetary value of the sale|
Unit|Number of units|
Orde #|Unique order identification|

### Dimensions of the dataset
### Years: 2013, 2014, 2015
### Central, North, South, West
### Salesperson: Bishop, Lee, Parker, Pullen, Watson
### Product categories: Ice Cream, Tasty Treats, Frozen Yogurt, Popsicles
### Months represented: January, February, March, April, May, November and December

# DATA PREPARATION
Before conducting the analysis, the dataset was reviewed to ensure that the information was suitable for analysis.

The following areas were considered:
1.	Data structure 
2.	Field names 
3.	Data types 
4.	Missing values 
5.	Consistency of categories 
6.	Duplicate/unique order numbers 
7.	Numerical fields 
8.	Year and month classifications

The dataset contains 444 unique order numbers and no blank values were identified in the eight principal fields.

# ANALYTICAL METHODOLOGY

Microsoft Excel was used as the primary analytical tool.
The analysis involved:
Step 1 - Data inspection
The raw dataset was examined to understand its structure and variables.
Step 2 - Data preparation
The fields were reviewed for consistency and suitability for analysis.

Step 3 - PivotTable analysis
PivotTables were used to summarize:
•	Sales by region 
•	Sales by salesperson 
•	Sales by product 
•	Sales by year 
•	Sales by month
Step 4 — Data visualization
Charts were created to communicate the results visually.
Step 5 — Dashboard development
The resulting analysis was brought together into an interactive dashboard containing:
1.	KPI cards 
2.	Region filter 
3.	Year filter 
4.	Month filter 
5.	Sales-by-region chart 
6.	Sales-by-salesperson chart 
7.	Sales-by-product chart 
8.	Annual sales trend 
9.	Monthly sales trend

# KEY PERFORMANCE INDICATORS
The dashboard currently shows three major KPIs.
Total Sales
₦3,254,576.95
This represents the total sales value recorded across the 444 transactions.
Total Units
2,322,594
This represents the total number of units recorded as sold.
Total Orders
444
This represents the number of unique orders in the dataset.
These three KPIs give management an immediate high-level view of the size of the sales activity.

# SALES PERORMANCE BY REGION

The regional analysis produced the following

|REGION|SALES|SHARE OF TOTAL|
|------|-----|--------------|
Central|N1,391,555.30|42.76%|
North|N760,122.80|23.36%|
West|N596,968.95|18.34%|
South|N505,968.95|15.55%|
Total|N3,254,576.95|100%|

<img width="639" height="383" alt="image" src="https://github.com/user-attachments/assets/90276c16-c70b-4585-b862-6115799c9681" />


### Interpretation
The Central region generated ₦1.39 million, representing approximately 42.76% of total sales.
The North region contributed approximately 23.36%, while West and South contributed approximately 18.34% and 15.55%, respectively.
This indicates that sales are not evenly distributed across the four regions, with the Central region accounting for a substantial proportion of the recorded sales.


# SALES PERFORMANCE BY SALESPERSON

|SALESPERSON|SALES|SHARE|
|-----------|-----|-----|
Parker|N760,122.80|23.36%|
Lee|N740,578.40|22.75%|
Watson|N650,970.90|20.00%|
Bishop|N596,929.90|18.34%|
Pullen|N505,968.95|15.55%|
Total|N3,254,576.95|100%|

<img width="628" height="379" alt="image" src="https://github.com/user-attachments/assets/6247e93a-c79a-49e1-b2e0-d15c0f93a165" />

### Interpretation
Parker recorded ₦760,122.80, the highest sales value among the five salespersons.
Lee followed closely with ₦740,578.40.
Pullen recorded the lowest sales value at ₦505,968.95.
This information allows management to examine differences in sales contribution across the sales team.
Important: The data shows sales contribution; it does not by itself explain why one salesperson generated more sales than another.

# SALES PERFORMANCE BY PRODUCT

|PRODUCT|SALES|SHARE|
|-------|-----|-----|
Ice Cream|N1,379,573.20|42.39%|
Tasty Treats|N840,113.65|25.81%|
Frozen Yogurt|N650,077.50|19.97%|
Popsicles|N384,812.60|11.82%|
Total|N3,254,560.95|100%|

<img width="619" height="383" alt="image" src="https://github.com/user-attachments/assets/8cfd61b1-64b0-4e71-b2c4-ead16bc18b0b" />


### Interpretation
Ice Cream generated the highest sales value at approximately ₦1.38 million, accounting for about 42.39% of total sales.
Popsicles generated the lowest sales value at approximately ₦384,813.
This gives management a clear view of the relative contribution of each product category.

# ANNUAL SALES PERFORMANCE
|YEAR|SALES|
|----|----|
2013|N1,008,662.75|
2014|N1,138,686.00|
2015|N1,107,228.20|

<img width="794" height="398" alt="image" src="https://github.com/user-attachments/assets/5ec9fc70-8e5b-4689-b5ea-8abec1489e4c" />

### Year-on-year movement
From 2013 to 2014:
Sales increased by approximately 12.89%.
From 2014 to 2015:
Sales decreased by approximately 2.76%.
Interpretation
The highest annual sales occurred in 2014, at approximately ₦1.14 million.
Sales increased substantially between 2013 and 2014, followed by a modest decline in 2015.
This suggests that management should investigate what factors contributed to the 2014 increase and the subsequent 2015 decline.


# MONTHLY SALES PERFORMANCE

|MONTH|SALES|
|------|----|
April|N640,494.40|
February|N521,344.75|
January|N513,336.00|
May|N428,512.40|
November|N383,151.70|
December|N344,533.00|


<img width="781" height="383" alt="image" src="https://github.com/user-attachments/assets/1f521cc1-66e0-484e-9af8-a28a74139298" />

### Interpretation
April recorded the highest sales among the months available in the dataset, with approximately ₦640,494.
December recorded the lowest sales among the represented months, at approximately ₦344,533.
Important analytical caution
Your dataset contains only seven months:
January, February, March, April, May, November and December.
Therefore, we should not say that April is the highest-selling month of the entire year.
The professional statement is:
"April recorded the highest sales among the months represented in the dataset."
That distinction is exactly the kind of thing I want you to learn as an analyst.

# KEY INSIGHT FOR MANAGEMENT

Based strictly on the available data, the following observations can be made:
1. Regional concentration
The Central region generated approximately 42.76% of total sales, making it a major contributor to overall sales.
2. Product concentration
Ice Cream generated approximately 42.39% of total sales, making it the largest product category by sales value.
3. Salesperson contribution
Parker and Lee recorded the two highest individual salesperson sales values.
4. Annual performance
2014 generated the highest annual sales, while 2015 experienced a modest decline from the previous year.
5. Monthly performance
April recorded the highest sales among the seven months available in the dataset.


# MANAGEMENT RECOMMEDATIONS

Recommendation 1 — Investigate regional performance
Management could examine the factors contributing to the Central region's high sales performance and determine whether relevant practices can be applied elsewhere.
Recommendation 2 — Review product performance
Management could review the factors contributing to the strong sales of Ice Cream and assess inventory and marketing strategies around high-performing products.
Recommendation 3 — Examine the 2015 decline
Since sales decreased by approximately 2.76% from 2014 to 2015, management could investigate potential factors such as product availability, pricing, customer demand, competition and sales activity.
Recommendation 4 — Investigate salesperson performance
Management could examine differences in salesperson performance to understand whether territory, customer portfolio, product mix or other operational factors contribute to the observed differences.
Recommendation 5 — Improve future data collection
Future datasets should contain additional business variables such as:
1.	Cost of goods sold 
2.	Selling price 
3.	Discounts 
4.	Profit 
5.	Profit margin 
6.	Customer information 
7.	Inventory 
8.	Sales targets 
This would allow management to move from sales-performance analysis to profitability analysis.


# DASHBOARD DESCRIPTION


This dashboard provides an interactive overview of Radopin Supermarket's sales performance between 2013 and 2015. It enables Radopin management to examine total sales, units sold and order volume, while also allowing performance to be analyzed by region, salesperson, product and time period."
Then point to the dashboard:

Top → KPIs
"At the top are the three key performance indicators: total sales of ₦3.25 million, 2.32 million units and 444 orders."

Left → Region
"The regional analysis shows that Central recorded the highest sales contribution."
Middle → Salesperson
"The salesperson analysis allows management to compare individual sales contributions."
Right → Product
"The product analysis shows that Ice Cream generated the highest sales among the four product categories."
Bottom left → Year
"The annual trend shows growth from 2013 to 2014 followed by a modest decline in 2015."
Bottom right → Month
"The monthly analysis shows April as the highest-performing month among the seven months represented in the dataset."

<img width="975" height="536" alt="image" src="https://github.com/user-attachments/assets/0121c3a9-c50a-41cb-a5b2-54fe419fbcfa" />







































