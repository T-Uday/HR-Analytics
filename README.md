# HR Analytics Dashboard — Power BI

## 📊 Project Overview

This project is an interactive **HR Analytics Dashboard built using Microsoft Power BI**. It transforms employee-level HR data into meaningful insights related to workforce composition, attrition, employee engagement, compensation, career progression, promotion, retrenchment, and employee risk.

The dashboard is designed to support **HR reporting, workforce planning, retention analysis, and data-driven decision-making**.

## 🎯 Objectives

* Analyze overall workforce and employee demographics
* Understand employee attrition and retention patterns
* Analyze employee satisfaction and engagement
* Evaluate compensation and income patterns
* Identify employees due for promotion
* Analyze retrenchment-related information
* Identify employee risk using a rule-based risk score
* Provide interactive employee-level analysis and drill-through

## 🗂️ Data Sources

The project uses an Excel workbook containing four main datasets:

* **HR** — Primary employee-level HR data
* **Employees** — Employee number and employee name mapping
* **Promotion** — Employees identified as due for promotion
* **Retrenchment** — Employees identified for retrenchment

The HR dataset contains **1,470 employee records and 35 columns**.

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query** — Data cleaning and transformation
* **DAX** — Calculated columns and KPI measures
* **Microsoft Excel** — Source data

## 📈 Dashboard Pages

### 1. HR Executive Dashboard

Provides an overall view of:

* Total Employees
* Attrition
* Retention
* Promotion
* Retrenchment
* Average Income
* Overtime
* Employee Risk

### 2. Attrition Analysis

Analyzes attrition across:

* Department
* Job Role
* Job Level
* Age
* Overtime
* Business Travel
* Tenure

### 3. Employee Engagement

Focuses on:

* Job Satisfaction
* Environment Satisfaction
* Relationship Satisfaction
* Work-Life Balance
* Engagement and attrition patterns

### 4. Workforce & Compensation

Analyzes:

* Headcount
* Job Levels
* Job Roles
* Monthly Income
* Salary Bands
* Employee Experience and Tenure

### 5. Promotion & Retrenchment

Provides analysis of:

* Promotion Due
* Retrenchment
* Department and Job Role distribution
* Performance-related segmentation
* Promotion/Retrenchment exceptions

### 6. HR Risk & Employee Details

Provides:

* Risk Score
* Risk Category
* Risk distribution
* Employee-level details
* Interactive filtering and drill-through

## ⚙️ Data Preparation

The data was prepared using Power Query through:

1. Data type validation
2. Text and whitespace cleaning
3. Duplicate and null-value checks
4. Employee identifier normalization
5. Merging related employee information
6. Creation of Promotion and Retrenchment flags
7. Creation of Age, Salary, Tenure and Distance bands
8. Validation of merged records

## 📌 Key DAX Concepts

The project uses DAX measures for:

* Total Employees
* Attrition Employees
* Attrition Rate
* Retention Rate
* Promotion Due
* Retrenchment
* Average Income
* Overtime %
* Risk Score
* Risk Category

The Risk Score is a **rule-based analytical indicator**, not a predictive machine-learning model.

## 🔍 Key Features

* Interactive dashboards
* KPI cards
* Slicers and filters
* Employee-level table
* Drill-through analysis
* Conditional formatting
* Risk categorization
* Department and job-role analysis
* Data-driven HR insights

## 📁 Project Structure

```text
HR-Analytics-PowerBI/
│
├── README.md
├── HR_Analytics_Data.xlsx
├── HR_Analytics.pbix
└── Screenshots/
    ├── Executive_Dashboard.png
    ├── Attrition_Analysis.png
    ├── Engagement.png
    ├── Compensation.png
    ├── Promotion_Retrenchment.png
    └── Risk_Analysis.png
```

## ⚠️ Scope Note

This project analyzes the supplied employee snapshot. It does not make causal claims, automated employment decisions, or true time-series turnover predictions where historical employee snapshots or hire/termination dates are unavailable.

## 👨‍💻 Project

**HR Analytics Dashboard | Microsoft Power BI**

Built to demonstrate practical skills in **Power BI, Power Query, DAX, data modeling, dashboard design, and HR analytics**.
# HR-Analytics
Power BI HR Analytics dashboard for analyzing employee attrition, workforce trends, compensation, engagement, promotion, retrenchment, and employee risk using interactive dashboards, KPIs, DAX measures, and data visualization.
