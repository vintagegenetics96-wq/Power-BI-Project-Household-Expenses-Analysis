# Power-BI-Project-Household-Expenses-Analysis

📊 Power BI Project: Household Expenses Analysis
🔹 Project Objective
To analyze monthly household expenses and identify spending patterns, savings opportunities, and budget optimization using interactive Power BI dashboards.

🔹 Dataset Description
The dataset represents household expenses recorded over 12 months.

Columns:

Date

Month

Expense Category (Rent, Groceries, Utilities, Transport, Medical, Education, Entertainment, Others)

Payment Mode (Cash, UPI, Card)

Amount

Expense Type (Fixed / Variable)

🔹 Key KPIs
💰 Total Expenses

📆 Average Monthly Expense

🧾 Highest Expense Category

📉 Month-over-Month Expense Change

💳 Most Used Payment Mode

🔹 Dashboard Insights
Monthly Expense Trend – Line chart showing spending variation

Category-wise Expense Breakdown – Donut chart

Fixed vs Variable Expenses – Stacked column chart

Payment Mode Analysis – Bar chart

Top 5 Expense Categories – Ranked visual

Expense Heatmap – Month vs Category

🔹 Power BI Features Used
Power Query (Data Cleaning & Transformation)

DAX Measures:

Total Expenses

Average Monthly Expense

% Contribution by Category

MoM Growth

Interactive Slicers (Month, Category, Payment Mode)

Conditional Formatting

Drill-through Pages

🔹 DAX Measures
Total Expenses = SUM(Expenses[Amount])

Average Monthly Expense = 
AVERAGEX(
    VALUES(Expenses[Month]),
    [Total Expenses]
)

Category Contribution % =
DIVIDE([Total Expenses], CALCULATE([Total Expenses], ALL(Expenses[Expense Category])))
🔹 Business Insights
Rent and groceries contribute the highest to total expenses

Variable expenses fluctuate significantly during festive months

Digital payments dominate household spending

Identified months with unusually high expenses for budget control

🔹 Tools & Skills Highlighted
Power BI

DAX

Data Modeling

Data Visualization

Business Insight Generation


🔹 Skills: Power BI | DAX | Data Modeling | Data Visualization

#PowerBI #DataAnalytics #DataAnalyst #DashboardDesign #PersonalFinance



