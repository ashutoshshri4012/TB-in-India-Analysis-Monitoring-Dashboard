# 📊 TB in India: Analytical & Monitoring Dashboard (Power BI)

An interactive Power BI dashboard tracking Tuberculosis (TB) notifications, demographic profiles, diagnostic methods, and treatment outcomes in India under the **TB Mukt Bharat (Ni-kshay)** initiative.

---

## 🖼️ Dashboard Preview

<img width="907" height="499" alt="TB_IN_INDIA-DASHBOARD" src="https://github.com/user-attachments/assets/4b551a21-6c41-46c5-8fcc-1e60376042e9" />


---

## 📌 Executive Summary
Tuberculosis continues to be a major public health priority in India. This dashboard provides a structured, data-driven view of patient trends, diagnostic distribution, clinical comorbidities, and treatment adherence across reporting periods (2023–2025).

---

## 🎯 Key Metrics & Highlights

| Metric | Value | Description |
| :--- | :--- | :--- |
| **Total TB Patients** | 31,232 | Cumulative notified TB patient records |
| **New TB Patients** | 22,039 | Newly detected and registered cases |
| **On Active Treatment** | 806 | Patients currently undergoing treatment regimens |
| **Successfully Cured** | 4,059 | Completed and clinically validated cured cases |
| **TB Deaths** | 1,200 | Total recorded mortality during reporting period |
| **Gender Distribution** | 61.71% M / 38.27% F | 19,274 Male vs. 11,952 Female patients |
| **Disease Site** | 69.94% Pulmonary | 21,840 Pulmonary vs. 9,392 Extra-Pulmonary |

---

## 🔍 Detailed Analytical Findings

* **Age Cohort Distribution:** The highest incidence is concentrated in individuals aged **25–34 years (6,700 cases)**, followed closely by **55 & above (6,300 cases)** and **15–24 years (5,900 cases)**, impacting the primary working-age population.
* **Diagnostic Basis:** **Chest X-Ray** remains the dominant screening method (12,197 cases), with significant contributions from molecular diagnostics such as **CBNAAT** (5,779 cases), **Microscopy** (2,863 cases), and **TrueNat** (1,322 cases).
* **Comorbidity Screening:** Integrated tracking for **HIV status** (28,922 screened) and **Diabetes status** (25,962 screened) to monitor dual-burden vulnerabilities.
* **Treatment Outcomes:** Visual tracking of Treatment Completed, Cured, Died, On Treatment, Treatment Regimen Changed, and Loss to Follow-up (LFU).

---

## 🛠️ Tech Stack & Implementation Details

* **Tool:** Microsoft Power BI Desktop
* **Data Modeling & DAX:**
  * Dynamic outcome percentage measures
  * Rate calculations per 1 Lakh Population
  * Year-over-Year (YoY) and monthly case trend aggregations
* **ETL & Data Cleaning:** Power Query (type casting, handling null values, conditional column mapping)
* **Visualizations:**
  * **KPI Cards:** Top-level summary metrics
  * **Line Chart:** Monthly trend analysis over time
  * **Horizontal Bar Chart:** Age group stratification
  * **Donut & Gauge Charts:** Gender split, Pulmonary status, and Comorbidity targets
  * **Vertical Column Chart:** Diagnostic test distribution
  * **Interactive Slicers:** Date Range, Year (2023, 2024, 2025), Basis of Diagnosis, Type of Case, HIV Status, and Diabetes Status

---

## 📂 Project Structure

```text
├── TB_Dashboard.pbix         # Main Power BI dashboard file
├── Data/                     # Cleaned dataset (CSV/Excel)
├── Screenshots/              # Dashboard preview and visual exports
│   └── dashboard_preview.png # High-resolution screenshot
└── README.md                 # Complete project documentation
