# Opioid Prescribing Trends Among Post-Discharge Patients

## Overview
This project visualizes prescribing patterns for opioids among hospital patients following discharge. Using de-identified administrative data, the visualizations explore associations between patient characteristics and prescription trends.

## Objectives
- Compare opioid usage to non-opioid alternatives (NSAIDs, psycholeptics, psychoanaleptics, anesthetics).
- Highlight differences by admission type, gender, age, and comorbidity levels.
- Inform safer prescribing practices and identify high-risk profiles.

## Visualizations
- **Bar Chart**: Opioid vs. non-opioid prescriptions by gender and admission type.
-  **Treemap**: Proportional distribution of drug classes prescribed.
- **Jitter Plot**: Opioid type vs. age and gender distribution.

## Tools
- R
- ggplot2, dplyr, treemapify

## Data Note
The dataset used in this project cannot be publicly shared due to licensing restrictions. However, code and visualizations are provided for reference. The dataset included the following variables:
- `gender`, `age`, `comorbidity_level`, `primary_diagnosis`
- `admission_type` (elective/emergency)
- `drug_name`, `drug_class`, `opioid_type`

## Author
Nadeem Bishtawi
