# Project Scope

## Overview

This document defines the boundaries, deliverables, and constraints of the Nexline Digital Twin project. It establishes what the system will and will not do, ensuring focused execution across all seven phases.

---

## In Scope

### 1. IoT Sensor Simulation
- Define sensor coverage across Nexline's production lines
- Simulate real-time readings for: temperature, vibration, power consumption, and production output rate
- Generate synthetic time-series datasets that reflect realistic factory floor behavior including normal operation, gradual wear, and failure events

### 2. Enterprise Architecture Design
- Develop a TOGAF ADM-based architecture blueprint covering:
  - Business architecture (stakeholders, processes, KPIs)
  - Data architecture (sensor schema, data flows, storage)
  - Application architecture (system components and integrations)
  - Technology architecture (infrastructure and deployment)

### 3. Predictive Analytics
- Build machine learning models to:
  - Forecast equipment failure based on sensor trend patterns
  - Detect energy consumption anomalies across production lines
  - Classify operational states (normal, warning, critical)

### 4. Interactive Dashboard
- Develop a real-time operational dashboard providing:
  - Live KPI monitoring (uptime, energy usage, output rate)
  - Maintenance alert system with failure probability scores
  - Energy consumption breakdown by production line
  - Role-based views for plant managers and maintenance teams

### 5. Technical Report
- Compile a final report documenting methodology, findings, model performance, and recommendations for real-world implementation

---

## Out of Scope

| Item | Reason |
|---|---|
| Live hardware integration | Project uses synthetic data; no physical IoT devices are connected |
| Real factory data | All datasets are simulated to protect confidentiality and enable controlled testing |
| ERP / MES system integration | Out of bounds for this phase; flagged as a future enhancement |
| Mobile application | Dashboard is web-based only in this version |
| Supply chain simulation | Scoped for future extension beyond core Digital Twin |
| Cloud deployment (production) | Dashboard will be deployed for demo purposes only, not production-grade infrastructure |

---

## Constraints

- **Data:** All sensor data is synthetically generated using Python — no real operational data is used
- **Tools:** Open-source stack only (Python, Scikit-learn, Plotly Dash, Jupyter)
- **Timeline:** Seven phases executed sequentially across the project duration
- **Team:** Individual contributor — all roles (data engineering, modeling, architecture, dashboard development) performed by one person

---

## Assumptions

- Nexline operates two plants with multiple production lines each
- Sensors are assumed to report data at 1-minute intervals
- Equipment failure is defined as any sensor reading exceeding defined thresholds for a sustained period
- Energy anomaly is defined as consumption deviating more than 20% from the rolling 7-day average for a given line

---

## Deliverables Summary

| Phase | Deliverable | Folder |
|---|---|---|
| 1 | Problem statement, scope, KPIs | `01-problem-definition/` |
| 2 | Research report, literature review | `02-research/` |
| 3 | TOGAF architecture blueprint | `03-architecture/` |
| 4 | Synthetic datasets + data dictionary | `04-data/` |
| 5 | Predictive model notebooks + evaluation | `05-predictive-models/` |
| 6 | Interactive dashboard + demo | `06-dashboard/` |
| 7 | Final technical report | `07-report/` |

---

*Document version: 1.0 — Phase 1: Problem Definition*
