---
title: Vendor currency revaluation simulation report (VendExchRateAdjSimulation)
TOCTitle: Vendor currency revaluation simulation report (VendExchRateAdjSimulation)
ms:assetid: f1ddea15-c9b2-4954-a8fd-c1e23007b628
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa634262(v=AX.60)
ms:contentKeyID: 36676495
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendExchRateAdjSimulation
---

# Vendor currency revaluation simulation report (VendExchRateAdjSimulation) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view the predicted effect of revaluing foreign currency amounts. In the simulation, you can select values for the same parameters that are available for the revaluation process: **Method**, **Considered date**, and **Date of rate**.

The report lists the open vendor balances on the considered date in the vendor currency and the accounting currency. It also indicates the open balance that would result if currency amounts are revalued according to the entered criteria. The exchange rates that are used in the simulation are listed.

The vendor balances are summed for each foreign currency. This displays the effect of the revaluation on the value of unrealized accounts payable.

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
<td><p><strong>Method</strong></p></td>
<td><p>Select the method to use for the revaluation simulation:</p>
<ul>
<li><p><strong>Standard</strong> – Adjustments for the foreign currency revaluation are posted regardless of whether the result is a profit or a loss.</p></li>
<li><p><strong>Minimum</strong> – Adjustments for the foreign currency revaluation are posted only if the result is a loss.</p></li>
<li><p><strong>Invoice date</strong> – Adjustments for the foreign currency revaluation use the original exchange rate of the transactions, which are revalued to their original value in the accounting currency. The effect of any prior revaluation is canceled.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Considered date</strong></p></td>
<td><p>Select the date when Microsoft Dynamics AX finds all transactions that have open (not settled) amounts on that date. Foreign currency revaluations are made by using the exchange rates that are entered in the <strong>Currency exchange rates</strong> form for the considered date.</p>
<div class="alert">

> [!NOTE]
> <P>The foreign currency revaluation simulation does not create any adjustment transactions.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Date of rate</strong></p></td>
<td><p>Select the date that determines the exchange rate that is used in the foreign currency revaluation simulation. If this field is blank, the exchange rate that applies to the date in the <strong>Considered date</strong> field is used in the revaluation.</p></td>
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
<td><p>VendExchRateAdjSimulation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendExchRateAdjSimulation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendExchRateAdjSimulation</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Periodic</strong> &gt; <strong>Foreign currency revaluation</strong>. Click <strong>Simulation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendExchRateAdjSimulationTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the VendExchRateAdjSimulationDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[About foreign currency revaluations for open vendor transactions](about-foreign-currency-revaluations-for-open-vendor-transactions.md)

  


