---
title: Intercompany goods in transit totals report (InterCompanyGoodsInTransitTotals)
TOCTitle: Intercompany goods in transit totals report (InterCompanyGoodsInTransitTotals)
ms:assetid: 8525b0a9-c307-4a48-8ffa-25b742f83c2e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227356(v=AX.60)
ms:contentKeyID: 36059555
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.InterCompanyGoodsInTransitTotals
---

# Intercompany goods in transit totals report (InterCompanyGoodsInTransitTotals) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Intercompany goods in transit totals** report to create a general ledger entry for the value of intercompany goods in transit for a specific period. By doing this, it will offset the existing balance for the main account. The report assumes that intercompany goods in transit are always owned by the buyer.

The report displays a period starting balance, a period ending balance, and the net change for a specific period. The balances and net change are printed per item and grouped by vendor. This allows you to manually enter general ledger data directly from the report totals without requiring you to export to Excel or to create Excel aggregations. The report also displays a calculated inventory value, liability, and variance to standard cost.

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
<td><p>InterCompanyGoodsInTransitTotals</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InterCompanyGoodsInTransitTotals</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InterCompanyGoodsInTransitTotals</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Inventory value</strong> &gt; <strong>Intercompany goods in transit totals</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - InterCompanyGoodsInTransitOrdersTmp table

  - InterCompanyGoodsInTransitTmp table


> [!NOTE]
> <P>To learn where the data in the temp tables comes from, view the cross-references for the InterCompanyGoodsInTransitTotalsDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

