# Call Center Data Analysis (2026)
## Dashboard

<img width="1872" height="664" alt="image" src="https://github.com/user-attachments/assets/ccc13468-9f3e-430e-9b99-26bb4ed1403b" />

---

## Project Overview
This project provides an interactive and fully dynamic Excel dashboard designed to analyze an entire year of call center operational data for 2026. The goal is to help management and stakeholders solve key business problems by evaluating call volumes, revenue generation, operational efficiency, caller demographics, and individual representative performance.

---

## Key Performance Indicators (KPIs)
* **Total Calls:** 1,000 calls
* **Total Revenue:** ₹96,623
* **Total Call Time:** 89,850 seconds
* **Average Rating:** 3.89 / 5.0

---

## Top Key Insights
1. **Top Volume Representative:** Representative 2 took the highest number of calls (218 calls), generating ₹20.6K in revenue (Rank 2).
2. **Top Revenue Representative:** Representative 3 generated the highest amount of revenue (₹20.9K) across 207 calls.
3. **Busiest Day:** Saturday consistently recorded the highest volume of calls throughout the year.
4. **Customer Satisfaction:** Representative 1 achieved the highest average satisfaction rating (~4.0 / 5.0) compared to the overall average of 3.89 / 5.0.
5. **Seasonal Trends:** Call volume peaked in March (155 calls) and dropped to its lowest in August (50 calls).

---

## Technical Workflow & Features

### 1. Data Cleaning & Modeling (Power Query)
* Cleaned, structured, and transformed raw data using **Power Query**.
* Connected the `Customer` table and `Calls` table via `Customer ID` using Excel Data Modeling.

### 2. Custom Calculations & Logic
* Calculated duration buckets and rounded rating categories.
* Derived day-of-week and month classifications for call trend analysis.
* Applied key Excel functions: `XLOOKUP`, `INDEX-MATCH`, `VLOOKUP`, `SUM`, `COUNTA`, `RANK`, and conditional `IF-ELSE` statements.

### 3. Dashboard Features & Design
* **Pivot Table Analytics:** Summarized call volumes, weekly trends, caller demographics, and rating distributions.
* **Dynamic Representative Profile:** Filter selection automatically updates representative profile photo, call share percentage, call volume rank, and revenue rank.
* **Geographic & Demographic Breakdown:** Analyzed caller gender diversity across the top 3 cities (Cincinnati, Cleveland, and Columbus).
* **Customer Matrix:** Detailed breakdown of revenue generated per representative per customer across top cities.
* **User Interface:** Applied conditional formatting and custom formatting for clean visualization.

---

## Repository Structure
```text
├── Call Center Report - 2026.xlsx   # Main Excel Workbook with Dashboard & Power Query
├── screenshots/                     # Dashboard screenshots
└── README.md                        # Project documentation
```

---

## Author
* **GitHub:** [Arghyajyoti007](https://github.com/Arghyajyoti007)
