💼 HR Analytics Dashboard (Attrition Analysis)

📘 Overview

This Power BI project analyzes employee attrition to identify key factors influencing turnover.
Using HR data, the dashboard explores attrition trends by education, age group, marital status, job role, job level, years at company, and time since last promotion.

🎯 Objectives

Understand what drives employee attrition.

Visualize attrition count and attrition rate across demographic and organizational dimensions.

Support HR teams in creating data-driven retention strategies.

🧩 Dataset

Source: HR_Analysis.csv 

Key fields:
EmployeeID, Age, Department, JobRole, Education, YearsAtCompany, YearsSinceLastPromotion, MaritalStatus, Attrition, JobLevel, MonthlyIncome

🛠️ Tools & Skills

Power BI – dashboard design, DAX measures, data modeling

Power Query – data transformation & cleaning

Excel / CSV – data preparation/cleaning

Data visualization – KPI cards, bar charts, heat maps

Data storytelling – interpreting attrition patterns

📊 Dashboard Highlights

Attrition Overview – total employees, attrition count, attrition rate, average monthly salary, average age and average tenure

Attrition by Education & Department – visualizing trends across job functions

Attrition by Age Range – identifying vulnerable age groups

Attrition vs. Years at Company / Last Promotion – detecting career stagnation risks

Attrition by Job Level & Role – pinpointing positions with high attrition rates with colour conditioning

Attrition by Marital status – analyzing on marital status

Attrition by Overtime – detecting the attrition by overtime work 

🔍 Key Insights

- Higher attrition observed among employees with 1–5 years tenure and younger age groups (25–35).

- Attrition peaks within the first 2 years, then decline -> Suggests onboarding and early employee engagement may be key to retention.
  
- Sales Representatives and Laboratory Technicians show the highest attrition.

- Attrition is particularly concentrated in Job Levels 1–3, suggesting junior employees are more prone to leave — likely due to limited progression opportunities or job dissatisfaction.
  
- Employees working overtime have higher attrition.

- Departments like Sales and R&D show above-average turnover. They face the most attrition.

- Employees with longer promotion gaps (>=3 years) have lower attrition.Attrition risk is highest within 1–2 years since last promotion.
This could mean that employees leave soon after being promoted, possibly when they realize the new role or workload doesn’t meet expectations.
After 3 years since the last promotion, attrition declines significantly — perhaps because those who remain are more stable, satisfied, or senior.

- Married employees exhibit lower attrition rates than single employees.

🚀 Outcome

This dashboard helps HR teams:

Identify patterns behind employee turnover.

Prioritize retention strategies for at-risk groups.

Monitor attrition KPIs in real time.

🧠 Future Enhancements

Predictive model for attrition using Python.

Integration with real-time HR data via SQL.

**Folder Structure**

HR-Analytics-Attrition-PowerBI/

├── README.md               

├── dataset/                  

│   └── HR_Analysis.csv

├── visuals/                  

│   ├── Attrition By Age.png

│   ├── Attrition by JobRole and level.png

│   └── Department vs Attrition.png

│   └── Dashboard Main.png
    
│   └── Years at Company vs Attrition.png
    
├── pbix/                     

│   └── Attrition Analysis.pbix

└── insights/                 

│   └── Key Insights.pdf


