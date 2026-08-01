 HR Analytics: Employee Attrition & Retention Executive Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Domain-HR_Analytics-blue?style=for-the-badge)

An end-to-end HR Analytics solution designed to investigate employee turnover patterns, evaluate key drivers of attrition, and deliver actionable data-driven strategies for workforce retention.

---

 Executive Dashboard Overview

![HR Attrition Dashboard](Screenshot%202026-08-01%20053818.png)

---

 Executive Summary & Core KPIs

The analysis evaluates a total workforce of **1,480 employees** to understand the high attrition rate of **16.08%** and identify critical operational risk factors:

| Metric | Value | Business Context |
| :--- | :---: | :--- |
| **Total Headcount** | **1,480** | Active workforce analyzed |
| **Attrition Count** | **238** | Total voluntary/involuntary departures |
| **Attrition Rate** | **16.08%** | Exceeds standard baseline thresholds (~10-12%) |
| **Avg Monthly Income** | **$6.50K** | Benchmark across retained vs. departed staff |

---
 Key Business Insights

 1. ⏳ Overtime Workload Impact
 *Insight:** Employees required to work **Overtime** exhibit a significantly disproportionate rate of attrition compared to non-overtime peers.

**Impact:** Burnout and extended working hours are primary drivers for talent drop-off.

 2.  Role-Specific Turnover
* *Insight:** **Sales Executives** and **Laboratory Technicians** record the highest absolute numbers of resignations.
* *Impact:* Sales and frontline operational positions face severe retention challenges requiring targeted compensation or incentive restructuring.

 3. Compensation & Salary Correlation
* *Insight:** Lower monthly salary tiers correlate directly with higher attrition rates. Employees earning below the median income bracket demonstrate higher turnover probability.

---
 Data Pipeline & Methodologies

1. *Data Cleaning & Transformation (SQL Server / Power Query):**
   * Standardized data types for metrics (`Age`, `MonthlyIncome`, `EmpID`).
   * Cleaned conditional categorical data (`Attrition`: Yes/No, `OverTime`: Yes/No).
   * Grouped age distribution into strategic cohorts (`AgeGroup`).

2. **Data Modeling & Measures (Power BI & DAX):**
   * Created custom measures for dynamic KPI tracking (`Attrition Rate %`, `Total Attrition`, `Avg Salary`).
   * Configured interactive cross-filtering slices (Gender, OverTime status, Department).

---

 Strategic Recommendations for HR Leadership
 **Workload Re-balancing:** Reduce mandatory overtime for high-risk roles (Lab Techs & Sales Execs) by implementing shift rotation or additional staffing.
 **Compensation Adjustment:** Review wage distributions for junior and mid-level roles to meet market benchmarks and prevent pay-driven resignations.
**Career Progression Programs:** Implement clear career pathways for high-turnover job roles to boost long-term retention.

---

 Repository Structure

```text
├── HR Analytics.csv                   # Raw Workforce Dataset
├── HR-Employee-Attrition-Dashboard.pbix # Interactive Power BI Dashboard
├── مشروع 2.pdf                         PDF Executive Report
├── Screenshot 2026-08-01 053818.png   # Dashboard Preview Image
└── README.md                          # Comprehensive Project Documentation
