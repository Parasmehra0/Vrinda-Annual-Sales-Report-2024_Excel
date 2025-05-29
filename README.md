# Vrinda Annual Sales Report Excel
📊 Vrinda Annual Sales Report 2024
This project contains a comprehensive Excel-based sales analysis of Vrinda Store's annual performance in 2024. The insights are derived from detailed data exploration and visualization using pivot tables, charts, filters, slicers, and custom formulas.

🧾 Files Included

Vrinda Annual Sales report 2024.xlsx – Final report with analysis, pivot tables, slicers, and charts

Raw Data Sheet – Contains transaction-level data (e.g., Order ID, Gender, Age, Channel, City, Status)

Analysis Sheet – Columns added for Age Group categorization, charts, pivot tables, etc.

🛠️ Columns Created for Analysis

Age Group: Categorized using a formula:

Age Group = IFS(E2>=50,"Senior", E2>=30,"Adult", E2<30,"Teenage")

Month: Extracted from order date for monthly trends.

Month = TEXT(G2,"mmm")

📈 Charts & Pivot Tables

Sales by Month: Column & Line combo chart

Sales by City and Gender: Stacked Column chart

Top Performing Channels: Pie chart

Sales by Age Group: Bar chart

Pivot Tables: To summarize sales by City, Channel, Gender, and Age Group.
