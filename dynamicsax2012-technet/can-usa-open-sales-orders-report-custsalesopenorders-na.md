---
title: (CAN, USA) Open sales orders report (CustSalesOpenOrders_NA)
TOCTitle: (CAN, USA) Open sales orders report (CustSalesOpenOrders_NA)
ms:assetid: d95822bb-8106-4bdf-b0d2-2380481c712a
ms:mtpsurl: https://technet.microsoft.com/library/Hh209661(v=AX.60)
ms:contentKeyID: 36060591
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Open
- SSRS_Reports.Reports.CustSalesOpenOrders_NA
- Sales order
---

# (CAN, USA) Open sales orders report (CustSalesOpenOrders\_NA) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Open sales orders** report displays information about open sales orders. An open sales order has one or more items that have been ordered by the customer but have not yet been shipped. This report is typically used by CFOs, CEOs, Accounts Receivable managers, and accountants to review customer invoices.


> [!NOTE]
> <P>(CAN, USA) This report is available only to legal entities whose primary address is in Canada or the United States.</P>



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
<td><p><strong>Status</strong></p></td>
<td><p>The status of the sales order.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales order</strong></p></td>
<td><p>The identification number of the sales order.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Ship date</strong></p></td>
<td><p>The date when the selling company must ship the order to meet the customer's requested receipt date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer account</strong></p></td>
<td><p>The identification number of the customer account that the sales order is generated for.</p></td>
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
<td><p>CustSalesOpenOrders_NA</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustSalesOpenOrders_NA</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustSalesOpenOrders_NA</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Reports</strong> &gt; <strong>Sales orders</strong> &gt; <strong>Open sales orders</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustSalesOpenOrders\_NA table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


