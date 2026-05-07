# 🏥 AthleteX Care — Sports Injury Analytics

**AthleteX Care dashboard** is a multi-page Power BI dashboard designed for sports medical teams to track, analyze, and act on athlete injury data across 
competitions, age groups, injury types, and recovery outcomes.

---

## 📌 Project Overview

This dashboard gives the AthleteX Medical Team a centralized, filterable 
view of injury intelligence from executive KPIs down to individual 
athlete injury records, enabling smarter decisions in sports healthcare management.

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


<img width="822" height="978" alt="Join athletex" src="https://github.com/user-attachments/assets/be7fee83-b12b-4d4b-b1af-7bcc2ef3787a" />










Click on the link below to access the dashboard and dataset ↓

https://app.powerbi.com/links/QB0BZR66X2?ctid=a36e1a13-c829-4154-8635-f2516711db50&pbi_source=linkShare


#### Data Structure

The dataset is structured as a star schema having one fact table and 
connecting dimension tables.

**FactInjuries** — the fact table representing each unique injury event, 
containing foreign keys to all dimension tables 

**DimPlayer** —  player name, gender, age, and region.

**DimInjuryType** — categorize each injury across: injury type (Fracture, 
Muscle Strain)

**DimClub** — club name, sport, and competition level. 

**DimEvent** — event type (Competition, Training, Warm-up)

**DimTreatment** — displays each treatment method to its recorded outcome



**Important Findings**

Injuries vs Treatment Cost
15,000 injuries occurred between 2022 and 2025 at a costing €27.70M on treatments. No reduction in injury rate despite data availability from previous years.This is a direct signal that existing reporting structures were not translating into preventive action.

Injury Severity Concentration
The highest injury severity rates across all competitions are Local Tournament (48.3%), Club Match and Champions League (both 48.8%), and WTA Tour (47.8%). EuroLeague (46.9%), La Liga (46.0%), and Amateur Cup (45.7%) also sit consistently above the programme average. These are predictable, competition-specific risk environments the medical team can plan resources around in advance.

Injuries by Age Group
Athletes aged 31–40 recorded the highest injury volume at 6,100 cases, followed closely by the 21–30 grouo at 5,900, together accounting for 80% of all injuries in the dataset. The under-20 group contributed 3,000 cases, the lowest volume but a population that warrants targeted load management given the physical demands placed on developing athletes.

---

## 🛠️ Tools & Techniques

- **Power BI Desktop** — Data modelling, DAX measures, report design, HTML content
- **Power Query (M)** — Data cleaning, column standardization, transformation
- **DAX** — KPI calculations, YoY variance, recovery metrics, severity scoring
- **Figma** - Designing of the wireframe
