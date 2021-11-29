---
title: Project prices report (ProjPriceList)
TOCTitle: Project prices report (ProjPriceList)
ms:assetid: 882240d3-7198-42cc-ac79-cd01a3b4f6ca
ms:mtpsurl: https://technet.microsoft.com/library/Aa598065(v=AX.60)
ms:contentKeyID: 37832018
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjPriceList
---

# Project prices report (ProjPriceList) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view the sales prices that are set up for hours, fees, expenses, and subscriptions.

You can set up a standard sales price for transactions, or you can set up sales prices by employee number, project number, category, transaction date, or any combination of these options.

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
<td><p><strong>Sales price - hour</strong></p></td>
<td><p>Select whether to display the sales price that is applied when a worker enters a transaction in an hour journal.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales price - expense</strong></p></td>
<td><p>Select whether to display the sales price that is applied when a worker enters a transaction in an expense journal.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales price - fee</strong></p></td>
<td><p>Select whether to display the sales price that is applied when a worker enters a transaction in a fee journal.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales price - subscription</strong></p></td>
<td><p>Select whether to display the sales price that is applied for a subscription. For more information, see <a href="about-subscription-sales-prices.md">About subscription sales prices</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Price group</strong></p></td>
<td><p>Select a price group. Only projects associated with the selected price group are displayed on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales currency</strong></p></td>
<td><p>Select a sales currency. Only projects associated with the selected sales currency are displayed on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Category</strong></p></td>
<td><p>Select a project category. Only projects associated with the selected project category are displayed on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Worker</strong></p></td>
<td><p>Select the name of a worker. Only projects to which the worker is assigned are displayed on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Subscription</strong></p></td>
<td><p>Select a subscription ID. Only projects associated with the selected subscription are displayed on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Effective date</strong></p></td>
<td><p>Select a date on which the sales price is valid.</p></td>
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
<td><p>ProjPriceList</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjPriceList</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjPriceList</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Prices</strong> &gt; <strong>Project prices</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjPriceListDP.processReport

  - TmpProjPriceList table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjPriceListDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Sales price - Subscription (form)](https://technet.microsoft.com/library/aa583956\(v=ax.60\))

[Sales price - fee (form)](https://technet.microsoft.com/library/aa575091\(v=ax.60\))

[Sales price - expenses (form)](https://technet.microsoft.com/library/aa599787\(v=ax.60\))

[Sales price - hour (form)](https://technet.microsoft.com/library/aa634053\(v=ax.60\))

  


