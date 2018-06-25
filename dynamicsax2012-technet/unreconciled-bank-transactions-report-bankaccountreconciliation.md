---
title: Unreconciled bank transactions report (BankAccountReconciliation)
TOCTitle: Unreconciled bank transactions report (BankAccountReconciliation)
ms:assetid: 0079ae9f-77f2-4ac1-b847-b4027448c295
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa548475(v=AX.60)
ms:contentKeyID: 36931891
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankAccountReconciliation
---

# Unreconciled bank transactions report (BankAccountReconciliation) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to show and print information about bank transactions that are not reconciled.


> [!TIP]
> <P>If you do not want the report to display payment transactions for which reversals have been entered but not yet posted, create a query where the <STRONG>Pending cancellation</STRONG> field in the <STRONG>Bank transactions</STRONG> table is set to <STRONG>No</STRONG>.</P>



You can reconcile bank statements with bank transactions in Microsoft Dynamics AX by using the **Account reconciliation** form.

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
<td><p>BankAccountReconciliation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankAccountReconciliation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankAccountNonReconciled</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Cash and bank management</strong> &gt; <strong>Reports</strong> &gt; <strong>Reconciliation</strong> &gt; <strong>Unreconciled bank transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankAccountTable table

  - BankAccountTrans table

  - DimensionAttributeValueCombination table

  - MainAccount table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Reconcile a bank account](reconcile-a-bank-account.md)

[Add additional tables to advanced queries](add-additional-tables-to-advanced-queries.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

