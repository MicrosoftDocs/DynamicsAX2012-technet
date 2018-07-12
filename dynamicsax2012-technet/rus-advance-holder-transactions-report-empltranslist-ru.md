---
title: (RUS) Advance holder transactions report (EmplTransList_RU)
TOCTitle: (RUS) Advance holder transactions report (EmplTransList_RU)
ms:assetid: d646f8e4-9c91-4ec1-aa9b-8277dd885671
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ945855(v=AX.60)
ms:contentKeyID: 51543175
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.EmplTransList_RU
---

# (RUS) Advance holder transactions report (EmplTransList\_RU) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The Advance holder transactions report displays the expense transactions of an employee and the amounts that are paid in advance to that employee. Accountants generate this report periodically or daily to review and monitor the advance transactions between an employee and the legal entity.

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
<td><p><strong>Main accounts only</strong></p></td>
<td><p>Select this check box to display only main accounts on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Employee</strong></p></td>
<td><p>The identification number of the employee about whom the transaction report is generated.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Advance holder</strong></p></td>
<td><p>The identification number of the advance holder for whom the transactions are posted.</p></td>
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
<td><p>EmplTransList_RU</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\EmplTransList_RU</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>EmplTransList_RU</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Advance holder</strong> &gt; <strong>Advance holder transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - EmployeeTable\_RU table

  - EmplTrans\_RU table

  - MainAccountLedgerDimensionView table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(EEUR) Balance (form)](https://technet.microsoft.com/en-us/library/jj910984\(v=ax.60\))

[(RUS) Advance holder transactions (form)](https://technet.microsoft.com/en-us/library/jj733234\(v=ax.60\))

  


