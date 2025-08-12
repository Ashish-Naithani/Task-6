# Sales Data Analysis with SQL

## 📌 Project Overview
This project focuses on analyzing sales data using SQL to extract meaningful insights about revenue and order volume over time.
The key objective was to leverage SQL functions and clauses for time-based aggregation, sorting, and filtering of results.

##🛠️ Key Steps & Queries Used
Extract Month from Date

Used EXTRACT(MONTH FROM order_date) to identify the month of each order.

Group Data by Time Periods

Applied GROUP BY for year and month to aggregate data.

Calculate Revenue

Used SUM() on sales amounts to compute total revenue per period.

Measure Order Volume

Applied COUNT(DISTINCT order_id) to count unique orders.

Sort Results

Used ORDER BY to arrange data in a meaningful order (e.g., descending revenue).

Filter by Time Periods

Limited results to specific months or years for focused analysis.

## 📊 Insights & Usage
Monthly revenue trends to monitor business performance.

Order volume analysis to understand demand patterns.

Ability to filter and focus on particular time ranges.

## 🧑‍💻 Tech Stack
SQL (MySQL)

Sales dataset with order_date, order_id, and revenue columns.
