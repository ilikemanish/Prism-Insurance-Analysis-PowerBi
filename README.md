
# 🛡️ Prism Insurance Analysis Dashboard

![Prism Insurance Logo](<prism logo.png>)

<p align="center">
  <b>Insurance Data Analysis | SQL Server | Power BI | DAX</b>
</p>

<p align="center">
  An interactive insurance analytics project focused on premiums, coverage, claims, and customer demographics.
</p>

---

## 📌 Project Overview

The **Prism Insurance Analysis Dashboard** is a data analytics project developed to analyze insurance performance, customer demographics, policy premiums, coverage amounts, and claim statuses.

The project uses Microsoft SQL Server for data retrieval and SQL queries, Power Query for data transformation, and Microsoft Power BI for dashboard development and visualization.

This project was developed as part of the **Complete Data Analyst Bootcamp: From Basic to Advanced** course on Udemy.

## 🎯 Project Objectives

- Analyze insurance premiums and coverage amounts.
- Compare premium contributions across policy types.
- Monitor settled, pending, and rejected claims.
- Understand claim patterns across customer age groups.
- Identify data quality issues.
- Generate actionable business recommendations.

---

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft SQL Server | Data retrieval and SQL queries |
| Microsoft Power BI | Dashboard development and visualization |
| Power Query | Data cleaning and transformation |
| DAX | KPI calculations and measures |
| CSV | Source dataset |

---

## 📊 Dashboard Preview

![Prism Insurance Dashboard Preview](<Dashboard Preview.png>)

---

## 📈 Key Performance Indicators (KPIs)

| KPI | Value |
|---|---:|
| Total Premium | 5.98M |
| Total Coverage | 600.55M |
| Total Claim Amount | 16.91M |
| Total Records | 10,004 |

> **Note:** Values are expressed in the source dataset's units. The currency is not specified.

---

## 🔍 Business Analysis and Insights

### 1. Premium Analysis by Policy Type

| Policy Type | Total Premium |
|---|---:|
| Travel | 2.48M |
| Health | 1.20M |
| Auto | 0.96M |
| Life | 0.73M |
| Home | 0.60M |

**Insight:** Travel insurance contributes the highest premium among the listed policy types.

### 2. Claim Status Analysis

| Claim Status | Number of Records | Claim Amount |
|---|---:|---:|
| Settled | 3,386 | 10.11M |
| Pending | 2,263 | 6.81M |
| Rejected | 4,355 | 0 |

**Insight:** Pending claims represent an important area for further investigation and processing improvements.

**Data note:** The dataset contains missing claim dates and zero claim amounts associated with rejected claims. These values should be validated before drawing conclusions about rejection reasons.

### 3. Claim Analysis by Age Group

| Age Group | Total Claim Amount |
|---|---:|
| Young Adults (30 and below) | 3.04M |
| Adults (31–60) | 7.48M |
| Older Adults (above 60) | 6.39M |

**Insight:** The 31–60 age group has the highest total claim amount among the three age groups.

---

## 💡 Business Recommendations

1. **Monitor Pending Claims:** Track claim ageing and establish service-level targets to improve processing efficiency.

2. **Investigate Rejected Claims:** Record rejection reasons to identify common causes and potential process improvements.

3. **Review Travel Insurance:** Investigate the high premium contribution from travel policies.

4. **Improve Data Quality:** Check duplicate records, missing claim dates, and inconsistent values.

5. **Track Additional KPIs:** Add settlement rate, rejection rate, average claim amount, and pending claim amount.

6. **Maintain Dashboard Accuracy:** Validate source data and refresh calculations regularly.

---

## 💻 SQL Analysis Example

The following query is an illustrative example. Update the table and column names to match your actual SQL Server database.

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
2. Clean and transform data using Power Query.
3. Create KPIs and calculated measures using DAX.
4. Develop interactive charts and dashboard visuals in Power BI.
5. Analyze policy premiums, coverage, and claim patterns.
6. Present findings and business recommendations.

---

## 📁 Repository Structure

```text
Prism-Insurance-Analysis-PowerBi/
│
├── README.md
├── InsuranceData.csv
├── Prism Insurance.pbix
├── Dashboard Preview.png
└── prism logo.png
```

---

## 🎓 Course Attribution

Developed as part of the **Complete Data Analyst Bootcamp: From Basic to Advanced** course on Udemy.

This project demonstrates practical skills in SQL, data transformation, DAX, Power BI dashboard development, and business analysis.

---

## 👨‍💻 About Me

I am an aspiring Data Analyst with knowledge of Excel, SQL, Power BI, Python, data cleaning, and data visualization.

I enjoy transforming raw data into meaningful insights that support better business decisions.

### 🔗 Connect With Me

- **GitHub:** [ilikemanish](https://github.com/ilikemanish)
- **Portfolio:** [Visit My Portfolio](https://portfolio-ci5f.vercel.app/)

---

⭐ **If you find this project useful, please consider giving this repository a star!**
