# COCACOLA_STOCK_ANALYSIS
Power BI dashboard and SQL analysis of Coca Cola stock(2019-2023) trends, returns, volatility, and key financial insights.

Coca-Cola Stock Analysis Dashboard: Power BI and SQL

Project Overview

This project analyzes Coca-Cola stock performance. It explores stock trends, returns, volatility, trading volumes, and key performance indicators to provide insights for investors using Power BI for visualization and SQL for data cleaning & transformations.

Dataset

Source: Kaggle

Fields:

Date (trading day) Open, High, Low, Close, Adj Close (prices) Volume (traded shares)

Steps performed in SQL:

Checked duplicates & null values

Validated Open vs Close consistency

Ensured Low ≤ High

Checked for unrealistic volume spikes

Calculated Daily, Monthly, Quarterly Returns

Derived Volatility % (High–Low)

Added 7-day & 30-day Moving Averages

Insights & Analysis

Business questions:

1.Trend Over Time

Highest and Lowest Prices

On which day did Coca Cola stock gain the most, and on which day did it fall the most?

What is the average closing price per month and per year?

Which days had the highest and lowest trading volumes?, Is there a trend in trading volume over time?

Which days had the largest difference between High and Low prices?

What is the 7days and 30days moving averages of Adj Close ?

How often does the stock close higher than it opens?

What is the distribution of daily /monthly/quarterly/yearly returns %?

Does Coca-Cola stock show any seasonal patterns /stronger performance in certain months/quarters?

Dashboard Features

Built in Power BI:

*KPI Cards: 1.Latest Stock Price

2.YTD Return %

3.Best & Worst Day with Date

*Interactive Filters: Year, Quarter

*Visuals:

1.Line Chart: 7-day & 30-day Moving Averages

2.Column Chart: Monthly Returns %

3.Line Chart: Daily Returns %

4.Line Chart: Cumulative Growth %

5.Line Chart: Average Daily Volatility %

6.Column Chart (bins): Distribution of Returns

*DAX with AI

Tools & Tech

Power BI: Dashboard & KPIs

PostgreSQL: Data Cleaning

GitHub: Project Hosting

Key Learnings

Hands-on with time-series stock data analysis

Building financial KPIs like YTD Returns

Data storytelling with Power BI dashboards

Using SQL for real-world data cleaning

Dashboard Preview
https://github.com/shrutispatil/COCACOLA_STOCK_ANALYSIS/blob/main/Dashboard%20Cocacola.png?raw=true

Author

Shruti Patil

Email: pshruti.connect@gmail.com

LinkedIn: www.linkedin.com/in/shrutipatil98
