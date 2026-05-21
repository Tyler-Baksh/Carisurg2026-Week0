# CariSurg 2026 - Week 0 
This repository contains the assignments completed for Week 0 of the **CariSurg Healthcare AI Training Program**.
Introductory data science assignments for the **CariSurg 2026** programme. Week 0 is a "structured simulation week designed to get [participants] familiar with the program's rythm, tools and community."

---

## Repository Structure

```
Carisurg2026-Week0/
└── Assignment1.ipynb   # Day 1 - Data Cleaning: Gender Column
└── Assignment2.ipynb   # Day 2 - Data Cleaning: RR Column
```

---

## Assignments

### Day 1 - Data Cleaning: Gender Column (`Assignment1.ipynb`)

Loads a reduced version of an Emergency Triage dataset and performs targeted cleaning on the `Gender` column.

**Tasks covered:**

- Loading a CSV dataset with pandas and inspecting its shape and column types
- Checking for and handling missing values (`NaN`) in the `Gender` column
- Auditing all unique values present in the column
- Normalising inconsistent string representations (e.g. `"male"`, `"1"`, `"female"`, `"0"`) to a consistent binary encoding:
  - `1` → Male
  - `0` → Female
- Replacing the original raw column with the cleaned version

### Day 2 - Data Cleaning: RR Column (`Assignment2.ipynb`)

- Loading a CSV dataset with pandas and inspecting the unique values, data type and statistical measures of the RR column
- Removing values outside of the expected clinical range
- Utilizing visualizations to assist in decision-making regarding NaN values
- Utilizing median-based imputation to replace instances of NaN values and avoiding removal of rows entirely

### Dataset
`EmergencyTriageDataset_Reduced_Dirty.csv` *(not included in this repository - provided separately by course facilitators)*

---

## Prerequisites

- Python ≥ 3.10
- Jupyter Notebook or JupyterLab
- Required libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
