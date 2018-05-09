---
title: (RUS) Deferrals balances report (RDeferralsBalances)
TOCTitle: (RUS) Deferrals balances report (RDeferralsBalances)
ms:assetid: 810e70fa-1099-4656-ab50-c3b6fff52f98
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Xx187160(v=AX.60)
ms:contentKeyID: 52055989
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RDeferralsBalances
---

# (RUS) Deferrals balances report (RDeferralsBalances) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

Use the Deferrals balances report to view the values of deferrals, such as initial amounts, written off sums, and retirement deferral amounts. Accountants generate this report periodically to analyze the remaining balance of deferrals for the current period, and for future costs.

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
<td><p>Select the model number for which the deferrals balance is included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reporting date</strong></p></td>
<td><p>Enter the date for which the deferrals balance information is included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Exclude zero turnovers</strong></p></td>
<td><p>Select this check box to exclude deferrals that have a net book value of zero.</p></td>
</tr>
<tr class="even">
<td><p><strong>Deferral ID</strong></p></td>
<td><p>The identification code for the deferral.</p></td>
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
<td><p>RDeferralsBalances</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RDeferralsBalances</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RDeferralsBalances</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Various</strong> &gt; <strong>Deferrals balances</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RDeferralsTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the RDeferralsDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Deferrals listing report (RDeferralsListing)](rus-deferrals-listing-report-rdeferralslisting.md)

[(RUS) Deferrals transaction listing report (RDeferralsTransactionListing)](rus-deferrals-transaction-listing-report-rdeferralstransactionlisting.md)

[(RUS) Factors for deferrals writing off report (RDeferralsWritingOffFactor)](rus-factors-for-deferrals-writing-off-report-rdeferralswritingofffactor.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

