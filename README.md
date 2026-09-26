# Customer Churn Analysis & Retention Insights

An end-to-end data analytics project focused on identifying the key drivers of customer churn using structural database queries and statistical correlations.

## 📊 Key Analytical Features
* **SQL Data Aggregation:** Designed custom relational queries in SQLite to extract data, manage transactional states, and prevent user account duplicates.
* **Feature Encoding:** Developed an isolated pandas preprocessing pipeline using explicit categorical type conversions (`.cat.codes`) to safely map text features into structured numeric variables.
* **Trend Analytics:** Built regularized time-series line charts tracking monthly account cancellation peaks.
* **Statistical Insights:** Extracted multi-variable relationships using a Seaborn correlation matrix heatmap (`numeric_only=True`) to flag linear retention trends.

## 🛠️ Tech Stack & Tooling
* **Database Management:** SQLite / SQL
* **Data Manipulation:** Python, Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib

## 📈 Summary of Data Fields Analyzed
* `plan_type` (Basic, Standard, Premium)
* `contract_type` (Monthly, Annual)
* `churn_score` & `churn_risk` (Low, Med, High)
* `escalations` (Binary mapping for support status)
* `churn_flag` (Target Variable)

---
*Note: The Jupyter Notebook source file containing all the execution tracebacks and visualization outputs can be reviewed directly in the `churn_analysis.ipynb` file above.*
