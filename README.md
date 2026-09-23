
# Skin Cancer Risk Intelligence – SQL Healthcare Analysis

## Project Overview

This healthcare SQL capstone project analyses skin cancer patient
and lesion data for the Dermalife Oncology & Research Institute (DORI).

The project investigates demographic, clinical, environmental and
lifestyle patterns within 1,088 patient and lesion records to identify
signals that may support earlier detection and targeted prevention.

The analysis was conducted using PostgreSQL.

## Tools & Techniques

- PostgreSQL
- SQL
- Data Filtering
- SQL Joins
- CASE Statements
- Aggregate Functions
- GROUP BY
- COUNT and COUNT DISTINCT
- FILTER
- UNION ALL
- Comparative Analysis
- Healthcare Data Analysis

## Business Questions

The analysis focused on four areas:

### Demographic Risk
- Which age groups account for the most diagnoses?
- How do diagnoses differ by sex?
- Which body regions have the most malignant diagnoses?
- How many patients have a previous history of skin cancer?

### Lesion Characteristics
- Which diagnosis categories occur most frequently?
- Which symptoms are most common?
- How many lesions were biopsied?
- Which diagnosis has the largest average lesion diameter?

### Environmental Factors
- Which body regions account for the highest clinical workload?
- How many patients lack piped water or sewage access?
- Is poor sanitation associated with more severe diagnoses?

### Lifestyle Factors
- How many patients smoke or consume alcohol?
- Which diagnoses are common among smokers?
- What percentage of smokers also consume alcohol?
- How do smoking, alcohol and pesticide exposure compare with
  malignant diagnosis outcomes?

## Key Findings

### Older adults represent the largest diagnosis group

Patients aged 60–79 account for the largest number of records,
representing approximately 42.3% of the dataset.

Male patients account for 66.7% of diagnoses, while 20.6% of
patients have a previous history of skin cancer.

### Lesion characteristics provide important clinical signals

Actinic keratosis (ACK) is the most frequently recorded diagnosis.

Itching is the most common recorded symptom, appearing in 670 records.

A total of 458 lesions were biopsied, representing approximately
42.1% of lesions.

Melanoma has the largest average lesion diameter at 14.09.

### Facial lesions represent a major clinical workload

The face records the highest overall number of lesions and the
highest number of biopsies by body region.

There are:

- 278 facial lesions
- 124 facial biopsies
- 102 malignant diagnoses involving the face

### Environmental findings require careful interpretation

The analysis examined access to piped water and sewage systems.

Within this dataset, poor sanitation access was not associated with
a higher proportion of malignant diagnoses.

This demonstrates the importance of allowing the data to challenge
initial assumptions rather than assuming a relationship exists.

### Lifestyle patterns identify a subgroup for further investigation

Among patients who both smoke and consume alcohol, 82.1% of
diagnoses were malignant.

However, this subgroup contains only 28 patients.

Therefore, the finding should be interpreted cautiously and should
not be considered evidence that smoking and alcohol caused the
malignant diagnoses.

## Recommendations

1. Prioritise routine lesion review for patients aged 60–79 and
   patients with a previous history of skin cancer.

2. Fast-track growing, itching, elevated or changing lesions,
   particularly larger lesions and lesions located on the face.

3. Consider targeted smoking-and-alcohol counselling and
   pesticide-safety education.

4. Continue monitoring diagnosis stage, lesion size and follow-up
   outcomes.

5. Adjust future analysis for age, region and other potential
   confounding factors before making causal conclusions.

## Skills Demonstrated

- PostgreSQL
- SQL Query Development
- Relational Data Analysis
- SQL Joins
- Conditional Logic
- Data Aggregation
- Healthcare Analytics
- Risk Analysis
- Data Interpretation
- Analytical Problem Solving
- Insight Generation
- Evidence-Based Recommendations

## Project Files

This repository contains:

- PostgreSQL SQL analysis script
- SQL analysis text file
- Skin Cancer Risk Intelligence capstone report (PDF)

## Conclusion

This project demonstrates how SQL can be used to transform healthcare
data into clinically relevant insights.

The analysis identifies age, lesion characteristics, body location
and lifestyle patterns that may help inform screening and prevention
strategies while also demonstrating the importance of distinguishing
association from causation.
