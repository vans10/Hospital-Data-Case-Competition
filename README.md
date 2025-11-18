# Hospital-Data-Case-Competition
Analyzed hospital operations data to identify capacity gaps, refusal drivers, and seasonal demand trends. Built a Tableau dashboard with KPIs, service-level insights, and a bed-capacity simulation to model how changes in beds impact predicted refusal rates and patient access.
# 🏥 Hospital Capacity & Patient Access Analysis — Tableau Project

## Overview
This project analyzes how hospital capacity, patient demand, refusal rates, and seasonal service patterns interact to influence patient access. Using a multi-table dataset (patients, beds, services, and staff), I built a Tableau dashboard that enables hospital decision-makers to:

- Understand **where and when capacity shortages occur**
- Identify **which services drive the highest strain**
- Evaluate **weekly admission vs. refusal patterns**
- Explore **seasonal trends** in satisfaction, volume, and length of stay
- Simulate **how bed capacity changes** affect refusal rates and patient access

---

## Main Business Question
**How can the hospital improve patient access and reduce refusal rates by understanding patterns in bed capacity, demand, seasonal performance, and capacity adjustments?**

---

## Analytical Approach

This project uses a **4-part analytical framework**:

### 1. Capacity vs. Demand Analysis
Compares monthly **beds requested vs. beds available**, calculating the *capacity gap (%)* to highlight when demand exceeds supply.

- Peak gap reaches **~189% overall**
- Flu-related demand spikes exceed **1,100%**, causing extreme strain
<img width="1072" height="849" alt="Screenshot 2025-11-15 164341" src="https://github.com/user-attachments/assets/42ccbe99-1f75-4d1a-a59a-dd87554c71f8" />


---

### 2. Access Consequences: Admission vs. Refusal Rates
Weekly visualization showing how **admission rates** and **refusal rates** fluctuate across services.

- Emergency refusals rise to **>90%** in some weeks  
- ICU remains stable with **much lower refusal spikes**
<img width="1201" height="827" alt="Screenshot 2025-11-15 165831" src="https://github.com/user-attachments/assets/c82d2a87-cf88-414c-895f-66b21a815633" />

---

### 3. Seasonality Trends (Age Group + Metric Selector)
A multi-metric line chart (patient count, LOS, satisfaction) showing service performance across:

**Fall • Spring • Summer • Winter**

- Emergency volume peaks in **Summer (71 patients)**  
- Surgery satisfaction dips slightly in **Spring**
- Age Group filter enables segmented seasonal analysis
<img width="1075" height="734" alt="Screenshot 2025-11-15 170151" src="https://github.com/user-attachments/assets/d7e1a524-e210-49aa-b321-02dbf4be15c9" />

---

### 4. What-If Simulation: Bed Adjustment & Predicted Refusal
Interactive parameter: **Bed Adjustment (+ / – beds)**  
Models how changes in bed supply impact predicted refusal rate.

- Adding beds reduces predicted refusals to **near 0%**
- Removing beds pushes predicted refusals **above 600%** during high-demand periods
<img width="1339" height="901" alt="Screenshot 2025-11-15 170502" src="https://github.com/user-attachments/assets/0b33398a-6355-4c15-9a9f-1fc2778f986c" />

---

## Key KPIs (EDA Layer)

10+ summary KPIs highlight the overall hospital landscape:

- Total Beds Available  
- Total Beds Requested  
- Total Patients Served  
- Total Patients Refused  
- Average Refusal Rate  
- Highest Refusal Week  
- Demand-to-Staff Ratio  
- Capacity Utilization %  
- Total Bed Shortage  
- Service-wise Refusal Highlights  

These KPIs provide a quick operational overview before exploring detailed visuals.

---

## Tools Used
- **Tableau** (visual analytics, parameters, filters, dual-axis charts)
- **Excel** (data cleaning & preparation)

**Interactive Controls:**
- Bed Adjustment parameter  
- Age Group filter  
- Service filter  
- Issue filter  
- Metric Selector  

---

## Insights Summary
- Hospital demand frequently exceeds available beds, especially during **flu season**.  
- Weekly refusal trends reveal **persistent stress** in Emergency services.  
- Seasonal analysis shows **summer patient volume peaks** and shifts in satisfaction/LOS across services.  
- Increasing bed supply yields **significant reductions in predicted refusal rates**, highlighting opportunities to improve patient access through staffing/bed expansion.
---

## Author
**Vanshika Gupta**  
MS in Business Analytics
