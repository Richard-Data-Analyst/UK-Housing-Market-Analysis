# UK-Housing-Market-Analysis
# UK Residential Property Market Intelligence Dashboard

## 📌 Project Overview
This project analyzes over 1 million rows of UK Land Registry data to identify regional price trends and sales volumes. It demonstrates a full-stack data pipeline from raw data ingestion to interactive visualization.

## 🛠️ Tech Stack
*   *Database:* Microsoft SQL Server (T-SQL)
*   *Visualization:* Power BI Desktop
*   *Data Source:* GOV.UK Land Registry Price Paid Data

## 🚀 Key Features & Challenges
*   *Large-Scale ETL:* Processed a massive CSV file using SQL Server, overcoming an *Arithmetic Overflow* error by casting price data to BIGINT.
*   *Data Transformation:* Built a SQL View to clean raw headers and standardize date formats for reporting.
*   *Interactive Insights:* Created a Power BI dashboard featuring a UK map of price hotspots and sales volume rankings by county.
