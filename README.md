# Drug Overdose Death Rate Dashboard (1999–2020)

An interactive Power BI dashboard analyzing 22 years of US drug overdose death rate data, with a focus on the opioid crisis.

## Dashboard Preview
![drug_dashboard](drug_dashboard.pdf)

## Project Overview
This project visualizes national drug overdose death rates from 1999 to 2020 using data from the CDC WONDER database. The dashboard highlights the dramatic rise of opioid-related deaths, particularly the explosion of synthetic opioid (fentanyl) deaths after 2013.

## Dataset
- **Source:** CDC WONDER
- **Coverage:** United States (national level)
- **Time Period:** 1999–2020 (22 years)
- **Drug Types Tracked:**
  - Any Opioid
  - Cocaine
  - Heroin
  - Synthetic Opioids
  - Prescription Opioids

## Dashboard Features
- **Line Chart** — Trends for all drug types from 1999 to 2020
- **KPI Cards** — Death rates per 100,000 Americans for 1999 and 2020 side by side
- **Bar Chart** — 1999 vs 2020 comparison across Opioids, Cocaine, and Heroin

## Key Findings
- Opioid death rates grew over **7x** from 1999 (2.90) to 2020 (21.40) per 100,000 Americans
- Synthetic opioid deaths began rapidly accelerating around **2013**, driven largely by fentanyl
- Cocaine death rates quadrupled from **1.40 in 1999 to 6.00 in 2020**
- Heroin deaths peaked around 2016–2017 before declining

## Tools Used
- **Power BI Desktop** — Dashboard creation and DAX measures
- **Power Query** — Data cleaning and column renaming

## Files
- `drug.csv` — Cleaned dataset
- `drug_dashboard.pbix` — Power BI dashboard file

## How to View
1. Download `drug_dashboard.pbix`
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. The dashboard will load with all visuals intact
