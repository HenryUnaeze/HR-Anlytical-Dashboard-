# 🧠 HR Analytics Insight
## A Data Analysis Project: Workforce Distribution, Satisfaction & Retention

## 📑 Table of Contents
## What Problem This Project Solves

1. Methodology

2. Tech Stack

3. Project Pipeline

4. Project Limitations & Areas for Improvement

5. Data Sources
# What Problem This Project Solves
This HR dashboard provides an at-a-glance summary of the workforce composition, job satisfaction, layoffs, and proximity-to-work insights by department.
The objective is to support strategic HR decision-making in the following areas:

- Gender diversity

- Employee retention (layoff vs. on-service)

- Job and environmental satisfaction

- Department-level staffing metrics

- Influence of commute distance on staffing

### 👉 This helps leadership and HR managers identify red flags like high attrition zones or satisfaction gaps across departments.

![alt text](https://github.com/HenryUnaeze/HR-Anlytical-Dashboard-/blob/main/HR%20Dashboard..png)

## 💡 Methodology
The dashboard aggregates and visualizes key HR metrics across departments:

- Gender distribution across the entire workforce

- Layoff and on-service rates by department

- Environment and job satisfaction levels

- Employee distribution by commuting distance

- Years at company by department

### Each metric is visualized for quick comparative insights using:

- Bar charts

- Pie charts

- Treemaps

## 🛠 Tech Stack
-Tool	Use Case
Excel and Power Query for initial HR data preparation
Power BI	Dashboard creation, interactive filtering, and charting

## 🔄 Project Pipeline
### 🗂 Data Collection
Sourced internal HR data on employees, departments, satisfaction levels, distance to workplace, and service status

### 🧹 Data Cleaning & Preparation
Standardized categories like gender, department, job satisfaction level

Classified distance ranges (Very Close, Close, Very Far)

## 📊 Data Analysis
- Summarized total employees (1K) and gender split (42% Female, 58% Male)

- Compared layoffs across departments (HR has visibly more layoffs than R&D or Sales)

Aggregated years-at-company by department (R&D dominates in experience)

## 📈 Data Visualization
- Bar Chart: Layoff vs On-service per department

- Pie Chart: Environment satisfaction by department

- Stacked Bar: Employees by commuting distance and department

- Treemap: Job satisfaction by department

- Combined bar chart: Headcount vs. total years at company

## ✅ Recommendations & Insights
- Human Resources shows higher layoffs and lowest total years, indicating potential instability

- Research & Development has strong satisfaction and retention, making it a model department

- Most employees live "Very Close" to the office—location is a likely hiring/retention factor

- Job satisfaction is lowest in Sales, suggesting a review of engagement strategies is needed

## Project Limitations & Areas for Improvement
- No Time-Series View	Cannot track how satisfaction, layoffs, or retention evolved over time
- No Performance Metrics	Satisfaction and tenure are analyzed, but not employee performance
- Ambiguous Definitions	Terms like “Very Close” or “High Satisfaction” could benefit from clear numeric boundaries
- Department Filter Only	Lacks filters for job level, age group, or location, which can provide deeper insights

## 🔧 Improvement Ideas:

- Add trend lines for satisfaction or layoffs over time

- Integrate performance reviews or KPIs

- Visualize correlation between commute distance and layoff rate

- Add drill-through filters by job level, region, or tenure bracket

## 📚 Data Sources
Data Type	Source
- Employee Data	Internal HRIS (Human Resource Information System)
- Satisfaction Scores	Internal HR surveys or appraisal data
- Layoff Status	HR administrative logs
- Commute/Distance Info	Self-reported or GPS-estimated commuting data

## 🎯 Summary Insight
- This dashboard provides a clear, comparative breakdown of departmental HR health in terms of satisfaction, retention, and demographics.
- The Research & Development department shows high retention and satisfaction, while Human Resources signals potential issues due to low tenure and higher layoffs.
T- his tool enables HR managers to target interventions by department and demographic to improve organizational health.
