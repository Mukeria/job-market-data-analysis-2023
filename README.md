# Data Analyst Job Market Analysis (2023)



A SQL project analyzing real 2023 job postings to understand what Data Analyst roles pay, which skills are most in demand, and which skills are linked to higher salaries in remote positions.

---

## Background

The idea behind this project was simple: instead of guessing what skills matter in data analytics, use actual job posting data to see what employers are hiring for.

I focused on remote Data Analyst roles from 2023 to answer questions like:
- What are the highest paying Data Analyst jobs?
- Which skills appear most often in job descriptions?
- Which skills are actually linked to higher salaries?

---

## Stack & Tools

- PostgreSQL (data querying & analysis)  
- SQL (joins, CTEs, aggregations)  
- Visual Studio Code (query development & project structure)  
- Job postings dataset (2023)

---

## Analysis

The project is built around a few core SQL analyses:

### 1. Top Paying Remote Data Analyst Jobs
Filtered for:
- Data Analyst roles
- Remote jobs (`job_work_from_home = true`)
- Valid salary data

Example result:
- Senior Data Analyst roles with high salary ranges in the dataset

---

### 2. Most In-Demand Skills
Joined job postings with skills tables to count frequency.

Example insight:
- SQL, Excel, and Python dominate job requirements
- Tableau and Power BI frequently appear in BI-focused roles

---

### 3. Skills vs Salary Analysis
Calculated average salary per skill to identify higher-paying tools.

Example insight:
- Python and cloud-related skills often correlate with higher salaries
- Basic tools remain essential but don’t always drive pay

---

### 4. Combined Skill Value (Demand + Salary)
Merged demand and salary metrics to identify “high-value skills”:
- High demand + strong salary impact = best ROI skills

---

## Conclusions

- SQL + Excel = entry point into the field  
- Python + BI tools = strong career growth  
- Specialized tools = lower demand but higher pay potential  
