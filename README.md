# Order Data Analysis Using R

## Project Overview

This project analyzes an order dataset using R programming. The dataset contains information about orders, users, products, items purchased, order price, and cost of goods sold (COGS).

## Dataset

The dataset used in this project is `orders.csv`.

It contains 32,313 observations and 8 variables.

Main variables include:

- order_id
- created_at
- website_session_id
- user_id
- primary_product_id
- items_purchased
- price_usd
- cogs_usd

## Analysis Performed

The following data analysis tasks were performed:

1. Loaded the CSV dataset into R.
2. Checked the structure of the dataset.
3. Generated summary statistics.
4. Checked for missing values.
5. Checked for duplicate records.
6. Created a boxplot to identify unusual order prices.
7. Calculated Q1, Q3 and IQR.
8. Identified price outliers.
9. Normalized the order price.
10. Converted the date column into date-time format.
11. Calculated correlations between items purchased, price and COGS.
12. Created a histogram of order prices.
13. Created a scatter plot of price versus COGS.

## Result

The dataset contained no missing values and no duplicate rows. The analysis helped understand the distribution of order prices, identify potential outliers, and examine relationships between price, cost, and number of items purchased.

## Tools Used

- R
- RStudio
- CSV Dataset
