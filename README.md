# 🏭 Nexline Digital Twin — Manufacturing Operational Optimization

> An end-to-end Digital Twin system for smart manufacturing — combining IoT sensor simulation, predictive analytics, and real-time dashboards to eliminate unplanned downtime and reduce energy waste.

---

## 📌 Project Overview

**Nexline Manufacturing** operates high-precision production lines for aerospace and automotive components, running 24/7 across two plants. Despite investment in advanced CNC machines and robotic assembly, the facility faced critical operational gaps:

- No centralized monitoring — machines reported data in silos
- Reactive maintenance — failures discovered only after downtime occurred
- Energy inefficiency — disproportionate consumption with no root-cause visibility
- Zero real-time insight — managers had no live view of output or anomalies

This project designs and implements a **Digital Twin platform** that simulates real-time factory floor operations, forecasts equipment failures before they happen, and delivers actionable dashboards for plant managers and maintenance leads.

---

## 🎯 Objectives

- Simulate real-time factory floor operations using IoT sensor data
- Forecast equipment wear and potential failures using predictive models
- Monitor energy consumption and production line efficiency
- Provide interactive dashboards for faster, data-driven decision making

---

## 🗂️ Repository Structure

```
nexline-digital-twin/
│
├── 01-problem-definition/     # Case study, problem statement, KPIs, project scope
├── 02-research/               # Industry trends, literature review, annotated sources
├── 03-architecture/           # TOGAF blueprint, system diagrams, IoT sensor mapping
├── 04-data/                   # Synthetic datasets (CSV), data dictionary, generation scripts
├── 05-predictive-models/      # Jupyter notebooks, trained models, evaluation reports
├── 06-dashboard/              # Interactive dashboard app with live demo
├── 07-report/                 # Final technical report and executive summary
│
├── README.md
├── CHANGELOG.md
└── requirements.txt
```

---

## 🛠️ Tech Stack

| Layer | Tools |
|---|---|
| Data Simulation | Python, NumPy, Pandas |
| Predictive Modeling | Scikit-learn, XGBoost, Jupyter |
| Dashboard | Plotly Dash / HTML + JavaScript |
| Architecture | TOGAF ADM Framework |
| Version Control | Git + GitHub |

---

## 📊 System Architecture

```
IoT Sensors (simulated)
        │
        ▼
  Data Ingestion Layer
  (synthetic CSV streams)
        │
        ▼
  Predictive Analytics Engine
  (failure forecasting · energy anomaly detection)
        │
        ▼
  Digital Twin Dashboard
  (real-time KPIs · maintenance alerts · energy monitor)
```

---

## 🗺️ Project Roadmap

| Phase | Deliverable | Status |
|---|---|---|
| 1 | Problem definition & project scope | ✅ Complete |
| 2 | Industry research & literature review | ✅ Complete |
| 3 | TOGAF enterprise architecture blueprint | 🔄 In Progress |
| 4 | Synthetic dataset generation | ⬜ Upcoming |
| 5 | Predictive failure & energy models | ⬜ Upcoming |
| 6 | Interactive dashboard | ⬜ Upcoming |
| 7 | Final technical report | ⬜ Upcoming |

---

## 🔑 Key KPIs Targeted

- **Unplanned downtime reduction** — target 30% decrease via predictive maintenance
- **Energy efficiency improvement** — identify top 3 high-consumption anomalies per line
- **Decision speed** — reduce time-to-action from hours to minutes via live dashboards
- **Equipment utilization** — maintain >85% uptime across all production lines

---

## 📁 Key Files

| File | Description |
|---|---|
| `02-research/nexline-research-report.pptx` | Industry trends, IoT & Digital Twin landscape analysis |
| `03-architecture/togaf-blueprint.pdf` | Full enterprise architecture document |
| `04-data/sensor_data.csv` | Synthetic IoT sensor dataset (temperature, vibration, energy) |
| `05-predictive-models/failure_prediction.ipynb` | Predictive maintenance model notebook |
| `06-dashboard/` | Live dashboard source code |

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.9+
pip install -r requirements.txt
```

### Run the dashboard locally
```bash
cd 06-dashboard
python app.py
```
Then open `http://localhost:8050` in your browser.

### Run the predictive model notebooks
```bash
cd 05-predictive-models
jupyter notebook
```

---

## 📈 Live Demo

> 🔗 Dashboard link will be added once deployed

---

## 🧠 Approach & Methodology

This project follows a structured engineering approach across seven phases:

1. **Problem Definition** — stakeholder analysis, KPI identification, scope boundary
2. **Research** — review of IIoT trends, Digital Twin frameworks, predictive maintenance literature
3. **Architecture** — TOGAF ADM-based enterprise architecture covering business, data, application, and technology layers
4. **Data Engineering** — synthetic IoT data generation simulating temperature, vibration, power consumption, and production output
5. **Predictive Modeling** — machine learning models for failure forecasting and energy anomaly detection
6. **Dashboard Development** — interactive, role-based dashboards for plant managers and maintenance teams
7. **Reporting** — final compiled technical report with findings, recommendations, and future roadmap

---

## 📚 Research Foundation

This project is grounded in 15 peer-reviewed and industry sources covering:
- Industrial IoT (IIoT) architecture and sensor integration
- Digital Twin frameworks in manufacturing
- Predictive maintenance using machine learning
- Energy efficiency optimization in production environments
- Real-time dashboard design for operational decision-making

Full source list available in [`02-research/sources.md`](02-research/sources.md)

---

## 🔮 Future Enhancements

- Integrate live MQTT/OPC-UA data streams to replace synthetic simulation
- Add anomaly detection using LSTM neural networks for time-series data
- Deploy dashboard to cloud (AWS / Azure) with role-based access control
- Extend Digital Twin to cover supply chain and inventory simulation

---

## ⚠️ Usage

© 2026 jagadeeshwari. All rights reserved.  
This project is for portfolio and educational purposes only. No part of this repository may be reproduced or used without explicit permission from the author.
