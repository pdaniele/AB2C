AB2C Datasets
================
Last Updated: November 05 2018

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
<td>BC Residency</td>
<td>BCResidency93dgap</td>
<td>Startdate, Enddate</td>
<td>Up to a 93 day gap in coverage is acceptable for continous registration.</td>
</tr>
<tr class="odd">
<td>MSP_Manip</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td>DAD_Manip</td>
<td></td>
<td></td>
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
<td></td>
<td></td>
<td></td>
</tr>
</tbody>
</table>
