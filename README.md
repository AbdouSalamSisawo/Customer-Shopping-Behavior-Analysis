# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional retail data to uncover meaningful trends, purchasing patterns, and key drivers of customer decision-making. The goal is to support data-driven marketing, product optimization, and customer engagement strategies by combining **Python**, **SQL (MySQL)**, and **Power BI** in a complete end-to-end analytics workflow.

The project follows a real-world data analytics pipeline: data preparation and exploration in Python, structured analysis in MySQL, and interactive visualization in Power BI.

---

## 🎯 Business Objective

A retail company has observed changes in customer purchasing behavior across demographics, product categories, and sales channels. Management seeks to understand:

* What factors influence customer purchasing decisions
* How subscriptions and discounts affect spending behavior
* Which products and categories perform best
* How customer behavior can be leveraged to improve engagement and retention

**Key Business Question:**
*How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?*

---

## 🛠️ Tools & Technologies

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
  → Data cleaning, exploratory data analysis (EDA), feature engineering

* **MySQL / MySQL Workbench**
  → Structured data storage, aggregation, and analytical queries

* **Power BI Desktop**
  → Interactive dashboards and business insights visualization

* **Jupyter Notebook**
  → Development and documentation of Python analysis

---

## 📂 Project Structure

```
customer-shopping-behavior-analysis/
│
├── data/
│   ├── raw/                     # Original dataset(s)
│   └── processed/               # Cleaned and transformed data
│
├── notebooks/
│   ├── data_exploration.ipynb    # EDA and data understanding
│   ├── data_cleaning.ipynb       # Cleaning and preprocessing steps
│
├── sql/
│   ├── customer_analysis.sql     # SQL queries for analysis
│
├── powerbi/
│   ├── customer_dashboard.pbix   # Power BI dashboard file
│
├── report/
│   ├── Customer_Shopping_Behavior_Report.pdf
│
└── README.md
```

---

## 🔄 Project Workflow

### 1️⃣ Data Preparation & Exploration (Python)

* Loaded raw transactional data
* Cleaned column names and data types
* Handled missing values and inconsistencies
* Explored data distributions (e.g., review ratings, purchase amounts)
* Created derived features to support analysis

### 2️⃣ Database Analysis (MySQL)

* Loaded cleaned data into a MySQL database
* Wrote SQL queries to:

  * Aggregate revenue and purchase metrics
  * Compare subscribed vs non-subscribed customers
  * Analyze discount usage across products
  * Segment customers based on purchasing behavior

### 3️⃣ Visualization & Insights (Power BI)

* Connected Power BI to MySQL database
* Built an interactive dashboard including:

  * Subscription status distribution
  * Product and category performance
  * Key business metrics (KPIs)
* Used Power BI Model View to verify data structure

### 4️⃣ Reporting

* Compiled insights into a structured analytical report
* Included figures, tables, and dashboard screenshots
* Provided business-oriented recommendations

---

## 📊 Key Insights (High-Level)

* Subscribed customers tend to show higher engagement and spending patterns
* Certain product categories contribute disproportionately to total revenue
* Review ratings are generally skewed towards positive values
* Discounts play a role in purchase behavior but require strategic optimization

---

## 📈 Power BI Dashboard

The Power BI dashboard presents an interactive overview of customer behavior and key metrics. It enables stakeholders to explore data dynamically using filters and visuals.

> Note: The dashboard is designed for **local use** and does not require Power BI Service sign-in.

---

## 🧾 Stakeholder Presentation

In addition to the analytical report and dashboard, a **stakeholder-focused presentation** was generated using **Google NotebookLM**. The presentation translates technical findings into clear, business-oriented insights suitable for industry audiences, including managers and decision-makers.

The slides emphasize:

* Business context and problem framing
* Key customer behavior insights
* Strategic implications of subscriptions, discounts, and product performance
* Actionable recommendations for improving engagement and revenue

This presentation is designed to complement the Power BI dashboard by providing a concise narrative that supports executive-level decision-making. The Power BI dashboard presents an interactive overview of customer behavior and key metrics. It enables stakeholders to explore data dynamically using filters and visuals.

> Note: The dashboard is designed for **local use** and does not require Power BI Service sign-in.

---

## 🚀 How to Run the Project

1. Clone this repository
2. Open the Jupyter notebooks to view Python analysis
3. Import the processed dataset into MySQL
4. Run SQL queries using MySQL Workbench
5. Open the `.pbix` file in Power BI Desktop to view the dashboard

---

## ⚠️ Notes & Limitations

* The analysis is limited to the scope and quality of the provided dataset
* Some variables show limited variation, which may affect comparative analysis
* Results should be interpreted within the context of the available data

---

## 👤 Author

**Abdou Salam Sisawo**
Computer Science Student
Albukhary International University

---

## 📄 License

This project is for academic and educational purposes.

---

*End of README*
