---
title: (RUS) Deferrals transaction listing report (RDeferralsTransactionListing)
TOCTitle: (RUS) Deferrals transaction listing report (RDeferralsTransactionListing)
ms:assetid: 3957b6e0-9c8b-4825-a3df-b28eb063075b
ms:mtpsurl: https://technet.microsoft.com/library/Dn126097(v=AX.60)
ms:contentKeyID: 52075232
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RDeferralsTransactionListing
---

# (RUS) Deferrals transaction listing report (RDeferralsTransactionListing) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The Deferrals transaction listing report displays the deferral transactions for a deferral model. The deferral transactions are categorized by deferral group. The data on the report includes deferral transaction details, such as the date, type, description, and amount of each transaction. It also includes the name of the deferral, the status, the initial amount, and the depreciated amount. Accountants generate this report periodically to view a list of the deferral transactions.

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
<td><p><strong>Model number</strong></p></td>
<td><p>Select the model number of a deferral.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reporting date</strong></p></td>
<td><p>Select the date to generate the report for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Exclude zero turnovers</strong></p></td>
<td><p>Select this check box to exclude deferrals that have a net book value of zero from this report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Transaction date</strong></p></td>
<td><p>The date when the transaction is posted.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Deferral ID</strong></p></td>
<td><p>The identification code of the deferral.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date attached</strong></p></td>
<td><p>The date when the deferral is created.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Expense code</strong></p></td>
<td><p>The expense code of the deferrals.</p></td>
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
<td><p>RDeferralsTransactionListing</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RDeferralsTransactionListing</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RDeferralsTransactionListing</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Deferrals transaction listing</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RDeferralsTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the RDeferralsTransactionListingDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Set up a deferrals model](rus-set-up-a-deferrals-model.md)

[(RUS) Deferrals (form)](https://technet.microsoft.com/library/jj923560\(v=ax.60\))

[(RUS) Deferrals models (form)](https://technet.microsoft.com/library/jj678655\(v=ax.60\))

  


