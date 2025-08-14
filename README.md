# Amazon-Sales-Forecasting (2019-2025)
Amazon Sales Forecasting (2019–2025)  This project predicts Amazon store sales from 2019 to 2025 using historical data from 2019–2020. The forecasting is done using Facebook Prophet, and results are visualized in an interactive Power BI dashboard.



📌 Project Overview

Goal: Predict future monthly sales trends for better business planning.

Data Source: Amazon Sales Dataset (2019–2020) – cleaned and processed.

Forecasting Method: Facebook Prophet (time series forecasting).

Visualization Tool: Power BI for interactive dashboard & trend analysis.

📂 Steps Performed

Data Preprocessing

Imported the Excel dataset.

Cleaned null/missing values.

Converted Order Date to datetime format.

Aggregated sales on a monthly basis.

Forecasting with Prophet

Trained Prophet model on monthly sales data.

Predicted sales up to December 2025.

Generated confidence intervals (yhat_lower, yhat_upper).

Exporting Forecast Data

Saved predictions (ds, yhat, yhat_lower, yhat_upper) as CSV.

Imported the CSV into Power BI.

Power BI Dashboard

Connected original sales data + forecast data.

Created sales trend and forecast visuals.

Displayed prediction ranges and actual historical trends.

Added slicers for year, quarter, month filtering.

📄 Power BI Dashboard Pages
1️⃣ Executive Summary

KPIs: Total Sales, Total Customers, Total Orders, Total Profit.

Purpose: Quick business health overview.

2️⃣ Sales Performance Insights

Total Sales by Category.

Total Sales by Order Date.

Profit Margin by Product Name.

Sum of Sales by Sub-Category.

Sum of Sales by Segment.

Filters for flexible analysis.

3️⃣ Advanced Analytics & Forecasting

KPI Cards:

Sales MTD (Month-to-Date)

Orders MTD

Profit MTD

Sales YTD (Year-to-Date)

Orders YTD

Profit YTD

Visuals:

Sales Distribution by State and Region (Map View)

Sales Forecast for upcoming months (Prophet model output)

📊 Model Output

yhat → Predicted sales (main forecast line).

yhat_lower → Lower bound of confidence interval.

yhat_upper → Upper bound of confidence interval.

🛠 Tech Stack

Python (pandas, prophet, matplotlib)

Power BI (visualization & dashboard creation)

Excel (original dataset storage)

📈 Dashboard Features

Historical sales trends (2019–2020)

Forecasted sales (2021–2025)

Confidence intervals for predictions

Date hierarchy (Year → Quarter → Month)

Interactive slicers and filters

Separate pages for KPIs, performance insights, and forecasting

🚀 How to Run the Code

Install dependencies:

pip install pandas prophet matplotlib openpyxl


Run the Python script to generate forecast CSV.

Import CSV into Power BI.

Connect to your sales dataset for comparison.

📌 Author

Smriti Pandey – Data Science & AI Enthusiast
