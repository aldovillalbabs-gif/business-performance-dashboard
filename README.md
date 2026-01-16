# Walmart Sales Executive Summary (2012) — KPI Dashboard (Google Sheets)

## Overview
This project delivers an **executive sales summary** for Walmart’s commercial leadership, using weekly sales data from **2012** to support decisions on **budget allocation and inventory adjustments**.

I cleaned and enriched raw datasets, built business KPIs, designed an interactive dashboard, and communicated insights using the **C-F-I (Context → Finding → Implication)** framework.

---

## Business Questions
1) **Which departments were the most efficient at generating sales in 2012?**  
   **KPI:** Sales per square meter (Sales / Store Size)

2) **Which departments contributed the most to total sales—and which underperformed?**  
   **KPI:** Department Share (Dept Sales / Total Sales)

---

## What I built
- **Clean data layer:** standardized dates and currency; created a `week_clean` key for time-based analysis  
- **Integrated dataset:** joined store and department lookup tables (type, size, department name)  
- **KPIs via pivots:**  
  - Sales per m² by department  
  - Department share of total sales (%)  
- **Interactive dashboard:** department dropdown + KPI cards + charts  
- **Executive summary:** C-F-I write-up to translate insights into actions  
- **Quality checks (QA):** validated missing department assignments, negative/zero sales, and zero store size

---

## Key Insights (Example)
- Departments with **high Sales/m²** indicate strong efficiency and can justify **higher inventory priority**.
- Departments with **high share** but **low efficiency** may need **assortment optimization** or cost review.
- Underperforming departments (low share + low efficiency) may be candidates for **budget reallocation**.

*(Replace these bullets with your final top 2–3 insights once you paste exact results.)*

---

## Recommendations
- Prioritize inventory and promotional budget toward **top efficiency departments** (Sales/m²).
- Use department share to protect core revenue drivers and identify **underperformers**.
- Review store type/size impact to refine allocations by **store segment (A/B/C)**.

---

## Visual Highlights (add screenshots)
### Dashboard (interactive KPIs)
### KPI 1 — Sales per m² by Department
### KPI 2 — Department Share of Total Sales
![Dashboard](images/dashboard.png)

---

## Tools & Skills
- **Google Sheets** (data cleaning, XLOOKUP, pivots, charts, dashboard filters)
- **Business KPIs** (efficiency, contribution/share)
- **Executive communication** (C-F-I)
- **Quality Assurance** (data validation & traceability)

---

## Files / Structure
- `assets/` → screenshots (dashboard, charts)
- `docs/` → executive summary (optional export)
- `README.md` → project overview + insights + visuals

---

## Takeaway
This project demonstrates the ability to deliver an end-to-end analytics workflow:  
**raw data → clean dataset → KPIs → dashboard → executive insights → QA**.
