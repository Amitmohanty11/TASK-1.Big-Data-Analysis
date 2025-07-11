# 🧑‍💼 HR Attrition Dashboard (Power BI)

This project analyzes employee attrition patterns within an organization using a Power BI dashboard. The insights help HR teams identify key factors behind employee turnover and make data-driven decisions to improve retention.

---

## 📊 Dashboard Overview

The dashboard includes the following visual components:

- ✅ **Attrition KPI**: Total number of employees who have left the organization  
- 📈 **Attrition by Department**: Visualizes attrition trends across different departments  
- 🕒 **Attrition by Age & Experience**: Highlights trends based on employee age and years at company  
- 🧑‍🤝‍🧑 **Attrition by Gender and Job Role**: Explores attrition distribution across roles and genders  
- 💰 **Monthly Income & Job Satisfaction**: Correlation between income levels, satisfaction, and attrition  
- 🔁 **Filters/Slicers**: Interactive slicers for Department
---

## 🗂️ Dataset

- **Source**: IBM HR Analytics Employee Attrition & Performance dataset  
- **Size**: ~1470 employee records  
- **Key Columns**:
  - `Attrition` (Yes/No)
  - `Age`, `Gender`, `JobRole`, `Department`
  - `MonthlyIncome`, `YearsAtCompany`, `JobSatisfaction`, etc.

---

## ⚙️ Tools Used

- **Power BI Desktop**
- Power Query Editor for data transformation
- DAX for custom KPIs and measures

---

## 🛠️ Features

- Created a **numeric column `Attrition Count`** to convert "Yes/No" to 1/0 for KPI aggregation  
- Interactive filters to explore attrition by various dimensions  
- Clean layout and color-coded visuals for clarity

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Refresh the data if connected to an external source
3. Interact with slicers and charts to explore attrition patterns

---

## 📌 Insights Derived

- Sales and HR departments have the highest attrition rates  
- Employees with lower income or job satisfaction are more likely to leave  
- Attrition is higher among mid-career employees with 1–5 years at the company

---

## 📁 File Structure
