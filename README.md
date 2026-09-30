DAX Query Dashboard

📊 Project Overview

This Power BI project demonstrates the practical use of DAX (Data
Analysis Expressions) to create dynamic measures, KPIs, calculations,
and interactive dashboard visualizations.

The goal is to convert raw business data into meaningful insights using
Power BI, DAX, data modeling, and visualization.

🛠️ Tools & Technologies

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query

Microsoft Excel / CSV

Data Modeling

Data Visualization

🎯 Key Objectives

Create business KPIs using DAX.

Build dynamic measures and calculations.

Analyze data using filter and row context.

Perform category and trend analysis.

Create interactive Power BI dashboards.

Present data-driven business insights.

🧮 DAX Concepts Used

The project covers practical use of:

SUM()

AVERAGE()

COUNT()

COUNTROWS()

DISTINCTCOUNT()

CALCULATE()

FILTER()

IF()

DIVIDE()

SUMX()

AVERAGEX()

Variables using VAR and RETURN

Filter context

Row context

Calculated columns

Calculated measures

Time-based analysis

📈 Dashboard Features

KPI cards

Interactive charts

Category-wise analysis

Trend analysis

Comparative analysis

Slicers and filters

Dynamic DAX measures

Drill-down analysis

💻 Example DAX Queries

Total Sales

Total Sales = SUM(Sales[SalesAmount])

Total Orders

Total Orders = DISTINCTCOUNT(Sales[OrderID])

Average Sales

Average Sales = AVERAGE(Sales[SalesAmount])

Profit Margin

Profit Margin =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)

Performance Status

Performance Status =
IF(
    [Total Sales] >= 100000,
    "Target Achieved",
    "Below Target"
)

🔄 Project Workflow

Raw Data
   ↓
Power Query
   ↓
Data Cleaning & Transformation
   ↓
Data Model
   ↓
DAX Measures
   ↓
Power BI Visualizations
   ↓
Business Insights

📂 Suggested Repository Structure

DAX-Query-Dashboard/
│
├── README.md
├── DAX Query Dashboard.pbix
├── Data/
│   └── source_data.xlsx
├── DAX/
│   └── dax_queries.txt
├── Screenshots/
│   └── dashboard.png
└── Documentation/
    └── project-notes.md

💡 Business Insights

The dashboard can be used to:

Monitor overall performance.

Identify high- and low-performing categories.

Understand trends over time.

Compare business segments.

Track KPIs against targets.

Support data-driven decisions.

Note: Actual insights depend on the dataset used in the Power BI
dashboard.

🎓 Skills Demonstrated

Data Analysis

DAX

Power BI

Data Modeling

Power Query

KPI Development

Business Intelligence

Dashboard Design

Analytical Thinking

👨‍💻 Author

Raj Jaiswal

B.Tech -- Information Technology
Government Engineering College, Bilaspur

Connect With Me

LinkedIn: https://www.linkedin.com/in/raj-jaiswal-644782336

GitHub: https://github.com/rajjais1232-coder

Portfolio:
https://portfolio-website-8p9oi8tbn-rajjais1232-coders-projects.vercel.app

⭐ Purpose

This project is part of my Data Analytics / Business Intelligence
portfolio and demonstrates practical skills in Power BI, DAX, data
modeling, and business analytics.
