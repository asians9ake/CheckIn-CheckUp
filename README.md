# 🏥 CheckIn-CheckUp: An Analytical View into Hospital Admissions  
*By Ashutosh Singhania – Completed in July 2025*

## 🧠 Project Overview

Last week, I completed a comprehensive data analysis project called **CheckIn-CheckUp**, focused on hospital patient admissions. Using a structured healthcare dataset, I explored how demographic and clinical variables influence billing, admission types, and overall patient care. The project reveals data-driven insights that can support hospitals in making smarter operational and financial decisions.

---

## 🎯 Objectives

- Uncover patterns in patient admissions based on **age, gender, condition**, and **insurance**
- Examine the **financial footprint** of different medical conditions and admission types
- Identify how demographic variables affect **length of stay** and **cost**
- Provide **practical recommendations** to improve hospital resource management

---

## 🧹 Data Preprocessing Steps

**Step 1: Initial Review**  
- Assessed column names, data types, and presence of missing or duplicate entries  
- Converted admission/discharge dates into standard datetime format

**Step 2: Feature Engineering**  
- Derived new features like:
  - **Length of Stay** = Discharge Date – Admission Date
  - **Admission Month** for trend analysis

---

## 📊 Exploratory Insights

### 🧍 Demographics  
- **Female Patients:** 27,470  
- **Male Patients:** 27,496  
- **Average Age:** 52 years  

### 🏥 Medical Summary  
- **Top Diagnoses:** Hypertension, Obesity, Diabetes  
- **Test Results:**  
  - Normal – 33.35%  
  - Abnormal – 33.54%  
  - Inconclusive – 33.11%  

📌 *Key Insight:* Medical conditions are almost evenly distributed, with a focus needed on chronic lifestyle diseases.

### 📈 Admission Patterns  
- **Admission Trends (2021–2022):** Relatively stable flow throughout the period  
- **Longer Stays:** Noted in patients with **Arthritis** and **Asthma**  
- **Admission Types:** Elective, Emergency, Urgent — each influencing billing differently  

### 💰 Financial Analysis  
- **Average Billing:** ~$25,540  
- **High-Billing Insurers:** Cigna, Medicare, Blue Cross  
- **Costliest Cases:** Emergency and chronic illness-related admissions  

---

## 🔧 Why This Analysis Matters

This project demonstrates how data can guide hospital decision-making:

- **Early Interventions**: Conditions like arthritis and asthma increase stay duration — identifying them early could reduce load
- **Seasonal Awareness**: Trends can help allocate beds and staff in advance
- **Targeted Insurance Negotiations**: Cigna leads in billing contributions — valuable for financial planning
- **Data-Driven Equity**: Equal gender distribution confirms unbiased care patterns

---

## 📌 Final Takeaways

**Recommendations:**
- Prioritize early screening and awareness for high-cost conditions  
- Analyze admission types to optimize hospital workflow  
- Use insights to renegotiate with major insurance partners  
- Watch month-on-month spikes to avoid future staff/resource shortages

---

## 🗂 Project Assets

📁 **CheckIn-CheckUp/**  
├── Interactive Dashboard (`Healthcareprojectdashboard.jpg`)  
├── Medical Trends Visuals (`Billingcomparison.png`, `Topmedicalcondition.png`, etc.)  
├── README Summary  
├── Cleaned Dataset *(Dataset placeholder only in current version)*

