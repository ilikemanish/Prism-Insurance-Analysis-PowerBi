
# 🛡️ Prism Insurance Analysis Dashboard

## 📌 Project Overview

The **Prism Insurance Analysis Dashboard** is a data analytics project developed using Microsoft Power BI to analyze insurance premiums, coverage amounts, claim statuses, and customer demographics.

This project was developed as part of the **Complete Data Analyst Bootcamp: From Basic to Advanced** course on Udemy.

The main objective is to transform raw insurance data into meaningful business insights through data cleaning, SQL queries, DAX calculations, and interactive visualizations.

---

## 🎯 Project Objectives

- Analyze insurance premium and coverage trends.
- Track claim amounts and claim statuses.
- Compare premiums across different policy types.
- Understand customer demographics and claim patterns.
- Identify opportunities to improve claims management.
- Generate actionable business recommendations.

---

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft SQL Server | Data retrieval and SQL queries |
| Microsoft Power BI | Interactive dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | KPI development and calculations |
| CSV | Source dataset |

---

## 📊 Key Performance Indicators (KPIs)

| KPI | Value |
|---|---:|
| Total Premium | 5.98M |
| Total Coverage | 600.55M |
| Total Claim Amount | 16.91M |
| Total Records | 10,004 |

> **Note:** Values use the source dataset's units. The currency is not specified.

---

## 📈 Dashboard Preview

![Prism Insurance Dashboard](Dashboard preview.jpg)

---

## 🔍 Business Analysis

### 1. Premium Analysis by Policy Type

| Policy Type | Total Premium |
|---|---:|
| Travel | 2.48M |
| Health | 1.20M |
| Auto | 0.96M |
| Life | 0.73M |
| Home | 0.60M |

**Key Insight:** Travel insurance contributes the highest premium among the listed policy types.

### 2. Claim Status Analysis

| Claim Status | Number of Records | Claim Amount |
|---|---:|---:|
| Settled | 3,386 | 10.11M |
| Pending | 2,263 | 6.81M |
| Rejected | 4,355 | 0 |

**Key Insight:** Pending claims require further investigation and monitoring to improve claim processing efficiency.

### 3. Claim Analysis by Age Group

| Age Group | Total Claim Amount |
|---|---:|
| Young Adults (30 and below) | 3.04M |
| Adults (31–60) | 7.48M |
| Older Adults (above 60) | 6.39M |

**Key Insight:** The 31–60 age group has the highest total claim amount among the three age groups.

---

## 💡 Business Recommendations

1. **Monitor Pending Claims:** Track claim ageing and establish service-level targets to reduce delays.

2. **Analyze Rejected Claims:** Add rejection reason codes to identify common causes and potential process improvements.

3. **Review Travel Insurance:** Investigate the high premium contribution from travel insurance policies.

4. **Improve Data Quality:** Validate duplicate records, missing claim dates, and inconsistent values.

5. **Track Additional KPIs:** Include settlement rate, rejection rate, average claim amount, and pending claim amount.

6. **Monitor Performance Regularly:** Refresh the dashboard and review trends to support data-driven decisions.

---

## 💻 SQL Analysis Example

The following is an illustrative query. Update the table and column names to match your actual SQL Server database.

```sql
SELECT
    PolicyType,
    SUM(PremiumAmount) AS TotalPremium,
    SUM(CoverageAmount) AS TotalCoverage,
    SUM(ClaimAmount) AS TotalClaimAmount
FROM InsuranceData
GROUP BY PolicyType
ORDER BY TotalPremium DESC;
```

---

## ⚙️ Project Workflow

1. Retrieve insurance data using SQL Server.
2. Clean and transform the dataset using Power Query.
3. Create calculated measures and KPIs using DAX.
4. Design interactive charts, tables, and dashboard visuals.
5. Analyze insurance performance and claim trends.
6. Develop business insights and recommendations.

---

## 📁 Repository Structure

```text
Prism-Insurance-Analysis-PowerBi/
│
├── README.md
├── ICONS/
│   └── prism_insurance_logo.png
├── InsuranceData.csv
├── Prism Insurance.pbix
└── Final_Dashboard.jpg
```

**Important:** Ensure these filenames and paths match the files uploaded to your repository. GitHub will not display images if the paths are incorrect.

---

## 🎓 Course Attribution

This project was developed as part of the **Complete Data Analyst Bootcamp: From Basic to Advanced** course on Udemy.

The project demonstrates practical skills in data retrieval, data transformation, dashboard development, KPI creation, and business analysis.

---

## 👨‍💻 About Me

I am an aspiring Data Analyst with knowledge of Excel, SQL, Power BI, Python, data cleaning, and data visualization.

I enjoy transforming raw data into meaningful insights that help businesses understand performance and make informed decisions.

### 🔗 Connect With Me

- **GitHub:** [ilikemanish](https://github.com/ilikemanish)
- **Portfolio:** [Visit My Portfolio](https://portfolio-ci5f.vercel.app/)

---

⭐ **If you find this project useful, please consider giving this repository a star!**
