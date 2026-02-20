# Datasets

This directory contains structured regulatory enforcement datasets used to analyze compliance capability, enforcement density, and post-event regulatory behavior.

Data is compiled from publicly available sources including:

- Federal Energy Regulatory Commission (FERC)
- North American Electric Reliability Corporation (NERC)
- State-level regulatory authorities
- Public enforcement reports and settlements

---

## Active Dataset Structures

### IOU Enforcement Findings (2015–2024)

Coverage:
- Investor-owned utilities
- Annual enforcement findings per firm-year
- Event markers for catastrophic regulatory events

Variables (Example Schema):

- Utility_Name
- Year
- Enforcement_Count
- Regulator
- Catastrophic_Event_Indicator (0/1)
- Event_Type
- Settlement_Amount
- Notes

Status: Under Construction

---

## Data Philosophy

Data included in this repository:

- Is sourced from public regulatory records
- Is cleaned for research consistency
- May include derived variables for modeling purposes

This dataset is designed for:
- Event-study analysis
- Time-series comparison
- Cross-firm compliance exposure modeling

---

## Limitations

Enforcement data reflects detected and pursued violations, not total compliance exposure.

Interpretation should account for:
- Regulatory discretion
- Reporting variability
- Settlement aggregation differences
