**📊 Bank Loan Analysis using SQL & Power BI**

**📌 Project Overview**

This project presents an end-to-end loan portfolio analytics solution developed using SQL for data processing and KPI computation and Power BI for data modeling, visualization, and interactive reporting. The objective is to analyze loan performance, assess credit risk, and derive actionable insights to support data-driven decision-making in a banking context.

The analytical solution is structured into three Power BI dashboards—Summary, Overview, and Details—each designed to address distinct analytical requirements ranging from executive-level insights to granular loan-level analysis.

---
**🎯 Problem Statement**

Financial institutions require timely and accurate insights into loan performance, borrower behavior, and portfolio risk to ensure sustainable lending practices. Raw loan data, while extensive, does not inherently provide meaningful insights without structured analysis and visualization.

This project aims to:

* Transform raw loan data into actionable metrics using SQL
* Enable portfolio-level monitoring through high-level KPIs
* Support risk assessment via Good vs Bad loan classification
* Provide trend, geographic, and segmentation analysis
* Deliver a comprehensive, drill-down reporting interface through Power BI

---
**🛠️ Tools & Technologies**

* SQL (SQL Server)
  * Data extraction, filtering, and aggregation
  * KPI calculations (MTD, PMTD, MoM)
  * Loan quality and risk classification
* Power BI
  * Data modeling and relationships
  * DAX measures for time intelligence
  * Interactive dashboards and visual analytics
---
**🗂️ Dataset Description**

**Table Used:** Bank_Loan_Data

The dataset includes:

* Loan issue date
* Loan amount and total payment received
* Interest rate and Debt-to-Income (DTI) ratio
* Loan status (Fully Paid, Current, Charged Off)
* Borrower attributes such as state, employment length, home ownership, loan purpose, and grade

---
**📌 SQL-Based Analysis & KPI Computation**

SQL queries are used to compute core performance metrics that feed directly into Power BI.

Loan Volume Metrics
* Total Loan Applications
* Month-to-Date (MTD) Loan Applications
* Previous Month-to-Date (PMTD) Applications
* Month-over-Month (MoM) change analysis

Financial Performance Metrics
* Total Funded Amount (overall, MTD, PMTD)
* Total Amount Received (overall, MTD, PMTD)

Risk & Profitability Metrics
* Average Interest Rate (overall, MTD, MoM)
* Average Debt-to-Income (DTI) Ratio (overall, MTD, MoM)

---

**✅ Loan Quality Classification**

Loans are categorized based on repayment status to evaluate portfolio quality.

**Good Loans (Fully Paid and Current)**
* Good Loan Application Percentage
* Total Good Loan Applications
* Good Loan Funded Amount
* Good Loan Total Amount Received

**Bad Loans (Charged Off)**

* Bad Loan Application Percentage
* Total Bad Loan Applications
* Bad Loan Funded Amount
* Bad Loan Total Amount Received
* This classification supports quantitative credit risk assessment and default analysis.


---

**📊 Power BI Dashboards**

The Power BI report consists of three interlinked dashboards, built on SQL-prepared data and enhanced with DAX-based measures.

---

**🧾 Dashboard 1: Summary**

**Objective:**

To provide a **high-level snapshot of loan portfolio performance** for executive and managerial decision-making.

**Key Features:**

* KPI cards displaying:
 * Total Loan Applications
 * Total Funded Amount
 * Total Amount Received
 * Average Interest Rate
 * Average DTI
* MTD and MoM performance comparisons
* Good Loan vs Bad Loan distribution (donut charts)
* Loan Status grid view including:
  * Total applications
  * Funded and received amounts
  * MTD metrics
  * Average interest rate and DTI
This dashboard enables rapid assessment of **portfolio health and risk exposure.**

---

📈 Dashboard 2: Overview

Objective:

To identify **trends, geographic distribution, and borrower segmentation** patterns.

**Visualizations Included:**

* Monthly loan application trends by issue date (line chart)
* Regional loan distribution by state (filled map)
* Loan term distribution (donut chart)
* Loan applications by employment length (bar chart)
* Loan purpose breakdown (bar chart)
* Home ownership impact on lending (tree map)

**Metrics Displayed:**

* Total Loan Applications
* Total Funded Amount
* Total Amount Received

This dashboard supports **strategic analysis and demand pattern identification.**

---

**🔍 Dashboard 3: Details**

**Objective:**

To provide a **granular, loan-level analytical view** supporting in-depth exploration and operational reporting.

**Key Capabilities:**

* Consolidated grid view of essential loan metrics
* Loan-level and segmented analysis
* Interactive filters and drill-down functionality
* Comprehensive access to borrower and loan performance data

The Details Dashboard serves as a **centralized analytical interface** for detailed portfolio evaluation and audit support.

**🎛️ Interactivity & User Controls**

Power BI slicers allow dynamic filtering by:

* State
* Grade
* Purpose
* Measure selection

---

**✅ Analytical Outcomes**

By integrating **SQL-based data aggregation** with **Power BI visual analytics**, this project delivers:

* Executive-level performance monitoring
* Quantitative credit risk and portfolio quality assessment
* Temporal, geographic, and segmentation insights
* Detailed, drill-down reporting for analytical and operational use cases

---

**Conclusion 🎯**

This project showcases an end-to-end **loan analytics solution using SQL and Power BI**, where raw loan data is transformed into meaningful KPIs and interactive dashboards. Through the **Summary, Overview, and Details** dashboards, the analysis enables high-level portfolio monitoring, trend and segmentation analysis, and detailed loan-level insights. The project demonstrates strong capabilities in data modeling, KPI development, and dashboard storytelling, highlighting how business intelligence tools can support **risk assessment, performance tracking, and data-driven decision-making** in a financial services environment.

---

**Contributions**

Explore the Power BI dashboard for interactive visualizations: 

Explore the SQL word file for query and data analysis:
