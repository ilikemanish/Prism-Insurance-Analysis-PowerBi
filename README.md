🛡️ Prism Insurance Analysis Dashboard

<p align="center">
  <img src="ICONS/prism_insurance_logo.png" alt="Prism Insurance Logo" width="250">
</p><h1 align="center">📊 Prism Insurance Analysis</h1><p align="center">
  <b>Turning Insurance Data into Actionable Business Insights 🚀</b>
</p><p align="center">
  <img src="https://img.shields.io/badge/POWER%20BI-Dashboard-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">  <img src="https://img.shields.io/badge/DATABASE-SQL%20SERVER-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server">  <img src="https://img.shields.io/badge/DAX-Power%20Query-00B4D8?style=for-the-badge&logo=microsoft&logoColor=white" alt="DAX and Power Query">
</p><p align="center">
  <img src="https://img.shields.io/badge/DOMAIN-INSURANCE%20ANALYTICS-243B55?style=for-the-badge" alt="Insurance Analytics">  <img src="https://img.shields.io/badge/LEARNING-UDEMY%20BOOTCAMP-A435F0?style=for-the-badge&logo=udemy&logoColor=white" alt="Udemy Bootcamp">
</p>---

📌 Project Overview

Prism Insurance Analysis is a data analytics project developed as part of my learning journey through the Complete Data Analyst Bootcamp: From Basic to Advanced on Udemy.

The project explores insurance premiums, policy coverage, claim amounts, claim status, and customer demographics.

Using Microsoft SQL Server for data retrieval and Microsoft Power BI for interactive visualization, the project transforms raw insurance data into meaningful insights and business recommendations.

---

🎯 Project Objectives

- 💰 Analyze total premium and insurance coverage.
- 📋 Evaluate claim amounts and claim status.
- 🛡️ Compare premium performance by policy type.
- 👥 Analyze customer demographics by age and gender.
- 🔍 Identify data quality issues.
- 📊 Develop KPIs for insurance performance monitoring.
- 💡 Provide actionable business recommendations.

---

📁 Dataset Information

Attribute| Details
Dataset| Prism Insurance Data
Database| Microsoft SQL Server
Visualization| Microsoft Power BI
Query Language| SQL
Transformation| Power Query
Calculations| DAX
Domain| Insurance Analytics
Analysis| Exploratory and Business Analysis

---

🖥️ Dashboard Preview

<p align="center">
  <img src="Final_Dashboard.jpg" alt="Prism Insurance Power BI Dashboard" width="100%">
</p><p align="center">
  <i>Interactive insurance analytics dashboard built with Power BI.</i>
</p>«Note: Upload your actual dashboard screenshot as "Final_Dashboard.jpg" in the repository root. Otherwise, replace the filename above with your screenshot's actual path.»

---

📊 Key Performance Indicators

KPI| Value| Purpose
💰 Total Premium| 5.98M| Measure premium volume
🛡️ Total Coverage| 600.55M| Understand total coverage
📋 Total Claim Amount| 16.91M| Monitor claim amounts

<p align="center">
  <img src="https://img.shields.io/badge/TOTAL%20PREMIUM-5.98M-00C9A7?style=for-the-badge&labelColor=141E30" alt="Total Premium">  <img src="https://img.shields.io/badge/TOTAL%20COVERAGE-600.55M-4472C4?style=for-the-badge&labelColor=141E30" alt="Total Coverage">  <img src="https://img.shields.io/badge/TOTAL%20CLAIM-16.91M-E67E22?style=for-the-badge&labelColor=141E30" alt="Total Claim">
</p>Note: Values are in the dataset's source units. Currency was not explicitly specified.

---

🔍 Business Analysis

1. 💰 Insurance Premium Analysis

Business Question: Which insurance policy types contribute the most to total premium?

Policy Type| Total Premium
✈️ Travel| 2.48M
🏥 Health| 1.20M
🚗 Auto| 0.96M
❤️ Life| 0.73M
🏠 Home| 0.60M

Key Insight: Travel insurance contributed the highest premium among the policy types analyzed.

Business Opportunity: Compare premium contributions with claim amounts and outcomes to understand policy-level performance more comprehensively.

---

2. 📋 Claim Status Analysis

Business Question: How are claims distributed across different processing outcomes?

Claim Status| Number of Records
✅ Settled| 3,386
⏳ Pending| 2,263
❌ Rejected| 4,355

Key Insight: The dataset contains a substantial number of rejected claim records, making rejection-reason analysis a useful follow-up.

Business Opportunity: Monitor pending claims and investigate rejection reasons where supporting data is available.

---

3. 💵 Claim Amount Analysis

Metric| Amount
Total Claim Amount| 16.91M
Settled Claim Amount| 10.11M
Pending Claim Amount| 6.81M
Rejected Claim Amount| 0

Key Insight: The claim amounts recorded in the dataset are associated with settled and pending claims, while rejected records contain zero claim amounts.

Recommendation: Validate source-system rules before interpreting zero claim amounts as actual financial outcomes.

---

4. 👥 Customer Demographic Analysis

Business Question: How do recorded claim amounts vary across customer age groups?

Age Group| Claim Amount
Young Adults (≤30)| 3.04M
Adults (31–60)| 7.48M
Older Adults (>60)| 6.39M

Key Insight: Adults aged 31–60 account for the largest recorded claim amount among the analyzed age groups.

These figures describe the dataset and do not establish that age causes differences in claim amounts.

---

🗄️ SQL Server Analysis

Microsoft SQL Server was used to retrieve and explore insurance data.

Skills Applied

- Data retrieval using "SELECT".
- Filtering using "WHERE".
- Aggregation using "SUM()" and "COUNT()".
- Grouping using "GROUP BY".
- Sorting using "ORDER BY".
- Comparing premium and claim metrics.

Example SQL Query

SELECT
    PolicyType,
    SUM(PremiumAmount) AS TotalPremium,
    SUM(CoverageAmount) AS TotalCoverage,
    SUM(ClaimAmount) AS TotalClaimAmount
FROM InsuranceData
GROUP BY PolicyType
ORDER BY TotalPremium DESC;

This is an illustrative example. Adjust the table and column names to match your actual SQL Server schema.

---

🛠️ Tools and Technologies

Tool| Purpose
🗄️ Microsoft SQL Server| Data retrieval and SQL queries
📊 Microsoft Power BI| Dashboard development
🔄 Power Query| Data transformation
📐 DAX| KPI calculations
📈 Data Visualization| Presenting analytical findings
💡 Business Analysis| Insights and recommendations

---

💡 Key Analytical Insights

- ✈️ Travel Insurance: Highest premium contribution among the analyzed policy types.
- 📋 Claim Status: Rejected claims represent a substantial portion of recorded statuses.
- ⏳ Pending Claims: Monitoring claim ageing can help identify processing delays.
- 👥 Customer Segmentation: Age-group analysis provides additional context for recorded claim amounts.
- 🧹 Data Quality: Missing dates and zero claim amounts require validation.
- 📊 Performance Monitoring: Consistent KPI definitions can improve insurance reporting.

---

🚀 Business Recommendations

1. Improve Claim Monitoring

Track pending claims by ageing category and establish processing targets.

2. Investigate Rejected Claims

Capture rejection reasons and identify recurring patterns.

3. Monitor Policy Performance

Compare premium contributions with claim amounts and claim outcomes.

4. Strengthen Data Quality

Validate missing dates, zero claim amounts, duplicate records, and identifiers.

5. Expand the KPI Framework

Consider introducing:

- Claim Settlement Rate
- Claim Rejection Rate
- Pending Claim Count
- Pending Claim Ageing
- Average Claim Amount
- Premium-to-Claim Ratio

---

🏗️ Project Workflow

<p align="center">SQL Server

⬇️

Data Retrieval

⬇️

Data Preparation

⬇️

Power BI Dashboard

⬇️

KPI Analysis

⬇️

Business Insights

</p>---

📂 Repository Structure

Prism-Insurance-Analysis-PowerBi/
│
├── README.md
├── ICONS/
│   └── prism_insurance_logo.png
├── InsuranceData.csv
├── Prism Insurance.pbix
└── Final_Dashboard.jpg

Keep the filenames in this example aligned with the files actually present in your repository.

---

🚀 How to Explore the Project

1. Install Microsoft Power BI Desktop.
2. Clone or download this GitHub repository.
3. Open "Prism Insurance.pbix".
4. Explore the dashboard visuals, KPIs, and report pages.
5. Review the analysis and business recommendations.

---

🎓 Learning Resource

<p align="center">
  <img src="https://img.shields.io/badge/PLATFORM-UDEMY-A435F0?style=for-the-badge&logo=udemy&logoColor=white" alt="Udemy">
</p>Course: Complete Data Analyst Bootcamp: From Basic to Advanced

Platform: Udemy

This project is part of my practical learning journey, helping me apply SQL, data analysis, visualization, and business reporting concepts.

---

🧠 Skills Demonstrated

- SQL Server and SQL Queries
- Data Retrieval and Exploration
- Power BI Dashboard Development
- Power Query Data Transformation
- DAX and KPI Development
- Data Quality Validation
- Exploratory Data Analysis
- Business Intelligence
- Analytical Thinking
- Data Storytelling

---

👨‍💻 About Me

Manish Kashyap

🎯 Aspiring Data Analyst

📊 SQL | Excel | Python | Power BI

🤖 Artificial Intelligence and Machine Learning Enthusiast

I'm passionate about transforming raw data into meaningful insights and continuously building projects to strengthen my analytical and technical skills.

<p align="center">
  <a href="https://github.com/ilikemanish">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>  <a href="https://portfolio-ci5f.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Visit-00C9A7?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio">
  </a>
</p>---

<p align="center">
  ⭐ <b>If you find this project useful, consider giving the repository a star!</b>
</p><p align="center">
  <b>Built with SQL Server, Power BI, and a passion for Data Analytics 📊</b>
</p><p align="center">
  <i>Turning Data into Insights. Turning Insights into Action. 🚀</i>
</p>