# Key Performance Indicators (KPIs)

## Overview

This document defines the measurable targets that determine the success of the Nexline Digital Twin project. Each KPI is tied directly to one of the four core operational challenges identified in the problem statement, and will be tracked through the dashboard and final evaluation report.

---

## KPI Framework

### 1. Equipment Uptime Rate

| Attribute | Detail |
|---|---|
| **Definition** | Percentage of scheduled production time during which equipment operates without unplanned interruption |
| **Target** | ≥ 85% uptime across all monitored production lines |
| **Baseline** | Estimated at ~68% based on reactive maintenance patterns |
| **Measurement** | Calculated from synthetic sensor data — ratio of operational time to total scheduled time |
| **Linked challenge** | Unpredictable downtime |

---

### 2. Unplanned Downtime Reduction

| Attribute | Detail |
|---|---|
| **Definition** | Reduction in the frequency and duration of unplanned equipment stoppages |
| **Target** | 30% reduction compared to pre-Digital Twin baseline |
| **Baseline** | Derived from simulated historical failure patterns in synthetic dataset |
| **Measurement** | Predictive model accuracy in flagging failures before occurrence (precision / recall) |
| **Linked challenge** | Reactive maintenance |

---

### 3. Predictive Model Accuracy

| Attribute | Detail |
|---|---|
| **Definition** | Performance of the failure forecasting model in correctly identifying upcoming equipment failures |
| **Target** | ≥ 85% accuracy · ≥ 80% recall on failure class |
| **Baseline** | N/A (new capability) |
| **Measurement** | Confusion matrix, F1-score, ROC-AUC evaluated on held-out test set |
| **Linked challenge** | Reactive maintenance |

---

### 4. Energy Anomaly Detection Rate

| Attribute | Detail |
|---|---|
| **Definition** | Percentage of simulated energy anomaly events correctly identified by the detection model |
| **Target** | Detect ≥ 90% of injected anomaly events in the synthetic dataset |
| **Baseline** | N/A (no current detection capability at Nexline) |
| **Measurement** | Anomaly detection precision and recall on labeled test data |
| **Linked challenge** | Wasted energy |

---

### 5. Energy Consumption Visibility

| Attribute | Detail |
|---|---|
| **Definition** | Identification of top energy-consuming production lines and root-cause patterns |
| **Target** | Surface top 3 high-consumption lines with drill-down breakdown in dashboard |
| **Baseline** | Currently zero visibility — no centralized energy monitoring |
| **Measurement** | Dashboard feature completeness — line-level consumption chart operational |
| **Linked challenge** | Wasted energy |

---

### 6. Dashboard Response Time

| Attribute | Detail |
|---|---|
| **Definition** | Time from data update to visible refresh on the operational dashboard |
| **Target** | < 5 seconds end-to-end refresh on simulated data stream |
| **Baseline** | N/A (no current dashboard) |
| **Measurement** | Measured during dashboard testing with synthetic data pipeline |
| **Linked challenge** | Lack of real-time visibility |

---

### 7. Time-to-Decision

| Attribute | Detail |
|---|---|
| **Definition** | Estimated time for a plant manager to identify and act on a critical alert using the dashboard |
| **Target** | Reduce from estimated hours (manual review) to < 5 minutes (dashboard alert) |
| **Baseline** | Qualitative estimate based on current fragmented monitoring described in problem statement |
| **Measurement** | Assessed through dashboard usability evaluation and alert workflow design |
| **Linked challenge** | Lack of real-time visibility |

---

## KPI Tracking Summary

| KPI | Target | Phase Measured |
|---|---|---|
| Equipment uptime rate | ≥ 85% | Phase 5 & 6 |
| Unplanned downtime reduction | 30% decrease | Phase 5 |
| Predictive model accuracy | ≥ 85% accuracy, ≥ 80% recall | Phase 5 |
| Energy anomaly detection rate | ≥ 90% detection | Phase 5 |
| Energy consumption visibility | Top 3 lines surfaced | Phase 6 |
| Dashboard response time | < 5 seconds | Phase 6 |
| Time-to-decision | < 5 minutes | Phase 6 |

---

*Document version: 1.0 — Phase 1: Problem Definition*
