# CariSurg 2026 - Week 0 
This repository contains the assignments completed for Week 0 of the **CariSurg Healthcare AI Training Program**.
Introductory data science assignments for the **CariSurg 2026** programme. Week 0 is a "structured simulation week designed to get [participants] familiar with the program's rythm, tools and community."

---

## Repository Structure

```
Carisurg2026-Week0/
└── Assignment1.ipynb   # Day 1 - Data Cleaning: Gender Column
└── Assignment2.ipynb   # Day 2 - Data Cleaning: RR Column
└── Assignment3.ipynb   # Day 3 - Data Visualization
└── Assignment4.pdf   # Day 4 - Vital Sign Description
└── Assignment5.pdf   # Day 5 - Unconsidered Metrics
```

---

## Assignments

### Day 1 - Data Cleaning: Gender Column (`Assignment1.ipynb`)

Loads a reduced version of an Emergency Triage dataset and performs targeted cleaning on the `Gender` column.

**Tasks covered:**

- Load a CSV dataset with pandas and inspecting its shape and column types
- Check for and handling missing values (`NaN`) in the `Gender` column
- Audit all unique values present in the column
- Normalize inconsistent string representations (e.g. `"male"`, `"1"`, `"female"`, `"0"`) to a consistent binary encoding:
  - `1` → Male
  - `0` → Female
- Replace the original raw column with the cleaned version

### Day 2 - Data Cleaning: RR Column (`Assignment2.ipynb`)

- Load a CSV dataset with pandas and inspect the unique values, data type and statistical measures of the RR column
- Remove values outside of the expected clinical range
- Utilize visualizations to assist in decision-making regarding NaN values
- Use median-based imputation to replace instances of NaN values and avoiding removal of rows entirely

### Day 3 - Data Visualization (`Assignment3.ipynb`)

- Use `matplotlib` create visualizations to aid in the answering of clinical questions
- Create a histogram of the Respiratory Rate (RR) distribution to answer: "What is the distribution of respiratory rates among patients, and how many fall outside the normal respiratory range?"
- Create a scatter plot of RR vs. Fio2 (Fraction of Inspired Oxygen) to determine if: "Do patients requiring higher oxygen concentrations also have higher respiratory rates?"

### Day 4 - Vital Sign Description: FiO2 (`Assignment4.pdf`)

- Define what FiO2 is
- State the clinical range of FiO2
- Explain the importance of FiO2 in the triaging process

### Day 5 - Unconsidered Metrics: SpO2 (`Assignment5.pdf`)

- After researching other vital signs and metrics that are considered in the triaging process, SpO2 was chosen for this report
- Define what SpO2 is
- State the clinical range of SpO2
- Explain the importance of SpO2 in the triaging process

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
