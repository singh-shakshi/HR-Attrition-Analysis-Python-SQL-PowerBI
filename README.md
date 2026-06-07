# 📊 HR Attrition Intelligence System
### *Analytics + Decision Support | BCA Final Year Project*

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

> **Shakshi Singh | BCA Final Year | Data Analytics Aspirant | Academic Year 2025–26**

---

## 🧠 Objective

This project converts raw HR employee data into a **decision-support analytics system** that helps identify high-risk employee segments and understand the key drivers behind employee attrition.

The system is designed to answer:
- 🔴 Which employee groups are most likely to leave?
- 📉 What business factors drive attrition the most?
- 💡 Which actionable HR interventions can reduce attrition?

---

## 🎯 Business Problem

Employee attrition leads to high **hiring cost**, **training cost**, and **productivity loss**.

This project focuses on identifying:
- High-risk employee segments
- Key drivers of attrition
- Department-wise and salary-wise vulnerability patterns
- Retention strategy opportunities

---

## 📂 Dataset

| Detail | Info |
|---|---|
| **Source** | IBM HR Analytics Employee Attrition Dataset (Kaggle) |
| **Records** | 1,470 employees |
| **Features** | 28 attributes |
| **Target Variable** | Attrition (Yes / No) |
| **Data Quality** | Clean dataset (no missing values) |

🔗 [Download Dataset from Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## 🧠 Methodology

### 1. Data Preprocessing
- Removed redundant/constant columns
- Created derived features:
  - Age bands
  - Salary bands
  - Tenure categories

### 2. SQL Analysis Layer
Used SQL to extract business-level insights:
- Department-wise attrition rate
- Salary-based attrition distribution
- Tenure-wise employee risk segmentation

> 👉 Purpose: simulate real-world HR database querying

### 3. Python Analysis Layer
Performed exploratory data analysis using Python:
- Attrition distribution analysis
- Correlation analysis
- Segment-wise comparisons

| Library | Purpose |
|---|---|
| Pandas | Data manipulation |
| NumPy | Numerical processing |
| Matplotlib / Seaborn | Visualization |

### 4. Power BI Dashboard Layer
Built an interactive executive dashboard including:
- KPI cards (Attrition Rate, Total Employees)
- Department-wise attrition breakdown
- Salary vs Attrition segmentation
- Tenure risk analysis
- Role-based attrition comparison

---

## 📸 Dashboard Preview

![HR Analytics Dashboard](images/dashboard.png)

> *Interactive Power BI dashboard showing attrition KPIs, department-wise breakdown, salary slab analysis, tenure risk, and job role comparison.*

---

## 📊 Key Insights

| Metric | Value |
|---|---|
| 📊 Overall Attrition Rate | **20.5%** (301 out of 1,470 employees) |
| 🏢 Highest Dept. Attrition | **HR Department — 26.81%** |
| 💰 Highest Salary Risk Band | **≤ ₹35,000 → 27.26% attrition** |
| ⏳ Highest Tenure Risk | **0–3 Years → 22.34% attrition** |
| 🧑 Highest Age Risk | **18–25 Years → 25.15% attrition** |
| 🚨 Top Risk Job Role | **Sales Executive → 39.8% attrition** |

---

## 🚨 High-Risk Employee Segment

> The most vulnerable employee profile:

**Low salary + Early tenure + Sales/HR role + Young age group**

This segment represents the **highest replacement cost** and **attrition risk exposure** at **31.1% attrition rate** — significantly above the 20.5% average.

---

## 💡 Business Recommendations

- ✅ Improve onboarding retention programs for **first 3 years**
- ✅ Review compensation structure for **low salary bands (≤ ₹35K)**
- ✅ Focus retention strategies on **Sales and HR departments**
- ✅ Strengthen **early-career engagement programs**

---

## 🛠️ Tech Stack

| Tool | Role |
|---|---|
| **Python** | Data cleaning, EDA |
| **SQL** | Aggregated business insights |
| **Power BI** | Dashboard & visualization |
| **Pandas** | Feature engineering |

---

## ▶️ How to Run This Project

### Python Analysis
```bash
# 1. Clone the repository
git clone https://github.com/singh-shakshi/HR-Attrition-Analysis-Python-SQL-PowerBI.git

# 2. Install required libraries
pip install pandas numpy matplotlib seaborn jupyter

# 3. Open the notebook
jupyter notebook notebooks/hr_attrition_analysis.ipynb
```

### SQL Queries
- Open `sql/attrition_queries.sql` in any SQL editor (MySQL Workbench, DBeaver, etc.)
- Import the CSV as a table named `employees`
- Run queries one by one

### Power BI Dashboard
- Open `dashboard/HR_Attrition_Dashboard.pbix` in **Power BI Desktop**
- Refresh data source if prompted and point to the CSV file

---

## 📈 Results & Conclusion

The analysis confirms that **no single factor alone explains attrition**. The overlap of **low salary + short tenure + a target-driven role** creates a significantly higher-risk combination.

Key takeaways for HR teams:
- Prioritise retention efforts for **new joiners in the first 3 years**
- Review compensation for employees in the **sub-₹35K salary band**
- Pay special attention to the **HR and Sales departments**
- Focus retention programmes on **Sales Executives** — the highest-risk job role

---

## 🔮 Future Enhancements

- [ ] Build machine learning model to predict attrition probability
- [ ] Deploy dashboard using Streamlit / Flask
- [ ] Add real-time HR data integration
- [ ] Improve feature engineering with behavioral metrics

---

## 👤 Author & Contact

**Shakshi Singh**
BCA Final Year | Data Analytics Aspirant
Academic Year: 2025–26

[![GitHub](https://img.shields.io/badge/GitHub-singh--shakshi-black?style=flat&logo=github)](https://github.com/singh-shakshi)

---

> ⭐ *If you found this project useful, consider starring the repository!*
