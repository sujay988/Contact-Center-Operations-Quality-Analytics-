# Contact-Center-Operations-Quality-Analytics-
# 📊 Customer Service Operations & Quality Analytics Tracker
> **Enterprise Contact Center Performance, Intraday Queue Analytics, and Workforce Quality Scorecard in Microsoft Excel**

[![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/excel)
[![Domain](https://img.shields.io/badge/Domain-Operations_%26_Contact_Center-blue?style=for-the-badge)]()
[![Dataset](https://img.shields.io/badge/Records-5%2C000_Transactions-orange?style=for-the-badge)]()

---

## 📌 Project Overview
This project presents an executive-ready **Operations & Workforce Analytics Dashboard** built in Microsoft Excel. Using a comprehensive contact center dataset of **5,000 inbound customer interactions**, the model evaluates core operational metrics, queue arrival dynamics, staffing bottlenecks, and frontline agent performance.

The dashboard bridges the gap between raw ticket logs and strategic decision-making, providing real-time visibility into queue leakage, SLA adherence, and customer satisfaction (CSAT) drivers.

---

## 🖼️ Dashboard Preview
 <img width="662" height="677" alt="rt" src="https://github.com/user-attachments/assets/a239db39-2e2e-40bd-9623-22b8b465c1ab" />


## 🔎 Deep-Dive Operational Insights & Root Cause Analysis

### 1. Macro Queue Health & Inbound Leakage
* **18.9% Abandonment Rate:** While an **81.1% Answer Rate** appears stable at face value, nearly **1 in every 5 callers (946 customers)** abandons before connecting with an agent.
* **ASA Bottleneck (67.5s):** Average Speed to Answer averages **67.5 seconds** across the operational day. Compared to standard contact center SLA thresholds (e.g., $80\%$ answered within 20 seconds), a 67-second baseline is the primary driver of queue abandonment.
* **FCR vs. Answer Rate Disconnect:** First Contact Resolution on answered calls is high at **89.9%**, and customer satisfaction holds at **3.40 / 5.0**. This confirms the core operational defect is **frontline queue capacity and speed of answer**, rather than agent knowledge or technical proficiency.

---

### 2. Intraday Arrival Curves & Shift Bottlenecks
* **Morning Surge & Spillover (09:00 – 11:00):** Inbound arrival spikes immediately at opening (**547 calls at 09:00**, peaking toward ~600 calls between 11:00 and 13:00). Wait times climb to a daily high of **71.1 seconds at 10:00**.
* **Understaffed Opening Window:** The 09:00 shift suffers a **20.3% abandonment rate** (547 offered vs. 436 answered) because floor coverage ramps up too slowly relative to opening queue arrival.
* **EOD Queue Drainage (18:00):** Volume drops to ~15 calls at hour 18, reflecting end-of-service queue flushing and schedule ramp-down.

---

### 3. Contact Driver Breakdown (Topic & Defect Analysis)
* **Evenly Distributed Demand:** Contact volume is split consistently across five core operational drivers (ranging from 976 calls in Admin Support to 1,022 in Streaming).
* **Technical Support Drops Highest Volume:** Despite balanced contact volume, **Technical Support experiences the highest abandonment rate (21.0%)** with an ASA of 68.1s—demonstrating that customers facing technical friction have the lowest patience threshold in queue.
* **Admin Support Prime for Deflection:** Admin Support achieves the floor's highest total resolution rate (**74.1%**) and highest CSAT (**3.43**), indicating standardized, low-complexity transactions suited for digital deflection.

---

### 4. Agent Performance & Quality Scorecard

#### The "Hour 9" Opening Shift Impact
* Filtering to **Hour 9** reveals an overall resolution drop from the floor benchmark of $72.9\%$ down to **71.85%**.
* **Diane** and **Greg** drop into **"Needs Coaching"** during this opening hour.
* **Greg's Call-Rushing Pattern:** Greg logs an average talk time of only **149.75 seconds** (well below the floor average of 176s) paired with an unsatisfactory **68.83% resolution rate**, signaling that calls are being rushed to clear the morning queue backlog at the cost of first-time resolution.

#### Full-Day Agent Profiles
* **Top Balanced Performers:** **Dan** (74.4% full-day resolution, 3.45 CSAT) and **Martha** (72.3% resolution, 3.47 CSAT) deliver consistent quality without compromising handle duration.
* **Specific Quality Opportunity (Joe):** Across the full day, Joe maintains strong resolution (**73.5%**), but records the lowest CSAT on the floor (**3.33**). His root cause is not procedural compliance, but soft skills, tone, and empathy.

---

## 🎯 Strategic Action Plan

1. **Stagger Shifts to 08:30:** Reallocate 20% of the 10:00 shift forward to 08:30–09:00 to absorb opening call arrival and compress the 67-second ASA closer to SLA targets.
2. **Deflect Tier-1 Admin Queries:** Route the 976 Admin Support and Contract inquiries through automated self-service IVR or web deflection, preserving agent bandwidth for high-friction Technical Support calls.
3. **Targeted Agent Coaching:**
   * Pair **Joe** with **Martha** for active listening and empathy coaching to raise satisfaction without increasing talk time.
   * Review **Greg's** opening-hour verification workflows to prevent call rushing during volume spikes.


