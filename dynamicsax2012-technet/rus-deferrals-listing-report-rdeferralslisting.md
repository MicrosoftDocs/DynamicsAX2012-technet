---
title: (RUS) Deferrals listing report (RDeferralsListing)
TOCTitle: (RUS) Deferrals listing report (RDeferralsListing)
ms:assetid: adfbc353-63df-4a4d-99c5-8a68821ae4b3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ955220(v=AX.60)
ms:contentKeyID: 51831852
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RDeferralsListing
---

# (RUS) Deferrals listing report (RDeferralsListing) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The Deferrals listing report displays a list of deferrals with their current statuses, such as **Scheduled**, **In process**, and **Closed**. The report also displays the initial amount and the remaining amount for each deferral. Accountants generate and print this report to analyze the value of current deferral charges.

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
<td><p>Select the deferrals model number.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reporting date</strong></p></td>
<td><p>Select a date to generate the report for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Exclude zero turnovers</strong></p></td>
<td><p>Select this check box to exclude deferrals that have a net book value of zero from the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Deferral ID</strong></p></td>
<td><p>The deferral code that is included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date attached</strong></p></td>
<td><p>The deferral creation date that is included on the report.</p></td>
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
<td><p>RDeferralsListing</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RDeferralsListing</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RDeferralsListing</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Deferrals listing</strong>.</p></td>
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

[(RUS) Set up a deferrals model](rus-set-up-a-deferrals-model.md)

[(RUS) Deferrals (form)](https://technet.microsoft.com/en-us/library/jj923560\(v=ax.60\))

[(RUS) Deferrals models (form)](https://technet.microsoft.com/en-us/library/jj678655\(v=ax.60\))

  


