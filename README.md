# Marketing_and_Sales
Marketing and Sales projects for Segmentation, RFM, Cohort Analysis using Python

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

1. [Online_store_sales(SQL)](https://github.com/runaevalina/Sales_Transactions_Orders/blob/main/Online_store_sales(SQL).pdf) shows a brief analysis of sales from several countries.

Questions to answer:
- countries with MAU top results
- AOV by country
- During the study, some anomolias were noticed in terms of the correspondence between the average check and the number of unique users. It turned out that in one of the countries one user purchased extremly hight number of positions.

2. Cohort analisys of users.

Questions to answer:
- How many users do we have? who made a purchase only once?
- How many orders per month, on average, are not delivered for various reasons (display details by reasons)?
- For each product, determine on which day of the week the product is most often bought.
- How many purchases does each user make on average per week (by months)? 
- Using pandas, conduct a [cohort analysis](https://github.com/runaevalina/Marketing_and_Sales/tree/main/RFM_and_Cohorts) of users. Between January and December, identify the cohort with the highest retention for the 3rd month.


2a. RFM user segmentation.

Questions to answer:
We build [RFM user segmentation](https://github.com/runaevalina/Marketing_and_Sales/blob/main/RFM_and_Cohorts/RFM%20for%20e-commerce.ipynb) to qualitatively evaluate the audience. In clustering, we will choose the following metrics:
R - time from the user's last purchase to the current date,
F - the total number of purchases from the user for the entire time,
M - the amount of purchases for the entire time. For each RFM segment,we will build the bounds of the recency metrics,frequency and monetary to interpret these clusters.
