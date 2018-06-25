---
title: Vendor/Item statistics report (PurchStatisticsVendItem)
TOCTitle: Vendor/Item statistics report (PurchStatisticsVendItem)
ms:assetid: f67bcf67-4415-4fd5-bede-9ac45c8bbbda
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227637(v=AX.60)
ms:contentKeyID: 36060835
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.PurchStatisticsVendItem
- vendor statistics report by item
- vendor/item
---

# Vendor/Item statistics report (PurchStatisticsVendItem) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Vendor/Item statistics** report displays a summary of products that your organization has purchased from each vendor during the date range that you specify. You can specify a second date range for comparison purposes.

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
<td><p><strong>From date:</strong></p></td>
<td><p>In the <strong>Period 1:</strong> section, enter the start date of the first date range for which you want to view transactions.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date:</strong></p></td>
<td><p>Enter the end date of the first date range.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date:</strong></p></td>
<td><p>In the <strong>Period 2:</strong> section, enter the start date of the comparative date range.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date:</strong></p></td>
<td><p>Enter the end date of the comparative date range.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Item</strong></p></td>
<td><p>The items whose transactions you want to include on the report. Click <strong>Select</strong> to select items.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor account</strong></p></td>
<td><p>The vendor accounts whose transactions you want to include on the report. Click <strong>Select</strong> to select vendor accounts.</p></td>
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
<td><p>PurchStatisticsVendItem</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ PurchStatisticsVendItem</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PurchStatistics_VendItem</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Vendor</strong> &gt; <strong>Vendor/Item statistics</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PurchVendItemStatisticsTmp table

  - VendInvoiceJour table

  - VendInvoiceTrans table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the PurchVendItemStatisticsDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

