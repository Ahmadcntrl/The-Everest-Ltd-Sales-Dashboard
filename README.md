# The Everest Ltd | Sales Performance Analysis
## 📌 Project Overview
This project involved transforming raw, unorganized sales data into a professional, interactive dashboard for The Everest Ltd. The goal was to provide executive leadership with a clear view of profitability across different regions, shipping modes, and customer segments.

## 📊 Final Dashboard Preview
## 🛠️ Technical Workflow (End-to-End)
Following strict business requirements, the project was executed in three primary phases:

### 1. Data Transformation (Power Query)
Before analysis, I used Power Query to perform heavy data cleaning and ETL:

- Data Standardization: Converted Order Date and Ship Date columns to proper date formats and ensured the Ship Mode column used proper case.

- Logic Mapping: Replaced numerical segment codes (1, 2, 3) with descriptive labels: Consumer, Home Office, and Corporate.

- Feature Engineering: Split the complex string 'City | State - Region' into three distinct columns named 'City', 'State', and 'Region'.

- Data Sanitization: Removed irrelevant columns (Country, Currency Service, etc.), handled blank rows, and stripped unwanted spaces.

### 2. Analysis & Modeling (Pivot Tables)
I built a robust data model using #Pivot Tables to calculate the following Key Performance Indicators (KPIs):

- Total Quantity Sold: 149,765 units.

- Total Sales Amount: PKR 9.13M.

- Total Profit: PKR 8.71M.

#Total Discounts Applied: PKR 364,033.

### 3. Visualization & UI Design
The final dashboard was designed for high readability and interactivity:

- Temporal Analysis: A doughnut chart showing Yearly Profit, highlighting a peak in 2019 at 30%.

- Operational Insights: A bar chart for Ship Mode by Profit, revealing that "Standard" class is the primary profit driver.

- Geographic Deep-Dive: A "State by Profit" bar chart showing #California as the lead market.

- Interactivity: Integrated #Category and Sub-Category Slicers for real-time data exploration.

## 💡 Key Business Insights
- Regional Strength: The West (32%) and East (30%) regions are the primary profit drivers, combined contributing 62% of total profit.

- Customer Loyalty: Profit is well-distributed, with Raymond Buch leading at PKR 67,341.

- Profitability: The company maintains a remarkably high profit-to-sales ratio, with total profit reaching PKR 8.71M.
