# Healthcare Performance & Patient Analytics Dashboard

A Power BI case study focused on analysing patient activity, hospital operations, financial performance, and patient experience across a multi-state healthcare organisation.

---

## 📌 Project Overview

This project involved designing and implementing an interactive healthcare analytics dashboard using Power BI.

The objective was to transform patient, operational, financial, and target data into a structured business intelligence solution that enables stakeholders to understand healthcare performance, identify patterns, compare performance across states and departments, and highlight areas that require further investigation.

The project covers:

- Patient activity and demographics
- Patient diagnoses and outcomes
- Department and branch performance
- Waiting time and patient satisfaction
- Revenue, cost and profitability
- Revenue target performance
- Time-based performance trends
- State-level performance
- Interactive drill-through analysis
- Dynamic executive insights
- Dynamic Row-Level Security

---

# 🎯 1. Project Brief

The project brief was to develop a healthcare performance and patient analytics dashboard for a healthcare organisation operating across multiple Nigerian states.

The dashboard was required to provide management with a consolidated view of:

- Patient activity
- Hospital operations
- Financial performance
- Patient experience

The solution was expected to use Power BI features including Power Query, data modelling, DAX, interactive visualisations, slicers, drill-through, tooltips, bookmarks/page navigation, and Row-Level Security.

The project also required the development of multiple analytical pages addressing specific healthcare and business questions.

---

# 🔎 2. Business Problem

Healthcare organisations generate data across different areas of their operations, including patient visits, departments, diagnoses, revenue, costs, waiting times, satisfaction and outcomes.

Without a consolidated analytical view, it can be difficult to identify patterns in patient activity, understand operational performance, compare financial results, and determine where further investigation may be required.

The key business question addressed by this project was:

> **How is our healthcare organisation performing, what are our patients experiencing, and where are the major areas that require attention?**

The dashboard was designed to answer questions such as:

- Which states and departments have the highest patient activity?
- What are the most common diagnoses and patient outcomes?
- Which departments experience longer waiting times?
- How does patient satisfaction vary across departments and branches?
- Which states and departments generate the most revenue and profit?
- How is revenue performing against targets?
- How does performance change over time?
- Which areas may require further operational or financial investigation?

---

# 👥 3. Who Was the Work For?

This project was developed around a **simulated healthcare organisation** operating across multiple Nigerian states.

The intended users of the dashboard are management and operational stakeholders who need visibility into:

- Patient activity
- Department performance
- Branch activity
- Financial performance
- Patient experience
- State-level performance

The dashboard was therefore designed to support both **high-level management review** and **more detailed operational investigation**.

---

# 📐 4. Project Scope

The project covered the development of a complete Power BI analytical solution rather than a single visual or report.

### Dashboard pages

The final solution includes:

1. **Executive Overview**
2. **Patient Analysis**
3. **Hospital Operations**
4. **Financial Performance**
5. **Patient Experience**
6. **State Performance Details**
7. **Branch Performance Details**

Additional report-page tooltip experiences were created for:

- State Financial Performance
- Department Performance

The project also includes:

- Data cleaning and transformation
- Data modelling
- DAX measures
- Time intelligence
- Dynamic executive insights
- Drill-through functionality
- Report-page tooltips
- Interactive slicers
- Page navigation
- Dynamic Row-Level Security

---

# 👤 5. My Role & Ownership

I independently handled the end-to-end development of the Power BI solution.

My responsibilities included:

- Inspecting and understanding the dataset
- Reviewing data quality
- Cleaning and transforming data using Power Query
- Creating calculated fields required for analysis
- Building the data model
- Creating and configuring the Date Table
- Developing DAX measures
- Implementing time-intelligence calculations
- Designing the dashboard layout
- Selecting appropriate visualisations
- Developing KPI cards
- Creating interactive slicers
- Building drill-through pages
- Creating report-page tooltips
- Developing dynamic executive insights
- Implementing dynamic Row-Level Security
- Reviewing dashboard usability and consistency
- Documenting the final analytical solution

The project therefore demonstrates ownership across the full Power BI development workflow, from data preparation through to the final interactive dashboard.

---

# 🛠️ 6. My Approach

I approached the project as an end-to-end analytics workflow rather than starting directly with dashboard visuals.

### Step 1 — Understand the requirements

I first reviewed the project requirements and identified the main analytical areas:

- Patient analysis
- Hospital operations
- Financial performance
- Patient experience
- Executive reporting

### Step 2 — Inspect the dataset

Before building the report, I reviewed the available tables, fields, data types, categories and numerical values.

The dataset contained:

- Patient visit information
- Demographic information
- State and branch information
- Department information
- Diagnoses
- Services
- Revenue
- Costs
- Visit counts
- Waiting times
- Satisfaction scores
- Patient outcomes
- State revenue targets
- Calendar information

### Step 3 — Prepare the data

I used Power Query to inspect and prepare the data before beginning the dashboard development.

### Step 4 — Build the data model

I established relationships between the analytical tables and created a dedicated Date Table for time-based analysis.

### Step 5 — Develop the analytical layer

I created DAX measures for patient, operational and financial KPIs and added time-intelligence measures.

### Step 6 — Build the dashboard

The dashboard was developed page by page, with each page designed around a specific business question.

### Step 7 — Add interactivity

After the core analysis was working, I added:

- Slicers
- Drill-through
- Report-page tooltips
- Dynamic titles and insights
- Page navigation
- Row-Level Security

### Step 8 — Review and refine

I reviewed the report for consistency, readability, analytical correctness and usability before preparing the final portfolio version.

---

# 🔍 7. What I Did Before Building the Dashboard

Before designing the visuals, I inspected the dataset and validated the underlying information.

The initial data review included checks for:

- Missing values
- Duplicate records
- Data types
- Category consistency
- Unusual values
- Date coverage
- Numerical fields
- Relationships between tables

The dataset contained no identified blank values or duplicate rows during the initial review, and the available categorical and numerical fields were checked before modelling.

This helped establish a reliable foundation before creating the analytical layer.

---

# 🧹 8. Data Preparation & Transformation

Power Query was used to prepare the dataset for analysis.

Key preparation activities included:

- Data quality checks
- Data type validation
- Category validation
- Date preparation
- Creation of patient age groups
- Preparation of analytical fields
- Structuring the tables for modelling

### Age Group

Age was transformed into analytical age groups:

- Under 18
- 18–24
- 25–34
- 35–44
- 45–54
- 55+

A separate sorting field was used to maintain the correct chronological age-group order in visualisations.

---

# 🏗️ 9. Data Model

The Power BI model uses the following main tables:

### Patient_Visits

The primary fact table containing patient, visit, operational and financial information.

### State_Targets

Contains revenue targets by state and supports target-performance analysis.

### Date_Table

A dedicated calendar table covering the 2025 reporting period.

# 📊 10. Dashboard Development

The dashboard was developed as a multi-page Power BI solution, with each page designed around a specific business question.

## Executive Overview

The Executive Overview provides a high-level view of overall healthcare performance.

### Key KPIs

- Total Patients
- Total Visits
- Total Revenue
- Total Profit
- Profit Margin %
- Revenue Target Achievement %

### Visual Analysis

- Monthly Patient Visits
- Revenue by State
- Patients by Department
- Revenue vs Target
- Patient Outcome Distribution

### Filters

- Date
- State
- Branch
- Department
- Gender

The page provides a starting point for understanding overall patient activity, financial performance and target achievement before moving into more detailed analysis.

---

## Patient Analysis

The Patient Analysis page focuses on patient demographics, behaviour, diagnoses and outcomes.

### Key KPIs

- Total Patients
- Total Visits
- Average Visits per Patient
- Returning Patients

### Visual Analysis

- Patients by Age Group
- Patient Distribution by Gender
- Patients by Diagnosis
- Patients by State
- New vs Returning Patients
- Patient Outcomes

The page provides insight into patient composition, patient volume, common diagnoses, patient status and outcomes.

---

## Hospital Operations

The Hospital Operations page examines operational activity across departments and branches.

### Key KPIs

- Total Visits
- Average Visits per Patient
- Average Waiting Time
- Average Satisfaction

### Visual Analysis

- Visits by Department
- Average Waiting Time by Department
- Patient Satisfaction by Department
- Patient Visits by Branch
- Monthly Patient Volume
- Patient Outcomes by Department

This page focuses on workload, waiting time, patient satisfaction and differences in operational activity across departments and branches.

---

## Financial Performance

The Financial Performance page focuses on revenue, costs, profitability and target performance.

### Key KPIs

- Total Revenue
- Total Cost
- Total Profit
- Profit Margin %
- Average Revenue per Patient

### Visual Analysis

- Revenue Target Achievement
- Revenue by State
- Revenue Variance
- Monthly Revenue Trend
- Profit by Department
- Financial Performance Breakdown

The page allows users to examine financial performance and compare actual revenue against assigned targets.

---

## Patient Experience

The Patient Experience page focuses on patient satisfaction, waiting time and outcomes.

### Key KPIs

- Average Satisfaction
- Average Waiting Time
- Total Patients

### Visual Analysis

- Satisfaction by Department
- Satisfaction by Branch
- Satisfaction vs Waiting Time
- Patient Outcomes

The page provides a focused view of patient experience and allows differences in satisfaction and waiting time to be explored across departments and branches.

---

## State Performance Details

A dedicated drill-through page was created to provide detailed analysis for individual states.

The page includes:

- Total Patients
- Total Visits
- Total Revenue
- Total Profit
- Average Satisfaction
- Monthly Patient Visits
- Visits by Department
- Patient Outcomes
- Patients by Diagnosis
- Revenue vs Target

Users can select a state from relevant report visuals and drill through to its detailed performance page.

---

## Branch Performance Details

A dedicated branch-level analysis page was also developed to provide more granular operational and performance information.

This allows branch activity to be investigated beyond the organisation-wide summary pages.

---

# 📐 11. DAX & Analytical Measures

DAX was used to create the analytical layer of the dashboard and calculate the key healthcare, operational and financial performance indicators.

## Core Measures

The dashboard includes measures for:

- Total Patients
- Total Visits
- Total Revenue
- Total Cost
- Total Profit
- Profit Margin %
- Average Revenue per Patient
- Average Waiting Time
- Average Satisfaction
- Previous Month Revenue
- MoM Revenue Growth %
- Previous Year Revenue
- YoY Revenue Growth %
- Revenue Target
- Revenue Variance
- Achievement %

## Dynamic Analytical Measures

Additional measures were developed to support dynamic dashboard insights, including:

- Top Revenue State
- Top Department by Patients
- Peak Visit Month
- Top Patient State
- Top Diagnosis
- Top Patient Outcome
- Busiest Branch
- Busiest Department
- Longest Waiting Department
- Lowest Satisfaction Department
- Top Profit Department
- Top Revenue Service
- Top Achievement State

These measures allow the dashboard to dynamically identify important patterns based on the current filter context.

---

# ⏱️ 12. Time Intelligence

Time-intelligence calculations were implemented to support period-based analysis.

The dashboard includes:

- Previous Month Revenue
- Month-over-Month Revenue Growth %
- Previous Year Revenue
- Year-over-Year Revenue Growth %

A dedicated Date Table was used to support chronological analysis and time-based calculations.

### Dataset Limitation

The available dataset covers only the 2025 reporting period.

Because there is no 2024 data in the supplied dataset, a meaningful year-over-year comparison against 2024 cannot be established.

The Previous Year and YoY measures were therefore included as part of the analytical framework, but the available data does not support interpretation of 2025 performance against an actual 2024 baseline.

---

# 🎛️ 13. Interactivity & User Experience

The dashboard was designed as an interactive analytical solution rather than a collection of static charts.

## Slicers

Users can filter the report by:

- Date
- State
- Branch
- Department
- Gender

## Drill-through

Drill-through functionality allows users to move from summary-level analysis into more detailed state and branch performance views.

## Report-Page Tooltips

Custom report-page tooltips were created to provide additional context without overcrowding the main dashboard.

The custom tooltip pages include:

- State Financial Tooltip
- Department Performance Tooltip

## Dynamic Insights

Dynamic DAX-based insight cards were created to provide context-aware summaries.

Examples include:

- Highest revenue state
- Highest patient-volume department
- Peak patient-visit month
- Most common diagnosis
- Most frequent patient outcome
- Busiest branch
- Longest waiting-time department
- Lowest satisfaction department
- Highest-profit department

These insights update according to the current report filter context.

## Page Navigation

Page navigation was implemented to make movement between the dashboard's analytical sections easier and improve the overall user experience.

---

# 🔐 14. Dynamic Row-Level Security

Dynamic Row-Level Security (RLS) was implemented as an additional security feature.

A security mapping table was created containing user email addresses and their assigned states.

The RLS logic uses:

`USERPRINCIPALNAME()`

to identify the current user and dynamically determine the state they are permitted to access.

### Example Security Mapping

| User | Assigned State |
|---|---|
| User A | Lagos |
| User B | Rivers |
| User C | Anambra |
| User D | Abuja |

The purpose of the implementation is to allow the same report to provide state-specific access to authorised users rather than requiring separate reports for each state.

---

# 🧹 15. Data Preparation & Transformation

Data preparation was performed using Power Query before the dashboard visuals were developed.

## Data Quality Checks

The dataset was reviewed for:

- Missing values
- Duplicate records
- Data type issues
- Inconsistent categories
- Unusual values
- Date coverage
- Numerical field validity

The initial review identified no blank values or duplicate rows, and the available categories and data types were validated before modelling.

## Transformations

The preparation process included:

- Validating data types
- Reviewing categorical fields
- Preparing date fields
- Creating patient age groups
- Creating an age-group sorting field
- Preparing tables for analysis
- Structuring the data for the Power BI model

## Patient Age Groups

Age was transformed into the following analytical groups:

- Under 18
- 18–24
- 25–34
- 35–44
- 45–54
- 55+

A separate sorting field was used to ensure that the age groups appeared in the correct logical order.

---

# 🧠 16. Analytical Approach

I approached the project as an end-to-end business intelligence workflow rather than starting directly with dashboard visuals.

### Step 1 — Understand the Requirements

I first reviewed the project requirements and identified the major analytical areas and business questions the dashboard needed to address.

### Step 2 — Inspect the Data

I reviewed the available tables, fields, data types, categories and numerical values before developing the model.

### Step 3 — Prepare the Data

I used Power Query to validate, transform and prepare the dataset for analysis.

### Step 4 — Build the Data Model

I established the required relationships and prepared the Date Table for time-based analysis.

### Step 5 — Develop the DAX Layer

I created measures for patient, operational and financial KPIs, as well as time-intelligence calculations.

### Step 6 — Design the Dashboard

Each dashboard page was designed around a specific analytical purpose and business question.

### Step 7 — Add Interactivity

I implemented slicers, drill-through pages, report-page tooltips, page navigation and dynamic insights.

### Step 8 — Implement Security

I added dynamic Row-Level Security using a user-to-state mapping approach.

### Step 9 — Review and Refine

I reviewed the report for analytical accuracy, visual consistency, usability and interaction behaviour.

---

# 🧩 17. Challenges Encountered & How I Solved Them

The development process involved several analytical and technical challenges.

## Challenge 1 — Defining Total Visits Correctly

The dataset contains a `Visit_Count` field.

A simple row count would represent the number of records rather than the actual number of visits.

### Solution

I used the `Visit_Count` field when calculating Total Visits and distinct Patient IDs when calculating Total Patients.

This ensured that the two KPIs represented different business concepts.

---

## Challenge 2 — Sorting Age Groups

The age-group categories required additional sorting logic because alphabetical sorting would not produce the intended age progression.

### Solution

I created a numerical sorting field and used it to control the display order:

- Under 18
- 18–24
- 25–34
- 35–44
- 45–54
- 55+

---

## Challenge 3 — Limited Historical Data

The dataset only contains 2025 records, making a genuine year-over-year comparison with 2024 impossible.

### Solution

I retained the required previous-year and YoY measures as part of the analytical framework but documented the data limitation rather than creating unsupported historical values.

---

## Challenge 4 — Drill-through Configuration

Drill-through required the source visual and drill-through page to use compatible state context.

### Solution

I reviewed the fields used by the source visuals and configured the drill-through pages around the relevant state and branch context.

---

## Challenge 5 — Dynamic Executive Insights

Static text would not respond to filters applied by the user.

### Solution

I created supporting DAX measures to dynamically identify top states, departments, branches, diagnoses, outcomes and other analytical categories.

These measures were then combined to generate context-aware narrative insights.

---

## Challenge 6 — Dynamic Row-Level Security

Implementing RLS required the security mapping to work with the existing state-based model.

### Solution

I created a user-to-state security table and used `USERPRINCIPALNAME()` within the RLS logic to dynamically determine the user's permitted state.

---

# 📈 18. Results & Key Findings

The completed dashboard provides a consolidated analytical view of the supplied healthcare dataset.

## Dataset Summary

- **1,200 patient records**
- **2,920 total visits**
- **4 states**
- **12 branches**
- **6 departments**
- **6 services**
- **6 diagnoses**
- **2 genders**
- **4 patient outcomes**
- **2025 reporting period**

## Key Findings

The analysis identified several notable patterns within the dataset:

- **Rivers recorded the highest revenue** among the states.
- **Pediatrics recorded the highest patient volume** among departments.
- **August recorded the highest monthly patient visits** within the 2025 reporting period.
- **Returning patients represented a substantial proportion of the patient population.**
- **Malaria was the most common diagnosis** in the analysed patient data.
- **Recovered was the most frequently recorded patient outcome.**
- Waiting time varied across departments.
- Patient satisfaction varied across departments and branches.
- Revenue performance differed across states relative to their assigned targets.

These findings describe patterns within the supplied dataset and should not be interpreted as measured improvements in a real healthcare organisation.

---

# 💡 19. Business Recommendations

Based on the patterns identified in the analysis, the following areas could be considered for further investigation.

## 1. Review Capacity in High-Volume Departments

Departments with higher patient volumes could be reviewed to determine whether staffing, scheduling and resource allocation are aligned with patient demand.

## 2. Investigate Waiting-Time Differences

Departments with relatively longer waiting times could be investigated to identify potential process, staffing or capacity constraints.

## 3. Monitor Patient Satisfaction

Differences in patient satisfaction across departments and branches could be monitored to identify areas that may require further investigation.

## 4. Review State-Level Target Performance

States with lower revenue target achievement could be investigated to understand the factors contributing to the observed performance.

## 5. Examine Revenue and Profit Drivers

High-performing services and departments can be examined to understand their contribution to overall revenue and profitability.

## 6. Use Patient Trends for Planning

Patient volume, diagnoses and outcomes can be monitored to support future operational planning and resource allocation.

These recommendations are based on analytical patterns in the supplied dataset and represent areas for further investigation rather than measured post-project outcomes.

---

# ⚠️ 20. Project Limitations

Several limitations should be considered when interpreting the analysis.

### Single-Year Dataset

The available data covers only 2025, which limits historical trend and year-over-year analysis.

### Simulated Business Context

The project uses a simulated healthcare organisation and should therefore be viewed as a portfolio/business intelligence case study rather than a live hospital implementation.

### No Measured Post-Project Business Impact

The project demonstrates analysis and recommendations, but it does not include implementation of the recommendations or measured business outcomes after deployment.

### Dataset Scope

The conclusions are limited to the fields and records available in the supplied dataset.

---

# 📸 21. Dashboard Preview

The repository contains screenshots of the completed Power BI dashboard.

## Executive Overview

![Executive Overview](Executive%20Overview%20Page%20v2.png)

High-level view of patient, operational and financial performance.

## Patient Analysis

![Patient Analysis](Patient%20Analysis%20Page.png)

Analysis of patient demographics, diagnoses, patient type and outcomes.

## Hospital Operations

![Hospital Operations](Hospital%20Operation%20Page.png)

Analysis of department activity, waiting time, satisfaction, branch activity and patient volume.

## Financial Performance

![Financial Performance](Financial%20Performance%20Page.png)

Analysis of revenue, costs, profitability and revenue target performance.

## Patient Experience

![Patient Experience](Patient%20Experience%20Page.png)

Analysis of patient satisfaction, waiting time and outcomes.

## State Performance Details

![State Details](State%20Details%20Page.png)

Detailed state-level drill-through analysis.

## Branch Performance Details

![Branch Details](Branch%20Details%20Page.png)

Detailed branch-level performance analysis.

---

# 📁 22. Project Files

The repository contains the following project resources:

| File | Description |
|---|---|
| `.pbix` | Completed Power BI dashboard |
| `.xlsx` | Healthcare project dataset |
| `.png` | Dashboard screenshots and supporting visual documentation |
| `README.md` | Project documentation |

---

# 🧰 23. Skills Demonstrated

## Data Analysis

- Data Cleaning
- Data Validation
- Data Transformation
- Exploratory Data Analysis
- KPI Development
- Trend Analysis
- Comparative Analysis
- Business Insight Generation

## Power BI

- Power Query
- Data Modelling
- DAX
- Time Intelligence
- Dashboard Development
- Data Visualisation
- Slicers
- Drill-through
- Report-Page Tooltips
- Dynamic Insights
- Row-Level Security

## Business Intelligence

- Business Requirements Analysis
- Business Question Development
- KPI Design
- Dashboard Storytelling
- Operational Analysis
- Financial Performance Analysis
- Patient Experience Analysis

---

# 🎓 24. What This Project Demonstrates

This project demonstrates my ability to take a structured analytics requirement and develop an end-to-end Power BI solution.

The work goes beyond creating individual charts and includes the complete analytical workflow:

```text
Business Requirements
        ↓
Data Inspection
        ↓
Data Preparation
        ↓
Data Modelling
        ↓
DAX & KPI Development
        ↓
Dashboard Design
        ↓
Interactive Analysis
        ↓
Drill-through & Tooltips
        ↓
Dynamic Insights
        ↓
Row-Level Security
        ↓
Validation & Documentation
```

# 👨‍💻 Author

Ibitoye David Oluwapelumi

First Class Mathematics Education Graduate | Data Analyst
