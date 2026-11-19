# -HR-Attrition-Performance-Analytics-Dashboard
An interactive, executive-ready **Microsoft Excel Dashboard** analyzing workforce retention, attrition drivers, employee satisfaction, and departmental performance across **1,470 employees** and **6,709 historical performance reviews** (total annual payroll: **₹16.60 Cr**).
## 🎯 Project Objectives
- Quantify overall employee attrition and associated payroll exposure in INR (`₹`).
- Identify the primary structural and behavioral drivers behind employee exits.
- Audit and resolve raw data anomalies (such as duplicate historical review records and reversed satisfaction lookup mappings).
- Provide leadership with actionable retention recommendations.

---

## 📈 Key Insights & Metrics

| Metric / Dimension | Key Finding |
| :--- | :--- |
| **Overall Headcount & Attrition** | **1,470** total employees \| **237** exited (**16.1%**) \| **1,233** retained (**83.9%**) |
| **Total Annual Payroll** | **₹16,60,46,052** (`₹16.60 Cr`) across High, Medium, and Low income bands |
| **OverTime Impact** | **30.5%** attrition for overtime staff vs. **10.4%** for non-overtime staff |
| **Tenure (Years at Company)** | Highest turnover in **Year 0 (31.6%)** and **Year 1 (34.5%)** |
| **Business Travel** | **24.9%** attrition for Frequent Travellers vs. **8.0%** for Non-Travellers |
| **Satisfaction & Work-Life Balance** | Exit rates spike to **25%–33%** at Rating Level 1 (Very Dissatisfied / Poor WLB) |
| **Department Performance** | Consistent average manager ratings (**3.44 – 3.51 / 5.0**) and estimated hikes (**~8.1% – 8.4%**) |

---

## 🧹 Data Cleaning & Audit Highlights
- **Deduplicated Review History:** Filtered 6,709 multi-year review entries down to each employee's latest review to prevent double-counting tenured staff.
- **Corrected Satisfaction Labels:** Fixed inverted lookup mappings where scores of `4` and `5` were mislabeled as *Dissatisfied*.
- **Fixed Gender Attrition Formula:** Replaced an erroneous age-to-headcount calculation with true row-level attrition percentages (~15%–17% across genders).

---

## 🛠️ Tools & Skills Demonstrated
- **Microsoft Excel:** PivotTables, PivotCharts, Dynamic Formulas (`SUM`, `INDEX`, `XLOOKUP`), Conditional & Currency Formatting (`₹#,##,##0`).
- **Data Analysis:** Root-cause analysis, cohort/tenure breakdown, data auditing, and executive storytelling.

---

## 📂 Repository Structure
- `HR_Attrition_Performance_Dashboard_INR.xlsx` — Complete Excel workbook containing the `Dashboard` and `Executive_Notes` tabs.
- `images/` — Presentation slides and dashboard previews.
U
