---
title: Expense management cube (TrvCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Expense management cube (TrvCube)
ms:assetid: a5fb1a49-4f5c-4247-8a07-ddfeb168cedd
ms:mtpsurl: https://technet.microsoft.com/library/JJ710395(v=AX.60)
ms:contentKeyID: 49384287
author: Khairunj
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Expense management cube (TrvCube) for Microsoft Dynamics AX 2012 R2 and R3 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Expense management cube for Microsoft Dynamics AX is used to report on expense reports and policy violations. This article provides details about the cube.

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

The Expense management cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Expense management cube:

  - Travel and expense (Trv)

  - Per diems (TrvPerDiem)

## Tables and views

The Expense management cube uses data from the following tables and views:

  - TrvCostType table

  - TrvCostTypeStatistics table

  - TrvDestinations table

  - TrvExpMerchant table

  - TrvPayMethod table

  - TrvTravelTxt table

  - TrvCategoryCube view

  - TrvDisputesCube view

  - TrvExpDistributionsCube view

  - TrvExpTableCube view

  - TrvExpTransCube view

  - TrvPolicyRuleCube view

  - TrvPolicyViolationsLogCube view

  - TrvRequisitionLineCube view

## Measures

The Expense management cube includes the following measure groups.

## Expense report

This measure group is based on the TrvExpTableCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
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
   
	 Expense report count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count 
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of expense reports.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Travel locations
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Expense report
  </p> <p>
   
	 Date (creation date time – date)
  </p> <p>
   
	 Date (posted date)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Posted expense reports
  </p> </td>
    <td colspan="1"> <p>
   
	 TrvExpTableCube.Posted
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of expense reports that have been posted.
  </p> </td>
  </tr>
</table>


## Policy violations log

This measure group is based on the TrvPolicyViolationsLogCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
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
   
	 Policy violations approved
  </p> </td>
    <td colspan="1"> <p>
   
	 TrvPolicyViolationsLogCube.PolicyViolationApproved
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of approved policy violations.
  </p> </td>
    <td rowspan="3"> <p>
   
	 Company
  </p> <p>
   
	 Policy
  </p> <p>
   
	 Payment method
  </p> <p>
   
	 Expense category
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (creation date time – date)
  </p> <p>
   
	 Worker (worker – rejected by)
  </p> <p>
   
	 Date (violation date)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Policy violations returned
  </p> </td>
    <td colspan="1"> <p>
   
	 TrvPolicyViolationsLogCube.PolicyViolationReturned
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of rejected policy violations.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Policy violations
  </p> </td>
    <td> <p>
   
	 TrvPolicyViolationsLogCube.PolicyViolationTotal
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of policy violations.
  </p> </td>
  </tr>
</table>


## Travel requisition lines

This measure group is based on the TrvRequisitionLineCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
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
   
	 Travel requisition lines count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count 
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of travel requisition lines.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Travel requisition lines
  </p> <p>
   
	 Date (estimated date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Estimated amount
  </p> </td>
    <td colspan="1"> <p>
   
	 TrvRequisitionLineCube.AccountingCurrencyAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The estimated value, in the accounting currency, of a set of travel requisition lines.
  </p> </td>
  </tr>
</table>


## Expense lines

This measure group is based on the TrvExpTransCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
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
   
	 Expense lines count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count 
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of expense line records.
  </p> </td>
    <td rowspan="9"> <p>
   
	 Company
  </p> <p>
   
	 Payment method
  </p> <p>
   
	 Merchant
  </p> <p>
   
	 Expense category
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Expense lines
  </p> <p>
   
	 Date (transaction date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Expense report amount paid by company
  </p> </td>
    <td colspan="1"> <p>
   
	 TrvExpTransCube.AmountMSTPaidByCompany
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The amount paid by the company, in the accounting currency, for a set of expense lines.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Expense report amount paid by worker
  </p> </td>
    <td colspan="1"> <p>
   
	 TrvExpTransCube.AmountMSTPaidByEmployee
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The amount paid by the employee, in the accounting currency, for a set of expense lines.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Expense amount
  </p> </td>
    <td> <p>
   
	 TrvExpTransCube.ExpenseAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total amount, in the accounting currency, for a set of expense lines.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Cash advance amount
  </p> </td>
    <td> <p>
   
	 TrvExpTransCube.CashAdvanceAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The amount of cash advances, in the accounting currency, for a set of expense lines.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Per diem amount
  </p> </td>
    <td> <p>
   
	 TrvExpTransCube.PerDiemAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The amount of per diem, in the accounting currency, for a set of expense lines.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Mileage amount
  </p> </td>
    <td> <p>
   
	 TrvExpTransCube.MileageAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The value of mileage, in the accounting currency, for a set of expense lines.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Miles traveled
  </p> </td>
    <td> <p>
   
	 TrvExpTransCube.MilesTraveled
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of miles traveled for a set of expense lines.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Expense report amount
  </p> </td>
    <td> <p>
   
	 TrvExpTransCube.AmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The value, in the accounting currency, for a set of expense lines.
  </p> </td>
  </tr>
</table>


## Disputes

This measure group is based on the TrvDisputesCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th> <p>
   
	 Aggregation
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 Disputes count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of credit card disputes.
  </p> </td>
    <td rowspan="3"> <p>
   
	 Company
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Disputes
  </p> <p>
   
	 Date (creation date time – date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Amount
  </p> </td>
    <td> <p>
   
	 TrvDisputesCube.AmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The value, in the accounting currency, of a set of credit card disputes.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Days taken to reach resolution
  </p> </td>
    <td> <p>
   
	 TrvDisputesCube.TimeToReachResolution
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of days taken to resolve a set of credit card disputes.
  </p> </td>
  </tr>
</table>


## Expense distributions

This measure group is based on the TrvExpDistributionsCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
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
   
	 Expense distributions count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count 
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of the distribution lines on the expense report.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Shared category
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Expense distributions
  </p> <p>
   
	 Date (transaction date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Projects (projects)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Expense distribution amount
  </p> </td>
    <td colspan="1"> <p>
   
	 TrvExpDistributionsCube.AccountingCurrencyAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The sum of the amounts of the distribution lines on the expense report.
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

The Expense management cube contains the following calculated measures.

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
<td><p>Average expense report total billed amount</p></td>
<td><p>Average</p></td>
<td><p>Expense lines</p></td>
<td><p>The average amount, per expense report, for posted expense reports.</p></td>
</tr>
<tr class="even">
<td><p>Average expense report amount paid by company</p></td>
<td><p>Average</p></td>
<td><p>Expense lines</p></td>
<td><p>The average amount paid by the company, per expense report, for posted expense reports.</p></td>
</tr>
<tr class="odd">
<td><p>Average expense report amount paid by employee</p></td>
<td><p>Average</p></td>
<td><p>Expense lines</p></td>
<td><p>The average amount paid by an employee, per expense report, for posted expense reports.</p></td>
</tr>
<tr class="even">
<td><p>Average policy violations per expense report</p></td>
<td><p>Average</p></td>
<td><p>Policy violations log</p></td>
<td><p>The average number of policy violations, per expense report, for posted expense reports.</p></td>
</tr>
<tr class="odd">
<td><p>Average approved policy violations per expense report</p></td>
<td><p>Average</p></td>
<td><p>Policy violations log</p></td>
<td><p>The average number of approved policy violations, per expense report, for posted expense reports.</p></td>
</tr>
<tr class="even">
<td><p>Average returned policy violations per expense report</p></td>
<td><p>Average</p></td>
<td><p>Policy violations log</p></td>
<td><p>The average number of returned policy violations, per expense report, for posted expense reports.</p></td>
</tr>
<tr class="odd">
<td><p>Percent change in expense report totals</p></td>
<td><p>Sum</p></td>
<td><p>Expense lines</p></td>
<td><p>The percentage change in total amount, in the accounting currency, of expense reports between the current and previous time period.</p></td>
</tr>
<tr class="even">
<td><p>Average days taken to reach resolution</p></td>
<td><p>Average</p></td>
<td><p>Disputes</p></td>
<td><p>The average number of days between when a credit card dispute was filed and when the dispute was closed.</p></td>
</tr>
<tr class="odd">
<td><p>Average expense line amount</p></td>
<td><p>Average</p></td>
<td><p>Expense lines</p></td>
<td><p>The average amount of an expense line in a given time period.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The following section describes the key performance indicators (KPIs) in the Expense management cube.

## KPI calculations

The following table lists the KPIs that are associated with the Expense management cube. You can use the information in the following table to help verify the information in your KPIs.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>KPI</p></th>
<th><p>Associated measure group</p></th>
<th><p>Calculation</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expenses trend</p></td>
<td><p>Expense lines</p></td>
<td><p>The percentage change in total expense amount.</p></td>
</tr>
<tr class="even">
<td><p>Policy violations approved per expense report</p></td>
<td><p>Policy violations log</p></td>
<td><p>The policy violations log count where action taken = 1 (approved by all approvers), 5 (approved by some approvers).</p></td>
</tr>
</tbody>
</table>


## Role Centers

By default, the KPIs of the Expense management cube are not displayed on Role Center pages. For information about how to add them to Role Center pages, see [Manage KPIs](manage-kpis.md).

## Security

The Expense management cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Accounts payable clerk

  - Accounts payable manager

  - Chief executive officer

  - Chief financial officer

  - Financial controller

  - Project manager

  


