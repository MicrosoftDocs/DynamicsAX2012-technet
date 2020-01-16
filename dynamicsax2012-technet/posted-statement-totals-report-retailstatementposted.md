---
title: Posted statement totals report (RetailStatementPosted)
TOCTitle: Posted statement totals report (RetailStatementPosted)
ms:assetid: a1046724-c07d-45a7-8d8c-1169f8fd11e0
ms:mtpsurl: https://technet.microsoft.com/library/Hh697684(v=AX.60)
ms:contentKeyID: 42518432
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RetailStatementPosted
---

# Posted statement totals report (RetailStatementPosted) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Use this report to view the transactions that are included in a posted statement. This report includes the terminal number, payment method, card number if applicable, currency, transaction amount, counted amount, and the amount of the transaction that was deposited in the safe or the bank, if applicable.

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
<td><p>RetailStatementPosted</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RetailStatementPosted</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RetailStatementPosted</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Retail</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Posted statements</strong>. In the <strong>Statement journal</strong> form, click <strong>Reports</strong> &gt; <strong>Statement</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - RetailStatementJour table

  - RetailStatementTrans table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


