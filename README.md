# Healthcare Appointment No-show Analysis

A complete healthcare analytics project focused on understanding patient appointment no-show behavior using Python and Power BI.

---

# Project Overview

Healthcare appointment no-shows are a major operational challenge for hospitals and clinics. Missed appointments lead to wasted resources, longer waiting times, and reduced healthcare efficiency.

This project analyzes healthcare appointment data to identify the major factors associated with missed appointments, including:

- Waiting time
- Age
- Gender
- Medical conditions
- SMS reminders
- Neighborhood patterns

The project combines:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Interactive Power BI Dashboards
- Business Insights & Recommendations

---

# Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- Jupyter Notebook

---

# Dataset Information

Dataset Source:
Brazilian Medical Appointment Dataset (Kaggle)

Dataset contains:
- ~72,000 appointment records
- 80 neighborhoods
- Patient demographic information
- Medical conditions
- Appointment scheduling details
- Attendance status

---

# Project Workflow

## 1. Data Cleaning & Preprocessing
- Removed invalid waiting day values
- Converted date columns to datetime format
- Created waiting time categories
- Created weekday and age-group features
- Removed inconsistent records
- Exported cleaned dataset for dashboard creation

---

## 2. Exploratory Data Analysis (EDA)

Performed detailed EDA to analyze:
- No-show distribution
- Waiting time impact
- Gender patterns
- Age distribution
- Weekday trends
- Medical condition analysis
- Neighborhood-level behavior

---

# Dashboard 1 — Executive & Operational Overview
<img width="1249" height="705" alt="Dashboard1" src="https://github.com/user-attachments/assets/d81617ec-6d7b-4633-bc67-c2030d0d2c71" />

This dashboard provides high-level operational insights into healthcare appointment attendance.

## Key Insights
- Longer waiting times were associated with higher no-show rates
- Wednesday and Thursday showed relatively higher no-show percentages
- Young adult age groups showed higher no-show behavior
- Female patients accounted for the majority of appointments

## Dashboard Features
- KPI Cards
- Waiting Time Analysis
- Gender Distribution
- Weekday Analysis
- Age Group Analysis
- Interactive Slicers

---

# Dashboard 2 — Patient & Geographic Insights
<img width="1249" height="694" alt="Dashboard2" src="https://github.com/user-attachments/assets/bd772f49-8ae7-4c1a-bbe2-d719b570610e" />

This dashboard focuses on geography, patient characteristics, and operational behavior.

## Key Insights
- Certain neighborhoods had significantly higher missed appointment counts
- Hypertension patients had the highest number of missed appointments
- SMS reminders alone were not sufficient to reduce no-shows significantly
- Geographic and demographic factors influenced attendance patterns

## Dashboard Features
- Neighborhood Analysis
- Medical Condition Analysis
- SMS Reminder Impact
- Operational KPIs
- Insight Cards

---

# Key Findings

- Waiting time was the strongest factor associated with no-show behavior
- More than 28% of appointments were missed
- Long waiting periods increased missed appointment rates significantly
- Certain neighborhoods consistently showed higher no-show counts
- Medical conditions influenced attendance behavior
- SMS reminders alone were not enough to fully reduce no-shows

---

# Recommendations

Based on the analysis:
- Reduce appointment waiting times
- Improve reminder systems beyond SMS
- Focus interventions on high-risk neighborhoods
- Monitor attendance patterns regularly
- Use dashboards for operational decision-making

---

# Project Structure

```bash
healthcare-no-show-analysis/
│
├── data/
├── notebooks/
├── dashboards/
├── reports/
├── images/
├── README.md
└── requirements.txt
