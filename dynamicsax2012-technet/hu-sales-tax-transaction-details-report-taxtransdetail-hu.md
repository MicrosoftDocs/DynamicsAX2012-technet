---
title: (HU) Sales tax transaction details report (TaxTransDetail_HU)
TOCTitle: (HU) Sales tax transaction details report (TaxTransDetail_HU)
ms:assetid: f84253a9-8ca2-4f24-9cc5-a57e0b4284f0
ms:mtpsurl: https://technet.microsoft.com/library/JJ851132(v=AX.60)
ms:contentKeyID: 50173439
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (HU) Sales tax transaction details report (TaxTransDetail\_HU) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this report to view a detailed list of sales tax transaction information grouped by sales tax code and tax direction in multiple currencies. You can print this report for selected transactions by using query filtering. This report is typically used by compliance managers, accounting managers, clerks, and accountants to inquire into posted sales tax transactions.

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
<td><p><strong>Include reversed</strong></p></td>
<td><p>Select the check box to include reversed transactions on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Run mode</strong></p></td>
<td><p>Select which currency amounts to print on the report. Select from the following options:</p>
<ul>
<li><p><strong>Amounts in company currency for accounting</strong> – Print the values with the transaction exchange rate.</p></li>
<li><p><strong>Amounts in company currency for sales tax reporting</strong> – Print the values with the transaction sales tax exchange rate. This includes any lines that contain discrepancies.</p></li>
<li><p><strong>Amounts in original currency</strong> – Print the values in the currency in which the transaction was posted.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Sales tax code</strong></p></td>
<td><p>The sales tax code that is associated with the posted sales tax transactions.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date of VAT register</strong></p></td>
<td><p>The transaction date for the value-added tax (VAT) register. This value is used to filter transactions on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Printer</strong></p></td>
<td><p>The printer that is currently selected. To select a different printer, click <strong>Destinations ...</strong>.</p>
<p>This field is blank if <strong>Screen</strong> is selected in the <strong>Print destination</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print destination</strong></p></td>
<td><p>The destination where the report is produced. Click <strong>Destinations ...</strong> to change the destination for the report.</p></td>
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
<td><p>TaxTransDetail_HU</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\TaxTranDetails_HU</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxTransDetail_HU</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Groupings</strong> &gt; <strong>Hungary</strong> &gt; <strong>Sales tax transactions - details</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxTransDetailTmp\_HU


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the TaxTransDetailDP_HU.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


