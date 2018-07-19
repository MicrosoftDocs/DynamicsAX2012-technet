---
title: VETS preparation report (HcmVETSPrepReport)
TOCTitle: VETS preparation report (HcmVETSPrepReport)
ms:assetid: 0cbd35a9-2307-46a2-b1e4-6ad54a8a20b5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn479036(v=AX.60)
ms:contentKeyID: 59632406
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# VETS preparation report (HcmVETSPrepReport) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This report provides data that you can use if you are required to prepare the VETS 100 or VETS100A report regarding your organization’s affirmative action efforts in employing veterans. Federal contractors and subcontractors who meet specific requirements must submit the VETS reports annually to the Office of Federal Contractor Compliance Programs (OFCCP).


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



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
<td><p><strong>End date</strong></p></td>
<td><p>The last day of the 12-month reporting period that is covered by the report that you are completing. The system calculates the first day of the reporting period based on the date that you enter here.</p></td>
</tr>
<tr class="even">
<td><p><strong>Regulatory establishment</strong></p></td>
<td><p>The work location that you are completing the report for.</p></td>
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
<td><p>HcmVETSPrepReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\HcmVETSPrepReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>HcmVETSPrepReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Workers</strong> &gt; <strong>Regulatory</strong> &gt; <strong>VETS preparation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - HcmVETSPrepReport query

  - HcmWorker table

  - HcmEmployemnt table

  - HcmEEOEstablishment table

  - HcmPositionWorkerAssignment table

  - HcmPositionDetail table

  - HcmJob table

  - HcmJobDetail table

  - HcmJobFunction table

  - Dirperson table

  - HcmPersonDetails table

  - HcmVeteranStatus table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


