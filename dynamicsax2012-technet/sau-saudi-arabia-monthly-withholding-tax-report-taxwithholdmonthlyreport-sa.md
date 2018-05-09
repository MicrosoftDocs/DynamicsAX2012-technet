---
title: (SAU) Saudi Arabia monthly withholding tax report (TaxWithholdMonthlyReport_SA)
TOCTitle: (SAU) Saudi Arabia monthly withholding tax report (TaxWithholdMonthlyReport_SA)
ms:assetid: f1cf6fd4-1e26-470c-9da5-c2716f4dbab6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352296(v=AX.60)
ms:contentKeyID: 36687924
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxWithholdMonthlyReport_SA
---

# (SAU) Saudi Arabia monthly withholding tax report (TaxWithholdMonthlyReport\_SA) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Saudi Arabia monthly withholding tax report** prints the withholding transaction details for a specified month. Legal entities operating in Saudi Arabia must submit this report to the Department of Zakat and Income Tax (DZIT) within the first 10 days following the end of the month for which the report is generated.


> [!NOTE]
> <P>(SAU) This report is available only to legal entities whose primary address is in Saudi Arabia.</P>



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
<td><p><strong>Settlement period</strong></p></td>
<td><p>Select the withholding tax settlement period.</p></td>
</tr>
<tr class="even">
<td><p><strong>Month</strong></p></td>
<td><p>The month for which you want to print the withholding transaction details.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Year</strong></p></td>
<td><p>The year for which you want to print the withholding transaction details.</p></td>
</tr>
<tr class="even">
<td><p><strong>Fiscal year</strong></p></td>
<td><p>The fiscal year for which you want to print the withholding transaction details.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Delay fine</strong></p></td>
<td><p>Enter the delay fine as calculated by the legal entity. This fine is imposed on the taxpayer for late filing and payment.</p></td>
</tr>
<tr class="even">
<td><p><strong>Evasion fine</strong></p></td>
<td><p>Enter the evasion fine as imposed by DZIT on the legal entity. This fine is imposed if it becomes clear that the taxpayer has willfully concealed facts, which could increase the tax liability.</p></td>
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
<td><p>TaxWithholdMonthlyReport_SA</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports/Reports/TaxWithholdMonthlyReport_SA</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxWithholdMonthlyReport_SA</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Withholding tax</strong> &gt; <strong>Saudi Arabia monthly withholding tax report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DirPartyTable table

  - TaxWithholdData table

  - TaxWithholdRevenueTable\_TH table

  - TaxWithholdTrans table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

