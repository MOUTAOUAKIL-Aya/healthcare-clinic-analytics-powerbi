# 🩺 Healthcare & Clinic Operations Analytics (Power BI)

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis%20Expressions-blue?style=for-the-badge)
![Healthcare Management](https://img.shields.io/badge/Healthcare-Operations-crimson?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

A comprehensive Business Intelligence dashboard designed for **healthcare clinics and private hospital facilities**. This project delivers end-to-end insights into patient consultations, revenue performance, clinical specialties, and patient care quality.

---

## 📌 Business Objectives

Managing modern healthcare facilities requires balancing clinical excellence with operational and financial efficiency. This dashboard empowers healthcare administrators and department leads to:
- **Monitor Clinical & Financial Performance:** Track total revenue, consultation volume, and invoice settlement rates.
- **Analyze Doctor & Specialty Workload:** Assess capacity and performance across medical specialties and practitioners.
- **Understand Patient Demographics:** Explore patient distributions by age bracket, gender, geographic origin (city), and health insurance provider.
- **Elevate Quality of Care:** Measure visit recurrence, consultation frequency per patient, and diagnostic distributions.

---

## 📊 Dashboard Architecture

The report file [`projetPOWERBI.pbix`](./projetPOWERBI.pbix) comprises **two interactive analytical pages**:

### 1. Operations & Financial Overview (*Vue d'ensemble*)
- **High-Level KPIs:**
  - Total Revenue generated
  - Total Number of Consultations
  - Unique Patients Served
  - Payment Collection Rate (% settled vs. pending)
- **Visual Analytics:**
  - Monthly consultation trend analysis (Line Chart).
  - Revenue and volume breakdown by medical specialty (Clustered Bar Charts).
  - Payment status & insurance distribution (Donut Chart).
  - Patient geographic dispersion map (Map Visual).
  - Detailed doctor consultation performance table.

### 2. Patient Demographics & Care Quality (*Patients & Qualité*)
- **Care Quality Metrics:**
  - Average Consultations per Patient (care intensity index).
  - Patient loyalty and recurring consultation rates.
- **Clinical & Demographic Insights:**
  - Age bracket and gender distribution pyramid.
  - Top clinical diagnoses analysis (Bar Chart).
  - Correlation scatter plot: patient age vs. visit frequency vs. specialty.
  - Multidimensional filter pane (Specialty, Physician, Diagnosis, Date).

---

## 📐 DAX Modeling & Key Measures

- `[Chiffre d'Affaires Total]`: Total gross revenue calculated across all billed medical procedures.
- `[Total Consultations]`: Aggregate count of patient appointments and consultations.
- `[Patients Uniques]`: Distinct patient count (`DISTINCTCOUNT`) measuring actual patient outreach.
- `[Consultations par Patient]`: Intensity ratio assessing follow-up care and patient retention.
- `[Consultations par Mois]`: Time-series measure for monthly operational trend tracking.
- `[Taux de Paiement]`: Financial collection KPI calculating the ratio of settled to billed invoices.

---

## 📂 Repository Contents

```
healthcare-clinic-analytics-powerbi/
│
├── 📊 projetPOWERBI.pbix      # Main interactive Power BI Desktop file
├── 🖼️ assets/                 # Background canvas, UI components, and icons
├── ⚙️ .gitignore              # Ignores temp files, backup files, and caches
└── 📖 README.md               # Complete project documentation
```

---

## 🚀 How to Run the Project

1. **Prerequisites:** Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. **Clone the repository:**
   ```bash
   git clone https://github.com/MOUTAOUAKIL-Aya/healthcare-clinic-analytics-powerbi.git
   cd healthcare-clinic-analytics-powerbi
   ```
3. **Open the Report:**
   Open [`projetPOWERBI.pbix`](./projetPOWERBI.pbix) in Power BI Desktop to interact with slicers, drill-throughs, and visual cards.

---

## 👩‍💻 Author
- **Aya MOUTAOUAKIL** - *Business Intelligence & Data Engineering Student (ESISA)*
- GitHub: [@MOUTAOUAKIL-Aya](https://github.com/MOUTAOUAKIL-Aya)
