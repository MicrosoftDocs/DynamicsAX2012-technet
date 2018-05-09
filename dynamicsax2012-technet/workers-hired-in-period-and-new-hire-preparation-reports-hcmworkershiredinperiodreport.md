---
title: Workers hired in period and New hire preparation reports (HcmWorkersHiredInPeriodReport)
TOCTitle: Workers hired in period and New hire preparation reports (HcmWorkersHiredInPeriodReport)
ms:assetid: 3bc01d14-2905-4bb1-b0b0-80d19d8e0a50
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn268417(v=AX.60)
ms:contentKeyID: 54916956
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.HcmWorkersHiredInPeriodReport
---

# Workers hired in period and New hire preparation reports (HcmWorkersHiredInPeriodReport) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

There are two versions of the report that you can use to create a list of recently hired workers: **Workers hired in period** and **New hire preparation**.


> [!NOTE]
> <P>The <STRONG>New hire preparation</STRONG> version of this report is available only if you’re using Microsoft Dynamics AX 2012 R3 or cumulative update 6 or later for AX 2012 R2.</P>



The **New hire preparation** version of this report is available only to legal entities in the USA. Organizations in the United States are required to provide a list of newly hired employees to the state in which the employees work. This information is included in the National Directory of New Hires (NDNH). The NDNH provides employment and unemployment insurance information to state Child Support Enforcement (IV-D) agencies. Reporting requirements are determined by the NDNH, but states can also request additional information. The **New hire preparation** report provides information to help you prepare the required report.

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
<td><p>The first date to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>The last date to include in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include contractors</strong></p></td>
<td><p>Select this check box to include contractors in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print social security number</strong></p></td>
<td><p>Select this check box to print the workers’ Social Security numbers on the report.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when you open the form from the <STRONG>New hire preparation</STRONG> link.</P>


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
<td><p>HcmWorkersHiredInPeriodReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\HcmWorkersHiredInPeriodReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>HRMWorkersHiredInPeriod</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Workers</strong> &gt; <strong>Workers hired in period</strong>.</p>
<p>–or–</p>
<p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Workers</strong> &gt; <strong>Regulatory</strong> &gt; <strong>New hire preparation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Data source name</p></th>
<th><p>Data source type</p></th>
<th><p>Additional information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>HcmWorkersHiredInPeriod</p></td>
<td><p>Query</p></td>
<td><p>This query is used to fetch data from the listed database tables and views.</p></td>
</tr>
<tr class="even">
<td><p>HcmEmployment</p></td>
<td><p>Table</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>HcmWorker</p></td>
<td><p>Table</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>DirPerson</p></td>
<td><p>Table</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>HcmPersonPrivateDetails</p></td>
<td><p>Table</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>DirPartyPostalAddress</p></td>
<td><p>View</p></td>
<td><p>This view contains the DirPartyLocation table and the LogisticsPostalAddressView view.</p></td>
</tr>
<tr class="odd">
<td><p>LogisticsPostalAddressView</p></td>
<td><p>View</p></td>
<td><p>This view contains theLogisticsPostalAddress table, the LogisticsLocation table, and the LogisticsAddressCountryRegion table.</p></td>
</tr>
</tbody>
</table>


If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

