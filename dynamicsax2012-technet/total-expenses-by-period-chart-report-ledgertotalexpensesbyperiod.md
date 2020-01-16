---
title: Total expenses by period chart report (LedgerTotalExpensesByPeriod)
TOCTitle: Total expenses by period chart report (LedgerTotalExpensesByPeriod)
ms:assetid: 93b4f3ab-3d50-480a-b316-92ee6b2a5ba9
ms:mtpsurl: https://technet.microsoft.com/library/Hh692469(v=AX.60)
ms:contentKeyID: 41702366
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerTotalExpensesByPeriod
---

# Total expenses by period chart report (LedgerTotalExpensesByPeriod) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this chart report to view the total expenses by period, in a graphical format.

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
<td><p>LedgerTotalExpensesByPeriod</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\LedgerTotalExpensesByPeriod</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerTotalExpenseByPeriod</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>This report is available on the Accounting Manager Role Center.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - BICOMPANYVIEW table

  - GENERALJOURNALCUBE table

  - LEDGERPERIODDATEDIMENSIONVIEW table

  - MAINACCOUNTCUBE table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


