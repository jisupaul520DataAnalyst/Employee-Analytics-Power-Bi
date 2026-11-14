# employee-analytics-power-bi
Interactive Employee Analytics Dashboard built with Microsoft Power BI, featuring Executive Overview, Workforce Composition, and Salary &amp; Pay Equity analysis.
# Employee Analytics Dashboard | Power BI

An interactive Employee Analytics Dashboard developed using Microsoft Power BI to analyze workforce composition, employee demographics, salary distribution, and pay equity.

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Analytics](https://img.shields.io/badge/Project-Data%20Analytics-blue)
![Domain](https://img.shields.io/badge/Domain-HR%20Analytics-green)

---

## 1. Project Overview

The Employee Analytics Dashboard is a business intelligence project designed to transform employee data into meaningful workforce insights.

Developed using Microsoft Power BI, the project provides an interactive view of employee distribution, departmental workforce composition, employment categories, salary patterns, and gender-based compensation metrics.

The dashboard consists of three analytical pages:

- Executive Overview
- Workforce Composition
- Salary & Pay Equity

The objective is to help users understand workforce trends and support data-driven human resource planning and compensation analysis.

## 2. Business Problem

Organizations generate employee data across multiple departments, employment categories, and work locations.

Analyzing this information manually can make it difficult to understand workforce distribution, monitor employee composition, compare salary patterns, and identify areas requiring further investigation.

This project addresses these challenges through an interactive Power BI dashboard that presents employee-related information in a structured and visually accessible format.

## 3. Project Objectives

- Analyze overall employee headcount and workforce distribution.
- Examine department-wise employee distribution.
- Understand workforce composition by gender.
- Analyze permanent, fixed-term, and temporary employment categories.
- Compare average salaries across departments.
- Examine gender-wise salary distribution.
- Analyze location-wise salary costs.
- Present workforce metrics through interactive visualizations.

## 4. Business Questions

This project explores the following business questions:

1. What is the total number of employees?
2. Which departments have the highest employee headcount?
3. How are employees distributed across different locations?
4. What is the gender composition of the workforce?
5. What percentage of employees belong to each employment category?
6. Which departments have the highest average salaries?
7. How does total salary differ between male and female employees?
8. Which locations contribute the highest salary costs?
9. What does the dashboard's gender pay-gap indicator reveal?

## 5. Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development |
| Power Query | Data preparation and transformation |
| DAX | Calculations and analytical measures |
| Microsoft Excel | Employee data source |
| Data Visualization | Presenting business insights |

*The exact Power Query operations and DAX formulas are subject to verification from the Power BI source file.*

## 6. Dataset Description

The project uses an employee dataset containing workforce-related information.

The dashboard analyzes the following dimensions and metrics:

- Department
- Gender
- Employee Type
- Work Location
- Salary
- Full-Time Equivalent (FTE)
- Employment Trends

**Dataset File:** `Employees Data.xlsx`

The dataset is included as a project asset only if it is authorized for sharing and contains no identifiable or confidential employee information.

## 7. Data Preparation & Analysis Process

The project follows a structured data analysis workflow:

1. **Data Source:** Employee information maintained in Microsoft Excel.
2. **Data Preparation:** Preparing the data for analysis.
3. **Data Transformation:** Organizing employee-related information for reporting.
4. **Data Analysis:** Examining workforce composition and salary distribution.
5. **DAX Calculations:** Creating analytical measures for dashboard KPIs.
6. **Data Visualization:** Developing interactive charts, KPI cards, and dashboard pages.
7. **Business Insights:** Presenting findings to support workforce analysis.

Detailed transformation steps and formulas can be found in the Power BI source file.

## 8. Key Performance Indicators

The supplied dashboard displays the following headline metrics:

| KPI | Value |
|---|---:|
| Total Employees | 242 |
| Total Salary | 19.19M |
| Total FTE | 246.50 |
| Average Salary | 69.51K |
| Male Employees | 49.17% |
| Female Employees | 50.41% |
| FTE Gap | -4.50 |

*Values are taken from the supplied dashboard PDF. Currency and salary units are not specified in the available dashboard.*

## 9. Dashboard Overview

### Page 1: Executive Overview

Provides a high-level summary of workforce performance.

**Key visualizations:**
- Total Employees
- Total Salary
- Total FTE
- Average Salary
- Department-wise Headcount
- Location-wise Headcount
- Employment Trends
- Employee Type Mix

### Page 2: Workforce Composition

Analyzes the demographic and structural composition of the workforce.

**Key visualizations:**
- Gender Distribution
- Department-wise Gender Distribution
- Gender-wise Employee Type
- Workforce Composition

### Page 3: Salary & Pay Equity

Focuses on salary distribution and compensation-related analysis.

**Key visualizations:**
- Department-wise Average Salary
- Gender-wise Total Salary
- Pay Gap by Gender
- Location-wise Salary Cost

## 10. Dashboard Screenshots

### Executive Overview

![Executive Overview](Screenshots/Executive%20Overview.png)

### Workforce Composition

![Workforce Composition](Screenshots/Workforce%20Composition.png)

### Salary & Pay Equity

![Salary & Pay Equity](Screenshots/Salary%20%26%20Pay%20Equity.png)

## 11. Key Business Insights

Based on the dashboard:

- The organization has 242 employees.
- Accounting has the highest department headcount, with 25 employees.
- India has the highest location-wise headcount, with 73 employees.
- Permanent employees represent 66.53% of the workforce.
- Female employees represent 50.41% of the workforce, while male employees represent 49.17%.
- Training has the highest department-wise average salary, approximately 82K.
- India has the highest location-wise salary cost at 5.60M.
- Total male salary is 9.54M, compared with 9.65M for female employees.

The dashboard also includes a gender pay-gap indicator. Its calculation and interpretation require validation before drawing conclusions about pay equity.

## 12. Business Recommendations

Based on the analytical coverage of the dashboard:

- Monitor department-wise workforce distribution for effective resource planning.
- Review employee composition across different employment categories.
- Investigate departmental salary differences using comparable job roles and experience levels.
- Conduct detailed pay-equity analysis using appropriate compensation criteria.
- Monitor location-wise salary costs for workforce budgeting.
- Review missing or unclassified employee records to improve data quality.

These recommendations indicate areas for further analysis rather than confirmed organizational problems.

## 13. Project Limitations

- The original dataset source and reporting period are not specified in the dashboard.
- One employee record has a blank gender classification.
- Blank department and location classifications are visible.
- The displayed gender pay-gap calculation requires further validation.
- Salary currency and units are not specified.
- The dashboard does not establish the causes of salary differences.
- Detailed DAX formulas and transformation steps require verification from the PBIX file.

## 14. Project Files

| File | Description |
|---|---|
| `Employee Analytics Dashboard.pbix` | Power BI source project |
| `Employee Analytics Dashboard.pdf` | Exported dashboard |
| `Employee_Insights_Report _.pdf` | Employee analytics insights report |
| `Employees Data.xlsx` | Employee dataset, subject to privacy clearance |
| `Executive Overview.png` | Executive dashboard screenshot |
| `Workforce Composition.png` | Workforce dashboard screenshot |
| `Salary & Pay Equity.png` | Salary dashboard screenshot |

## 15. Conclusion

This project demonstrates the application of Microsoft Power BI in employee data analysis and human resource analytics.

By combining workforce composition, demographic analysis, and salary-related metrics into a single interactive reporting solution, the dashboard provides a structured approach to understanding employee data.

It also demonstrates practical skills in business intelligence, data visualization, and analytical reporting.

---

## Repository Structure

```text
employee-analytics-powerbi/
│
├── README.md
├── Dashboard/
├── PowerBI/
├── Documentation/
├── Screenshots/
└── Dataset/
```

---

**Project:** Employee Analytics Dashboard

**Domain:** Human Resource Analytics

**Technology:** Microsoft Power BI

**Project Type:** Data Analytics & Business Intelligence

**Purpose:** Data Analyst Portfolio Project
