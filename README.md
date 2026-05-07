# E-Commerce-Health-Marketing-ROI-Audit

Author: Erik Santana   

Tools Used: BigQuery SQL, Excel, Power BI

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Project Overview
This project performs a comprehensive "Health Check" on campaign finance and e-commerce data to evaluate marketing efficiency and organizational risk. By transforming raw transactional data into actionable business intelligence, the audit identifies where capital is concentrated and where data integrity is failing.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Key Insights & Analytics
1. Concentration Risk (Lender Dependency)
The Business Question: Are we funded by a diverse group, or are we dependent on a few sources?

Technical Approach: Analyzed lender distribution to identify "Single Points of Failure" in fundraising.

Actionable Insight: The data revealed that 49% of total capital was concentrated among just three lenders; therefore, a diversification strategy is required to mitigate the risk of losing major backers.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2. Cash Flow Velocity (Cumulative Debt)
The Business Question: How fast is our debt "snowballing" over time?

Technical Approach: Created a time-series growth model using SQL window functions (SUM OVER) to track the velocity of borrowing.  

Actionable Insight: Borrowing accelerates drastically during election cycles (October/November); therefore, a cash reserve should be established six months prior to these "high-velocity" windows to reduce reliance on high-interest loans.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3. Compliance & Data Integrity Audit
The Business Question: Are our records legally compliant and complete?

Technical Approach: Performed a data health check to identify missing regulatory information, specifically in the "Occupation" fields.

Actionable Insight: Identified a specific segment of records missing mandatory job titles; therefore, a targeted "To-Do" list was generated to fix these entries before regulatory filing deadlines.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4. Operational Accuracy (The Correction Ratio)
The Business Question: Is our data entry team getting more accurate over time?

Technical Approach: Analyzed the Correction field (New vs. Modify flags) to measure the ratio of errors year-over-year.

Actionable Insight: The "Modification Rate" peaked between 2014–2016 and has since stabilized; therefore, early errors were used to create a "Lessons Learned" training guide for new staff to ensure future filing accuracy.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ Technical Skills Demonstrated
SQL (BigQuery): CTEs, Window Functions, EXTRACT for time-series, and SAFE_DIVIDE for ratios.

Data Modeling: Transforming raw transaction logs into executive-level summaries.

Business Intelligence: Translating technical findings into "Stakeholder-ready" insights.

Documentation: Writing technical summaries that bridge the gap between IT and Management.

