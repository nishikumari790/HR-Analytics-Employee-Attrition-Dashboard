# HR Analytics & Employee Attrition Dashboard

An end-to-end HR Analytics project designed to analyze workforce demographics, compensation trends, and key drivers behind employee attrition using **Python (Pandas)** and **Power BI**.

---

## Dashboard Preview
![HR Analytics & Employee Attrition Dashboard](Hr%20analytics%20%26%20employee%20attrition%20dashboard.png)
*(Note: Ensure the image filename above matches the exact screenshot filename uploaded in your repository.)*

---

## Tools & Technologies
* **Data Cleaning & Preprocessing:** Python (Pandas)
* **Data Modeling & Visualization:** Power BI, DAX, Power Query
* **Dataset Format:** CSV

---

## Key KPIs & Custom DAX Measures
* **Total Employees:** Overall headcount across the organization.
* **Attrition Count:** Total number of employees who left the company.
* **Attrition Rate (%):** Percentage of workforce attrition calculated dynamically using `DIVIDE` and `CALCULATE`.
* **Average Monthly Income:** Mean monthly salary across job levels and departments.

---

## Key Features & Analysis
* **Attrition Breakdown:** Analyzed employee turnover across **Job Role**, **Department**, **Education Field**, and **OverTime**.
* **Compensation & Performance Trends:** Evaluated **Average Monthly Income by Job Level**, **Monthly Income by Total Working Years**, and **Employee Count by Performance Rating**.
* **Interactive Filtering:** Added dynamic slicers for **Marital Status**, **Gender**, **Education Field**, and **Job Role** for self-service drill-down reporting.

---

## Repository Structure
* `hr_analytics.pbix` — Interactive Power BI dashboard file.
* `hr_analytics.csv` — Cleaned HR dataset used for modeling and visualization.
* `Hr analytics.ipynb` — Python (Pandas) script/notebook for data preprocessing.
* `Hr analytics & employee attrition dashboard.png` — High-resolution dashboard snapshot.

---

## How to Use
1. Download the `hr_analytics.pbix` file from this repository.
2. Open it in **Power BI Desktop**.
3. Use the top slicers (**Marital Status**, **Gender**, **Education Field**, **Job Role**) to filter metrics dynamically.
