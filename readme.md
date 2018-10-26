README.md
================
Patrick Daniele
October 24, 2018

<p>
Summary: This repository will serve to save all analysis related documentation for the project. The table below indicates the location of all information regarding the project. For privacy reasons, analyses are performed on Popdata BC's Secure Research Environment (SRE), therefore no data is stored in this repository.
</p>
<h3>
Project Progress Table
</h3>
<table style="width:100%">
<tr>
    <th>Task</th>
    <th>Status</th>
    <th>Date Completed</th>
    <th>Filename</th>

</tr>
<tr>
    <td>Meta-data file Creation</td>
    <td>Complete</td>
    <td>October 24, 2018</td>
    <td>0.0 Meta-data File.SAS</td>

</tr>
<tr>
    <td>Data Import</td>
    <td>Complete</td>
    <td>October 26, 2018</td>
    <td>1.0 Data Import.SAS</td>

</tr>
    <tr>
    <td>Define BC Residency Periods</td>
    <td>Complete</td>
    <td>October 26, 2018</td>
    <td>2.0 BC Residency.SAS</td>

</tr>
    <tr>
    <td>Define Comorbidities</td>
    <td></td>
    <td></td>
    <td></td>

</tr>
    <tr>
    <td>Identify Events</td>
    <td></td>
    <td></td>
    <td></td>

</tr>
    <tr>
    <td>Define Concomitant Medications</td>
    <td></td>
    <td></td>
    <td></td>

</tr>
    <tr>
    <td>OAC Prescriptions dates and dosages</td>
    <td></td>
    <td></td>
    <td></td>

</tr>
    <tr>
    <td>AF Cases (Index diagnosis dates)</td>
    <td></td>
    <td></td>
    <td></td>

</tr>
</table>
<h3>
Raw Datasets
</h3>
<p>
<B>Location:</B> R:/SAS Data/Raw\_Data<br> <B>Libname:</B> Raw\_Data
</p>
<table style="width:100%">
<tr>
    <th>Dataset</th>
    <th>Description</th>
    <th>Variables</th>
    <th>Notes</th>

</tr>
<tr>
    <td>Demographics</td>
    <td>Demographics data from Registry File</td>
    <td>DOB, SEX</td>
    <td></td>

</tr>
<tr>
    <td>DAD</td>
    <td>Hospitalizations datasets</td>
    <td></td>
    <td></td>

</tr>
<tr>
    <td>Deaths</td>
    <td>Death Dates</td>
    <td></td>
    <td></td>

</tr>
    <tr>
    <td>Census_GEO</td>
    <td>Census Indicators (SES)</td>
    <td>QAIPPE, DAIPPE</td>
    <td></td>

</tr>
      <tr>
    <td>Dinpin_List</td>
    <td>All medications extracted</td>
    <td></td>
    <td></td>

</tr>
      <tr>
    <td>Cohort_Dinpin_List</td>
    <td>Medications used for cohort definition</td>
    <td></td>
    <td></td>

</tr>
      <tr>
    <td>NACRS</td>
    <td>NACRS Data</td>
    <td></td>
    <td></td>

</tr>
    <tr>
    <td>Pnet_clm_rpt</td>
    <td>Pharmanet Claims Dataset</td>
    <td></td>
    <td></td>

</tr>
    <tr>
    <td>pnt_dsp_rpt</td>
    <td></td>
    <td></td>
    <td></td>

</tr>
    <tr>
    <td>pnt_hlth_rpt</td>
    <td>Health Products details</td>
    <td></td>
    <td></td>

</tr>
      <tr>
    <td>Registry</td>
    <td>BC Registration dataset</td>
    <td></td>
    <td></td>

</tr>
</table>
<h3>
Processed Datasets
</h3>
<p>
<B>Location:</B> R:/SAS Data<br> <B>Libname:</B> Data
</p>
<table style="width:100%">
<tr>
    <th>Dataset</th>
    <th>Description</th>
    <th>Variables</th>
    <th>Notes</th>

</tr>
<tr>
    <td>Demographics</td>
    <td>Patient demogs from Registry and Consolidation datasets</td>
    <td>DOB, SEX, Death Date</td>
    <td>N/A</td>

</tr>
<tr>
    <td>BC Residency</td>
    <td>BCResidency93dgap</td>
    <td>Startdate, Enddate</td>
    <td>Up to a 93 day gap in coverage is acceptable for continous registration.</td>

</tr>
<tr>
    <td>Comorbidities</td>
    <td></td>
    <td></td>
    <td></td>

</tr>
    <tr>
    <td>Medications</td>
    <td></td>
    <td></td>
    <td></td>

</tr>
</table>
<h3>
Directory
</h3>
<table style="width:100%">
<tr>
    <th>Folder</th>
    <th>Description</th>

</tr>
<tr>
    <td>Objective 1 - Trends</td>
    <td></td>

</tr>
<tr>
    <td>Objective 2 - Patterns</td>
    <td></td>

</tr>
    <tr>
    <td>Objective 3 - Adherence</td>
    <td></td>

</tr>
    <tr>
    <td>Objective 4 - Outcomes</td>
    <td></td>

</tr>
</table>
