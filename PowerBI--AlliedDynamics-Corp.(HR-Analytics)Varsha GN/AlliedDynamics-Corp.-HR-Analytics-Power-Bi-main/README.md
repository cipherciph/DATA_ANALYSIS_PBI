# HR Analytics Power BI Dashboard

**Case Study Title**: *Attrition Analytics – Solving the Talent Turnover Puzzle*

## Overview

This project is a Power BI-based HR analytics case study focused on analyzing employee attrition for a mid-sized technology company – **AlliedDynamics Corp.**. The goal is to uncover the key factors behind high employee turnover and recommend actionable retention strategies through interactive dashboards and DAX-driven metrics.

## Problem Statement

AlliedDynamics Corp. is facing a **15%+ attrition rate** among mid-level professionals, especially in technical departments. This leads to increased hiring costs, project disruptions, and delivery delays.

## Project Objectives

- Identify key **drivers of attrition**
- Segment **high-risk employee groups**
- Empower stakeholders with **data-driven retention insights**
- Build a comprehensive **Power BI Dashboard** using visuals and DAX

## Dataset

The dataset includes employee records with the following attributes:

- **Demographics**: Age, Gender, Marital Status, Distance From Home
- **Job Attributes**: Department, Job Role, Monthly Income, Job Level
- **Behavioral Data**: Overtime, Job Satisfaction, Training Times, Work-Life Balance
- **Tenure & Career**: Years at Company, Total Working Years, NumCompaniesWorked

[Dataset Link (Google Sheets)](https://docs.google.com/spreadsheets/d/1rnG64DTOKCnhprWZ4udHTuA0sBAXaW3M/edit?usp=sharing)

## Tools & Technologies

- **Power BI**: Interactive dashboarding
- **DAX**: Calculated columns and measures
- **Excel**: Data cleaning and pre-processing (if needed)

## Power BI Visuals Included

| Visual Type           | Description                                          |
|-----------------------|------------------------------------------------------|
| KPI Cards             | Total Employees, Total Attrition                     |
| Bar/Column Charts     | Attrition by Department, Job Role, Work-Life Balance |
| Pie/Donut Charts      | Gender, Marital Status Composition                   |
| Matrix                | Attrition by Department vs Job Role                  |
| Line Chart            | Attrition vs Distance From Home                      |
| Histogram             | Age Distribution                                     |
| Scatter Plot          | Monthly Income vs Total Working Years                |
| Tree Map              | Attrition by Education Field                         |
| Slicers               | Gender, Department                                   |

## DAX Measures & Calculated Columns

| Function           | Purpose                                              |
|--------------------|------------------------------------------------------|
| `DISTINCTCOUNT()`  | Count unique employees                               |
| `DIVIDE()`         | Calculate attrition rate                             |
| `CALCULATE()`      | Filtered aggregation (e.g., satisfaction of leavers) |
| `SWITCH(TRUE())`   | Group tenure ranges                                  |
| `RANKX()`          | Rank departments by attrition                        |
| `FILTER()`         | High-income leavers identification                   |

Also includes: `AVERAGE()`, `IF()`, `FORMAT()`, `DATEDIFF()`, `CONCATENATE()`, `ALL()`

## Key Insights

- **Technical Support** and **R&D** have the highest attrition
- Employees with **long commutes** and **overtime** are at greater risk
- Low **Job Satisfaction** and **Work-Life Balance** correlate strongly with turnover
- **Single** employees and those with fewer years at the company tend to leave more
- High-income leavers pose a significant cost risk to the company

## Business Impact

The dashboard helps HR leaders to:
- Identify high-risk employees early
- Optimize retention strategies
- Reduce hiring and onboarding costs
- Make data-driven decisions for talent management

## How to Use

1. Clone/download this repository.
2. Open the `.pbix` Power BI report file in Power BI Desktop.
3. Link to the provided dataset or replace with your own structured HR data.
4. Interact with the slicers and charts to explore attrition patterns.

## License

This project is for **educational and non-commercial use** only.

## Contributing

Want to add more HR KPIs or a predictive model to this dashboard?  
Feel free to fork this repo and submit a pull request!

## Contact

For any queries or collaboration opportunities, feel free to reach out on [LinkedIn](https://www.linkedin.com/in/anshika-singh-293324211).
---

