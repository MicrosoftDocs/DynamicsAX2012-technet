---
title: (RUS) Advance holder balance report (EmplBalance_RU)
TOCTitle: (RUS) Advance holder balance report (EmplBalance_RU)
ms:assetid: 31ced6dc-c493-47df-b2b3-904bdee57727
ms:mtpsurl: https://technet.microsoft.com/library/JJ992742(v=AX.60)
ms:contentKeyID: 51739430
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.EmplBalance_RU
---

# (RUS) Advance holder balance report (EmplBalance\_RU) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The Advance holder balance report displays the balances of amounts that are paid to advance holders in an organization. Accountants generate this report periodically or daily to review and monitor the debts of an advance holder.

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
<td><p><strong>To date:</strong></p></td>
<td><p>Select the date on which to generate the advance holder amount balance report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Currency distribution</strong></p></td>
<td><p>Select this check box to display the advance holder amount balance grouped by currency code.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Worker ID</strong></p></td>
<td><p>The identification number of the employee about whom the advance holder amount balance is displayed.</p></td>
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
<td><p>EmplBalance_RU</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\EmplBalance_RU</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>EmplBalance_RU</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Advance holder</strong> &gt; <strong>Advance holder balance</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - EmplBalanceTmp\_RU
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the EmplBalanceDP_RU.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Set up the advance holder](rus-set-up-the-advance-holder.md)

[(RUS) Close balances for an advance holder](rus-close-balances-for-an-advance-holder.md)

[(RUS) Advance holder transactions report (EmplTransList\_RU)](rus-advance-holder-transactions-report-empltranslist-ru.md)

  


