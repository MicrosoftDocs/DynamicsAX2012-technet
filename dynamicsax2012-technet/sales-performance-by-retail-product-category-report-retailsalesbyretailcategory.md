---
title: Sales performance by retail product category report (RetailSalesByRetailCategory)
TOCTitle: Sales performance by retail product category report (RetailSalesByRetailCategory)
ms:assetid: 218ae9af-21c2-4186-824c-5cf7a1bc59f9
ms:mtpsurl: https://technet.microsoft.com/library/Hh697604(v=AX.60)
ms:contentKeyID: 42518405
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RetailSalesByRetailCategory
- MsDynAx060.SSRS_Reports.Reports.RetailSalesByRetailCategory
---

# Sales performance by retail product category report (RetailSalesByRetailCategory) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Use this report to view and compare sales performance by retail product category during periods that you specify. The retail product categories are based on the retail product hierarchy that is defined for your organization. This report includes the sales quantity, sales amount, profit margin, and profit percentage. This report is only available to users who are assigned to the Merchandising manager role.


> [!NOTE]
> <P>This report can also be accessed in Enterprise Portal for Microsoft Dynamics AX. When you access the report in Enterprise Portal, the following sections of this topic do not apply:</P>
> <UL>
> <LI>
> <P>How to filter the data on this report</P>
> <LI>
> <P>How to work with reports</P></LI></UL>



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
<td><p>Select the sort order for the sales performance data on the report. You can sort the data by <strong>Sales amount</strong>, <strong>Gross profit margin</strong>, or <strong>Sales quantity</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Enter the earliest date for the sales performance data to include on this report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the latest date for the sales performance data to include on this report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Printer</strong></p></td>
<td><p>The printer that is currently selected. To select a different printer, click <strong>Destinations ...</strong>. This field is blank if <strong>Screen</strong> is selected in the <strong>Print destination</strong> field.</p></td>
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
<td><p>RetailSalesByRetailCategory</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RetailSalesByRetailCategory</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RetailSalesByRetailCategory</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Retail</strong> &gt; <strong>Reports</strong> &gt; <strong>Sales performance by retail product category</strong>.</p>
<p>To access the report from Enterprise Portal, click the <strong>Retail</strong> tab. Under <strong>Reports</strong>, click the <strong>Performance by retail category</strong> report. Specify a date range by using the <strong>From date</strong> and <strong>To date</strong> fields, and then click <strong>View report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - CUSTINVOICETRANSEXPANDED table

  - RETAILCATEGORYEXPANDED table (Enterprise Portal only)

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


