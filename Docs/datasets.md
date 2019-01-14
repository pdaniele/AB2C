AB2C Datasets
================
Last Updated: January 14 2019

#### Raw Datasets

##### Location: R:/SAS Data/Raw\_Data

##### Libname: Raw\_Data

| Dataset              | Description                            | Variables      | Notes |
|----------------------|----------------------------------------|----------------|-------|
| Demographics         | Demographics data from Registry File   | DOB, SEX       |       |
| DAD                  | Hospitalizations datasets              |                |       |
| Deaths               | Death Dates                            |                |       |
| Census\_GEO          | Census Indicators (SES)                | QAIPPE, DAIPPE |       |
| Dinpin\_List         | All medications extracted              |                |       |
| Cohort\_Dinpin\_List | Medications used for cohort definition |                |       |
| NACRS                | NACRS Data                             |                |       |
| Pnet\_dsp\_clm       | Medications dispensed                  |                |       |
| pnt\_hlth\_rpt       | Health Products detail                 |                |       |
| Registry             | BC Registration dataset                |                |       |

#### Processed Datasets

##### Location: R:/SAS Data/

##### Libname: Data

<table style="width:22%;">
<colgroup>
<col width="5%" />
<col width="5%" />
<col width="5%" />
<col width="5%" />
</colgroup>
<thead>
<tr class="header">
<th>Dataset</th>
<th>Description</th>
<th>Variables</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Demographics</td>
<td>Patient demogs from Registry and Consolidation datasets</td>
<td>DOB, SEX, Death Date</td>
<td></td>
</tr>
<tr class="even">
<td>BCResidency93dgap</td>
<td>BC Residency time frames</td>
<td>Startdate, Enddate</td>
<td>Up to a 93 day gap in coverage is acceptable for continous registration.</td>
</tr>
<tr class="odd">
<td>MSP_Manip</td>
<td>Manipulated MSP Data</td>
<td>Service Date, Comorbidities</td>
<td></td>
</tr>
<tr class="even">
<td>Hosp_comorb_index</td>
<td>Manipulated DAD Data</td>
<td>Admission date, separation date, comorbidities</td>
<td>Comorbidities are defined as prior to admission</td>
</tr>
<tr class="odd">
<td>Hosp_comorb_pre</td>
<td>Manipulated DAD Data</td>
<td>Admission date, separation date, comorbidities</td>
<td>Comorbidities are defined as anytime prior or during admission</td>
</tr>
<tr class="even">
<td>Outcomes</td>
<td>Outcomes identified in DAD Data</td>
<td>Admission Date, Separation date, outcome indicators</td>
<td></td>
</tr>
<tr class="odd">
<td>PharmaNet_Manip</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td>NACRS_Manip</td>
<td>Manipulated NACRS data</td>
<td>Admission date, comorbidities</td>
<td></td>
</tr>
<tr class="odd">
<td>Cohort_Prevalent</td>
<td>Prevalent Cohort</td>
<td>Diagnosis Date, Source, Criteria</td>
<td></td>
</tr>
</tbody>
</table>
