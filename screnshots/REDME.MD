# 📊 Airline Passenger & Booking Data Analytics Report

A structured interpretation of the interactive Excel dashboard views (`dashborad`, `dashbord2`, and `analysis`), detailing operational metrics, revenue breakdowns, and key analytical observations.

---

## 📌 Dashboard KPI Overview

The dashboard header highlights four primary metrics summarizing overall operations:

* **Total Revenue:** **$58,112.25** total revenue generated across all valid bookings.
* **Total Bookings:** **292** cleaned and processed booking records.
* **Average Fare:** **$199.01** average ticket price across all passenger segments.
* **Completion Booking:** **159** flights successfully completed by passengers (a **54.45%** overall completion rate).

---

## 📈 Chart & Visualization Interpretation

### 1. Revenue by Route (Bar Chart)

* **High Performer (MGQ-ADD):** Generates the highest single-route ticket price total, surpassing **1,200 units** on the primary axis.
* **Secondary Routes:** **MGQ-KMU** and **MGQ-NBO** show moderate, balanced revenue returns around **400 units**.
* **Lower Volume Routes:** **MGQ-BSA** and **MGQ-HGA** yield lower total revenues, with MGQ-HGA falling below **200 units**.

### 2. Booking Status Breakdown (Pie Chart)

* **Confirmed (7):** Represents the largest proportion in the current filtered view.
* **Completed (5):** Represents the secondary segment of active passenger travel.
* **Cancelled (3):** Accounts for cancelled trips that reduce overall operational efficiency.

### 3. Summary Statistics (`analysis` sheet)

| Metric | Recorded Value | Interpretation |
| --- | --- | --- |
| **TOTAL_revenue** | $58,112.25 | Aggregate ticket revenue across all active records. |
| **avarage_ticket_price** | $199.01 | Mean ticket spend per passenger. |
| **total_booking** | 292 | Total clean passenger transaction records. |
| **minumun price** | -$7.00 | Data anomaly/refund flag requiring system validation. |
| **max_price** | $1,018.00 | Peak premium single ticket transaction. |
| **SUMIF (Confirmed Revenue)** | $17,272.97 | Total revenue locked in confirmed status. |
| **AVERAGEIF (Business)** | $318.42 | High-yield average fare for Business Class passengers. |

---

## 🎛 Interactivity & Filtering Setup

* **Route Slicer:** Filters dataset by flight corridors (*MGQ-ADD*, *MGQ-BSA*, *MGQ-HGA*, *MGQ-KMU*, *MGQ-NBO*, *Unknown*).
* **Booking Status Slicer:** Real-time visual dynamic filtering by *Cancelled*, *Completed*, *Confirmed*, and *Unknown*.
* **Dashboard Themes:** Available in both warm gold (`dashborad`) and classic blue (`dashbord2`) executive layout themes.
