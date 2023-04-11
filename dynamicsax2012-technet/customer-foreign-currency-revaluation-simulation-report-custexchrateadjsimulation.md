---
title: Customer foreign currency revaluation simulation report (CustExchRateAdjSimulation)
TOCTitle: Customer foreign currency revaluation simulation report (CustExchRateAdjSimulation)
ms:assetid: b8a5e236-7d2f-49a6-813e-69c94064b139
ms:mtpsurl: https://technet.microsoft.com/library/Aa556586(v=AX.60)
ms:contentKeyID: 37832030
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustExchRateAdjSimulation
---

# Customer foreign currency revaluation simulation report (CustExchRateAdjSimulation) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report that to view the predicted effect of revaluing the amounts of transactions that use currencies other than the accounting currency. In the simulation, you can select values for the same parameters that are available for the revaluation: **Method**, **Considered date**, and **Date of rate**. For information about these fields, see [Customer foreign currency revaluation (form)](https://technet.microsoft.com/library/aa586009\(v=ax.60\)).

The report lists the open customer balances on the considered date in the customer currency and the accounting currency. The report also lists the open balance that would result if a foreign currency revaluation is run according to the criteria that is entered. The exchange rates that are used in the simulation are also listed.

The report displays the total of the customer balances for each foreign currency. The balances show the effect of the revaluation of the value of unrealized accounts receivable.

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
<td><p>CustExchRateAdjSimulation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustExchRateAdjSimulation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustExchRateAdjSimulation</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Periodic</strong> &gt; <strong>Foreign currency revaluation</strong>. Click <strong>Simulation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustExchRateAdjSimulationTmp table

  - DimensionAttributeValueCombination table

  - VendExchRateAdjustmentTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the CustExchRateAdjSimulationDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[About foreign currency revaluations for open customer transactions](about-foreign-currency-revaluations-for-open-customer-transactions.md)

  


