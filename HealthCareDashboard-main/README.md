[README.md](https://github.com/user-attachments/files/28721998/README.md)
# Healthcare Intelligence Dashboard

A premium dark-theme Power BI dashboard for healthcare analytics, built from the Kaggle **Healthcare Dataset**.  
This project focuses on patient insights, clinical risk, and revenue analysis with a clean SaaS-style UI.

## Preview

### Page 1 — Executive Overview
![Executive Overview] <img width="1425" height="802" alt="page-1-executive-overview" src="https://github.com/user-attachments/assets/f0683bf8-c108-4101-bfe1-159ab6d5866c" />


### Page 2 — Patient Intelligence
![Patient Intelligence] <img width="1422" height="793" alt="page-2-patient-intelligence" src="https://github.com/user-attachments/assets/ffedded6-c539-46c0-b128-017fc749da83" />


## Dataset

- **Dataset:** Healthcare Dataset
- **Source:** Kaggle
- **Rows:** 55,500 patient records
- **Columns:** 15
- **Main fields:** Name, Age, Gender, Blood Type, Medical Condition, Date of Admission, Doctor, Hospital, Insurance Provider, Billing Amount, Room Number, Admission Type, Discharge Date, Medication, Test Results

## Tools Used

- Power BI Desktop
- Power Query Editor
- DAX
- Kaggle CSV data
- Custom dark premium theme

## Dashboard Pages

### 1) Executive Overview
A high-level business summary with:
- KPI cards for Total Patients, Total Revenue, Average Billing, and Average Length of Stay
- Monthly admissions trend
- Patients by Medical Condition
- Top hospitals by revenue
- Insurance distribution
- Executive insights panel

### 2) Patient Intelligence
A patient-focused analysis page with:
- Risk-level matrix by medical condition
- Gender distribution
- Age group analysis
- Patient detail table
- Slicers for condition, gender, age group, and hospital

### 3) Revenue Intelligence
A finance-focused page with:
- Total revenue KPIs
- Revenue by department
- Revenue by insurance provider and medical condition
- Revenue trend over time
- Key financial insights

## Power Query Transformations

The dataset was cleaned and shaped in Power Query with:
- Proper case conversion for patient and doctor names
- UPPERCASE formatting for hospital names
- Negative billing values fixed using `Number.Abs()`
- Rounded billing values for reporting
- Date type conversion for admission and discharge dates
- Admission year, month, and month number extraction
- Length of stay calculation
- Index column for Patient ID
- Conditional columns for:
  - Age Category
  - Billing Tier
  - Stay Category
  - Risk Flag
- Department lookup merge using a manual condition-to-department table
- Grouped summary queries for condition, hospital, insurance, and monthly admissions

## DAX Measures

Key measures used in the report:
- Total Patients
- Total Revenue
- Average Billing
- Average LOS
- High Risk Patients
- Female %
- Average Age

## Design Style

- Dark premium SaaS-style theme
- Minimal cards with subtle borders
- Soft shadows and rounded corners
- Purple / blue / teal accent palette
- Clean executive presentation

## Repository Structure

```text
.
├── HealthCareDashboard.pbix
├── README.md
└── screenshots
    ├── page-1-executive-overview.png
    └── page-2-patient-intelligence.png
```

## How to Use

1. Download or clone the repository.
2. Open `HealthCareDashboard.pbix` in Power BI Desktop.
3. Refresh the data if needed.
4. Explore the report pages and slicers.
5. Review the screenshots in the `screenshots` folder for a quick preview.

## Notes

This project was designed as a portfolio-ready Power BI dashboard for healthcare analytics and presentation.
