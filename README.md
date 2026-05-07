# 🏥 AthleteX Care — Sports Injury Analytics

**AthleteX Care** is a multi-page Power BI dashboard designed for sports 
medical teams to track, analyze, and act on athlete injury data across 
competitions, age groups, injury types, and recovery outcomes.

---

## 📌 Project Overview

This dashboard gives the AthleteX Medical Team a centralized, filterable 
view of injury intelligence — from executive KPIs down to individual 
athlete-level injury records — enabling smarter decisions in sports 
healthcare management.

---

## 📊 Key Metrics (All-Time | Full Dataset)

| Metric                    | Value           |
|---------------------------|-----------------|
| Total Injuries Recorded   | 15,000          |
| Total Medical Expenses    | €27.70M         |
| Avg Recovery Days         | 48.7 days       |
| Top Injury Type           | Fracture (2,043 cases) |
| Full Recovery Rate        | 79.9% (11,982 athletes) |
| Recovered with Limitation | 14.9% (2,236)   |
| Career-Ending (Retired)   | 5.2%  (782)     |
| Avg Fracture Cost         | €1.8K           |
| Fracture Recovery Rate    | 80%             |


## 📄 Dashboard Pages

### Page 1 — Overview
- KPI cards: Total Injuries, Expenses, Avg Recovery Days, Top Injury
- Monthly trend sparklines per KPI
- Injuries by Age Group (bar chart)
- Recovery Status breakdown (donut chart)
- Injuries by Top Injury Type (grouped bar: Cost / Count / Avg Recovery Days)
- Medical Breakdown by Sports Events


### Page 2 — Injury Log
- Full athlete-level injury history
- Columns: InjuryID, Player, Gender/Age, Injury Details, Severity & 
  Recurrence, Sport & Event, Timeline (Injury/Return), Recovery Days, 
  Workload (20D), Cost, Treatment Outcome
- Workload status indicators: Normal / Overuse / High Load / Recovery
- Filters: Severity (Minor / Moderate / Severe) | 
  Status (Fully Recovered / Recovered with Limitation / Retired)

---

## 🛠️ Tools & Techniques

- **Power BI Desktop** — Data modelling, DAX measures, report design
- **Power Query (M)** — Data cleaning, column standardization, 
  transformation
- **DAX** — KPI calculations, YoY variance, recovery metrics, 
  severity scoring
- **Star Schema** — Fact and dimension table

🔗 [Live Report / Screenshots] | 📁 [Dataset Source]
