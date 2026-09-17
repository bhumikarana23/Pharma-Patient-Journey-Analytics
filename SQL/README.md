# SQL Analysis

This folder contains the SQL queries used to analyze patient treatment journeys and therapy-switching behavior.

## Objective

The SQL analysis focuses on identifying treatment patterns, patient characteristics, therapy switching, treatment discontinuation, clinical factors, and patient segments relevant to pharmaceutical analytics.

## Analysis Performed

- Patient and demographic analysis
- Disease severity analysis
- Current and previous therapy analysis
- Treatment switching analysis
- Switching rates by therapy and patient characteristics
- Clinical factor analysis
- Medication adherence analysis
- Adverse event analysis
- Treatment outcome analysis
- Treatment discontinuation analysis
- Patient segmentation analysis
- High-risk patient identification

## Key SQL Techniques

- `SELECT`
- `WHERE`
- `GROUP BY`
- `ORDER BY`
- `CASE`
- Aggregate functions such as `COUNT()` and `AVG()`
- Conditional aggregation using `SUM(CASE WHEN...)`
- Subqueries
- Percentage calculations
- Cross-category analysis

## Key Business Questions

The queries were designed to answer questions such as:

- What percentage of patients switched therapy?
- Which therapies have higher switching rates?
- How does disease severity relate to therapy switching?
- How does medication adherence differ across patients?
- What is the relationship between adverse events and therapy switching?
- Which patient segments have higher switching rates?
- Which patients exhibit characteristics associated with higher treatment-switching risk?
- How does treatment discontinuation vary across therapies?

## Files

| File | Description |
|------|-------------|
| `patient_journey_queries.sql` | SQL queries used for patient journey and treatment-switching analysis |

## Database

**Database:** MySQL

**Table:** `patients`

The table contains the cleaned synthetic patient dataset used throughout the analysis.

## Note

The dataset used in this project is synthetic and does not contain real patient information.
