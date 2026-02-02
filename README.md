# School-Workforce-Pressure-Funding-Allocation-Analysis

The Scenario
The Department is reviewing resource allocation across 120 schools for the upcoming budget. There are concerns that staffing shortages in specific regions are driving down student performance, and that our funding grant database is inflating costs due to legacy system errors.

The Data
You will be provided with four CSV files:
  dim_schools.csv: A list of 120 schools, their Region, and Sector.
  fact_enrolments.csv: Student headcounts and teacher FTE counts (2022–2024).
  fact_performance.csv: Attendance rates and average NAPLAN scores.
  raw_funding_requests.csv: A raw, uncleaned log of maintenance and capital works grants.

Strategic Questions to Answer
As a minimum, your dashboard should feature visualisations to address the following:
  Which Schools are facing the highest pressure regarding Class Sizes (Student/Teacher ratios) in 2024?
  Is there a visible correlation between this workforce pressure (Student/Teacher ratios) and Academic Results (NAPLAN)?
  Using the funding data, provide a Ranked List of schools in each region by total funding approved. Which categories are costing the Department the most?
  Does the region with the highest student enrolment actually receive the highest funding?

Caveats & Constraints
Data Integrity: The raw_funding_requests.csv file is a raw export known to contain data entry errors and duplicates. You are expected to identify and resolve these issues before performing any aggregation.
