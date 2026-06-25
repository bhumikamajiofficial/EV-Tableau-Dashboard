# ⚡ Electric Vehicle Population Analysis — Tableau Dashboard

An interactive Tableau dashboard analysing **150,000+ electric vehicle registrations** across United States — exploring adoption trends, top manufacturers, EV types, and geographic distribution.

🔗 **[View Live Dashboard on Tableau Public](https://public.tableau.com/views/EVTableauDashboard/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## 📊 Dashboard Preview

> ![Dashboard Preview](assets/EV%20Tableau%20Screenshot.png)

---

## 📁 Project Structure

```
EV-Tableau-Dashboard/
├── Electric_Vehicle_Population_Data.csv   # Raw dataset (150K+ records)
├── EV_Tableau_Dashboard.twbx              # Tableau packaged workbook
├── README.md
└── LICENSE
```

---

## 🗂️ Dataset Overview

**Source:** Washington State Department of Licensing (DOL)
**Records:** 150,482 registered electric vehicles
**Time Period:** 1997 – 2024

| Column | Description |
|---|---|
| `VIN` | Unique vehicle identifier |
| `County / City / State` | Registration location |
| `Model Year` | Year of manufacture |
| `Make / Model` | Vehicle brand and model |
| `Electric Vehicle Type` | BEV (Battery) or PHEV (Plug-in Hybrid) |
| `Electric Range` | Range in miles on electric charge |
| `Base MSRP` | Manufacturer's suggested retail price |
| `CAFV Eligibility` | Clean Alternative Fuel Vehicle eligibility |
| `Electric Utility` | Utility provider for the area |

---

## 📈 Key Insights

### 🚗 Market Dominance
- **Tesla leads** with 68,983 registrations — nearly **46% of all EVs** in Washington State
- Top 5 manufacturers: Tesla → Nissan → Chevrolet → Ford → BMW
- Tesla's dominance is 5x that of the second-ranked brand (Nissan: 13,497)

### ⚡ BEV vs PHEV
- **Battery Electric Vehicles (BEV): 77.6%** (116,807 vehicles)
- **Plug-in Hybrids (PHEV): 22.4%** (33,675 vehicles)
- Clear consumer preference shift toward fully electric over hybrid

### 📅 Adoption Trend
- EV registrations grew exponentially from **2016 onwards**
- Peak adoption visible in **2022–2023** — driven by new model launches and fuel price hikes
- Early registrations (pre-2010) were minimal — less than 1% of total fleet

### 🗺️ Geographic Distribution
- **King County** (Seattle metro) has the highest EV concentration — tech-forward, high-income demographic
- Urban counties dominate; rural counties show significantly lower adoption
- Seattle, Bellevue, and Redmond are the top cities by EV count

### 🔋 Electric Range
- Average electric range has increased steadily with newer model years
- Older models (pre-2015) had ranges under 100 miles
- Modern BEVs average 200+ miles — crossing the range anxiety threshold

---

## 🛠️ Tools Used

- **Tableau Desktop / Tableau Public** — dashboard building & publishing
- **Dataset:** Washington State Open Data Portal

---

## 🖥️ Dashboard Features

- **KPI Cards** — Total vehicles, BEV count, PHEV count, average range
- **Year-wise Trend Chart** — EV adoption growth over time
- **Top Manufacturers Bar Chart** — ranked by registration count
- **BEV vs PHEV Split** — donut/pie breakdown
- **County-wise Map** — geographic distribution across Washington State
- **Interactive Filters** — filter by EV type, make, model year

---

## ⭐ Give a Star

If you found this project helpful or interesting, consider giving it a star — it means a lot and helps others discover it too!
