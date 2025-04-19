# 🧑‍💼 Employee Attrition and Retention Analysis Dashboard

This project is an analytical dashboard built with **Power BI** and **Power Query** to provide valuable insights into employee attrition, satisfaction, and workplace engagement. It is tailored to support HR professionals and analysts in identifying high-risk employees, improving retention strategies, and fostering a healthier work environment.
---
## Dashboard Preview

![employee attrition dashboard_page-0001](https://github.com/user-attachments/assets/e42c4515-bfba-406d-abf7-6f7b0632b906)

---

## 📚 Table of Contents


1. [Project Overview](#-project-overview)  
2. [Key Insights Explored](#-key-insights-explored)  
3. [Tools Used](#tools-used)  
4. [Data Transformation (Power Query + DAX)](#-data-transformation-power-query--dax)  
5. [Dashboard Highlights](#-dashboard-highlights)    
6. [Dataset](#dataset)  
7. [Contact](#contact)

---

## 📝 Project Overview

Employee attrition remains a critical concern for organizations, affecting both productivity and morale. This project leverages interactive visualizations to analyze attrition patterns using HR data sourced from Kaggle. It tracks and explains trends across demographics, job satisfaction, promotions, absenteeism, distance from work, and salary distribution. By understanding these factors, businesses can make data-informed decisions to improve employee retention.

---

## 🔍 Key Insights Explored

- What is the gender and age distribution of the workforce?
- How many employees are at higher risk of attrition?
- What is the correlation between job satisfaction, promotion history, and attrition?
- How does absenteeism or distance from home impact retention?
- What job levels or salary tiers are more prone to turnover?

---

## Tools Used

- **Power BI** – For dashboard creation and visualization  
- **Power Query** – For data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – For creating KPIs, metrics, and calculated columns

---

## 🔄 Data Transformation (Power Query + DAX)

1. **Age Grouping**:  
   - Youth (20–29), Young Adults (30–39), Adults (40–49), Seniors (50+)

2. **Income per Hour**:  
   - `Monthly Income / (Average Weekly Hours * 4)`

3. **Years at Company Grouping**:  
   - Newcomers (1–5), Developing Employees (6–10), Established Staff (11–15), Experienced Staff (16–20), Loyal Employees (21–25), Veteran Employees (26+)

4. **DAX Metrics**:  
   - Total Employees  
   - Total Stay  
   - Total Left  
   - High Risk Employees → Job Satisfaction ≤ 2, Years Since Last Promotion ≥ 5, Overtime = Yes, Attrition = No  
   - Happy Employees → Job Satisfaction ≥ 3, Recent Promotion (≤ 3 yrs), Good Work-Life Balance and Environment Satisfaction

5. **Payment Tiering**:
   - Based on hourly income: Tier 1 (13–33.9), with +20 intervals to Tier 7 (135+)

6. **Distance Grouping**:
   - Very Close, Close, Moderate, Far, Very Far (interval of 10 from range 1–50)

7. **Absenteeism Grouping**:
   - Never (0), Rarely (1–5), Occasionally (6–10), Frequently (11–15), Highly Absent (16+)

---

## 📊 Dashboard Highlights

- **Total Employees**: 1000  
- **Attrition**: 189 (19%)  
- **Stay**: 811 (81%)  
- **Happy Employees**: 53 (5%)  
- **High Risk**: 80 (8%)  
- **Gender**: 52% Male, 48% Female  
- **Avg. Performance Score**: 2.53  
- **Work Environment Satisfaction**: 2.49


---

##  Dataset

- **Source**: [Employee Attrition Prediction Dataset](https://www.kaggle.com/datasets/ziya07/employee-attrition-prediction-dataset)

---

##  Contact

  
📧 Email: [mayowa24.jan@gmail.com](mailto:mayowa24.jan@gmail.com)  
🔗 LinkedIn: [mayor9774](https://www.linkedin.com/in/mayor9774)

---

> ⭐️ If you found this project insightful, feel free to connect on LinkedIn or leave a star on the repository!
