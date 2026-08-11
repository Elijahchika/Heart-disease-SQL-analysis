# ❤️ Heart Disease Analysis | SQL 

![Healthcare Analytics](https://img.shields.io/badge/Project-Healthcare%20Analytics-blue)
![SQL](https://img.shields.io/badge/SQL-MySQL-orange)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Project-green)


## 📸 SQL Analysis Screenshots

### Overall Heart Disease Analysis

![Overall Heart Disease Analysis](SQL/screenshots/overall_analysis.png)

### Heart Disease by Chest Pain Type

![Chest Pain Analysis](SQL/screenshots/chest_pain_analysis.png)

### Heart Disease by Age Group

![Age Group Analysis](SQL/screenshots/age_group_analysis.png)

## 📊 Project Overview

This project analyzes a **Heart Failure Prediction dataset containing 918 patient records** to identify patterns and trends associated with heart disease.

Using **MySQL for data analysis** and **Power BI for interactive visualization**, I transformed healthcare data into meaningful insights that can support data-driven decision-making.

The project demonstrates the complete data analytics workflow:

**Dataset → SQL Analysis → Insights → Power BI Dashboard**

---

## 🎯 Project Objectives

- Analyze the overall prevalence of heart disease.
- Identify patterns across different age groups.
- Analyze heart disease rates by chest pain type.
- Examine exercise-induced angina.
- Analyze heart disease rates by ST slope.
- Calculate healthcare KPIs.
- Communicate findings through an interactive Power BI dashboard.

---

## 🛠️ Tools & Technologies

- **MySQL** — Data querying and analysis
- **Power BI** — Interactive dashboard and visualization
- **Excel/CSV** — Dataset preparation
- **GitHub** — Project documentation and portfolio

---

## 📁 Dataset

The dataset contains **918 patient records** with cardiovascular and demographic variables including:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Angina
- Oldpeak
- ST Slope
- Heart Disease

---

# 🔎 SQL Analysis

The dataset was imported into MySQL using the table:

``sql
heart_human


SELECT 
    COUNT(*) AS total_patients,
    SUM(HeartDisease) AS patients_with_heart_disease,
    ROUND(
        SUM(HeartDisease) * 100.0 / COUNT(*),
        2
    ) AS heart_disease_rate
FROM heart_human;


Results
Metric
Result
Total Patients
918
Patients with Heart Disease
508
Heart Disease Rate
55.34%
🫀 Heart Disease by Chest Pain Type
Chest Pain Type
Total Patients
Heart Disease
Rate
ASY
496
392
79.03%
TA
46
20
43.48%
NAP
203
72
35.47%
ATA
173
24
13.87%
Key Insight
The ASY chest pain category recorded the highest observed heart disease rate at 79.03% in this dataset.
👥 Heart Disease by Age Group
Age Group
Total Patients
Heart Disease
Rate
60–69
222
163
73.42%
70+
31
22
70.97%
50–59
374
212
56.68%
40–49
211
85
40.28%
Under 40
80
26
32.50%
Key Insight
The 60–69 age group had the highest observed heart disease rate among the defined age groups at 73.42%.
📈 Heart Disease by ST Slope
ST Slope
Total Patients
Heart Disease
Rate
Flat
460
381
82.83%
Down
63
49
77.78%
Up
395
78
19.75%
Key Insight
The Flat ST Slope group recorded the highest observed heart disease rate at 82.83%.
📊 Power BI Dashboard
The SQL analysis was transformed into an interactive Power BI dashboard.
Dashboard Highlights
Total Patients KPI
Patients with Heart Disease
Heart Disease Rate
Age Group Analysis
Chest Pain Analysis
Exercise Angina Analysis
ST Slope Analysis
Interactive filters
Healthcare data visualizations
Dashboard Preview
�

💡 Key Findings
918 patients were analyzed.
508 patients had a positive heart disease outcome.
The overall observed heart disease rate was 55.34%.
ASY chest pain had the highest observed rate at 79.03%.
The 60–69 age group had the highest observed rate among the defined age groups at 73.42%.
Flat ST Slope had the highest observed rate at 82.83%.
Note: These findings describe patterns within the dataset and should not be interpreted as medical diagnoses or causal relationships.
🧠 Skills Demonstrated
SQL
SELECT
COUNT()
SUM()
ROUND()
GROUP BY
ORDER BY
CASE WHEN
Aggregate functions
Calculated metrics
Data Analytics
Data exploration
Data aggregation
KPI development
Segmentation
Trend analysis
Healthcare analytics
Insight generation
Data Visualization
KPI cards
Interactive dashboards
Comparative charts
Data storytelling


Heart-Disease-Analysis/
│
├── README.md
│
├── SQL/
│ ├── heart_disease_analysis.sql
│ └── screenshots/
│ ├── overall_analysis.png
│ ├── chest_pain_analysis.png
│ ├── age_group_analysis.png
│ └── st_slope_analysis.png
│
│
└── Dataset/
    └── heart_failure_prediction.csv


👩‍💻 About Me
I am a Data Analyst passionate about transforming data into meaningful insights, building interactive dashboards, and helping organizations make better data-driven decisions.
Technical Skills
Excel | SQL | Power BI | Tableau | Python | Data Analytics
I enjoy turning raw datasets into clear visualizations and actionable insights.


## 📬 Contact

**Elijah Chika**

📧 Email: onnibellmultipurpose@gmail.com.com


🌐 Portfolio: https://sites.google.com/view/chikas-data-analytics/home

💻 GitHub: https://github.com/Elijahchika

💼 LinkedIn: https://www.linkedin.com/in/your-linkedin-profile
