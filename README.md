# nhs-Prescribing-dashbaord
Excel dashboard; analysis of NHS Hospital Prescribing
## project description and instructions:
This repository contains an Excel-based analysis and interactive dashboard built on the NHS * Hospital Prescribing Dispensed in the Community (August 2025). The dashboard highlights top medicines by cost and volume, hospital trust-level spending, efficiency metrics (average cost per item), and quantity-driven insights.
This project demonstrates end-to-end data cleaning, pivot-based analysis and dashboard layout suitable for health informatics and NHS analytics roles.
---
## What’s included
- excel-dashbaord.xlsx — Final cleaned dashboard (Excel workbook, pivots, charts)
- screenshots/ — Images: key charts for quick preview
- README.md — This file
- .gitignore, LICENCE
- Full rasw data set is not included.Link to official NHS source is below 
---
## Data source
Original data source: NHS Buisness Services Authority- Hospital Prescribing Dispensed in the Community (Public dataset).  
Link: [NHSBSA Prescribing Dataset] https://opendata.nhsbsa.net/dataset/hospital-prescribing-dispensed-in-the-community/resource/a82df23f-e8a5-4220-86a1-03fdcac8944e
 
> Note: Raw full dataset is not uploaded to this repo to po=rotect any sensitive or restricted fields.
---
## How to reproduce / run
1. Openg excel-dashboard.xlsx in Microsoft Excel (Excel 365 recommended for full function support).  
2. On the Dashboard sheet
    - Refresh data when reconnecting to full data is required.
    - Use slicer for hospital trust filtering.
3. To reproduce from raw csv:
   - Download and load "hospital_disp_community.csv" into power query.
   - Apply the cleaning steps.
   - Create pivot tables in the workbook.  
   - Create pivot tables as in the workbook.
---
## Key insights
- A small set of medicines contributes a large share of total spend (cost concentration).
- Several trusts show higher average cost per item compared to the national average — flags for medicines optimisation.
  

