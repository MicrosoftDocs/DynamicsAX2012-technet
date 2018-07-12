---
title: Customer relationship management cube (smmCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack
TOCTitle: Customer relationship management cube (smmCube)
ms:assetid: c6373462-f3a4-4c66-b15f-51f3e7069639
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh781075(v=AX.60)
ms:contentKeyID: 43894474
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Customer relationship management cube (smmCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack 


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the Customer relationship management cube to report on sales transactions.

## Configuration keys

The following configuration keys are required to use all features of the Customer relationship management cube:

  - General ledger (LedgerBasic)

  - Leads (SmmLead)

  - Quotations (QuotationBasic)

  - Project I (ProjBasic)

## Tables and views

The Customer relationship management cube uses data from the following tables and views:

  - smmActivites table

  - smmActivityPhaseGroup table

  - smmActivityPlanGroup table

  - smmActivityTypeGroup table

  - smmBusSectorGroup table

  - smmCampaignGroup table

  - smmCampaignReasonGroup table

  - smmCampaignTargetTable table

  - smmCampaignTypeGroup table

  - smmLeadPriorityTable table

  - smmLeadRatingTable table

  - smmLeadTypeTable table

  - smmQuotationCompetitorGroup table

  - smmQuotationProbabilityGroup table

  - smmQuotationPrognosisGroup table

  - smmQuotationReasonGroup table

  - smmResponsibilityGroup table

  - smmSalesUnit table

  - smmSourceTypeTable table

  - smmCampaignView view

  - smmCustBusRelView view

  - smmLeadByCampaignView view

  - smmLeadView view

  - smmOpportunityByCampaignView view

  - smmOpportunityByCompetitorView view

  - smmOpportunityView view

  - smmProcessStageTemplateView view

  - smmProjectSalesView view

  - smmSalesTargetTransView view

## Measures

The Customer relationship management cube includes the following measure groups.

## Activity

This measure group is based on the SMMActivities table and includes the following measures.

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
<p>Phase for quotation</p>
<p>Activity plan table</p>
<p>Activity type</p>
<p>Responsibility table</p>
<p>Activities</p>
<p>Date (activities – end date time)</p>
<p>Date (activities – start date time)</p>
<p>Worker (activities – done by worker</p>
<p>Worker (activities – worker responsible)</p>
<p>Date (date opened)</p>
<p>Date (date closed)</p>
<p>Date</p></td>
</tr>
</tbody>
</table>


## Competitor group

This measure group is based on the SMMQuotationCompetitorGroup table and includes the following measures.

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
<td><p>Competitor group count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>The number of competitors.</p></td>
<td><p>Company</p>
<p>Competitor</p>
<p></p></td>
</tr>
</tbody>
</table>


## Leads by campaigns

This measure group is based on the SMMLeadByCampaignView view and includes the following measures.

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
<td><p>Leads by campaigns count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>The number of leads by campaign.</p></td>
<td><p>Company</p>
<p>Campaign</p>
<p></p></td>
</tr>
</tbody>
</table>


## Opportunities by campaigns

This measure group is based on the SMMOpportunityByCampaignView view and includes the following measures.

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
   
	 Opportunities by campaigns count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of opportunities by campaign.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Campaign
  </p> <p>
   
	 Date (date opened)
  </p> <p>
   
	 Date
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Opportunities by campaigns estimated revenue
  </p> </td>
    <td colspan="1"> <p>
   
	 SMMOpportunityByCampaignView.Estimated_Revenue
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The estimated revenue on opportunities from campaigns.
  </p> </td>
  </tr>
</table>


## Opportunities by competitor group

This measure group is based on the SMMOpportunityByCompetitorView view and includes the following measures.

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
   
	 Opportunities by competitor group count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of opportunities by competitor group.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Competitor
  </p> <p>
   
	 Opportunities by competitor group
  </p> <p>
   
	 Date (date opened)
  </p> <p>
   
	 Date
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Opportunities by competitor group estimated revenue
  </p> </td>
    <td colspan="1"> <p>
   
	 SMMOpportunityByCompetitorView.EstimatedRevenue
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The estimated revenue on opportunities by competitor group.
  </p> </td>
  </tr>
</table>


## Sales

This measure group is based on the SMMProjectSalesView view and includes the following measures.

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
   
	 Sales count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of sales.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Sales management units
  </p> <p>
   
	 Customers - prospects
  </p> <p>
   
	 Date (sales – invoice date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Date
  </p> <p>
   
	 Worker (sales – sales person)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Invoice revenue
  </p> </td>
    <td colspan="1"> <p>
   
	 SMMProjectSalesView.InvoiceRevenue
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The total invoiced revenue.
  </p> </td>
  </tr>
</table>


## Lead

This measure group is based on the SMMLeadView view and includes the following measures.

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
   
	 Lead rating
  </p> <p>
   
	 Source type
  </p> <p>
   
	 Quotation reason
  </p> <p>
   
	 Sales management units
  </p> <p>
   
	 Process stage
  </p> <p>
   
	 Customers - prospects
  </p> <p>
   
	 Lead
  </p> <p>
   
	 Worker (lead – closed by worker)
  </p> <p>
   
	 Worker (lead – opened by worker)
  </p> <p>
   
	 Worker (lead – owner)
  </p> <p>
   
	 Date (date opened)
  </p> <p>
   
	 Date (date closed)
  </p> <p>
   
	 Date
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Days to close lead
  </p> </td>
    <td colspan="1"> <p>
   
	 SMMLeadView.DaysToClose
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
   
	 SMMLeadView.DaysOpened
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

This measure group is based on the SMMOpportunityView view and includes the following measures.

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
   
	 Quotation probability
  </p> <p>
   
	 Quotation prognosis
  </p> <p>
   
	 Quotation reason
  </p> <p>
   
	 Sales management units
  </p> <p>
   
	 Process stage
  </p> <p>
   
	 Customers - prospects
  </p> <p>
   
	 Opportunity
  </p> <p>
   
	 Worker (worker – responsible – owner)
  </p> <p>
   
	 Worker (opportunity – owner)
  </p> <p>
   
	 Worker (opportunity – opened by worker)
  </p> <p>
   
	 Worker (opportunity – close by worker)
  </p> <p>
   
	 Date (date opened)
  </p> <p>
   
	 Date (date closed)
  </p> <p>
   
	 Date
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Days to close opportunity
  </p> </td>
    <td colspan="1"> <p>
   
	 SMMOpportunityView.DaysToClose
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
   
	 SMMOpportunityView.DaysOpened
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
   
	 Actual revenue
  </p> </td>
    <td colspan="1"> <p>
   
	 SMMOpportunityView.ActualRevenue
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
   
	 SMMOpportunityView.Estimated_Revenue
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
   
	 SMMOpportunityView.OpportunityWon
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
   
	 SMMOpportunityView.OpportunityLost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of opportunities lost.
  </p> </td>
  </tr>
</table>


## Sales targets transactions

This measure group is based on the SMMSalesTargetTransView view and includes the following measures.

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
   
	 Sales targets transactions count
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
   
	 Sales targets transactions
  </p> <p>
   
	 Date (sales target transactions – target date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Worker (sales target transactions – sales person)
  </p> <p>
   
	 Date
  </p> <p>
   
	 Worker (sales – sales person)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sales targets transactions amount
  </p> </td>
    <td> <p>
   
	 SMMSalesTargetTransView.AmountMst
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

This measure group is based on the SMMCampaignView view and includes the following measures.

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
<td><p>Campaign count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>The number of campaigns.</p></td>
<td><p>Company</p>
<p>Process stage</p>
<p>Campaign</p>
<p>Date (campaign date)</p>
<p>Date (campaign – end date)</p>
<p>Date (campaign – follow-up date)</p>
<p>Worker (campaign – worker responsible)</p>
<p>Worker (campaign – worker)</p>
<p>Date</p></td>
</tr>
</tbody>
</table>


## Customers - prospects

This measure group is based on the SMMCustBusRelView view and includes the following measures.

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
<td><p>Customers – prospects count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>The number of prospects.</p></td>
<td><p>Currency</p>
<p>Company</p>
<p>Customers - prospects</p>
<p>Date (created date)</p>
<p>Worker (customer – prospect – worker responsible)</p></td>
</tr>
</tbody>
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
<p>Analysis currency</p>
<p>Date</p></td>
</tr>
</tbody>
</table>


## Calculated measures

The Customer relationship management cube contains the following calculated measures.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Calculated measure</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Average opportunity days open</p></td>
<td><p>Average</p></td>
<td><p>The average number of days that opportunity records are open.</p></td>
</tr>
<tr class="even">
<td><p>Average days to close opportunity</p></td>
<td><p>Average</p></td>
<td><p>The average number of days that it takes to close an opportunity record.</p></td>
</tr>
<tr class="odd">
<td><p>Opportunity win loss percentage</p></td>
<td><p>Sum</p></td>
<td><p>The percentage of won opportunities.</p></td>
</tr>
<tr class="even">
<td><p>Average lead days open</p></td>
<td><p>Average</p></td>
<td><p>The average number of days that a lead record is open.</p></td>
</tr>
<tr class="odd">
<td><p>Average days to close lead</p></td>
<td><p>Average</p></td>
<td><p>The average number of days that it takes to close a lead record.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The following sections describe the key performance indicators (KPIs) in the Customer relationship management cube.

## KPI calculations

The following table lists the KPIs that are associated with the Customer relationship management cube. You can use the information in the following table to help verify the information in your KPIs.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>KPI</p></th>
<th><p>Calculation</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Active Leads</p></td>
<td><p>Lead count where Lead Status = 0 (Open)</p></td>
</tr>
<tr class="even">
<td><p>Active Opportunities</p></td>
<td><p>Opportunity count where Opportunity Status = 1 (None)</p></td>
</tr>
<tr class="odd">
<td><p>New Leads</p></td>
<td><p>Lead count in the past 7 days</p></td>
</tr>
<tr class="even">
<td><p>New Opportunities</p></td>
<td><p>Opportunity count in the past 7 days</p></td>
</tr>
<tr class="odd">
<td><p>Sales</p></td>
<td><p>Project and customer invoice sales total</p></td>
</tr>
</tbody>
</table>


## Role Centers

The following table lists the Role Centers and web parts that display the KPIs associated with the Customer relationship management cube.

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

The Customer relationship management cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Chief executive officer

  - Marketing coordinator

  - Marketing manager

  - Sales manager

  - Sales representative

  


