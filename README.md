# Customer_shopping_behaviour
data analysis project showcasing  customer shopping behaviour analysis using python,sql and powerbi

# 🛍️ Customer Shopping Behavior Analysis
### End-to-End Data Analytics Project | Python • SQL • Power BI

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?logo=pandas)
![SQL](https://img.shields.io/badge/SQL-Database-orange?logo=postgresql)
![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-success?logo=github)

---

# 📌 Project Overview

This project presents an end-to-end data analytics solution focused on understanding customer shopping behavior in a retail business.

Using Python for data preparation, SQL for business analysis, and Power BI for interactive visualization, the project converts raw transactional data into actionable business insights that support data-driven decision making.

The project follows a real-world analytics workflow commonly used by data analysts in industry.

---

# 🎯 Business Objective

Retail organizations collect massive amounts of customer transaction data every day. However, extracting meaningful insights from this data remains a challenge.

The objective of this project is to answer questions such as:

- Which customer segments generate the highest revenue?
- Which product categories contribute most to sales?
- Does subscription status affect customer spending?
- Which age groups are the most valuable customers?
- Which shipping methods are most preferred?
- Which products receive the highest customer ratings?
- How do discounts influence purchasing behavior?

The findings help businesses improve marketing strategies, customer retention, inventory planning, and overall revenue generation.

---

# 📊 Dataset Information

**Dataset:** Customer Shopping Behavior Dataset

### Dataset Size

- **Rows:** 3,900
- **Columns:** 18

### Features

- Customer ID
- Age
- Gender
- Category
- Item Purchased
- Purchase Amount
- Review Rating
- Subscription Status
- Shipping Type
- Payment Method
- Discount Applied
- Previous Purchases
- Frequency of Purchases
- Season
- Size
- Color
- Location
- Promo Code

---

# ⚙️ Project Architecture

```
Customer Dataset
        │
        ▼
Python (Pandas & NumPy)
        │
Data Cleaning
        │
EDA & Feature Engineering
        │
        ▼
SQL Database
(PostgreSQL/MySQL)
        │
Business SQL Queries
        │
        ▼
Power BI Dashboard
        │
Business Insights
        │
Recommendations
```

---

# 🛠️ Technologies Used

| Tool | Purpose |
|------|----------|
| Python | Data Cleaning & Analysis |
| Pandas | Data Manipulation |
| NumPy | Numerical Analysis |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| SQL | Business Analysis |
| PostgreSQL / MySQL | Database |
| Power BI | Dashboard Development |
| Git | Version Control |
| GitHub | Project Repository |

---

# 🐍 Python Data Preparation

The data preprocessing stage includes:

- Loading dataset
- Dataset exploration
- Handling missing values
- Removing inconsistencies
- Renaming columns
- Feature engineering
- Creating Age Groups
- Purchase Frequency Analysis
- Preparing clean data for SQL

---

# 📈 Exploratory Data Analysis

EDA was performed to identify customer behavior patterns including:

- Customer demographics
- Purchase amount distribution
- Product category analysis
- Customer age analysis
- Gender analysis
- Subscription behavior
- Shipping preferences
- Customer review analysis
- Seasonal purchasing trends

---

# 🗄️ SQL Business Analysis

SQL was used to solve real-world business problems.

### Business Questions Solved

- Revenue by Gender
- High Spending Discount Users
- Top Rated Products
- Shipping Type Comparison
- Subscribers vs Non-Subscribers
- Discount Dependent Products
- Customer Segmentation
- Top Products by Category
- Repeat Buyers vs Subscription Status
- Revenue by Age Group

### SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- HAVING
- ORDER BY
- Aggregate Functions
- CASE WHEN
- Common Table Expressions (CTEs)
- Window Functions
- Joins
- Subqueries

---

# 📊 Power BI Dashboard

An interactive Power BI dashboard was developed to visualize key business metrics.

### Dashboard Features

### KPI Cards

- Total Customers
- Average Purchase Amount
- Average Review Rating

### Interactive Slicers

- Subscription Status
- Gender
- Category
- Shipping Type

### Visualizations

- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Distribution

---

 💼 Business Insights

The analysis identified several valuable business insights:

- Clothing generated the highest revenue among all product categories.
- Young Adults contributed the highest overall revenue.
- Most customers were non-subscribers.
- Express shipping customers spent slightly more on average.
- Loyal customers represented the largest customer segment.
- Certain products showed significantly higher discount dependency.
- Customer reviews remained consistently positive across products.

---

 📢 Business Recommendations

Based on the analysis:

- Increase subscription adoption through exclusive member benefits.
- Introduce loyalty programs for repeat customers.
- Optimize discount strategies to improve profitability.
- Promote high-rated products in marketing campaigns.
- Target high-value customer age groups with personalized offers.
- Improve inventory planning using product demand trends.

---

📂 Project Structure

```
Customer-Shopping-Behavior-Analysis
│
├── Dataset
│     └── customer_shopping_behavior.csv
│
├── Python
│     └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── SQL
│     └── customer_behavior_sql_queries.sql
│
├── Dashboard
│     └── customer_behavior_dashboard.pbix
│
├── Reports
│     ├── Customer Shopping Behavior Analysis.pdf
│     └── Business Problem Document.pdf
│
├── Images
│     └── Dashboard.png
│
└── README.md
```

---

# 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy
```

### Run the Project

1. Execute the Jupyter Notebook.
2. Load the cleaned data into your SQL database.
3. Run the SQL queries.
4. Open the Power BI dashboard (.pbix).
5. Explore the dashboard using interactive slicers.

---

# 📸 Dashboard Preview

> Add screenshots of your Power BI dashboard here.


<img width="1365" height="737" alt="image" src="https://github.com/user-attachments/assets/17901575-afb6-4850-9828-d2d526c53eef" />


---

# 🎯 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL Query Writing
- Database Management
- Business Analysis
- Data Visualization
- Power BI Dashboard Development
- KPI Design
- Data Storytelling

---

# 📈 Future Enhancements

- Customer Segmentation using Machine Learning
- Sales Forecasting
- Recommendation System
- Automated ETL Pipeline
- Live Database Connectivity
- Real-Time Power BI Dashboard

---

# 👨‍💻 Author

**Nani**

Aspiring Data Analyst

**Skills:** Python • SQL • Power BI • Excel • Pandas • NumPy • Data Visualization

📧 Email: nanit3022@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/thirunam-nagendra-kumar-167165313 


---

⭐ If you found this project useful, consider giving it a star on GitHub.
