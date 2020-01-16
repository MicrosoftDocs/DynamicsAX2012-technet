---
title: Applicant resume report (HcmApplicantResume)
TOCTitle: Applicant resume report (HcmApplicantResume)
ms:assetid: 4911670a-2f5c-4d89-a1e9-968e8094d965
ms:mtpsurl: https://technet.microsoft.com/library/JJ994003(v=AX.60)
ms:contentKeyID: 51784125
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.HcmApplicantResume
---

# Applicant resume report (HcmApplicantResume) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Print this report to view a list of skills and competencies for an applicant.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Resume content</strong></p></td>
<td><p>Select the information to display in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Empty transactions</strong></p></td>
<td><p>Select this check box to display information in the report for applicants who do not have information for the check boxes that you selected in the <strong>Resume content</strong> field.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Applicant</strong></p></td>
<td><p>Specify the criteria used to identify the applicants to display information for.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>HcmApplicantResume</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\HcmApplicantResume</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>HRMApplicantResume</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Recruitment</strong> &gt; <strong>Applicant résumé</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - HcmApplicantResumeTmpTable table

  - DirPerson table

  - HcmApplicant table


> [!NOTE]
> <P>To find out where the data in the temp tables comes from, view the cross-references for the HcmApplicantResumeDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


