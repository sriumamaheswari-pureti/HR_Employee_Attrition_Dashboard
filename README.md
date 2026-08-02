<div align="center">

# 📊 HR Employee Attrition Dashboard

### *Turning HR data into a story about why people leave*

![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Modeling-FFCA28?style=for-the-badge)
![Excel](https://img.shields.io/badge/Excel-Data%20Source-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

<img src="https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square" alt="status"/>
<img src="https://img.shields.io/badge/Type-HR%20Analytics-blueviolet?style=flat-square" alt="type"/>
<img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square" alt="license"/>

</div>

---

## 🧭 Project Overview

Employee attrition is one of those problems that sounds simple until you actually try to dig into it — is it the department, the overtime, the salary, the age group, or all of it at once? I built this dashboard to pull all of that into one place instead of digging through spreadsheets every time HR asks "so why are people leaving?"

The dashboard takes raw HR data (department, job role, salary, overtime, income, experience, age, education field, etc.) and turns it into a single interactive view where you can filter by whatever angle you're curious about and immediately see how attrition shifts.

It's built to be used, not just looked at — every chart is filterable, so it works as an actual exploration tool rather than a static report.

---

## 🧩 Dashboard Components

### 🎯 KPI Cards
A quick pulse-check on the workforce at a glance:

| Metric | What it tells you |
|---|---|
| 💰 **Average Salary** | Overall salary benchmark across the company |
| 📉 **Attrition Rate** | % of employees who have left |
| 👥 **Total Employees** | Full headcount in the dataset |
| 🚪 **Employees Left** | Raw count of employees who exited |

### 🔍 Filters Panel
Slice the entire dashboard by:
- 🎓 Education Field
- 💼 Job Role
- 🏢 Department
- ⚧ Gender
- ⏰ OverTime

### 📈 Visual Breakdown

| Chart | Insight it surfaces |
|---|---|
| **Attrition by Job Role** | Which roles see the highest exits (Laboratory Technicians & Sales Executives lead here) |
| **Attrition by Department** | Employees left vs. attrition rate, department-wise |
| **Attrition by Income vs Experience** | Scatter plot showing how income and experience years relate to attrition |
| **Attrition by OverTime** | Split of employees who worked overtime vs. those who didn't |
| **Attrition by Age Group** | Which age bracket is most likely to leave |

---

## 🛠️ Tech Stack

<div align="center">

| Tool | Purpose |
|:---:|:---|
| 📊 **Power BI** | Dashboard building & interactivity |
| 🧮 **DAX** | Calculated measures (attrition rate, averages, etc.) |
| 📑 **Excel / CSV** | Raw HR dataset source |

</div>

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/hr-attrition-dashboard.git
cd hr-attrition-dashboard
```

### 2️⃣ Open the file
Open `HR_Attrition_Dashboard.pbix` in **Power BI Desktop**.

### 3️⃣ Connect your data
Point it to your own HR dataset (or the sample data used here) and hit **Refresh**.

### 4️⃣ Explore
Use the filter panel on the left to slice by department, job role, gender, education field, or overtime — everything updates live.

---

## 💡 Key Insights

- 🧪 **Laboratory Technicians** and **Sales Executives** have the highest raw attrition counts among job roles.
- ⏰ Employees working **overtime** show a noticeably different attrition split than those who don't — overtime looks like a real pressure point.
- 👶 The **18–29 age group** shows the highest attrition, suggesting early-career employees leave more often than senior staff.
- 💵 The income vs. experience scatter shows a lot of attrition clustered in the **lower income bands**, regardless of experience.
- 🏢 Departments like **Research & Development** and **Sales** carry the bulk of the workforce, so even small attrition % shifts there hit total numbers hard.

---

## 📁 Project Structure

```
📦 hr-attrition-dashboard
 ┣ 📊 HR_Attrition_Dashboard.pbix   → Power BI dashboard file
 ┣ 📄 hr_data.csv                    → Dataset (not included — add your own)
 ┣ 🖼️ assets/Dashboard_Preview.png   → Dashboard screenshot
 ┗ 📄 README.md                      → You are here!
```

---

## 🙌 Acknowledgements

Built using a standard HR employee attrition dataset structure, commonly used for HR analytics and dashboarding practice.

---

## 👩‍💻 Author

**Pureti Sri Uma Maheswari**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect%20with%20me-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/uma-chowdary05/)

---

<div align="center">

### ⭐ If you found this dashboard useful, consider giving it a star!

*Built with 📊, ☕, and a lot of DAX measures*

</div>
