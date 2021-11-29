---
title: Intercompany goods in transit transactions report (InterCompanyGoodsInTransitTransactions)
TOCTitle: Intercompany goods in transit transactions report (InterCompanyGoodsInTransitTransactions)
ms:assetid: 8df7de28-ac55-4720-bcae-1ca2a15000a5
ms:mtpsurl: https://technet.microsoft.com/library/Hh227393(v=AX.60)
ms:contentKeyID: 36059639
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.InterCompanyGoodsInTransitTransactions
---

# Intercompany goods in transit transactions report (InterCompanyGoodsInTransitTransactions) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Intercompany goods in transit transactions** report to identify all sales packing slips and all purchase product receipts for intercompany goods that are in transit. This report assumes that intercompany goods in transit are always owned by the buyer. It can be reconciled against the **Intercompany goods in transit totals** report.

This report displays all shipment to and receipts from in transit for a specific period. You can export the details to Excel and manually create appropriate groupings and subtotals. It is also possible to use pivot table capabilities. The report also displays a calculated inventory value, liability, and variance to standard cost.

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
<td><p>Date interval code</p></td>
<td><p>Select the time interval you want to print from the list of date interval codes. You can select from various time intervals including one-month periods, years, and quarters. These intervals can be either previous or upcoming.</p></td>
</tr>
<tr class="even">
<td><p>From date</p></td>
<td><p>When you select a date interval code, the system populates the <strong>From date</strong> field. You can also enter a specific from date.</p></td>
</tr>
<tr class="odd">
<td><p>To date</p></td>
<td><p>When you select a date interval code, the system populates the <strong>To date</strong> field. You can also enter a specific to date.</p></td>
</tr>
<tr class="even">
<td><p>In transit time fence in days</p></td>
<td><p>The number of days in advance of the from date that the report uses to identify if a shipment or receipt that affects in transit is included in the report.</p></td>
</tr>
<tr class="odd">
<td><p>Deduct in transit quantity variance</p></td>
<td><p>Select this check box to deduct the in transit quantity variance from the in transit quantity.</p></td>
</tr>
<tr class="even">
<td><p>Vendor account</p></td>
<td><p>Click <strong>Select</strong> to indicate one or more specific vendors for the report.</p></td>
</tr>
<tr class="odd">
<td><p>Vendor company</p></td>
<td><p>By default, the vendor company is currently selected.</p></td>
</tr>
<tr class="even">
<td><p>Active</p></td>
<td><p>Click <strong>Select</strong> to indicate the status of the trading relationship between the partners.</p></td>
</tr>
<tr class="odd">
<td><p>Customer company</p></td>
<td><p>Click <strong>Select</strong> to indicate one or more specific customers for the report.</p></td>
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
<td><p>InterCompanyGoodsInTransitTransactions</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InterCompanyGoodsInTransitTransactions</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InterCompanyGoodsInTransitTransactions</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Inventory value</strong> &gt; <strong>Intercompany goods in transit transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - InterCompanyGoodsInTransitOrdersTmp table

  - InterCompanyGoodsInTransitTmp table


> [!NOTE]
> <P>To learn where the data in the temp tables comes from, view the cross-references for the InterCompanyGoodsInTransitTransDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


