# Sales-Analysis-Project
This project is based on a case study I completed during a technical assessment as part of a job application process. The task involved analyzing sales data for a company operating in the tech product sector. The goal was to extract insights that would support data-driven decision-making for the sales department.


## Overview

The sales department of a company that specializes in tech products required an in-depth analysis of their sales data. The objective was to help the sales team identify product trends and better understand customer behavior. By exploring sales patterns and customer interactions, the analysis aimed to support more informed and strategic decisions.


## Steps:
### Data Cleaning & Transfomation:
### Customers:
  * Impute the blank rows with “unknown” because this is better for visualization.
  * Split the Customer Code into two new columns: “Code Prefix”, “Code Number”
  * Edit the format of the Name Column


Sales:
There are many duplicates in the data. While it would normally make sense to remove them, I decided not to because:
The data seems to be generated, as it follows a consistent pattern.


When I removed the duplicates, the actual sales figures differed significantly from the forecasted sales.


In a real-world scenario, I would go back and consult the data source before making any decisions.


Data Modeling
Create a date table using DAX


This is how the schema looks:


Power BI
Create some measures like: Sales Forecast, Sales Difference, Sales Growth, Total Sales, Variance(Between Actual and Forecasted Sales)
The Dishboard:





Insights:
Total Sales in July for both 2008 and 2009 were the lowest
Overall, Total Sales are on a decline
The sales forecast across all countries is relatively similar with difference by 4,14%, with the United States leading in terms of sales
The top-performing customer is Sabrina Alvarez.
The most profitable product is Contoso Projector 1080p X980 white




Recommendations:
Offer discounts and promotions for July to boost sales during this slow period
Focus on marketing efforts in the United States, as it is the top-performing country
Investigate the declining sales trend and analyze underlying causes, such as market demand or product issues
Introduce loyalty programs to encourage repeat customers and increase sales volume
Provide targeted offers for top customers, like Sabrina Alvarez, to maintain their loyalty and increase lifetime value
Optimize the inventory for products with lower sales to avoid overstocking or understocking


