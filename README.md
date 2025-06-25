# Electric-Vehicle-PESTEL-Analysis
Data-driven PESTEL analysis of the US EV market using Power BI. Cleaned &amp; visualized 239K+ EV registrations, tested key hypotheses, and delivered actionable business recommendations. [See dashboard, code, and full report!]
# Electric Vehicle Market Analysis: A PESTEL & Data Analytics Approach

## 🚗 Overview
This project explores the U.S. electric vehicle (EV) market using the PESTEL framework (Political, Economic, Social, Technological, Environmental, Legal) and data analytics. The analysis covers EV model diversity, technology trends, price-performance, regional adoption patterns, and strategic opportunities/risks. Key visuals and an interactive Power BI dashboard support evidence-based recommendations.

## 📊 Dataset
- **Source:** [U.S. Department of Energy – Electric Vehicle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data)
- **Size:** 239,000+ EV registrations (2008–2025)
- **Features:** Make, Model, Year, Type (BEV/PHEV), Electric Range, MSRP, Location (City, County), more

## 🛠️ Methods
- **Data Cleaning:** Filled missing MSRP with model averages and external sources (manufacturer/industry research). Removed duplicates, handled nulls, checked for outliers.
- **Statistical Analysis:** Descriptive stats, hypothesis testing (t-test, correlation), dashboard KPIs
- **Dashboarding:** Power BI – multi-page, interactive, with DAX measures, cards, bar/line/box/scatter/map visuals, decomposition tree, key influencers

## 🔬 Hypotheses
1. **BEVs have higher average electric range than PHEVs.**  
   - Supported: BEVs consistently outperform PHEVs in range (statistically significant).
2. **Higher MSRP means longer range.**  
   - Not supported: Price does not strongly correlate with range in this dataset.

## 🗺️ Key Findings
- **BEVs dominate the U.S. market** (4x as many models as PHEVs; Tesla leads in share)
- **Wide choice & progress:** 173 unique models, with ranges up to 337 miles
- **Median EV range:** 58 miles (mix of city-focused PHEVs and longer-range BEVs)
- **Geographic divide:** Urban/coastal regions see the most adoption
- **Price ≠ Range:** Affordable models can deliver competitive performance

## 💡 Recommendations
- Expand incentives and rural charging
- Invest in supply chain and battery recycling
- Prioritize infrastructure in underserved regions
- Promote affordable, high-range models

## 📂 Files
- `report.pdf` — Full analysis & recommendations
- `Case_study_Dashboard.pbix` — Power BI dashboard file
- `data/cleaned_data.csv` — Cleaned dataset (sample)
- `screenshots/` — Dashboard & key visual images
- `scripts/` — Python and DAX code samples

## 🌐 Connect
- [LinkedIn: Akash Kumar](www.linkedin.com/in/akash-kumar-28b747277)
