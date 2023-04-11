---
title: Sales order report (SalesHeading)
TOCTitle: Sales order report (SalesHeading)
ms:assetid: 4b6e4df8-6d90-4db1-96f7-9059810091b2
ms:mtpsurl: https://technet.microsoft.com/library/Aa576308(v=AX.60)
ms:contentKeyID: 36058504
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.SalesHeading
---

# Sales order report (SalesHeading) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Sales order** report to print a list of sales orders sorted by customer.

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
<td><p>Forms</p></td>
<td><p>Select this check box to print information about the customer’s <strong>Last packing slip</strong> and <strong>Last invoice</strong> for a specific sales order.</p></td>
</tr>
<tr class="even">
<td><p>Totals</p></td>
<td><p>Select this check box to print information about the <strong>Invoiced amount</strong>, <strong>Ordered, not invoiced</strong>, and <strong>Margin, not invoiced</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Customer account</p></td>
<td><p>Click <strong>Select</strong> and then create a query for sales orders for one or more specific customers.</p></td>
</tr>
<tr class="even">
<td><p>Sales order</p></td>
<td><p>Click <strong>Select</strong> and then create a query for one or more specific sales orders.</p></td>
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
<td><p>SalesHeading</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\SalesHeading</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>SalesHeading</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Sales orders</strong> &gt; <strong>Sales order</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustTable table

  - SalesTable table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


