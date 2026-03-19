# Data Professionals Survey Breakdown Dashboard

![Data Professionals Survey Breakdown](https://github.com/user-attachments/assets/ab3515fa-0656-4df8-80a8-81b9616ae2d2)

#  Data Professionals Survey Breakdown Dashboard

> **Role:** Data Analyst | **Tools:** Power BI · SQL Server · DAX · Excel | **Domain:** HR Analytics · Career Intelligence · Industry Research

---

##  Project Overview

Analyzed survey responses from **630 data professionals** across multiple countries, roles, and experience levels to uncover patterns in **salary trends, job satisfaction, gender pay gaps, and programming language preferences**. The interactive Power BI dashboard serves as a strategic tool for job seekers, HR teams, and educators — providing a data-backed picture of the current state of data careers globally.

---

##  Business Problem

Despite the explosive growth in data careers, there was no structured, visual analysis available on:

- What **makes a data career truly rewarding** beyond salary
- How **job satisfaction and compensation differ** across roles, gender, and geographies
- Which **programming languages** are most valued and widely used in the field
- What **salary benchmarks** exist by job title for career planning and HR strategy

---

##  Key KPIs

| Metric | Value |
|---|---|
| Total Survey Respondents | 630 Data Professionals |
| Average Age | 29.87 years |
| Male Representation | 73.46% |
| Female Representation | 26.54% |
| Work-Life Balance Score | 5.74 / 10 |
| Salary Satisfaction Score | 5.61 / 10 |
| Highest Earning Role | Data Scientist |
| Most Popular Language | Python |
| Top Country by Respondents | India → USA → UK → Canada |

---

##  Key Findings

### Demographics
- **Majority of respondents are from India**, followed by the United States, UK, and Canada
- Average age of **29.87 years** confirms the field is dominated by a **young, early-career workforce**
- Geographic concentration in India suggests strong pipeline growth in emerging markets

### Job Roles and Salaries
- **Data Scientists command the highest average salaries** across all roles
- **Data Engineers and Data Architects** also offer competitive, above-average compensation
- **Entry-level respondents** (Students/Looking/None) report the lowest salaries — significant gap vs senior roles

### Gender Disparity
- Male professionals significantly outnumber female professionals (**73.46% vs 26.54%**)
- **Average salaries for males are notably higher** — indicating a measurable gender pay gap requiring industry attention
- Gender imbalance addressed in visualization using **percentage-based comparisons** rather than raw counts

### Satisfaction Scores
- **Work-Life Balance: 5.74/10** — below industry expectation for a knowledge work field
- **Salary Satisfaction: 5.61/10** — middling scores signal widespread compensation dissatisfaction
- Both scores suggest **significant room for improvement** across organizations in data careers

### Programming Language Preferences
| Language | Popularity |
|---|---|
| Python | #1 — dominant across nearly all roles |
| R | #2 — popular in research and data science |
| JavaScript | #3 — used in data engineering and analytics |
| SQL | #4 — universal across all data roles |
| C/C++ / Java | Role-specific — varies significantly |

---

##  Recommendations

### For Organizations & HR Teams
- Conduct **regular salary audits** to identify and correct gender-based pay gaps
- Improve **work-life balance policies** — current scores signal retention risk
- Implement **transparent salary bands** across roles and locations to build trust

### For Aspiring Data Professionals
- **Master Python and SQL first** — most in-demand skills across all roles
- Target **Data Scientist and Data Engineer** roles for highest salary potential
- Invest in both **technical and soft skills** — negotiation power comes from the combination

### For Educators and Trainers
- **Align curriculum with Python, R, and SQL** as primary languages
- Add **real-world application modules** and career guidance to programs
- Help students understand **role-specific skill requirements** from day one

---

##  Technical Approach

### SQL Server
- **AVG() and COUNT()** aggregations for age, satisfaction, and salary analysis by role and country
- **GROUP BY** for multi-dimensional analysis across gender, language, job title, and geography
- **Data Standardization** — unified inconsistent job titles (e.g., "JS" → "JavaScript") for clean grouping
- **NULL Filtering** — removed invalid salary and satisfaction records to prevent result skewing
- **Role Categorization** — grouped minor roles under "Others" for cleaner visual storytelling

### Power BI
- **Interactive dashboard** with filters by country, job role, gender, and programming language
- **KPI cards** for all headline metrics — age, satisfaction, salary, and gender distribution
- **Bar charts** for salary by job title and language preference by role
- **Donut charts** for gender distribution and language share
- **DAX measures** for average calculations, satisfaction scoring, and gender-based comparisons

### Excel
- Initial data profiling, quality assessment, and field validation
- Pre-processing of categorical inconsistencies before SQL import

---

##  Challenges Faced & Solutions

| Challenge | Solution |
|---|---|
| Inconsistent job titles and language names | SQL CASE statements for standardization |
| Heavily skewed gender distribution | Used percentage-based visuals instead of raw counts |
| Null and invalid salary/satisfaction values | Filtered out in SQL before dashboard load |
| Minor role categories cluttering visuals | Grouped under "Others" for cleaner storytelling |

---

##  Repository Structure
```
📂 Data-Professionals-Survey-Breakdown
├── 📊 DataSurvey_Dashboard.pbix           — Interactive Power BI dashboard
├── 📄 DataSurvey_Analysis.sql             — SQL cleaning and query scripts
├── 📄 Data_Professionals_Survey.xlsx      — Raw survey dataset
├── 🖼️  Data Professional Survey Analysis Dashboard.jpg — Dashboard preview
└── 📄 README.md                           — Project documentation
```

---


##  About

**Khurram Naveed** — Data Analyst specializing in Power BI, SQL, and business intelligence.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/khurramnaveed3233)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)](https://github.com/Khurramnaveed3233)
[![Email](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](mailto:khurramnaveed4545@gmail.com)

---

> 💼 *This project demonstrates how survey data — often overlooked as anecdotal — can be transformed into structured, visual intelligence that drives smarter career decisions, better HR strategies, and more relevant educational programs in the data industry.*

