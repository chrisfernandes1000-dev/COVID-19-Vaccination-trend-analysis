# COVID-19-Vaccination-trend-analysis
data analysis project showcasing COVID-19 vaccination trend analysis using powerbi

#  COVID-19 Vaccinations Trend Analysis — Power BI Dashboard

## Overview

This project analyses global COVID-19 vaccination trends using Power BI. It provides an interactive dashboard that visualises vaccination progress across countries and time periods, helping users understand the pace, coverage, and distribution of COVID-19 vaccines worldwide.

---

## Dataset

The dataset contains global COVID-19 vaccination records sourced from publicly available data (e.g., Our World in Data / Kaggle).

**Key columns include:**

| Column | Description |
|---|---|
| `Country` | Name of the country |
| `Date` | Date of the vaccination record |
| `Total Vaccinations` | Cumulative total doses administered |
| `People Vaccinated` | Number of people who received at least one dose |
| `People Fully Vaccinated` | Number of people fully vaccinated |
| `Daily Vaccinations` | New doses administered on a given day |
| `Vaccines Used` | Types of vaccines used in the country |

---

## Tools Used

- **Power BI Desktop** — dashboard development and data visualisation
- **Power Query (M Language)** — data cleaning and transformation
- **DAX (Data Analysis Expressions)** — calculated columns and measures

---

## Steps Performed

**1. Data Loading**
- Imported the COVID-19 vaccination dataset directly into Power BI.

**2. Data Cleaning (Power Query)**
- Removed null and blank rows.
- Corrected data types (dates, numbers, text).
- Filtered out irrelevant or incomplete records.
- Renamed columns for clarity.
- Handled missing vaccination counts by replacing nulls with zero.

**3. Data Modelling**
- Created a clean, single-table model ready for analysis.
- Added calculated columns using DAX (e.g., vaccination rate per 100 people).

**4. Dashboard Building**
- Designed an interactive, multi-visual dashboard with:
  - **KPI Cards** — Total vaccinations, people vaccinated, fully vaccinated count.
  - **Line Chart** — Daily vaccination trend over time.
  - **Bar Chart** — Top countries by total vaccinations.
  - **Map Visual** — Geographic distribution of vaccinations.
  - **Slicers** — Filter by country and date range.

---

## Dashboard Highlights

- Global vaccination trend over time with daily and cumulative views
- Country-wise vaccination map for geographic comparison
- Top 10 countries ranked by vaccination coverage
- Interactive slicers to filter by country and time period

---

## Results

- Identified the countries with the highest and lowest vaccination rates.
- Tracked the acceleration and slowdown of vaccination drives globally.
- Highlighted gaps in vaccination coverage between high-income and low-income nations.

---

## How to Run

1. **Clone or download the repository.**

2. **Open Power BI Desktop.**
   *(Download from [Microsoft Power BI](https://powerbi.microsoft.com/desktop/) if not installed)*

3. **Open the `.pbix` file:**
   - Go to `File` → `Open` → Select `Project1-COVID-19_Vaccinations_Trend_Analysis.pbix`

4. **Refresh the data** (if connected to a live source):
   - Go to `Home` → `Refresh`

5. Explore the dashboard using the slicers and visuals.

---

## Project Structure

```
covid-vaccination-analysis/
│
├── Project 1 power bi(Sheet1).csv                          # Raw dataset
├── Project1-COVID-19 Vaccinations Trend Analysis.pbix      # Power BI file
├── README.md
├── project1-COVID-19 Vaccinations Trend Analysis.docx      # Project documentation
└── project1-COVID-19 Vaccinations.pptx                     # Presentation file
```

---
