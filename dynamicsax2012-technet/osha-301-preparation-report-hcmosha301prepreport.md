---
title: OSHA 301 preparation report (HcmOSHA301PrepReport)
TOCTitle: OSHA 301 preparation report (HcmOSHA301PrepReport)
ms:assetid: 5c5d7157-9b1e-467f-9d41-6e02ebf6af03
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn479038(v=AX.60)
ms:contentKeyID: 59632404
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# OSHA 301 preparation report (HcmOSHA301PrepReport) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This report provides data that you can use to prepare OSHA 301 incident reports. An OSHA 301 report is required for each injury or illness that is recorded in the OSHA 300 log.


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
<td><p>HcmOSHA301PrepReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\HcmOSHA301PrepReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>HcmOSHA301PrepReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Workers</strong> &gt; <strong>Regulatory</strong> &gt; <strong>OSHA incidents</strong> &gt; <strong>OSHA 301 preparation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - HRMInjuryIncident table

  - HRMInjuryIncidentTreatment table

  - HcmWorker table

  - HRMInjuryBodyPart table

  - HRMInjuryType table

  - DirPerson table

  - HcmEmployment table

  - HcmPersonPrivateDetails table

  - DirPartyPostalAddressView view, which contains the DirPartyLocation table and the LogisticsPostalAddressView view

  - LogisticsPostalAddressView view, which contains the LogisticsPostalAddress, LogisticsLocation, and LogisticsAddressCountryRegion tables

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

