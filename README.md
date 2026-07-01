# Healthcare Data Analysis & Insights Dashboard

An end-to-end data analysis project focused on hospital operations, patient demographics, clinical conditions, and financial health. This project processes raw healthcare data using Python, uncovers critical operational trends, and visualizes key metrics through an executive dashboard to assist in healthcare decision-making.

## 📌 Project Overview
Managing hospital efficiency while maintaining high standards of patient care and financial sustainability is a major challenge for healthcare institutions. This project analyzes a comprehensive healthcare dataset to uncover patterns in:[cite: 1]
* **Patient Demographics & Medical Conditions:** Distribution of illnesses across age and gender.[cite: 1]
* **Hospital Operations:** Admission types, average length of stay (LOS), and operational balances.[cite: 1]
* **Financial Performance:** Billing trends across various medical conditions and treatments.[cite: 1]

---

## 📊 Key Insights & Findings

### 1. Hospital Operations & Efficiency
* **Admission Balance:** Hospital admissions are almost perfectly balanced across all categories: **Elective (33.61%)**, **Urgent (33.46%)**, and **Emergency (32.93%)**.[cite: 1]
* **Length of Stay (LOS):** The severity or type of admission does not significantly affect how long a patient stays. The average length of stay remains highly consistent across all three categories, ranging tightly between **15.4 to 15.6 days**.[cite: 1]

### 2. Clinical & Patient Demographics
* **Gender-Based Prevalence:** Clear variances exist in medical conditions by gender:[cite: 1]
    * **Female patients** exhibit a higher prevalence of **Arthritis**.[cite: 1]
    * **Male patients** show a higher likelihood of being diagnosed with **Diabetes**.[cite: 1]
* **Medication Trends:** For patients with "Abnormal" test results, **Ibuprofen** is the most frequently prescribed medication, followed closely by Aspirin, Paracetamol, Lipitor, and Penicillin at highly similar rates.[cite: 1]

### 3. Financial & Billing Insights
* **Average Billing:** The overall average billing amount per patient across the entire hospital system is approximately **$25,544**.[cite: 1]
* **Condition-Specific Billing:** 
    * **Highest Revenue Drivers:** **Obesity** ($25,804 avg) and **Diabetes** ($25,660 avg) drive the highest average billing amounts.[cite: 1]
    * **Lowest Billing:** **Cancer** treatments account for the lowest average billing at approximately $25,152.[cite: 1]

---

## 🛠️ Tech Stack & Tools Used
* **Language:** Python 3.x[cite: 1]
* **Data Manipulation:** Pandas, NumPy[cite: 1]
* **Data Visualization:** Seaborn, Matplotlib[cite: 1]
* **Environment:** Jupyter Notebook / Google Colab[cite: 1]
* **BI Dashboards:** (e.g., Power BI / Tableau / Excel - *Adjust if necessary*)

* ### Executive Analysis
*A high-level view of hospital operations, overall admissions, and system-wide metrics.*

![Executive Analysis](executive-analysis.jpg)

### Health and Patients Analysis
*Deep dive into patient gender splits, age distributions, and condition prevalence.*

![Health and Patients Analysis](health-and-patients-analysis.jpg)

### Revenue and Financial Analysis
*Breakdown of hospital billing across various medical conditions and treatment types.*

![Revenue and Financial Analysis](revenue-and-financial-analysis.png)

---
