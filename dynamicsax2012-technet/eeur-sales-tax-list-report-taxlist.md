---
title: (EEUR) Sales tax list report (TaxList)
TOCTitle: (EEUR) Sales tax list report (TaxList)
ms:assetid: 980e181d-cf26-4ae4-b550-db7c4413c85d
ms:mtpsurl: https://technet.microsoft.com/library/Dn133212(v=AX.60)
ms:contentKeyID: 53365030
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- tax report
- SSRS_Reports.Reports.TaxList
- sales tax
- VAT
---

# (EEUR) Sales tax list report (TaxList) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The procedures for reporting sales taxes, purchase taxes, and value-added taxes (VAT) to the tax authorities vary by country or region. Before you begin the process that is applicable for your country/region, you can view and analyze the amount of taxes collected and paid, and the related taxable transactions that were posted to Microsoft Dynamics AX.

Use this report to view and print sales tax transactions.

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
<td><p><strong>Main accounts only</strong></p></td>
<td><p>Select this check box to print sales tax information for main accounts only.</p>
<p>If you do not select this check box, the full ledger account is printed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Voucher</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Sales tax list</strong> form, in the <strong>Criteria</strong> field, select a voucher number to include on the report. To select more than one voucher, click <strong>Add</strong>, and then enter the criteria in the row just added.</p>
<p>If you do not select a voucher number, all vouchers are displayed on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales tax code</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Sales tax list</strong> form, in the <strong>Criteria</strong> field, select a sales tax code to include on the report. To select more than one sales tax code, click <strong>Add</strong>, and then enter the criteria in the row just added.</p>
<p>If you do not select a sales tax code, transactions for all tax codes are displayed on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date of VAT register</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Sales tax list</strong> form, in the <strong>Criteria</strong> field, select a date for transactions to include on the report. To select more than one date, click <strong>Add</strong>, and then enter the criteria in the row just added.</p>
<p>If you do not select a date, transactions for all dates are displayed on the report.</p></td>
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
<td><p>TaxList</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\TaxList</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxList</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Sales tax list</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxListDP.processReport

  - TaxListTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the TaxListDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


