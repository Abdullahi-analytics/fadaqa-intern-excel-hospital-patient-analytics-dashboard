# Fadaqa Intern Excel Hospital Patient Analytics Dashboard

## Project Overview

An Excel-based healthcare analytics project focused on analyzing 1,000 hospital patient records to understand patient demographics, departmental performance, billing activities and payment status.

The project demonstrates data preparation, Excel formulas, PivotTables, PivotCharts and dashboard development to transform raw hospital records into meaningful analytical insights.

## Business Objectives

- Analyze patient distribution by age, gender and department.
- Examine hospital billing across departments.
- Evaluate payment status and associated billing amounts.
- Calculate average patient length of stay.
- Explore hospital admission patterns.
- Develop a dashboard for performance monitoring.

## Dataset Overview

| Attribute | Description |
|---|---|
| Total Records | 1,000 |
| Original Columns | 12 |
| Prepared Columns | 14 |
| Departments | 6 |
| Gender Categories | 2 |
| Payment Categories | 3 |
| Admission Period | 2024–2025 |

The dataset contains patient demographics, admission and discharge dates, diagnoses, departmental information, billing amounts, insurance coverage and payment status.

*Dataset provenance and privacy status require confirmation before public release.*

## Tools and Technologies

- Microsoft Excel
- Excel Formulas (IF, IFS and date calculations)
- PivotTables
- PivotCharts
- Excel Dashboard

## Methodology

The project followed these analytical stages:

1. **Data Understanding:** Examined the dataset structure and available variables.
2. **Data Preparation:** Reviewed missing values, duplicates and data consistency.
3. **Data Transformation:** Created age categories, admission validation and length-of-stay calculations.
4. **Data Analysis:** Used PivotTables to summarize patient distribution, billing and payment performance.
5. **Visualization:** Developed PivotCharts and an Excel dashboard to communicate findings.

## Dashboard Preview

![Hospital Patient Analytics Dashboard](images/Hospital_patient_dashboard.png)

## Key Findings

| Performance Indicator | Result |
|---|---:|
| Total Patients | 1,000 |
| Total Billing | $8,053,143.44 |
| Billing Associated with Paid Status | $4,568,527.32 |
| Average Length of Stay | 4.81 days |

### Departmental Insights

- General recorded the highest patient volume (252).
- Orthopedics recorded the highest total billing ($2,553,862.32).
- Neurology recorded the lowest patient volume (94).
- Orthopedics had the highest average length of stay (8.38 days).

### Payment Analysis

| Payment Status | Patients |
|---|---:|
| Paid | 564 |
| Pending | 257 |
| Partially Paid | 179 |

Pending and partially paid records represent areas for further financial monitoring.

## Business Recommendations

- Monitor patient distribution to support departmental planning.
- Investigate billing differences across departments.
- Review pending and partially paid records.
- Monitor departmental length-of-stay patterns.
- Maintain regular reporting of hospital performance indicators.

## Repository Structure

```text
fadaqa-hospital-patient-analytics-dashboard/
│
├── README.md
├── data/
│   └── Fadaqa_Hospital_Patients_Dataset.xlsx
│
└── images/
    ├── Hospital_patient_dashboard.png
    ├── Hospital_patient_cleandata.png
    └── Hospital_patient_pivot.png
```

## Limitations

- Dataset source and currency denomination require confirmation.
- An insurance coverage value of 0.7 requires verification.
- Some existing dashboard calculations and chart labels require correction.
- The analysis is descriptive and does not establish causal relationships.
- Patient-identifying information must be protected before publication.

## Conclusion

This project demonstrates the use of Microsoft Excel for healthcare data preparation, analysis and visualization. It highlights how patient records can be transformed into meaningful information for understanding departmental activity, billing patterns and patient demographics.

## Author

**Abdullahi Muhammed Soliu**

Data Analyst | Business Analytics | Business Intelligence

[Email](mailto:abdullahimuhammedsoliu0018@gmail.com) | [LinkedIn](mailto:https://www.linkedin.com/in/abdullahi-muhammed-soliu-074598417)
