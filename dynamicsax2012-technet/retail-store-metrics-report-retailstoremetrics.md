---
title: Retail store metrics report (RetailStoreMetrics)
TOCTitle: Retail store metrics report (RetailStoreMetrics)
ms:assetid: 33813c84-b933-4db7-ac28-16655cccdce7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh697610(v=AX.60)
ms:contentKeyID: 42518414
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RetailStoreMetrics
- MsDynAx060.SSRS_Reports.Reports.RetailStoreMetrics
---

# Retail store metrics report (RetailStoreMetrics) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Use this report to view the performance of your retail stores by organization unit. The organization unit is based on the default reporting hierarchy. This report includes the sales quantity and amount by store, and the profit margin for each store.

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
<td><p><strong>Sort by</strong></p></td>
<td><p>Select how to sort the store metric data on the report. Select one of the following options:</p>
<ul>
<li><p><strong>Sales amount</strong></p></li>
<li><p><strong>Gross profit margin</strong></p></li>
<li><p><strong>Sales quantity</strong></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Enter the earliest date for the store metrics to include on this report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the latest date for the store metrics to include on this report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Printer</strong></p></td>
<td><p>The printer that is currently selected. To select a different printer, click <strong>Destinations ...</strong>.</p>
<p>This field is blank if <strong>Screen</strong> is selected in the <strong>Print destination</strong> field.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Print destination</strong></p></td>
<td><p>The destination where the report is produced. Click <strong>Destinations ...</strong> to change the destination for the report.</p></td>
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
<td><p>RetailStoreMetrics</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RetailStoreMetrics</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RetailStoreMetrics</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Retail</strong> &gt; <strong>Reports</strong> &gt; <strong>Retail store metrics</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - CUSTINVOICETRANSEXPANDED table

  - RETAILOMHIERARCHYVIEW table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


