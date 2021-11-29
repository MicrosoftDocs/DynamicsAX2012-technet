---
title: (ITA) Withholding tax - yearly report (TaxWithholdYearlyReport_IT)
TOCTitle: (ITA) Withholding tax - yearly report (TaxWithholdYearlyReport_IT)
ms:assetid: 59baf260-a1dc-45f5-9636-c796cfa91d43
ms:mtpsurl: https://technet.microsoft.com/library/Hh335150(v=AX.60)
ms:contentKeyID: 36687361
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxWithholdYearlyReport_IT
---

# (ITA) Withholding tax - yearly report (TaxWithholdYearlyReport\_IT) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Withholding tax - yearly** report is used to print the Italian yearly withholding tax report in the withholding tax currency, sorted by the vendor account and the withholding tax code. This report is used to inquire into the status of sales tax transactions. This report is typically used by collections managers, accounts receivable clerks, accounts receivable managers, accountants, accounting managers, accounting supervisors, sales clerks, sales managers, and accounts payable clerks.


> [!NOTE]
> <P>(ITA) This report is available only to legal entities whose primary address is in Italy.</P>



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
<td><p><strong>Vendor account</strong></p></td>
<td><p>Specify the range of vendors to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment date</strong></p></td>
<td><p>Specify the payment date interval.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Competence date</strong></p></td>
<td><p>Specify the competence date interval. The <strong>Competence date</strong> field on invoices or credit notes is filled in with the document date, but can be overwritten. Use this field to assign the withholding tax to the correct sales tax settlement period.</p></td>
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
<td><p>TaxWithholdYearlyReport_IT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxWithholdYearlyReport_IT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxWithholdYearlyReportIT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Withholding tax - yearly</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxWithholdYearlyReportTmp\_IT Table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxWithholdYearlyReportDP_IT.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


