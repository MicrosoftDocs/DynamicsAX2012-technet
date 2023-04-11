---
title: Credit memo report (RetailCreditVoucherTable)
TOCTitle: Credit memo report (RetailCreditVoucherTable)
ms:assetid: 76e9a4fd-1445-4697-8cff-139e798679ce
ms:mtpsurl: https://technet.microsoft.com/library/Hh697614(v=AX.60)
ms:contentKeyID: 42518423
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RetailCreditVoucherTable
---

# Credit memo report (RetailCreditVoucherTable) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view retail credit memos that have been issued. This report includes detailed transaction information, such as the store number, register, staff member, and receipt number.

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
<td><p><strong>Filter</strong></p></td>
<td><p>Select a filter to apply to the information. The options are <strong>Show all</strong>, <strong>Open</strong>, and <strong>Closed</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Enter the earliest date for the credit memos to include on this report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the latest date for the credit memos to include on this report.</p></td>
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
<td><p>RetailCreditVoucherTable</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RetailCreditVoucherTable</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RetailCreditVoucherTable</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Retail</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Credit memos</strong>. In the <strong>Credit memo table</strong> form, click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - RetailCreditVoucherTable table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


