# Banking-EDA

## 📌 Overview  
This project demonstrates an end-to-end data analysis workflow for the banking domain using:
- **Python** for data cleaning, transformation, and exploratory analysis
- **SQL** for structured data storage and SQL queries
- **Power BI** for dashboard and visualization

The goal is to explore customer and transaction behavior, detect trends and outliers, and provide insights through visual storytelling.

---

## 📁 Project Structure
banking-eda-project/
│
├── data/
│ ├── customer_accounts.csv
│ └── banking_transactions.csv
│
├── sql/
│ └── schema_and_queries.sql
│
├── python/
│ └── eda_analysis.ipynb
│
└── powerbi/
└── Banking_Dashboard.pbix

Python key operations:

- Load data from CSV files
- Summary statistics
- Null value checks and handling
- Correlation matrix
- Data visualization using seaborn and matplotlib

Power BI Dashboard:
Open powerbi/Banking_Dashboard.pbix in Power BI Desktop.

Dashboard includes:
- KPIs: Total transactions, total amount
- Region-wise breakdown
- Customer segmentation
- Currency normalization using DAX
- Interactive filters and slicers

  EDA Highlights in Python:
- Visualize interest rate distributions
- Analyze delayed payments by age
- Correlation heatmap for numeric features
- Segment customers by transaction patterns

  Objectives Achieved
- Built a relational database for banking data
- Cleaned and analyzed customer behavior in Python
- Created an interactive dashboard to visualize key banking metrics
- Gained insights on customer trends, risk segments, and financial operations
