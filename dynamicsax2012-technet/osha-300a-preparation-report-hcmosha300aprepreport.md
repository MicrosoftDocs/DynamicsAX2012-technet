---
title: OSHA 300A preparation report (HcmOSHA300APrepReport)
TOCTitle: OSHA 300A preparation report (HcmOSHA300APrepReport)
ms:assetid: 47ac3613-19cf-4bb3-8ce9-f8349f5e29f0
ms:mtpsurl: https://technet.microsoft.com/library/Dn479035(v=AX.60)
ms:contentKeyID: 59632403
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# OSHA 300A preparation report (HcmOSHA300APrepReport) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This report provides data that you can use to prepare OSHA 300A summary report. The OSHA 300A report is an annual summary of the incidents that are recorded in the OSHA 300 log. It must be posted in a visible location at each workplace to make employees aware of the work-related injuries and illnesses that have occurred in their workplace.

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
<td><p><strong>From date</strong></p></td>
<td><p>Enter the first date in the reporting period.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the last date in the reporting period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Regulatory establishment</strong></p></td>
<td><p>The workplace location to create the report for.</p></td>
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
<td><p>HcmOSHA300APrepReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\HcmOSHA300APrepReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>HcmOSHA300APrepReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Workers</strong> &gt; <strong>Regulatory</strong> &gt; <strong>OSHA incidents</strong> &gt; <strong>OSHA 300A preparation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - HcmWorker table

  - HcmEmployment table

  - HRMInjuryIncident table

  - HRMInjuryType table

  - HRMInjuryOutcomeType table

  - HcmEEOEstablishment table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


