<p align="center">
  <img src="banner.jpg" alt="Data Analytics Banner" width="100%"/>
</p>
<h1 align="center">👨🏻‍💻 Customer Shopping Behavior Analysis</h1>
<h3 align="center">End-to-End Data Analytics Project</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-2ea44f?style=flat-square"/>
  <img src="https://img.shields.io/badge/Domain-Data%20Analyst-378ADD?style=flat-square"/>
  <img src="https://img.shields.io/badge/Type-End--to--End%20Project-9B59B6?style=flat-square"/>
</p>

---

## 📖 Overview

This project demonstrates a complete **end-to-end data analytics workflow** using Python, SQL, MySQL, and Power BI. The objective is to analyze customer shopping behavior, identify business trends, and generate actionable insights through data visualization and reporting.

The project simulates a real-world analytics environment where raw customer transaction data is transformed into meaningful business intelligence for decision-making.

---

## 📌 Project Objectives

| # | Objective |
|---|-----------|
| 1 | Analyze customer purchasing behavior |
| 2 | Identify revenue-driving product categories |
| 3 | Understand customer demographics and shopping patterns |
| 4 | Perform SQL-based business analysis |
| 5 | Build an interactive Power BI dashboard |
| 6 | Generate business insights and recommendations |

---

## 🛠️ Tools & Technologies

| Category | Tools |
|----------|-------|
| **Language** | Python 3.x |
| **Libraries** | Pandas, NumPy |
| **Database** | MySQL, SQL |
| **Visualization** | Power BI |
| **Environment** | Jupyter Notebook |
| **Version Control** | Git & GitHub |

---

## 🔄 Project Workflow

```
📂 CSV Dataset
      │
      ▼
🐍 Python — Data Cleaning & EDA
      │
      ▼
🗄️  MySQL Database — Data Storage
      │
      ▼
🔍 SQL — Business Analysis Queries
      │
      ▼
📊 Power BI — Interactive Dashboard
      │
      ▼
💡 Business Insights & Reporting
```

---

## 📁 Repository Structure

```
customer-shopping-analysis/
│
├── 📂 dataset/
│   └── customer_shopping_data.csv
│
├── 📂 notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_sql_analysis.ipynb
│
├── 📂 sql/
│   ├── schema.sql
│   └── business_queries.sql
│
├── 📂 dashboard/
│   └── shopping_dashboard.pbix
│
├── 📂 reports/
│   └── insights_summary.pdf
│
├── banner.svg
└── README.md
```

---

## 📊 Key Analysis Areas

### 1. Revenue Analysis
- Top-performing product categories by total revenue
- Monthly and seasonal revenue trends
- Average order value by customer segment

### 2. Customer Demographics
- Age group distribution and spending patterns
- Gender-based purchasing behavior
- Location-wise customer concentration

### 3. Shopping Patterns
- Peak shopping hours and days
- Preferred payment methods
- Repeat purchase frequency

### 4. SQL Business Queries
```sql
-- Top 5 revenue-generating categories
SELECT 
    category,
    SUM(amount) AS total_revenue,
    COUNT(*) AS total_orders
FROM customer_shopping
GROUP BY category
ORDER BY total_revenue DESC
LIMIT 5;
```

```sql
-- Customer segmentation by age group
SELECT 
    CASE 
        WHEN age BETWEEN 18 AND 25 THEN '18–25'
        WHEN age BETWEEN 26 AND 35 THEN '26–35'
        WHEN age BETWEEN 36 AND 50 THEN '36–50'
        ELSE '50+'
    END AS age_group,
    COUNT(*) AS customer_count,
    ROUND(AVG(amount), 2) AS avg_spend
FROM customer_shopping
GROUP BY age_group
ORDER BY avg_spend DESC;
```

---

## 💡 Key Insights

- 🛍️ **Clothing & Electronics** account for the highest revenue share
- 📅 **Weekends** see 40% more transactions than weekdays
- 👥 The **26–35 age group** has the highest average order value
- 💳 **Credit card** is the most preferred payment method
- 🔁 Customers with loyalty memberships show **2.3× higher retention**

---

## 📈 Power BI Dashboard

The interactive dashboard includes:
- Revenue KPI cards (total revenue, avg. order value, total customers)
- Category-wise sales bar chart
- Monthly trend line chart
- Customer demographic pie charts
- Geographic heat map

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/customer-shopping-analysis.git

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql jupyter

# 3. Set up MySQL database
mysql -u root -p < sql/schema.sql

# 4. Launch Jupyter Notebook
jupyter notebook notebooks/01_data_cleaning.ipynb
```

---

## 🎯 Project Impact

This project demonstrates the ability to:

- ✅ Design and execute a full analytics pipeline from raw data to dashboard
- ✅ Clean and preprocess real-world messy datasets using Python
- ✅ Load and query structured data efficiently in MySQL
- ✅ Write complex SQL queries for business analysis
- ✅ Build interactive, stakeholder-ready dashboards in Power BI
- ✅ Communicate data-driven insights for business decision-making

---

## 👨🏻‍💻 Author
MIHIRR DOBARIYA

**Your Name**
📧 Email: mihirofficial33.edu@gmail.com 

💼 LinkedIn: [linkedin.com/in/mihirr51](https://linkedin.com/in/mihirr51)

🐙 GitHub: [github.com/mihirr00051](https://github.com/mihirr00051)

---

> *"Without data, you're just another person with an opinion." — W. Edwards Deming*

---

<p align="center">⭐ If you found this project helpful, please give it a star!</p>
