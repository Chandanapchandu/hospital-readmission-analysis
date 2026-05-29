# Hospital Readmission Analysis

## Problem Statement
Hospitals lose millions annually due to preventable 30-day readmissions.
This project analyzes 101,766 patient records to identify which patient 
groups are most at risk of being readmitted within 30 days of discharge.

## Dataset
- Source: UCI Machine Learning Repository
- Name: Diabetes 130-US Hospitals Dataset (1999-2008)
- Records: 101,766 patients
- Features: 50 columns

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Findings
1. Only 11.16% of patients are readmitted within 30 days
2. Age group 20-30 has surprisingly highest readmission rate
3. Longer hospital stays correlate with higher readmission risk
4. Higher medication count strongly predicts readmission
5. Previous inpatient visits are strongest predictor of readmission
6. Previous emergency visits increase readmission risk significantly
7. More lab procedures correlate with higher readmission rates

## High Risk Patient Profile
Patients most likely to be readmitted within 30 days:
- Age group: 20-30 years
- Hospital stay: 7+ days
- Medications: 15+ prescribed
- Previous inpatient visits: 3+
- Previous emergency visits: 2+
- Lab procedures: 50+

## Business Recommendations
1. Flag patients with 15+ medications for dedicated discharge counseling
2. Assign case managers to patients with 3+ previous inpatient visits
3. Mandatory follow up calls for patients with 50+ lab procedures

## Project Structure
hospital-readmission-analysis/
│
├── diabetic.ipynb          # Main analysis notebook
├── README.md               # Project documentation
└── data/                   # Dataset folder

## How to Run
1. Clone this repository
2. Download dataset from UCI ML Repository
3. Open diabetic.ipynb in Jupyter Notebook
4. Run all cells

## Data Source
[UCI Machine Learning Repository - Diabetes 130-US Hospitals]
(https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008)
