---
title: (CAN, USA) Gross margin by customer report (CustGrossMarginbyAccount_NA)
TOCTitle: (CAN, USA) Gross margin by customer report (CustGrossMarginbyAccount_NA)
ms:assetid: 08527508-5d90-4046-b5d8-eab397e5f0b7
ms:mtpsurl: https://technet.microsoft.com/library/Hh433478(v=AX.60)
ms:contentKeyID: 36941238
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustGrossMarginbyAccount_NA
---

# (CAN, USA) Gross margin by customer report (CustGrossMarginbyAccount\_NA) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Gross margin by customer** report displays sales order information, including the item number, item description, quantity, sales amount, cost, gross profit, and gross profit percentage, for individual customers. This information is sorted by customer name and customer number. You can choose to display either summarized or detailed information based on your selection in the **Summary** field. This report is typically used by accounting managers, accounts receivable managers, chief executive officers, chief financial officers, compliance managers, and financial controllers to review invoice and cash process performance.


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
<td><p><strong>Summary</strong></p></td>
<td><p>Select this check box to display only a summary of sales order information for each customer. Clear this check box to include detailed information for each sales order. By default, the check box is not selected.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer account</strong></p></td>
<td><p>The customer account that is used to generate the sales order.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales order</strong></p></td>
<td><p>The sales order number that is included in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date</strong></p></td>
<td><p>The sales order transaction date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Item</strong></p></td>
<td><p>The identification of the item that the sales order is generated for.</p></td>
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
<td><p>CustGrossMarginbyAccount_NA</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustGrossMarginbyAccount_NA</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustGrossMarginbyAccount_NA</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Customer</strong> &gt; <strong>Gross margin by customer</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustGrossMarginbyAccount\_NA table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


