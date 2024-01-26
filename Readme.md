# CHURN SALES DATASET

## Objective:
This project aimed to analyze the business performance of a company through the comprehensive examination of Key Result Areas (KRAs) and Key Performance Indicators (KPIs). The focus was on leveraging data from customer, division, region, and sales tables to gain insights into sales dynamics, customer behavior, and overall profitability.
Data Preparation:

In the initial dataset for our project, we encountered four primary tables: one containing customer data, another for divisions, a third for regions, and the last focusing on sales data, which serves as our primary table. A notable issue in the dataset involved the date key, where some entries erroneously listed the date as 29/2/2009, a non-existent date in a non-leap year (2009). To address this, we corrected the date to the nearest valid date, 28/2/2009. Subsequently, we loaded the dataset into Power Query for further modifications, adjusting column types to their appropriate data types. Additionally, a derived table was created, featuring the date key and sales amount, to facilitate the calculation of cumulative sales revenue.

## Data Processing:
The processed data was then uploaded to Power BI for dashboard creation. In Power Query, we implemented transformations to refine the table for optimal dashboard integration. Utilizing DAX (Data Analysis Expressions), several key measures were derived to provide valuable insights:
1. Total Number of Orders: Calculated as the distinct count of order numbers.
2. Net Profit: Derived by subtracting the total sales cost amount from the total sales amount.
3. Gross Margin: Calculated as the ratio of gross profit to total sales amount.
4. Average Deal Size: Obtained by dividing the total sales amount by the distinct count of order numbers.
5. Cumulative Sales Revenue Calculated Column: Utilizing a calculated column, the cumulative sales revenue was computed based on the cumulative sum of sales amounts over time.

## Key Result Areas:
The analysis yielded significant insights:
-Last Year's Sales Performance: Sales revenue for the last year amounted to 15,690,000 million, comprising 1,596 orders. The net profit reached 6,628,600 million, with a gross margin of 40%.
-Top Product and Customer: The best-selling product was identified as "Better Large Canned Shrimp," and the primary customer contributing to sales was "Acer Superstore."
-Profitable Customer Type: The net profit for the company was predominantly generated from customers classified under the "G2" customer type.
-Customer Distribution: The majority of customers were identified as international customers.


These insights collectively provide a comprehensive overview of the company's sales performance, highlighting key metrics and influential factors shaping the business landscape.
Dashboard Presentation:
The project culminated in the creation of a dynamic dashboard in Power BI, visually representing the key findings. The dashboard provided an intuitive interface for stakeholders to interact with the data, enabling them to gain actionable insights and make informed business decisions.



## Conclusion:
This project not only addressed data anomalies but also provided a deep understanding of critical business metrics. The combination of data preparation, processing, and insightful visualizations in the dashboard offered a holistic view of the company's performance, facilitating strategic decision-making for future growth and optimization.
