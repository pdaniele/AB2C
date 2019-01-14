Cohort Definition
================
Last Updated: January 14 2019

### Overview:

This page describes the cohort definition and process for the project.

### Cohort

#### Prevalent AF Cases

Steps to identify prevalent AF Cases:

1.  Identify AF diagnosis dates in each source

-   DAD - ICD10 = I48 in any diagnosis position
-   MSP - ICD9 = 4273 in any diagnosis position
-   NACRS - ICD10 = I48 in any diagnosis position
-   PNet - AF Specific medications

1.  Identify pairs of AF diagnoses in MSP between 30 days and 2 years apart.
2.  Merge diagnosis dates from each criteria, sort by date
3.  Exclude cases based on BC Residency (Not registered at time of diagnosis)

#### Incident AF Cases

Steps to identify incident AF Cases:

1.  Limit prevalent cases based on BC residency with a minimum 3 years lookback.

### Groups

1.  Age - &lt;65, 65-74, &gt;=75 at diagnosis
2.  Sex - Male, Female
3.  Socioeconomic Status - SES Quintile
