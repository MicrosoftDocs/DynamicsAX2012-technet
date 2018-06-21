---
title: Payment advice report (BankPaymAdviceCheque)
TOCTitle: Payment advice report (BankPaymAdviceCheque)
ms:assetid: 9a09b812-818c-4ddd-853d-b5f7f404657f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa617011(v=AX.60)
ms:contentKeyID: 37832024
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankPaymAdviceCheque
---

# Payment advice report (BankPaymAdviceCheque) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view check number and bank account information about a payment.


> [!TIP]
> <P>The payment advice can be printed when checks are printed. Select the <STRONG>Payment advice</STRONG> check box in the <STRONG>Payment by check</STRONG> form.</P>
> <P>If you do not want the report to display payment transactions for which reversals have been entered but not yet posted, create a query where the <STRONG>Pending cancellation</STRONG> field is set to <STRONG>No</STRONG>.</P>



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
<td><p>BankPaymAdviceCheque</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankPaymAdviceCheque</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankPaymAdviceCheque</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Cash and bank management</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Payment advice</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankPaymAdviceChequeTmp table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Vendor payment by check (form)](https://technet.microsoft.com/en-us/library/bb220751\(v=ax.60\))

[Add additional tables to advanced queries](add-additional-tables-to-advanced-queries.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

