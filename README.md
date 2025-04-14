# Opioid Prescribing Trends Among Post-Discharge Hospital Patients


## Overview
This project explores opioid prescribing patterns for hospital patients discharged with at least one opioid prescription. Using de-identified administrative health data, we investigate trends in prescribing across patient demographics, admission characteristics, and primary diagnoses.

The goal is to generate insight into which patient groups are more likely to receive opioids, what diagnoses are most associated with these prescriptions, and how factors like age, hospital stay, and admission type influence patterns.

## Visualizations
Six visualizations are included in the analysis:

1. **Number of Diagnoses Distribution**  
   Histogram showing the clinical complexity of patients based on total recorded diagnoses.

2. **Top 10 Primary Diagnoses (ICD-10-CA)**  
   Bar chart of the most frequent reasons for admission, with mapped clinical labels.

3. **Treemap of Diagnoses**  
   Visual proportion of the top 10 diagnoses using area-based comparison.

4. **Opioid Prescriptions by Age Group**  
   Bar chart illustrating which age groups are more likely to receive opioids.

5. **Admission Category Breakdown**  
   Comparison of opioid prescriptions by elective vs. emergency admissions.

6. **Length of Stay Distribution**  
   Histogram showing how opioid prescriptions are distributed by hospital stay duration.

---

## Data & Methods

- Data was pre-processed separately (`PIN DAD Linkage.Rmd`) to create derived variables (e.g., `n_diagnoses`, `age_group`, `opioid_type`).
- Diagnosis codes (`DAD_DXCODE1`) were mapped to readable clinical labels using the official **ICD-10-CA Appendix 1.18** from [Cancer Care Ontario](https://ext.cancercare.on.ca/ext/databook/db2122/Appendix/Appendix_1.18_-_ICD10CA_.htm).

---

## Data Privacy Notice

Due to data-sharing restrictions, the underlying dataset is not included in this repository. However, all code, plots, and the ICD-10 reference table used are provided for full transparency and reproducibility (where permitted).

## Author
Nadeem Bishtawi
