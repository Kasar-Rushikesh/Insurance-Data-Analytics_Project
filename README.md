# Insurance Analytics Dashboard | Power BI + SQL + Tableau

## 📌 Project Overview

The **Insurance Analytics Dashboard** is a complete Business Intelligence project designed to analyze insurance business performance using interactive dashboards and data-driven insights.
This project combines **SQL for data preparation**, **Power BI for advanced visualization**, and **Tableau for storytelling dashboards**.

The dashboard helps stakeholders monitor policies, claims, customers, revenue, renewals, opportunities, and executive performance in one place.

---

# 🎯 Objectives

* Track total policies and customers
* Analyze claim status and claim amount
* Monitor policy renewals and new business growth
* Measure cross-sell opportunities
* Evaluate account executive performance
* Understand customer demographics
* Improve decision-making using visual insights

---

# 🛠️ Tools & Technologies Used

* **MySQL** – Data cleaning, transformation, SQL queries
* **Power BI** – Interactive dashboards, KPIs, slicers, DAX measures
* **Tableau** – Data storytelling and executive dashboards
* **Excel / CSV** – Raw dataset source

---

# 📂 Dataset Modules

The project includes multiple insurance-related tables such as:

* Brokerage
* Fees
* Individual Budget
* Invoice
* Meeting List
* Opportunity
* Placed Achievement
* Claims
* Customers
* Policies

---

# 📊 Dashboard Pages & Features

---

# 1️⃣ Weekly Branch Dashboard

This dashboard focuses on weekly branch performance and sales pipeline tracking.

### Key KPIs:

* Cross Sell Placement Achievement %
* New Placement Achievement %
* Renewal Placement Achievement %
* Cross Sell Invoice Achievement %
* New Invoice Achievement %
* Renewal Invoice Achievement %

### Visual Insights:

* Cross Sell Target vs Invoice vs Achievement
* New Business Performance
* Renewal Performance
* Number of Meetings by Account Executive
* Open Opportunity Top Accounts
* Total Opportunities
* Total Open Opportunities
* Opportunity Revenue Top Accounts
* Opportunity Product Distribution
* Number of Invoices by Executive
* Stage Funnel by Revenue

### Business Value:

This dashboard helps managers track branch targets, executive activity, and revenue opportunities in real time.

---
<img width="1919" height="1006" alt="Screenshot 2026-04-13 203827" src="https://github.com/user-attachments/assets/29781357-b3f3-4271-9008-1e66d0aba17a" />

# 2️⃣ Insurance Analyst Dashboard

This dashboard provides performance tracking of opportunities, renewals, invoices, and product sales.

### Included Metrics:

* Cross Sell Achievement %
* New Invoice Achievement %
* Renewal Achievement %
* Open Opportunities Count
* Meetings by Account Executive
* Invoice Count by Executive
* Opportunity Revenue
* Product Distribution
* Revenue Funnel

### Benefits:

* Compare executive performance
* Monitor sales pipeline
* Analyze revenue generation
* Improve branch productivity
<img width="1601" height="742" alt="Screenshot 2026-04-13 203914" src="https://github.com/user-attachments/assets/ae47021f-5bb3-4833-8268-5505b89ed2dc" />

---

# 3️⃣ Insurance Analytics Dashboard

This dashboard focuses on customer, claims, policy, and premium analysis.

### Main KPIs:

* Total Policies
* Total Customers
* Total Claim Amount
* Claim Status Wise Policy Count
* Age Bucket Wise Policy Count
* Gender Wise Policy Count
* Payment Status Wise Policy Count
* Policy Type Wise Total Policies
* Expiring Policies This Year
* Premium Growth Rate (Year Wise)

### Filters Available:

* Marital Status
* Gender
* Policy Status
* Policy Type
* Year

### Business Benefits:

* Understand customer demographics
* Track policy growth trends
* Monitor claim approval rates
* Identify expiring policies
* Analyze premium revenue growth
<img width="861" height="490" alt="Screenshot 2026-04-13 204110" src="https://github.com/user-attachments/assets/652ed613-a3d5-40c5-bb84-6d2d0701eaf4" />

---

# 🧮 SQL Work Performed

The SQL part of this project includes:

* Importing raw insurance datasets
* Creating tables
* Renaming columns
* Data cleaning
* Handling null values
* Joining multiple tables
* Aggregations
* KPI queries
* Year-wise / Month-wise analysis
* Claim status analysis
* Customer segmentation

Example Queries:

```sql
SELECT Claim_Status, COUNT(*) 
FROM Claims
GROUP BY Claim_Status;
```

```sql
SELECT YEAR(Date), SUM(Premium_Amount)
FROM Policies
GROUP BY YEAR(Date);
```

---

# 📈 Power BI Features Used

* Cards
* KPI Indicators
* Clustered Bar Charts
* Donut Charts
* Funnel Charts
* Slicers
* DAX Measures
* Drillthrough
* Filters
* Conditional Formatting

---

# 📉 Tableau Features Used

* Interactive Dashboards
* Parameters
* Filters
* Highlight Actions
* Story Sheets
* Executive Layout Design

---

# 💡 Key Insights Generated

* Approved claims are higher than denied claims
* Renewal business contributes significant revenue
* Certain executives generate more meetings and invoices
* Premium growth trend changes year by year
* Some policy categories have high expiration risk
* Customer demographics help target products better

---

# 🚀 Outcome

This project demonstrates strong skills in:

✔ SQL Query Writing
✔ Data Cleaning
✔ Data Modeling
✔ Dashboard Design
✔ Business Analysis
✔ KPI Reporting
✔ Power BI Development
✔ Tableau Visualization

---

# 📷 Dashboard Screenshots

(Add your screenshots here in GitHub repository)

* Weekly Branch Dashboard
* Insurance Analyst Dashboard
* Insurance Analytics Dashboard

---

# 🔗 GitHub Repository Includes

* SQL File
* Power BI Dashboard (.pbix)
* Tableau Dashboard (.twb / .twbx)
* Dataset Files
* Screenshots
* README.md

---

# 🙌 Author

**Rushikesh Kasar**
Aspiring Data Analyst | Power BI Developer | SQL Enthusiast

---

# ⭐ If you like this project, give it a star on GitHub!
