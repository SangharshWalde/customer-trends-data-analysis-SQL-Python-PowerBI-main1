📊 Customer Behavior Data Analytics Project

Python • SQL • PostgreSQL • Power BI • Data Cleaning • EDA • Cohort Analysis

This project showcases an end-to-end, industry-standard analytics workflow for understanding customer shopping behavior and identifying patterns that impact revenue, loyalty, and marketing strategy.
The dataset includes 3,900+ customer transactions with demographic, product, discount, subscription, rating, and purchase history attributes.

🔍 1. Project Overview

Retail businesses often struggle to understand:

Which customer segments bring maximum revenue

How discounts impact profitability

What factors drive repeat purchases / loyalty

Which products perform best across demographics

How to design targeted marketing campaigns

This project answers these questions through a complete data analytics pipeline:

✔ Data Cleaning & Preprocessing (Python)
✔ Exploratory Data Analysis
✔ SQL-based analytical modeling
✔ Power BI dashboard
✔ Business insights + recommendations

🎯 2. Business Problem

A leading retail company has observed inconsistent buying behavior across:

demographics

product categories

seasons

discount campaigns

shipping preferences

The objective is to identify:

“How can customer shopping data be used to increase revenue, improve retention, and optimize product & marketing strategies?”

🏗️ 3. Architecture / Workflow
Raw CSV Data  
      │
Python (pandas)
- Data Cleaning
- Missing Value Imputation
- Feature Engineering
      │
PostgreSQL
- Data Modeling
- SQL Analytical Queries
- Cohort Segmentation
      │
Power BI
- KPI Dashboard
- Visual Insights
      │
Business Insights + Report + Presentation

🧹 4. Data Cleaning & Feature Engineering (Python)
✔ Cleaning Steps

Converted inconsistent column names → snake_case

Removed redundant column: promo_code_used

Validated datatypes & corrected casting issues

Handled missing values:

review_rating imputed using median rating within each category

✔ Feature Engineering

Age Segmentation using quantile groups

Young Adult

Adult

Middle-Aged

Senior

Numeric purchase frequency (weekly → 7 days, monthly → 30 days, etc.)

Normalized frequency_of_purchases

Created analytical fields for SQL modeling

🗂️ 5. SQL Analytical Modeling (PostgreSQL)

A total of 12+ advanced SQL queries were developed using:

CTEs

Window Functions

CASE Statements

Aggregations

Ranking Functions

Key business questions answered:
🔹 Revenue analysis

Revenue by gender

Revenue by age group

Revenue by shipping type

Revenue contribution by subscribers vs non-subscribers

🔹 Product performance

Top 5 highest-rated products

Top 3 products per category (window functions)

Products most dependent on discounts

🔹 Customer behavior

Segment customers into new, returning, loyal

Subscription behavior of repeat buyers

Discount usage among high spenders

📊 6. Power BI Dashboard

Dashboard Includes:

KPI Cards

Total Customers

Average Purchase Amount

Average Review Rating

Revenue by Category

Sales by Category

Revenue by Age Group

Subscription Status

Slicers: Gender, Category, Shipping Type, Subscription Status

This allows stakeholders to interactively explore customer behavior patterns.

👉 Add screenshots here when uploading to GitHub

/screenshots/dashboard_1.png
/screenshots/dashboard_2.png

🚀 7. Key Insights
⭐ High-Impact Discoveries

Young Adults contribute the highest revenue, indicating strong spending power.

Express Shipping customers spend 17–22% more on average.

5 products show heavy dependency on discounts, suggesting low organic demand.

Majority of repeat buyers are not subscribers → opportunity for subscription redesign.

Clothing-related items have higher average ratings than footwear.

⭐ Business Recommendations

Target Young Adults with premium product bundles.

Expand express shipping with loyalty incentives.

Reduce discount dependency via product repositioning.

Launch a redesigned subscription program with tailored rewards.

Cross-sell based on category-specific ratings and seasonality.

📁 8. Folder Structure
/customer-behavior-analytics
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_behavior_EDA.ipynb
│
├── sql/
│   └── analytical_queries.sql
│
├── dashboard/
│   └── powerbi_report.pbix
│
├── screenshots/
│   └── dashboard_1.png
│   └── dashboard_2.png
│
└── README.md

🛠️ 9. Tools & Technologies
Category	Tools
Languages	Python, SQL
Libraries	pandas, matplotlib, seaborn
Database	PostgreSQL
Visualization	Power BI
Concepts	Data Cleaning, EDA, Feature Engineering, SQL Analytics, BI Reporting, Cohort Analysis
▶️ 10. How to Run This Project
1. Clone the repository
git clone https://github.com/<your-username>/<repo-name>
cd customer-behavior-analytics

2. Install dependencies
pip install -r requirements.txt

3. Run the notebook
jupyter notebook

4. Import cleaned data into PostgreSQL

Use SQLAlchemy or PGAdmin.

5. Load the database into Power BI

Connect using:
localhost:5432 → Database → customer_behavior

📞 Contact

Sangharsh Walde
📧 sangharshwalde2701@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/sangharsh-walde-92b7b9201/

✅ Ready for GitHub
