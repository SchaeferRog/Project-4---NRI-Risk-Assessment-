# FEMA National Risk Index — Sensitivity Analysis
**CIVE 202 | Spring 2026 | Group 151-14**

## Overview
This project conducts a sensitivity analysis of the [FEMA National Risk Index (NRI)](https://hazards.fema.gov/nri/) to identify potential categorical bias. The current NRI scoring method is compared against an alternative risk model developed by our team:

> **Risk = Probability × Impact**

The analysis focuses on census-tract level data across **Oklahoma** and **Rhode Island**, chosen because they sit at opposite ends of the tornado risk spectrum — Oklahoma lies in the heart of Tornado Alley, while Rhode Island experiences very few tornadoes annually.

---

## Background

### NRI Risk Formula
The FEMA National Risk Index calculates risk as:
Risk Index = (Expected Annual Loss × Social Vulnerability) / Community Resilience

- **Expected Annual Loss** — Average annual cost from natural hazards (buildings, people, agriculture)
- **Social Vulnerability** — Susceptibility of social groups to natural hazard impacts
- **Community Resilience** — A community's ability to prepare for, withstand, and recover from hazards

---

## Repository Contents
| File | Description |
|---|---|
| `CIVE202_Spring2026_P4-151-14_Project4_GanttChart` | Project timeline |
| `CIVE202_Spring2026_P4-151-14_Project4_SOW` | Scope of Work |
| `CIVE202_Spring2026_P4-151-14_Project4_PythonCode` | Python code |
| `CIVE202_Spring2026_P4-151-14_Project4_ACD` | Annotated Code Document |
| `CIVE202_Spring2026_P4-151-14_Project4_TimeSheet` | Team time sheet |
| `CIVE202_Spring2026_P4-151-14_Project4_Report` | Final report (methodology + bias discussion) |

---

## Methodology
1. **Data Processing** — Download and clean NRI and SVI data for Oklahoma and Rhode Island
2. **Model Development** — Implement alternative risk scoring model in Python
3. **Visualization** — Summary tables, sensitivity analysis comparison, and GeoPandas risk map
4. **Final Report** — Methodology, findings, and ethical implications of model bias on FEMA mitigation funding
