# Mining Insight Workbench

## Overview

This project focuses on analyzing data using Python and SQL to extract useful insights.

The goal was to practice thinking like a data analyst — not just running code, but actually understanding what the data is saying.

## Why I built this

I wanted to improve my ability to explore datasets and answer real questions using data.

Instead of just plotting graphs, I focused on identifying patterns like trends, top categories, and performance over time.

## What it does

- Loads and explores datasets using Pandas
- Uses SQL queries to extract insights
- Performs aggregations and filtering
- Generates basic summaries and trends

## Tech used

- Python
- Pandas
- SQL

## Example insights

- Which categories generate the most revenue
- How performance changes over time
- Distribution of sales across different segments

## Example query

```sql
SELECT strftime('%Y-%m', date) AS month, SUM(sales) AS total_sales
FROM transactions
GROUP BY month
ORDER BY month;
