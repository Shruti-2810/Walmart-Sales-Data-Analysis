# Walmart-Sales-Data-Analysis
This project investigates Walmart sales data to identify top-performing branches and productsanalyze sales trends across various products, and study customer behavior. The primary goal is to discover insights that could help improve and optimize sales strategies.the dataset, sourced from Kaggle's Walmart Sales Forecasting Competition, includes historical sales information for 45 Walmart stores across different regions. Each store comprises multiple departments, and the project involves forecasting sales for each department within each store. The dataset also features holiday markdown events, which significantly impact sales patterns, though predicting the affected departments and the level of impact presents a unique challenge.


**Project Objectives**
The main objective is to gain a deeper understanding of the factors that influence sales across different Walmart branches.

**Approach Used**

1. Data Wrangling: This is the first step where inspection of data is done to make sure NULL values and missing values are detected and data replacement methods are used to replace, missing or NULL values.
2. Build a database

3. Create table and insert the data.

Select columns with null values in them. There are no null values in our database as in creating the tables, we set NOT NULL for each field, hence null values are filtered out.


**Feature Engineering**: This will help use generate some new columns from existing ones.
Add a new column named time_of_day to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the day most sales are made.
Add a new column named day_name that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question on which week of the day each branch is busiest.
Add a new column named month_name that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine which month of the year has the most sales and profit.

**Exploratory Data Analysis (EDA):** Exploratory data analysis is done to answer the listed questions and aims of this project.
**
**Conclusion:**
**

**Generic Question**

How many unique cities does the data have?

In which city is each branch?

**Product**

How many unique product lines does the data have?

What is the most common payment method?

What is the most selling product line?

What is the total revenue by month?

What month had the largest COGS?

What product line had the largest revenue?


What is the city with the largest revenue?

What product line had the largest VAT?

Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales

Which branch sold more products than average product sold?

What is the most common product line by gender?

What is the average rating of each product line?

**Sales**

Number of sales made in each time of the day per weekday

Which of the customer types brings the most revenue?

Which city has the largest tax percent/ VAT (Value Added Tax)?

Which customer type pays the most in VAT?

**Customer**

How many unique customer types does the data have?

How many unique payment methods does the data have?

What is the most common customer type?

Which customer type buys the most?

What is the gender of most of the customers?

What is the gender distribution per branch?

Which time of the day do customers give most ratings?

Which time of the day do customers give most ratings per branch?

Which day fo the week has the best avg ratings?

Which day of the week has the best average ratings per branch?
