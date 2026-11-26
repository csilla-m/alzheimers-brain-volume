

Source: OASIS longitudinal dataset (Marcus et al., 2010), via Kaggle.

| Column | Original name | Description | Type / values |
|---|---|---|---|
| subject_id | Subject ID | Unique ID for each person | Text, e.g. OAS2_0001 |
| group | Group | Diagnosis group | Demented, Nondemented, Converted |
| sex | M/F | Sex | M, F |
| age | Age | Age at visit | Years |
| educ | EDUC | Years of education | Years |
| ses | SES | Socioeconomic status | 1 (highest) to 5 (lowest) |
| mmse | MMSE | Mini-Mental State Exam score | 0–30, lower = more impairment |
| cdr | CDR | Clinical Dementia Rating | 0, 0.5, 1, 2 |
| etiv | eTIV | Estimated total intracranial volume | cm³ |
| nwbv | nWBV | Normalised whole brain volume | Proportion (0–1) |
| asf | ASF | Atlas scaling factor | Number |

## Cleaning notes
- SES: filled from the same person's other visits; remaining gaps filled with the median
- MMSE: rows with no score were dropped
