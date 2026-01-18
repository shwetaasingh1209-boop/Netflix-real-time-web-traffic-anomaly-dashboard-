# real-time-web-traffic-anomaly-dashboard-
# Real-Time Web Traffic Anomaly Monitoring Dashboard

## 📌 Overview
This project implements a **near real-time web traffic monitoring system** that detects abnormal spikes or drops in website traffic using **statistical anomaly detection** and visualizes the results in **Power BI Desktop**.

The system simulates live website traffic, aggregates requests per minute, calculates anomaly scores using a **Z-score–based approach**, and exposes the data through a **Flask REST API**. Power BI Desktop consumes this API and updates visuals using **Auto Page Refresh**.

---

## 🎯 Problem Statement
Web platforms frequently experience unexpected traffic changes due to marketing campaigns, outages, or system issues. Without near real-time monitoring, these anomalies can go unnoticed, leading to delayed response and potential business impact.

**Objective:**  
Build a near real-time monitoring solution that continuously tracks website traffic and flags anomalies for faster operational awareness.

---

## 🏗️ System Architecture

Traffic Simulation (Python)
↓
Requests Per Minute Aggregation
↓
Z-Score Based Anomaly Detection
↓
Flask REST API
↓
Power BI Desktop (Auto Page Refresh)
## ⚙️ Technologies Used
- Python
- Flask
- Pandas
- NumPy
- Power BI Desktop

---

## 🚦 Key Features
- Simulated real-time website traffic generation
- Requests-per-minute aggregation
- Statistical anomaly detection using Z-score thresholds
- REST API serving live and historical traffic metrics
- Near real-time Power BI dashboard with auto refresh
- Visual indicators for traffic spikes and anomalies

---

## 📊 Dashboard Visuals
The Power BI dashboard includes:
- Traffic trend line chart (near real-time)
- Current traffic (RPM) card
- Anomaly status alert card


---
