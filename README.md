# Identifying the Factors Affecting School Dropout Rates in India

## Project Overview
This project, part of the **SOC 476: Contemporary Applications of Social Demography** course at IIT Kanpur, investigates the socio-economic and infrastructural factors influencing **school dropout rates** in rural India.  
The analysis leverages data from the **Annual Status of Education Report (ASER)** for the years **2010, 2014, and 2018** to uncover correlations between teacher attendance, school infrastructure, welfare provisions, and student retention.

---

## Objectives
- Quantify dropout rates for primary classes (1–3 and 4–5) across rural India.
- Identify the influence of **teacher coverage, attendance ratios, infrastructure, and welfare schemes** on dropout rates.
- Provide **data-driven recommendations** for policymakers to improve retention.

---

## 📂 Dataset
- **Source**: Annual Status of Education Report (ASER) – Pratham NGO  
- **Coverage**: 26 states & 3 Union Territories, rural schools only  
- **Sample Size**: ~49,000 school-level records  
- **Years Analyzed**: 2010, 2014, 2018  

---

## ⚙️ Methodology
1. **Data Preprocessing**  
   - Standardized column names and state names  
   - Filled missing values with appropriate defaults  
   - Created derived variables:
     - `dropout_rate_1to3`, `dropout_rate_4to5`
     - `teacher_coverage_ratio`
     - `teacher_attendance_ratio`
     - `infra_score` (0–5 scale)
     - `food_water_score` (0–4 scale)  

2. **Analysis**
   - State-wise dropout trends  
   - Correlation between metrics and dropout rates  
   - Region-specific case studies (Bihar, UP, Assam, Maharashtra)  

3. **Tools Used**
   - **Python** (pandas, matplotlib, seaborn)  
   - Google Colab for collaborative analysis  

---

## Key Findings
- **Teacher availability and attendance** are the strongest predictors of low dropout rates.  
- High infrastructure and welfare scores alone do not ensure low dropout unless paired with adequate teacher presence.  
- States with high teacher shortages (Bihar, Uttar Pradesh) have dropout rates >40%, while states with high teacher coverage (Maharashtra, Tamil Nadu) show <15% dropout.  


