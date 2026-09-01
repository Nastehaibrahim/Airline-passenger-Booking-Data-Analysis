# Airline Performance & Revenue Analysis

A comprehensive Excel data analytics project focused on evaluating flight schedules, ticketing data, passenger demographics, and revenue metrics to optimize airline operations.

---

## 📌 Project Overview

* **Dataset File:** `airline project.xlsx`

* **Prepared By:** Nasteha Ibrahim Hussien


* **Date:** August 24, 2026


* **Scope:** Cleaned 300 raw booking entries down to 292 valid records across 12 analytical variables.



---

## 📊 Key Performance Indicators (KPIs)

* **Total Revenue:** $58,112.25


* **Total Bookings:** 292 confirmed clean records


* **Average Fare:** $199.01


* **Completion Rate:** 54.45% (159 completed bookings)



---

## 🛠 Data Cleaning & Preparation

* **Data Formatting:** Enforced correct data types across text, currency (`$#,##0.00`), and dates (`YYYY-MM-DD`).


* **Deduplication:** Highlighted and removed 8 duplicate entries, reducing the dataset from 300 to 292 clean rows.


* **Missing Value Management:** Standardized missing `Travel_Class` and `Booking_Status` fields using the `Unknown` placeholder.


* **Text Standardization:** Utilized core text formulas (`TRIM`, `PROPER`, `UPPER`) to eliminate whitespace, format passenger categories, and standardize route codes.



---

## 📈 Analysis & Formulas Applied

| Category | Excel Formulas Used | Purpose |
| --- | --- | --- |
| **Statistical** | `=SUM()`, `=AVERAGE()`, `=MIN()`, `=MAX()`, `=COUNT()` | Summary revenue and fare statistics.

 |
| **Conditional** | `=SUMIF()`, `=COUNTIF()`, `=AVERAGEIF()` | Target revenue & pricing metrics by status and class.

 |
| **Logical** | `=IF()`, `=IFS()` | Categorize fares into yield and pricing brackets.

 |
| **Date & Time** | `=YEAR()`, `=MONTH()`, `=DAY()`, `=NETWORKDAYS()` | Extract booking trends and operational lead times.

 |

---

## 🖥 Dashboard Architecture

* **PivotTables:** Dynamic summarization by route performance, seating class yield, and booking status.


* **Visualizations:** Visualized data via Route Revenue Bar Chart, Booking Status Donut Chart, Class Yield Column Chart, and Monthly Flight Line Chart.


* **Interactivity:** Integrated dynamic Slicers for *Route*, *Travel Class*, and *Booking Status*.



---

## 💡 Key Findings & Recommendations

### Key Findings

1. **Top Revenue Route:** MGQ-NBO generated the highest total revenue at $22,331.80.


2. **Highest Fare Route:** MGQ-ADD recorded the highest average ticket price ($267.32).


3. **Class Yield:** Business Class yielded significantly higher returns ($318.42 avg) than Economy Class ($178.17 avg).


4. **Cancellations:** 30 bookings were cancelled, representing $5,899.04 in lost revenue.



### Strategic Recommendations

1. **Capacity Optimization:** Allocate higher seat capacity to top routes (MGQ-NBO and MGQ-ADD) during peak periods.


2. **Premium Marketing:** Target corporate clients with tailored loyalty packages to boost high-margin Business Class seats.


3. **Data Integrity & Reminders:** Implement field validation controls during booking and automated pre-flight notifications to cut down cancellations.
