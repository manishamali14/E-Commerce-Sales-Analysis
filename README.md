# E Commerce Sales Analysis

This is an exploratory data analysis of Amazon India apparel sales from March to June 2022. I did this project as part of the Jobaaj exam test using Python in Google Colab.

## Dataset

The dataset has around 1.29 lakh orders with details like date, status, category, size, amount, fulfilment and shipping location.

## What I did

1. Explored the data to check columns, data types, missing values and duplicates.
2. Cleaned the data by removing duplicates and an empty column, filling missing Amount with the median, fixing date formats and correcting state names.
3. Checked outliers in Amount using the IQR method.
4. Analysed sales, customers, fulfilment, products and returns.

## Key findings

* Net revenue is ₹7.18 crore and the average order value is ₹695.89.
* April had the highest sales.
* Set and Kurta are the best selling categories.
* Maharashtra and Karnataka bring the most revenue.
* 14.22% of orders were cancelled, and Merchant orders are cancelled more than Amazon orders.
* The return rate is 1.64%, and Western Dress has the highest return rate.

## Tools used

Python, Pandas, Matplotlib and Google Colab.

## How to run

Open the notebook in Google Colab and click Runtime, then Run all. The dataset downloads automatically from Google Drive.
