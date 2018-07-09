---
title: Sales performance by sales category report (RetailSalesBySalesCategory)
TOCTitle: Sales performance by sales category report (RetailSalesBySalesCategory)
ms:assetid: 79e14d92-5b49-4d70-887e-c2489fb1ded7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh697615(v=AX.60)
ms:contentKeyID: 42518424
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RetailSalesBySalesCategory
---

# Sales performance by sales category report (RetailSalesBySalesCategory) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Use this report to view and compare sales performance by sales category during periods that you specify. The sales category is based on the default sales category hierarchy. This report includes the sales quantity, sales amount, profit margin, and profit percentage. This report is only available to users who are assigned to the Merchandising manager role.


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
<td><p>Select the sort order for the sales performance data on the report. Select one of the following options:</p>
<ul>
<li><p><strong>Sales amount</strong></p></li>
<li><p><strong>Gross profit margin</strong></p></li>
<li><p><strong>Sales quantity</strong></p></li>
</ul></td>
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
<td><p>RetailSalesBySalesCategory</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RetailSalesBySalesCategory</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RetailSalesBySalesCategory</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p><strong>Retail</strong> &gt; <strong>Reports</strong> &gt; <strong>Sales performance by sales category</strong></p>
<p>To access the report from Enterprise Portal, click the <strong>Retail</strong> tab. Under <strong>Reports</strong>, click the <strong>Performance by sales category</strong> report. Specify a date range by using the <strong>From date</strong> and <strong>To date</strong> fields, and then click <strong>View report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - CUSTINVOICETRANSEXPANDED table

  - ECORESSALESCATEGORYEXPANDED table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

