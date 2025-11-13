# Retail Performance Analysis Report
## Overview
The project aims to analyse the sales performance of a retail store from 2023 to 2025, The goal is to identify high performing products in terms of sales and profits,understand customer demographics, evluate regional and city level performance. It also explores montly sales and profit trends to uncover seasonal patterns.

Findings from this analysis aim to guide in making data driven decisions in marketing focus, inventory planning and pricing strategies.
## Project Objectives
1. Evaluate total sales and profit trends across months, region, cities and product category
2. Identify top performing products in each region
3. Segment customer data by age group to understand spending behaviours
4. Asessing store level performance by sales and profit contribution
5. Evaluate montly profit pattern to detect seasonal variations

## Tools Used
- Language: Python
- Libraries: pandas,matplotlib and seaborn
- Environment: Jupyter Notebook and VS code

## Dataset
1. It has 10,000 unique orders
2. Timeframe: 2023-2025
3. Columns: Order_ID, Order_Date, Customer_ID, Gender, Customer_Age, Region, Store_Location, Product_Category, Product_Name, Quantity, Unit_Price, Discount, Sales, Cost	Profit_Channel, Payment_Method

## Methodology
1. Data Cleaning and Preparation
   - Checked for missing and duplicate values
   - Converted Order dates to datetime column
   - Extracted Month and Year columns for the trend analysis
   - Ordered the dates for months to enable chronological visualisation
2. Data Processing
   - Tracked monthly profit for 2024 and 2025.
   - Grouped and aggregated data by Region,Store location and Product Category
   - Identified top products in each region
   - Segmented data for each age groups
  
  ## Recommendations for the Retail Store:
1. Prioritize high performing region,stores and segments and customer age groups
   - Focus resources, marketing and inventory in top regions (South America and Africa) ,top stores(Aaronbury and Aaronburgh), core customer age groups(19-35 and 50-65) as they drive majority of sales and profits.
   - Invest in high margin product categories like Electronics and Beauty to maximize profitability,while aligning product focus with regional performance trends.
   
2. Tailor marketing to Customer Segment
    - Target 19-35 years with engaging campaigns,digital outreach and product suited to their preferences.
    - Retain 50-65 year through loyalty programs and personalized offerings

3. Leverage seasonal Demand and Adress Dips
    - Analyze the factors behind January and July's strong performance and replicate those sucess drivers  across other months.
    - Mitigate low profit months by improving inventory timing and launching seasonal or promotional campaigns 

4. Adress Underperforming stores and regions 
   - Investigate causes of poor performance in specific stores and regions to identify operational,marketing or supply challenges
   - Apply localized promotions,operational improvements or consider restructuring if necessary


### Conclusion:
This projects provides a detailed understanding of sales and profit drivers.These insights can enhance forcasting accuracy,improve marketing effectiveness and support smarter buisness decisions on resource allocation 
