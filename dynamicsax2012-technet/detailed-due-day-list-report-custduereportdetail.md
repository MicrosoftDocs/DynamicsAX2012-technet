---
title: Detailed due day list report (CustDueReportDetail)
TOCTitle: Detailed due day list report (CustDueReportDetail)
ms:assetid: 25d1fbdc-60fc-4a54-ba5f-8524d9ffb05d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551818(v=AX.60)
ms:contentKeyID: 36057470
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustDueReportDetail
---

# Detailed due day list report (CustDueReportDetail) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Detailed due day list** report displays a detailed list of customer payments that are due on a specific date.

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
<td><p><strong>Billing classification</strong></p></td>
<td><p>Select one or more billing classifications to include on the report.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Include transactions without a billing classification</strong></p></td>
<td><p>If this check box is selected, all transactions that do not have a billing classification assigned to them will appear on the report.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>As on</strong></p></td>
<td><p>Select a date to determine which customer payments to include on the report. Any transactions that are due on or before the date are included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customers</strong></p></td>
<td><p>The information displayed in this section is determined by your selections when you create a query.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer transactions</strong></p></td>
<td><p>The information displayed in this section is determined by your selections when you create a query.</p></td>
</tr>
<tr class="even">
<td><p><strong>Open customer transactions</strong></p></td>
<td><p>The information displayed in this section is determined by your selections when you create a query.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Current print destination</strong></p></td>
<td><p>The information displayed in this section is determined by your selections when you set up printing options.</p></td>
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
<td><p>CustDueReportDetail</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustDueReportDetail</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustDueReportDetail</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Detailed due day list</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustTable table

  - CustTrans table

  - CustTransOpen table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

