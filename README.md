# 📊  Churn Analysis & Customer Intelligence

## 📌 Overview
This repository contains a complete project on **customer churn analysis** in the OTT industry (Netflix, Hotstar, Prime).  
It demonstrates how SQL + Python integration can be used to extract, clean, and analyze multi‑dimensional datasets (demographics, subscription tiers, support escalations) to identify **high‑risk subscribers** and generate actionable business insights.

---

## 🛠️ Tech Stack
- **Languages**: Python, SQL
- **Libraries**: pandas, numpy, sqlite3, matplotlib, seaborn
- **Concepts**: Data Cleaning, Feature Engineering, Churn Modeling, BI Dashboards

---

## 📂 Repository Structure

├── data/                # Raw and cleaned datasets
├── notebooks/           # Jupyter notebooks for analysis
│   ├── 01_data_extraction.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_churn_modeling.ipynb
│   └── 04_reporting_visuals.ipynb
├── scripts/             # Python scripts for SQL integration & analytics
│   ├── sql_connector.py
│   ├── feature_engineering.py
│   └── churn_analysis.py
├── visuals/             # Plots and BI dashboards
├── README.md            # Project documentation


---

## 🚀 Project Milestones
1. **Relational Data Extraction**  
   - Connect Python to SQL databases.  
   - Perform multi‑table JOINs to unify customer, subscription, and support data.  

2. **Advanced Feature Engineering**  
   - Calculate tenure, churn flags, customer aging.  
   - Encode categorical variables using `astype('category')`.  

3. **Executive Reporting**  
   - Build churn prediction models (Logistic Regression, Decision Trees).  
   - Visualize churn drivers and CLTV distribution.  
   - Deliver BI dashboards highlighting churn trends and retention strategies.  

---

## 🔍 Key Insights
- High churn among **basic tier users**.  
- Escalation frequency strongly correlated with churn.  
- Premium tier customers show **higher CLTV and lower churn**.  
- Top 20% of customers contribute ~70% of revenue.  

---

## 💡 Business Recommendations
- Personalized onboarding for new subscribers.  
- Loyalty rewards for high CLTV customers.  
- Predictive alerts for at‑risk customers.  
- Faster support resolution to reduce churn linked to escalations.  



