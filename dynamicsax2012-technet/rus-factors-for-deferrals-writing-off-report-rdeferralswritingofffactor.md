---
title: (RUS) Factors for deferrals writing off report (RDeferralsWritingOffFactor)
TOCTitle: (RUS) Factors for deferrals writing off report (RDeferralsWritingOffFactor)
ms:assetid: 8a90ab78-c2dc-445e-80ea-0de79412ad37
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ945854(v=AX.60)
ms:contentKeyID: 51543174
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RDeferralsWritingOffFactor
---

# (RUS) Factors for deferrals writing off report (RDeferralsWritingOffFactor) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The Factors for deferrals writing off report displays a list of deferral factors that are grouped by the starting date of the period that the report is generated for. The data on this report may include the expense code, the coefficient of the factor, normalized amounts, and base amounts. Accountants generate this report to view a list of deferral factors to calculate depreciation.

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
<td><p><strong>Start date</strong></p></td>
<td><p>The starting date of the period that the report is generated for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Deferrals group</strong></p></td>
<td><p>The identification code of the deferrals group for which the deferral factors are included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Expense code</strong></p></td>
<td><p>The expense code of the deferral factors that are included on the report.</p></td>
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
<td><p>RDeferralsWritingOffFactor</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RDeferralsWritingOffFactor</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RDeferralsWritingOffFactor</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Various</strong> &gt; <strong>Factors for deferrals writing off</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RDeferralsFactorCalculation table

  - RDeferralsWritingOffFactor table

  - RTax25ProfitTable table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Factors for deferrals writing off (form)](https://technet.microsoft.com/en-us/library/jj853189\(v=ax.60\))

  


