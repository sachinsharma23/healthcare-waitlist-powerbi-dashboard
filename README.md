Healthcare Waitlist Analysis Dashboard (Power BI)

Overview
This project is a Power BI dashboard built to analyze healthcare patient waitlist data from 2018 to 2021. It covers inpatient and outpatient cases and focuses on identifying trends, performance gaps, and areas with high waiting times.

Objectives

* Track the current status of the patient waiting list
* Compare performance with the same period in the previous year
* Analyze trends across inpatient, outpatient, and day case categories
* Provide insights based on specialty and age profile

Dataset

* Inpatient data (patients admitted to the hospital)
* Outpatient data (patients treated and discharged the same day)
* Specialty mapping file used to group related specialties

Tools Used
Power BI Desktop, Power Query, DAX

Data Preparation
Data was loaded using the folder connector in Power Query. Multiple files were combined and cleaned. Key steps included standardizing column names, creating a case type column, handling missing values, removing duplicates, and appending inpatient and outpatient data into a single dataset.

Data Modeling
A separate mapping table was used to group specialties. This table was linked to the main dataset to support better aggregation and filtering during analysis.

Dashboard Features

* KPI cards for latest month waitlist and previous year comparison
* Toggle to switch between average and median values
* Waitlist breakdown by case type
* Age group and time band analysis
* Top specialties based on waitlist
* Monthly trend analysis across all case types

Interactivity

* Filters for date, case type, and specialty
* Navigation between summary and detailed views
* Dynamic average vs median toggle using DAX SWITCH
* Tooltip-based drill-down for additional insights

Learnings

* End-to-end Power BI workflow
* Folder-based data loading in Power Query
* Writing DAX measures for dynamic calculations
* Basic data modeling concepts
* Designing interactive dashboards

