## 🦠 COVID-19 Early Pandemic Global Analysis
📌 Project Overview
This project performs an end-to-end analysis of the initial waves of the COVID-19 pandemic (January – August 2020). By integrating global snapshots, daily time-series tracking, and specific demographic mortality data from the US, this study identifies patterns in viral spread and clinical vulnerability.

## 📂 Dataset Architecture
The analysis is built upon three primary data sources:

covid.csv: A country-level snapshot (as of Aug 2020) containing total cases, deaths, and testing metrics normalized per 1M population.

covid_grouped.csv: Daily time-series data providing a granular view of new cases and recovery rates across all WHO regions.

coviddeath.csv: Detailed US mortality data segmented by Age Group and Condition Group (Comorbidities).

## 🛠️ Technical Stack
Data Manipulation: Python (Pandas, NumPy)

Statistical Visualization: Seaborn, Matplotlib

Business Intelligence: Microsoft Power BI

Data Modeling: Star Schema logic connecting global metrics with temporal trends.

## 🚀 Key Implementation Steps
1. Data Cleaning & Transformation
Standardized date formats across multiple sources for accurate time-series joining.

Handled missing values in testing metrics and suppressed data flags in mortality records.

Calculated Case Fatality Rate (CFR) and Recovery Rates as primary performance indicators.

2. Exploratory Data Analysis (EDA)
Geographic Spread: Identified the USA, Brazil, and India as the primary epicenters during the study period.

Temporal Trends: Mapped the exponential growth phase of March 2020 and the subsequent secondary peaks in July 2020.

Demographic Deep-Dive: Quantified the high correlation between age (65+) and respiratory comorbidities with mortality rates.

3. Power BI Dashboard Features
Global KPI Header: Real-time tracking of Total Cases, Global Deaths, and Testing Intensity.

Epidemic Curve: Area charts showing daily new cases vs. recoveries.

Mortality Decomposition: Treemaps showing the impact of pre-existing conditions (e.g., Circulatory and Respiratory diseases).

## 💡 Top Insights
Testing Bias: Higher case counts in the West often correlated strongly with aggressive testing infrastructure (Tests/1M pop).

Vulnerability Profile: Over 80% of fatalities were concentrated in older age brackets, emphasizing the need for age-stratified public health policies.

Regional Shifts: The data visualizes the shift of the pandemic epicenter from Europe to the Americas and South-East Asia within a 7-month window.
