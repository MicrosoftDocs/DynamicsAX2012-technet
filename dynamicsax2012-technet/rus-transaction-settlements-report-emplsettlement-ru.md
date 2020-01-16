---
title: (RUS) Transaction settlements report (EmplSettlement_RU)
TOCTitle: (RUS) Transaction settlements report (EmplSettlement_RU)
ms:assetid: fd9f3ccf-cc48-482a-b2bf-990dd315be26
ms:mtpsurl: https://technet.microsoft.com/library/JJ945857(v=AX.60)
ms:contentKeyID: 51543177
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.EmplSettlement_RU
---

# (RUS) Transaction settlements report (EmplSettlement\_RU) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The Transaction settlements report displays cash refunds and advance amounts that are paid to an employee by the legal entity. Accountants generate this report periodically or daily to analyze transactions that occur in multiple currencies between an employee and the legal entity to calculate the debt balance of the employee.

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
<td><p><strong>Worker ID</strong></p></td>
<td><p>Select the identification number of the employee about whom the transaction settlements report is generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select a date up to which the transactions are included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Real-time settlement</strong></p></td>
<td><p>Select this check box to include real-time settlement transactions on the report.</p></td>
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
<td><p>EmplSettlement_RU</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\EmplSettlement_RU</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>EmplSettlement_RU</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Advance holder</strong> &gt; <strong>Transaction settlements</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - EmplSettlement\_RU table

  - EmplTrans\_RU table

  - EmplSettlementTmp\_RU table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the EmplSettlementDP_RU.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(EEUR) Settle advance holder balances](eeur-settle-advance-holder-balances.md)

  


