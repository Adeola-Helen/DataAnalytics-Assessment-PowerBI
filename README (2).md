\# Power BI Assessment – ADASHI Project

This repository contains my Power BI report for the ADASHIi assessment. The dashboard was designed to help various departments including Marketing, Finance, and Operations derive actionable insights from customer transaction and account data. The report focuses on four core areas: High-Value Customers, Transaction Analysis, Account Inactivity, and Customer Lifetime Value (CLV) Estimation.

NB: Transaction amount has been converted from kobo to naira for effective  visualization and understanding.

\---

\#\# Dashboard Sections and Insights

\#\#\# High-Value Customers    
\*\*Goal:\*\* Identify customers with high total deposits across savings and investment plans (for potential cross-selling opportunities).    
\*\*Highlights:\*\*    
\- \*\*222 customers\*\* tagged as high-value based on combined savings and investment volume    
\- \*\*Top customers\*\* like Opeoluwa Popoola stand out with deposits over ₦100M    
\- Product distribution shows \*\*Savings (98.92%)\*\* dominating over \*\*Investments (1.08%)\*\*

\---

\#\#\# Transaction Frequency Analysis    
\*\*Goal:\*\* Segment customers based on how frequently they transact, to support targeted communication strategies.    
\*\*Highlights:\*\*    
\- Total of \*\*4,492 transactions\*\* analyzed    
\- Customers were segmented into:  
  \- \*\*High Frequency:\*\* ≥10 transactions/month (28.03%)  
  \- \*\*Medium Frequency:\*\* 3–9 transactions/month (28.05%)  
  \- \*\*Low Frequency:\*\* ≤2 transactions/month (43.92%)    
\- Visuals show trends in transaction volume by frequency group and category

\---

\#\#\# Inactive Accounts    
\*\*Goal:\*\* Flag accounts with no inflow (charges or transactions) in the last 365 days.    
\*\*Highlights:\*\*    
\- \*\*4,847 inactive accounts\*\* identified    
\- Breakdown by account type:  
  \- Many records show \`No charge\` for over a year  
  \- Clear distinction between inactivity in \*\*savings\*\* and \*\*investment\*\* accounts    
\- Inactivity duration visualized via \*\*Last Transaction Date\*\* filter

\---

\#\#\# CLV Estimation    
\*\*Goal:\*\* Estimate Customer Lifetime Value (CLV) using a simplified model based on tenure and transaction activity.    
\*\*Formula Used:\*\*    
\> (Monthly transaction rate × 12 × average profit per transaction)

\*\*Highlights:\*\*    
\- \*\*Total estimated CLV:\*\* ₦186.44M    
\- CLV ranking highlights \*\*Chima Ataman\*\* as the most valuable customer    
\- Visuals include:  
  \- CLV by tenure    
  \- CLV breakdown for Top 10 customers

\---

\#\# Challenges Encountered

\- \*\*Slicer Conflicts:\*\* Managing slicer interactions across multiple pages required syncing filters to avoid cross-filtering issues (e.g., owner\_id selections).  
\- \*\*Date Consistency:\*\* Some \`last\_transaction\_date\` values were \`NULL\`, requiring cleaning before accurate inactivity detection.  
\- \*\*Value Formatting:\*\* Adjusting for large currency figures (in billions) required careful labeling and formatting across visuals to ensure readability.

\---

\#\# Tools & Techniques

\- Power BI Desktop    
\- DAX for calculated columns and measures    
\- Custom visuals: bar charts, pie charts, matrix tables, and KPI cards    
\- Filter panes, drill-through features, and page navigation

\---

\*\*Adebiyi Adeola\*\*    
\*Data Analyst-in-Training\*  
