# 🧾 Bank Customer Churn Analysis Dashboard - Power BI

## 📌 Project Overview
This Power BI project explores customer churn behavior in a bank using real-world customer data. The goal is to identify the patterns and factors leading to churn and provide insights that can help reduce customer attrition.

## 📂 Dataset
**Filename:** `Bank Customer Churn Prediction.csv`  
**Size:** ~10,000 records  
**Source:** Simulated bank customer data  
**Key Features:**
- `CustomerId`, `Surname`, `Geography`, `Gender`
- `Tenure`, `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`
- `EstimatedSalary`, `Exited` (Target - 1: Churned, 0: Retained)

## 🧠 Key Objectives
- Visualize the overall churn rate and trends  
- Analyze demographic and financial factors influencing churn  
- Segment customers by geography, tenure, and product usage  
- Build an interactive dashboard for decision-makers  

## 📊 Power BI Dashboard Highlights
- **Churn Overview Card** – Key KPIs like Churn Rate, Total Customers, Active vs Inactive  
- **Customer Segmentation** – Filters by Gender, Geography, Tenure, Product Count  
- **Bar & Pie Charts** – Distribution of churn by country, gender, and credit card ownership  
- **Scatter/Tree Maps** – Balance vs Churn, Salary vs Activity status  
- **Drill-through Functionality** – Deep dive into specific customer groups

## 🧰 Tools & Techniques Used
- **Power BI Desktop (.pbix)**  
- **Power Query Editor** – Data transformation and cleanup  
- **DAX Measures** – Custom KPIs and calculated columns  
- **Slicers and Filters** – Enhanced interactivity  
- **Conditional Formatting** – Highlight churn-heavy segments  

## 💡 Key Insights
- Customers with **low tenure** and **low balance** had the highest churn rates  
- **Inactive customers** and those with **fewer products** were more likely to leave  
- **Germany** showed higher churn compared to France and Spain  
- Having a **credit card** or **high salary** did not guarantee retention

## 📈 Outcome
The dashboard empowers stakeholders to:
- Identify and address customer pain points  
- Target high-risk segments with retention offers  
- Monitor churn dynamics over time  

## 🔗 Future Enhancements
- Integrate predictive churn model using Python or R  
- Add real-time data connection  
- Build alert mechanisms for high-risk churn signals  


