---
title: OSHA 300 log preparation report (HcmOSHA300LogPrepReport)
TOCTitle: OSHA 300 log preparation report (HcmOSHA300LogPrepReport)
ms:assetid: 98b3d69c-3373-44a0-a408-5ba4bab2d231
ms:mtpsurl: https://technet.microsoft.com/library/Dn479039(v=AX.60)
ms:contentKeyID: 59632407
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# OSHA 300 log preparation report (HcmOSHA300LogPrepReport) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This report provides data that you can use to prepare the OSHA 300 log of workplace injuries and illnesses.


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
<td><p><strong>From date</strong></p></td>
<td><p>Enter the first date in the reporting period.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the last date in the reporting period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Regulatory establishment</strong></p></td>
<td><p>Enter the workplace location to create the report for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Case number</strong></p></td>
<td><p>Enter the case number or select a range of case numbers to include in the report.</p>
<div class="alert">

> [!NOTE]
> <P>If you search by both date and case number, you will find only incidents that match both the date range and the case number range that you specify. If the case number exists, but it is not within the date range that you specify, it will not be found.</P>


</div></td>
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
<td><p>HcmOSHA300LogPrepReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\HcmOSHA300LogPrepReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>HcmOSHA300LogPrepReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Workers</strong> &gt; <strong>Regulatory</strong> &gt; <strong>OSHA incidents</strong> &gt; <strong>OSHA 300 log preparation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - HRMInjuryIncident table

  - HcmWorker table

  - HcmPosition table

  - HRMInjuryType table

  - HRMInjuryOutcome table

  - HRMInjuryBodyPart table

  - DirPerson table

  - HcmEmployment table

  - HcmEEOEstablishment table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


