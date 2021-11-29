---
title: Budget control cube (BudgetControlCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Budget control cube (BudgetControlCube)
ms:assetid: 644eb8b0-ee0c-4723-9bce-0fd2315cffef
ms:mtpsurl: https://technet.microsoft.com/library/JJ710392(v=AX.60)
ms:contentKeyID: 49384283
author: Khairunj
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Budget control cube (BudgetControlCube) for Microsoft Dynamics AX 2012 R2 and R3 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Budget control cube for Microsoft Dynamics AX is used to analyze data from budget register entries. Analysis of this data helps organizations effectively manage their approved budgets and make decisions based on accurate information. This article provides details about the cube.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/JJ710380.TopicIcons_Reference(AX.60).png" title="Reference" alt="Reference" />
<p>Deployment</p>
<p>Configuration keys</p>
<p>Tables and views</p>
<p>Measures</p>
<p>Calculated measures</p>
<p>Key performance indicators</p>
<p>Security</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-r2-and-r3.md">Cube and KPI reference for Microsoft Dynamics AX 2012 R2 and R3</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md">Cube and KPI reference for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack</a></p></td>
</tr>
</tbody>
</table>


## Deployment

The Budget control cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Budget control cube:

  - Budget control (LedgerAdv2BudgetCtrl)

## Tables and views

The Budget control cube uses data from the following tables and views:

  - BudgetControlConfigurationCube view

  - BudgetSourceTrackingCube view

## Measures

The Budget control cube includes the following measure groups.

## Budget control amounts

This measure group is based on the BudgetSourceTrackingCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Amount
  </p> </td>
    <td> <p>
   
	 BudgetSourceTrackingCube.TrackingDetailAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The budgeted amount, in the accounting currency.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Budget control configuration
  </p> <p>
   
	 Budget control
  </p> <p>
   
	 Company
  </p> <p>
   
	 Chart of accounts
  </p> <p>
   
	 Ledger derived financial attribute value combinations
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Fiscal period date (transaction date – fiscal calendar
  </p> <p>
   
	 Date (transaction date)
  </p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Relieved amount
  </p> </td>
    <td> <p>
   
	 BudgetSourceTrackingCube.TrackingRelievedDetailAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The relieved budgeted amount, in the accounting currency.
  </p> </td>
  </tr>
</table>


## Exchange rates by day

This measure group is based on the BIExchangeRateView view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Exchange rate</p></td>
<td><p>BIExchangeRateView.CrossRate</p></td>
<td><p>Max</p></td>
<td><p>The exchange rate.</p></td>
<td><p>Currency</p>
<p>Date (exchange rate date)</p>
<p>Analysis currency</p></td>
</tr>
</tbody>
</table>


## Calculated measures

The Budget control cube contains the following calculated measures.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Calculated measure</p></th>
<th><p>Aggregation</p></th>
<th><p>Associated measure group</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Original budget</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The budget register entries that have the following budget type: Original budget, Fixed asset, Project, Demand, and Supply and have a budget register entry status = Confirmed.</p>
<p>Fixed asset, project, demand, and supply transaction types are used when transferring budget from either Fixed assets, Project, or Inventory, and are treated as original budget amounts. For example, when budget transactions of these types are checked for budget control, they are translated to the original budget category.</p></td>
</tr>
<tr class="even">
<td><p>Completed revisions</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The budget register entries with the transaction type = Revision, and that have a budget register entry status = Confirmed.</p></td>
</tr>
<tr class="odd">
<td><p>Draft revisions</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The budget register entries with the transaction type = Revision, and that have a budget register entry status = Draft.</p></td>
</tr>
<tr class="even">
<td><p>Total revisions</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The sum of completed and draft budget revisions.</p></td>
</tr>
<tr class="odd">
<td><p>Completed budget transfers</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The budget register entries with the budget type = Transfer, and that have a budget register entry status = Confirmed.</p></td>
</tr>
<tr class="even">
<td><p>Draft budget transfers in</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The budget register entries with the transaction type = Transfer, have a budget register entry status = Draft, and the impact to budget is an increase.</p></td>
</tr>
<tr class="odd">
<td><p>Draft budget transfers out</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The budget register entries with the budget type = Transfer, have a budget register entry status = Draft, and the impact to budget is a decrease.</p></td>
</tr>
<tr class="even">
<td><p>Total transfers</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The sum of completed budget transfers, draft budget transfers in, and draft budget transfers out.</p></td>
</tr>
<tr class="odd">
<td><p>Total revised budget</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The sum of original budget, total revisions, and total transfers.</p></td>
</tr>
<tr class="even">
<td><p>Posted actual expenditures</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The vendor invoices and expense reports that have been recorded in the subledger journal, as well as accounting journals that have been posted. The amounts for the source documents and accounting journals are only included in the budget check when the corresponding document type is enabled for budget control. For these source documents and accounting journals the actual expense is recorded in the ledger at this time.</p></td>
</tr>
<tr class="odd">
<td><p>Unposted actual expenditures</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The vendor invoices and expense reports that have been entered, but not yet recorded in the subledger journal. This also includes accounting journals that have been entered, but not yet posted to ledger. The amounts for the source documents and accounting journals are only included in the budget check when the corresponding document type or accounting journal is enabled for budget control.</p></td>
</tr>
<tr class="even">
<td><p>Total actual expenditures</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The sum of posted and unposted actual expenditures.</p></td>
</tr>
<tr class="odd">
<td><p>Confirmed encumbrances</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The budget reservations that are created for confirmed purchase orders or travel requests. This also includes budget register entries that are in a status of Confirmed and utilize the budget type of Encumbrance (manual reservations of budget created through budget register entries).</p></td>
</tr>
<tr class="even">
<td><p>Unconfirmed encumbrances</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The budget reservations that are created for unconfirmed purchase orders or travel requests. This also includes budget register entries that are in a status of Draft and utilize the budget type of Encumbrance (manual reservations of budget created through budget register entries that are not yet included in the overall budget balance).</p></td>
</tr>
<tr class="odd">
<td><p>Unconfirmed encumbrance reductions</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The correction made to a confirmed purchase order, and that change results in a decrease to the original budget reservation related to the purchase order amounts and accounts.</p></td>
</tr>
<tr class="even">
<td><p>Total budget reservations for encumbrances</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The sum of confirmed and unconfirmed encumbrances and unconfirmed reductions.</p></td>
</tr>
<tr class="odd">
<td><p>Confirmed pre-encumbrances</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The budget reservations that are created for approved or confirmed purchase requisitions. This also includes budget register entries that are in a status of Confirmed and utilize the budget type of Pre-encumbrance.</p></td>
</tr>
<tr class="even">
<td><p>Unconfirmed pre-encumbrances</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The budget reservations that are created for unconfirmed and unapproved purchase requisitions. This also includes budget register entries that are in a status of Draft and utilize the budget type of Pre-encumbrance (manual reservations of budget created through budget register entries that are not yet included in the overall budget balance).</p></td>
</tr>
<tr class="odd">
<td><p>Total budget reservations for pre-encumbrances</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The sum of confirmed and unconfirmed pre-encumbrances.</p></td>
</tr>
<tr class="even">
<td><p>Carry-forward revised budget amount</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The revised budget amounts that were carried forward as part of the purchase order year-end process, or budget register entries that use a budget type of Carry Forward.</p></td>
</tr>
<tr class="odd">
<td><p>Carry-forward encumbrances amount</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The encumbrance amounts that were carried forward as part of the purchase order year-end process, or budget transactions that use a transaction type of Carry Forward.</p></td>
</tr>
<tr class="even">
<td><p>Carry-forward actual expenditures amount</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The actual expenditure amounts that were carried forward as part of the purchase order year-end process, or budget register entries that use a budget type of Carry Forward.</p></td>
</tr>
<tr class="odd">
<td><p>Total carry-forward budget amounts</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The sum of revised, encumbrance, and actual expenditure carry-forward amounts.</p></td>
</tr>
<tr class="even">
<td><p>Budget funds available</p></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The remaining balance of a budget using the formula defined on the budget control configuration.</p></td>
</tr>
<tr class="odd">
<td><p>Carry-forward budget</p>
<div class="alert">

> [!NOTE]
> <P>This calculated measure is available only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>Sum</p></td>
<td><p>Budget control amounts</p></td>
<td><p>The original budget amounts that were carried forward as part of the purchase order year end process or budget register entries that use a budget type of Carry Forward.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The Budget control cube does not include any key performance indicators (KPIs).

## Security

The Budget control cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Accounting manager

  - Accounting supervisor

  - Budget manager

  - Chief executive officer

  - Chief financial officer

  - Compliance manager

  - Financial controller

  


