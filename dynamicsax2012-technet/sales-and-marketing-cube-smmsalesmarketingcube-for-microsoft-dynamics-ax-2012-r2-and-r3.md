---
title: Sales and marketing cube (smmSalesMarketingCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Sales and marketing cube (smmSalesMarketingCube)
ms:assetid: 1e93656f-ee61-4b52-a0c5-c6000b73b1e7
ms:mtpsurl: https://technet.microsoft.com/library/JJ710384(v=AX.60)
ms:contentKeyID: 49384276
author: tonyafehr
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Sales and marketing cube (smmSalesMarketingCube) for Microsoft Dynamics AX 2012 R2 and R3 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Sales and marketing cube for Microsoft Dynamics AX is used to report on sales transactions. This article provides details about the cube.

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

The Sales and marketing cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Sales and marketing cube:

  - General ledger (LedgerBasic)

  - Leads (smmLead)

  - Quotations (QuotationBasic)

  - Project I (ProjBasic)

## Tables and views

The Sales and marketing cube uses data from the following tables and views:

  - smmBusSectorGroup table

  - smmLeadPriorityTable table

  - smmLeadRatingTable tabe

  - smmLeadTypeTable table

  - smmQuotationProbabilityGroup table

  - smmQuotationPrognosisGroup table

  - smmSalesUnit table

  - smmSourceTypeTable table

  - ProjTransPostingCube view

  - smmActivitiesCube view

  - smmCampaignView view

  - smmCustBusRelView view

  - smmCustInvoiceJourSalesView view

  - smmLeadView view

  - smmOpportunityView view

  - smmProcessStageTemplateView view

  - smmProjectSalesView view

  - smmQuotationView view

  - smmSalesTargetTransView view

## Measures

The Sales and marketing cube includes the following measure groups.

## Project sales order

This measure group is based on the ProjTransPostingCube view and includes the following measures.

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
   
	 Project sales order count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of sales orders of type project.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Activity
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Projects
  </p> <p>
   
	 Date (date – date)
  </p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Project sales revenue
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualRevenue
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total revenue for sales orders of type project.
  </p> </td>
  </tr>
</table>


## Sales order

This measure group is based on the smmCustInvoiceJourSalesView view and includes the following measures.

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
   
	 Sales order count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of sales orders of type sales.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Campaign
  </p> <p>
   
	 Customer - prospect
  </p> <p>
   
	 Sales quotation
  </p> <p>
   
	 Sales management units
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (date – date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Sales order revenue
  </p> </td>
    <td colspan="1"> <p>
   
	 smmCustInvoiceJourSalesView.InvoiceRevenue
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The total invoiced revenue of type sales.
  </p> </td>
  </tr>
</table>


## Sales

This measure group is based on the smmProjectSalesView view and includes the following measures.

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
<td><p>Sales count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>The number of invoices for both sales and project.</p></td>
<td><p>Company</p>
<p>Sales management units</p>
<p>Worker</p>
<p>Date (sales – invoice date)</p>
<p>Date (sales target – target date)</p>
<p>Worker (sales – sales person)</p></td>
</tr>
<tr class="even">
<td><p>Invoice revenue</p></td>
<td><p>smmProjectSalesView.InvoiceRevenue</p></td>
<td><p>Sum</p></td>
<td><p>The total invoiced amount for both sales and project.</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Sales target

This measure group is based on the smmSalesTargetTransView view and includes the following measures.

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
   
	 Sales target count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of sales target transactions.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Sales management units
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (sales target – target date)
  </p> <p>
   
	 Worker (sales – sales person)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sales targets transactions amount
  </p> </td>
    <td> <p>
   
	 smmSalesTargetTransView.AmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The amount of sales target transactions.
  </p> </td>
  </tr>
</table>


## Campaign

This measure group is based on the smmCampaignView view and includes the following measures.

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
   
	 Campaign count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of campaigns.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Campaign
  </p> <p>
   
	 Process stage
  </p> <p>
   
	 Activity
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Projects
  </p> <p>
   
	 Date (date – date)
  </p> <p>
   
	 Projects (projects – parent project)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual campaign cost
  </p> </td>
    <td> <p>
   
	 smmCampaignView.ActualCostCommitted
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The posted project expenses for the campaign.
  </p> </td>
  </tr>
</table>


## Customer - prospect

This measure group is based on the smmCustBusRelView view and includes the following measures.

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
<td><p>Customer – prospect count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>The number of prospects.</p></td>
<td><p>Currency</p>
<p>Company</p>
<p>Customer - prospect</p>
<p>Worker</p>
<p>Date (date – date opened)</p></td>
</tr>
</tbody>
</table>


## Lead

This measure group is based on the smmLeadView view and includes the following measures.

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
   
	 Lead count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of lead records.
  </p> </td>
    <td rowspan="3"> <p>
   
	 Company
  </p> <p>
   
	 Lead type
  </p> <p>
   
	 Lead priority
  </p> <p>
   
	 Source type
  </p> <p>
   
	 Lead rating
  </p> <p>
   
	 Campaign
  </p> <p>
   
	 Customer - prospect
  </p> <p>
   
	 Lead
  </p> <p>
   
	 Process stage
  </p> <p>
   
	 Sales management units
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (date – date)
  </p> <p>
   
	 Worker (worker – opened by)
  </p> <p>
   
	 Worker (worker – closed by)
  </p> <p>
   
	 Date (date – date opened)
  </p> <p>
   
	 Date (date – date closed)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Days to close lead
  </p> </td>
    <td colspan="1"> <p>
   
	 smmLeadView.DaysToClose
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of days to close a lead record.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Days opened lead
  </p> </td>
    <td colspan="1"> <p>
   
	 smmLeadView.DaysOpened
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of days a lead record has been open.
  </p> </td>
  </tr>
</table>


## Opportunity

This measure group is based on the smmOpportunityView view and includes the following measures.

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
   
	 Opportunity count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of opportunity records.
  </p> </td>
    <td rowspan="7"> <p>
   
	 Company
  </p> <p>
   
	 Source type
  </p> <p>
   
	 Campaign
  </p> <p>
   
	 Customer - prospect
  </p> <p>
   
	 Process stage
  </p> <p>
   
	 Opportunity
  </p> <p>
   
	 Quotation probability
  </p> <p>
   
	 Quotation prognosis
  </p> <p>
   
	 Sales management units
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (date – date)
  </p> <p>
   
	 Worker (worker – opened by)
  </p> <p>
   
	 Worker (worker – salesperson – owner)
  </p> <p>
   
	 Worker (worker – closed by)
  </p> <p>
   
	 Date (date – date opened)
  </p> <p>
   
	 Date (date – date closed)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Days to close opportunity
  </p> </td>
    <td colspan="1"> <p>
   
	 smmOpportunityView.DaysToClose
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of days to close an opportunity record.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Days opened opportunity
  </p> </td>
    <td colspan="1"> <p>
   
	 smmOpportunityView.DaysOpened
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of days that an opportunity record has been open.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Actual revenue gained from opportunity
  </p> </td>
    <td colspan="1"> <p>
   
	 smmOpportunityView.ActualRevenue
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The total invoiced revenue for the opportunity.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Estimated revenue
  </p> </td>
    <td colspan="1"> <p>
   
	 smmOpportunityView.Estimated_Revenue
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The total opportunity estimated revenue.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Opportunity won
  </p> </td>
    <td colspan="1"> <p>
   
	 smmOpportunityView.OpportunityWon
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of opportunities won.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Opportunity lost
  </p> </td>
    <td> <p>
   
	 smmOpportunityView.OpportunityLost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of opportunities lost.
  </p> </td>
  </tr>
</table>


## Activity

This measure group is based on the smmActivitiesCube view and includes the following measures.

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
<td><p>Activity count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>The number of activities.</p></td>
<td><p>Company</p>
<p>Activity</p>
<p>Worker</p>
<p>Date (date – date opened)</p>
<p>Date (date – date closed)</p>
<p>Date (date – start date)</p>
<p>Date (date – end date)</p></td>
</tr>
</tbody>
</table>


## Sales quotation

This measure group is based on the smmQuotationView view and includes the following measures.

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
   
	 Sales quotation count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of sales quotations.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Campaign
  </p> <p>
   
	 Customer - prospect
  </p> <p>
   
	 Opportunity
  </p> <p>
   
	 Sales quotation
  </p> <p>
   
	 Sales management units
  </p> <p>
   
	 Worker
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Sales quotation amount
  </p> </td>
    <td colspan="1"> <p>
   
	 smmQuotationView.LineAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The total amount of sales quotations.
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

The Sales and marketing cube contains the following calculated measures.

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
<td><p>Average opportunity open days</p></td>
<td><p>Average</p></td>
<td><p>Opportunity</p></td>
<td><p>The average number of days that an opportunity record is open.</p></td>
</tr>
<tr class="even">
<td><p>Average days to close opportunity</p></td>
<td><p>Average</p></td>
<td><p>Opportunity</p></td>
<td><p>The average number of days that it takes to close an opportunity record.</p></td>
</tr>
<tr class="odd">
<td><p>Opportunity win loss percentage</p></td>
<td><p>Sum</p></td>
<td><p>Opportunity</p></td>
<td><p>The percentage of won opportunities.</p></td>
</tr>
<tr class="even">
<td><p>Average lead open days</p></td>
<td><p>Average</p></td>
<td><p>Lead</p></td>
<td><p>The average number of days that a lead record is open.</p></td>
</tr>
<tr class="odd">
<td><p>Average days to close lead</p></td>
<td><p>Average</p></td>
<td><p>Lead</p></td>
<td><p>The average number of days that it takes to close a lead record.</p></td>
</tr>
<tr class="even">
<td><p>Average sales order amount</p></td>
<td><p>Average</p></td>
<td><p>Sales order</p></td>
<td><p>The average value of sales orders.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The following sections describe the key performance indicators (KPIs) in the Sales and marketing cube.

## KPI calculations

The following table lists the KPIs that are associated with the Sales and marketing cube. You can use the information in the following table to help verify the information in your KPIs.

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
<td><p>Active leads</p></td>
<td><p>Lead</p></td>
<td><p>Lead count where Lead Status = 0 (Open).</p></td>
</tr>
<tr class="even">
<td><p>Active opportunities</p></td>
<td><p>Opportunity</p></td>
<td><p>Opportunity count where Opportunity Status = 1 (None).</p></td>
</tr>
<tr class="odd">
<td><p>New leads</p></td>
<td><p>Lead</p></td>
<td><p>Lead count in the past 7 days.</p></td>
</tr>
<tr class="even">
<td><p>New opportunities</p></td>
<td><p>Opportunity</p></td>
<td><p>Opportunity count in the past 7 days.</p></td>
</tr>
<tr class="odd">
<td><p>Sales</p></td>
<td><p>Sales order</p></td>
<td><p>Project and customer invoice sales total.</p></td>
</tr>
<tr class="even">
<td><p>Average sales order amount</p></td>
<td><p>Sales order</p></td>
<td><p>Total sales orders (including project) divided by the number of sales orders.</p></td>
</tr>
</tbody>
</table>


## Role Centers

The following table lists the Role Centers and web parts that display the KPIs associated with the Sales and marketing cube.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Role Center</p></th>
<th><p>Web parts and KPIs</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sales and marketing executive</p></td>
<td><p>Business overview:</p>
<ul>
<li><p>Sales</p></li>
<li><p>Average days to close opportunity</p></li>
<li><p>New leads</p></li>
<li><p>Average days to close lead</p></li>
<li><p>New opportunities</p></li>
<li><p>Opportunities per segment</p></li>
</ul>
<p>KPI list:</p>
<ul>
<li><p>New opportunities</p></li>
<li><p>Active opportunities</p></li>
<li><p>New leads</p></li>
<li><p>Active leads</p></li>
<li><p>Sales per sales unit</p></li>
<li><p>Sales per salesperson</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Sales manager</p></td>
<td><p>Business overview:</p>
<ul>
<li><p>Sales</p></li>
<li><p>Average days to close opportunity</p></li>
<li><p>New leads</p></li>
<li><p>Average days to close lead</p></li>
<li><p>New opportunities</p></li>
<li><p>Opportunities per segment</p></li>
</ul>
<p>KPI list:</p>
<ul>
<li><p>New opportunities</p></li>
<li><p>Active opportunities</p></li>
<li><p>New leads</p></li>
<li><p>Active leads</p></li>
<li><p>Sales per sales unit</p></li>
<li><p>Sales per salesperson</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Super sales representative</p></td>
<td><p>KPI list:</p>
<ul>
<li><p>New leads</p></li>
<li><p>Active leads</p></li>
<li><p>New opportunities</p></li>
<li><p>Active opportunities</p></li>
<li><p>Sales per sales unit</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Dedicated sales representative</p></td>
<td><p>KPI list:</p>
<ul>
<li><p>New leads</p></li>
<li><p>Active leads</p></li>
<li><p>New opportunities</p></li>
<li><p>Active opportunities</p></li>
<li><p>Sales per sales unit</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Marketing manager</p></td>
<td><p>Business overview:</p>
<ul>
<li><p>Sales</p></li>
<li><p>New leads</p></li>
<li><p>Average days to close lead</p></li>
<li><p>Opportunities per segment</p></li>
<li><p>Leads per segment</p></li>
</ul>
<p>KPI list:</p>
<ul>
<li><p>New leads</p></li>
<li><p>Active leads</p></li>
<li><p>Sales per sales unit</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Marketing staffer</p></td>
<td><p>KPI list:</p>
<ul>
<li><p>New leads</p></li>
<li><p>Active leads</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Account manager</p></td>
<td><p>KPI list:</p>
<ul>
<li><p>New opportunities</p></li>
<li><p>Active opportunities</p></li>
<li><p>Sales per sales unit</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Security

The Sales and marketing cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Chief executive officer

  - Marketing coordinator

  - Marketing manager

  - Sales manager

  - Sales representative

  


