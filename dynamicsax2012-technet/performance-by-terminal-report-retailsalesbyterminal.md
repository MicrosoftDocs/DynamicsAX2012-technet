---
title: Performance by terminal report (RetailSalesByTerminal)
TOCTitle: Performance by terminal report (RetailSalesByTerminal)
ms:assetid: 1e68ac2c-64a8-441b-ad82-6016a7670ef8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ851126(v=AX.60)
ms:contentKeyID: 50173435
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Performance by terminal report (RetailSalesByTerminal) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this report to identify the retail terminals that are performing the best within an operating unit, based on the date range and filter criteria that you specify. The terminal performance ranking is based on the quantity sold, sales revenue, and profit margin for the terminal. You can use this report to determine the proper placement of product assortments in your retail channels.


> [!NOTE]
> <P>This report can also be accessed in Enterprise Portal for Microsoft Dynamics AX, and the report data is filtered by store. When you access the report in Enterprise Portal, the following sections of this topic do not apply:</P>
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
<td><p><strong>From date</strong></p></td>
<td><p>Enter the earliest date for which to include terminal performance data on this report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the latest date for which to include terminal performance data on this report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>POS registers</strong></p></td>
<td><p>Select one or more point of sale registers to include on this report.</p></td>
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
<td><p>RetailSalesByTerminal</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RetailSalesByTerminal</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RetailSalesByTerminal</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Retail</strong> &gt; <strong>Reports</strong> &gt; <strong>Performance by terminal</strong>.</p>
<p>To access the report from Enterprise Portal, click the <strong>Retail</strong> tab. Under <strong>Reports</strong>, click the <strong>Performance by terminal</strong> report. Specify a date range by using the <strong>From date</strong> and <strong>To date</strong> fields, select one or more point of sale registers in the <strong>POS registers</strong> field, and then click <strong>View report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

