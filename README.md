Requirement

✅ Step 1: Identify and remove duplicates to avoid skewed analysis. 
✅ Step 2: Detecting null values  
✅ Step 3: Treating null values 
✅ Step 4: Handle negative values in numeric columns  
✅ Step 5: Fix inconsistent date formats and invalid dates. 
✅ Step 6: Validate and correct email addresses. 
✅ Step 7: Check and correct data types for seamless analysis.

Create an interactive dashboard using power bi after cleaning that . Use power query to clean the data. Show KPI's, charts and data visualization in html format. Use power bi to create a dashboard. Need clean and interactive dashboard in html format. As I need to show it to my manager.


🧹 Data Cleaning (7 Steps Applied to your 1,004-row file)
StepIssue FoundAction Taken14 duplicate rowsRemoved — 1,000 clean rows remain2Nulls in 8 columnsDetected — names, emails, category, price, amounts, address3Null treatmentNames → "Unknown", amounts recalculated from price × qty, price filled by category median4318 negative quantities & 234 negative amountsConverted to absolute values551 invalid dates (e.g., Feb 30, 2024)Replaced with median date6102 invalid emails (no @ sign)Replaced with invalid@placeholder.com78 inconsistent payment labelsNormalized to 5 clean values (Credit Card, Debit Card, Bank Transfer, PayPal, Unknown)

📊 Dashboard Features

5 KPI Cards — Total Revenue ($10.80M), Orders, Avg Order Value, Customers, Units Sold
Monthly Revenue Trend — 24-month line chart with fill
Revenue by Category — Donut chart + custom legend with percentages
Category Bar Chart — Horizontal bars for quick comparison
Delivery Status — Doughnut with 7 status types
Payment Methods — Bar chart with normalized labels
Quarterly Revenue — Color-coded by quarter (Q1–Q4)
Units Sold Mini-bars — Animated progress bars per category
Top 10 Customers Table — With revenue, orders, and status pills
Cleaning Summary Cards — All 7 steps at a glance
Interactive Filters — Filter by Year (2023/2024/2025) and Category — all charts update live
