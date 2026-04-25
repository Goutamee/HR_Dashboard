# HR_Dashboard

## 1. 🏷️ Headline

**HR Analytics Dashboard | Employee Salary, Demographics & Leave Analytics**

---

## 2. 📋 Purpose

This dashboard delivers a comprehensive view of an organization's human resource landscape across **161 employees** hired between April 2017 and June 2023. It enables HR managers and leadership teams to monitor workforce composition, analyse salary distribution by role and gender, evaluate educational qualification spread, track leave balances, and understand headcount trends over time — supporting smarter decisions around hiring, compensation equity, and workforce planning.

---

## 3. 🛠️ Key Technologies Used

- **Microsoft Power BI Desktop** — interactive dashboard and visual analytics (`.pbix`)
- **Microsoft Excel** — primary employee data source and raw data repository (`.xlsx`)
- **DAX (Data Analysis Expressions)** — calculated KPIs such as total headcount, average salary, average age, average leave balance, and gender-wise comparisons
- **Power Query (M Language)** — data transformation, date formatting (joining year/month extraction), and data type standardisation inside Power BI

---

## 4. 📦 Data Source

More info on where data come from and how it's structured.
- **Source:** Kaggle
- **File:** `HR_data.xlsx`
- **Records:** 161 employee entries
- **Date Range:** April 2017 – June 2023
- **Fields (9 columns):**

| Field | Details |
|---|---|
| `Emp ID` | 161 unique IDs (AC0001–AC0161) |
| `Name` | Employee full names |
| `Gender` | Female (88) / Male (73) |
| `Age` | Range: mid-20s to late 50s; Avg: 35.2 years |
| `Education Qualification` | Bachelor's Degree (49), High School Diploma (42), Diploma (41), Master's Degree (29) |
| `Date of Join` | Hire date from 2017 to 2023 |
| `Job Title` | 10 roles: Chocolatier, Production Operator, Packaging Associate, Sales Representative, Quality Control, Research Analyst, Product Manager, Research Scientist, Marketing Specialist, Marketing Manager |
| `Salary` | Range: ₹28,900 – ₹85,000 \| Avg: ₹54,231 \| Total Bill: ₹87.31 Lakh |
| `Leave Balance` | Available leave days (2–37 days; Avg: 16.4) |

---

## 5. ✨ Features of the Dashboard

- **Workforce KPI Cards** — Total headcount (161), average salary (₹54,231), average age (35.2), and average leave balance (16.4) as headline metrics
- **Gender Distribution** — Visual split of Female (88) vs. Male (73) employees with percentage breakdown; Female employees earn a slightly higher average salary (₹55,368 vs. ₹52,860)
- **Salary Analysis by Job Title** — Ranked view from Product Manager (₹82,825 avg) at the top down to Packaging Associate (₹33,409) — clear compensation hierarchy across 10 roles
- **Education Qualification Breakdown** — Donut or bar chart comparing Bachelor's, High School Diploma, Diploma, and Master's Degree holders across the workforce
- **Headcount by Job Role** — Packaging Associates (22) and Production Operators (20) form the largest workforce segments; Marketing roles (10 each) are the smallest
- **Joining Trends Over Time** — Year-wise and month-wise hiring trend from 2017–2023 to identify recruitment peaks and growth phases
- **Leave Balance Distribution** — Analysis of leave availability across employees and departments to flag potential burnout or leave bottlenecks
- **Age vs. Salary Correlation** — Scatter or matrix view comparing employee age with compensation levels across roles
- **Salary by Gender Equity View** — Side-by-side gender pay comparison to support diversity and inclusion reporting
- **Interactive Filters / Slicers** — Dynamic filtering by Gender, Job Title, Education Qualification, and Joining Year for targeted workforce drill-downs

---

## 6. ✨ Screenshot of the Dashboard

https://github.com/Goutamee/HR_Dashboard/blob/main/dashboard_screenshot.png
