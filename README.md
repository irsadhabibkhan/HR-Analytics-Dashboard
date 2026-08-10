# 📊 HR Analytics Dashboard

An interactive **Power BI** dashboard built to analyze employee attrition patterns and workforce composition, helping HR teams identify where and why employees are leaving.

![Tool](https://img.shields.io/badge/Tool-Power%20BI-F2C811?logo=powerbi&logoColor=black)
![Domain](https://img.shields.io/badge/Domain-HR%20Analytics-1E7CD3)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 🧭 Project Overview

Employee attrition is one of the most costly challenges HR departments face. This project turns raw employee records into a single-page, interactive Power BI dashboard that lets stakeholders quickly answer:

- How many employees does the company have, and how many are active vs. have left?
- What is the overall attrition rate?
- Which departments, job roles, education fields, and salary bands are losing the most people?
- Does gender, marital status, or age play a role in attrition?

The dashboard is designed to be explored, not just read — a job-role slicer lets users filter every visual on the page in real time.

---

## 🎯 Objective

- Consolidate employee data into a single, clean view for HR decision-makers.
- Surface attrition trends across demographic and organizational dimensions.
- Provide a filterable, self-service tool instead of static reports.
- Practice end-to-end BI workflow: data modeling → DAX measures → dashboard design.

---

## 🛠️ Tools & Skills Used

| Tool / Skill | Purpose |
|---|---|
| **Power BI Desktop** | Data modeling, DAX measures, dashboard/report design |
| **Power Query** | Data cleaning and shaping |
| **DAX** | Custom measures (e.g., Attrition Rate %) |
| **Data Visualization** | KPI cards, charts, treemap, funnel, slicers |

---

## 🗂️ Dataset

The dashboard is built on an HR employee records table (`HR_Analytics`) containing fields such as:

`EmployeeCount` · `Age` · `Attrition` · `Department` · `EducationField` · `JobRole` · `Gender` · `MaritalStatus` · `SalarySlab`

*(This structure closely follows the well-known IBM HR Analytics Employee Attrition dataset commonly used for HR analytics practice projects.)*

---

## 📈 Dashboard Features

**KPI Cards (top row):**
- Total Employees
- Active Employees
- Attrition (count of employees who left)
- Average Age
- Attrition Rate % (custom DAX measure)

**Visuals (interactive & cross-filtering):**
| Visual | Insight it Provides |
|---|---|
| Clustered Column Chart | Attrition by Education Field |
| Treemap | Attrition by Job Role |
| Bar Chart | Attrition by Gender |
| Pie Chart | Attrition by Marital Status |
| Donut Chart | Attrition by Department |
| Funnel Chart | Attrition by Salary Slab |
| Slicer | Filter the entire dashboard by Job Role |

All visuals are cross-filtered — selecting a job role in the slicer instantly updates every KPI and chart on the page.

---

## 🖥️ Preview

> Add a screenshot of the dashboard here for best presentation, e.g.:
>
> ```markdown
> ![Dashboard Preview](assets/dashboard_preview.png)
> ```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `HR_ANALYTICS_DASHBOARD.pbix` in **Power BI Desktop** (free download from Microsoft).
3. Use the **Job Role slicer** on the left to filter all visuals.
4. Hover over any chart for detailed tooltips.

---

## 📌 Key Takeaways (Skills Demonstrated)

- Building KPI cards and applying visual-level filters in Power BI
- Writing DAX measures for rate calculations (e.g., Attrition Rate %)
- Choosing the right chart type for the story (treemap for hierarchy, funnel for stage-based drop-off, donut/pie for share-of-whole)
- Designing a clean, single-page executive dashboard with consistent branding/color theme

---

## 👤 Author

**Your Name**
[LinkedIn](https://www.linkedin.com/in/irsadhabibkhan/)  · [Email:- irsadhabibkhan5@gmail.com]

---

*This project is part of my Data Analytics portfolio, showcasing Power BI dashboard design and HR analytics skills.*
