# Bike Sales

## A data analytic project uncovering facts about the Bike Sales in order to boost and increase sales

This Project uses SQL as the tool for cleaning the data and exploring the data to get insights that can be used to increase sales and revenue for the company. It then makes use of PowerBI as the visualization tool to graphically show these facts.

### With MySQL this project does the following;
- Data Cleaning
  * Creates a new table from the existing table and copies all the data into this new table in order to preserve the original data
  * In the new table, it checks for duplicates and removes any duplicate found to ensure the data is not redundant
  * Drops "product_category" and "sub_category" because they are the same and is'nt useful in exploratory analysis
  * Drops the date column since we have 'day', 'month', 'year' which will be very useful in the analysis
  * Makes sure the data have the same alignment by Triming it
    
- Exploratory Analysis
  * Counts the states alongside their corresponding countries with the most sales
  * Counts the top 5 days they sold the most(ignoring quantity ordered)
  * Counts the top 5 days they sold the most(including quantities ordered)
  * Finds the top 5 days they made the most (profit)
  * Finds the age group that buys the most
  * Finds the number of males and females

### With Microsoft PowerBI this project visualizes the following in a multi-page dashboards;
* Customers by state and country
* Top 5 daily sales (ignoring quantity ordered)
* Daily Sales (including quantities ordered)
* Age group buying the most (ignoring quantites ordered)
* Percentages of males and females
* Days with Most profit
* Age group buying the most

This analysis clearly shows the states with most sales as well as the age group that purchases the most products. This is pivotal and focusing on the result of this data will boost sales by a significant percentage
