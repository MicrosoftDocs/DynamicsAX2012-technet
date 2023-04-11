---
title: (FIN) Finnish sales tax report (TaxReport_FI)
TOCTitle: (FIN) Finnish sales tax report (TaxReport_FI)
ms:assetid: f7cfcf1f-2b00-411a-b27e-cf5d0a1e1f43
ms:mtpsurl: https://technet.microsoft.com/library/Hh352299(v=AX.60)
ms:contentKeyID: 36687927
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales tax reports
- payment report
- SSRS_Reports.Reports.TaxReport_FI
- Finland
- FIN
- Sales tax report
- sales tax payment
- FI - 00012
- payment reports
- sales tax payments
---

# (FIN) Finnish sales tax report (TaxReport\_FI) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the Finnish sales tax report to view the summary of sales tax components, and to review the status of the sales tax process and sales tax transactions. Accountants, accounting managers, accounting supervisors, accounts payable centralized payment clerks, accounts payable clerks, accounts payable managers, accounts payable payment clerks, chief financial officers, and financial controllers can generate this report.


> [!NOTE]
> <P>In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: You can set up a foreign currency for a sales tax code, and then generate the sales tax report in the foreign currency. Alternatively, you can generate the sales tax report in a foreign currency that you specify in the <STRONG>Finnish sales tax report</STRONG> form.</P>



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
<td><p><strong>Tax currency</strong></p></td>
<td><p>Select the currency that determines which transactions to include in the report.</p>
<div class="alert">

> [!NOTE]
> <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Reporting currency</strong></p></td>
<td><p>Select the foreign currency in which the report is generated.</p>
<p>If the reporting currency is different from the tax currency, and if you select the <strong>Currency rate on reporting date</strong> check box, the currency rate on the reporting date that you specify in the <strong>Reporting date</strong> field is used for all of the transactions in the report. Alternatively, if the reporting currency is different from the tax currency, and if you clear the <strong>Currency rate on reporting date</strong> check box, the currency rate on the transaction date is used for all of the transactions in the report.</p>
<div class="alert">

> [!NOTE]
> <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Currency rate on reporting date</strong></p></td>
<td><p>Select this check box to indicate that the currency rate on the reporting date is used for all of the transactions.</p>
<div class="alert">

> [!NOTE]
> <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Reporting date</strong></p></td>
<td><p>Select the date when the report is generated. This field is available only if you select the <strong>Currency rate on reporting date</strong> check box.</p>
<div class="alert">

> [!NOTE]
> <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>


</div></td>
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
<td><p>TaxReport_FI</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxReport_FI</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxReport_FI</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Sales tax payments</strong> &gt; <strong>Sales tax payments</strong>. Specify the criteria, such as settlement period, transaction date, and sales tax payment version for sales tax calculation, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TmpTaxReportById table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxReportDP_FI.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(FIN) Set up and generate the Finnish sales tax report in a foreign currency](fin-set-up-and-generate-the-finnish-sales-tax-report-in-a-foreign-currency.md)

  


