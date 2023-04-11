---
title: Vendor transactions report (VendTransListReport)
TOCTitle: Vendor transactions report (VendTransListReport)
ms:assetid: 38a30d16-2f8b-41e8-884d-aeada174c21f
ms:mtpsurl: https://technet.microsoft.com/library/Aa553670(v=AX.60)
ms:contentKeyID: 37831996
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendTransListReport
---

# Vendor transactions report (VendTransListReport) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use report to view a list of vendor transactions that have been invoiced. The report includes the debit, credit, and currency amounts for each invoice. Amounts are displayed in the currency of the transaction and in the accounting currency.

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
<td><p><strong>Exchange rates</strong></p></td>
<td><p>Select <strong>Invoice date</strong> to show amounts using the original exchange rate for the transaction. Select <strong>Adjustment date</strong> to show amounts using the exchange rate from the most recent foreign currency revaluation adjustment.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include reversed</strong></p></td>
<td><p>Select this check box to include transactions that have been reversed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include transactions</strong></p></td>
<td><p>Select whether to include open, settled, or all transactions.</p>
<ul>
<li><p><strong>Open</strong> – Include only transactions that have not been settled.</p></li>
<li><p><strong>Closed</strong> – Include only transactions that have been settled.</p></li>
<li><p><strong>Open and closed</strong> – Include all transactions.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Settlements details</strong></p></td>
<td><p>Select this check box to include the <strong>Settled voucher</strong> column on the report.</p></td>
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
<td><p>VendTransListReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendTransListReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendTransList</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Vendor</strong> &gt; <strong>Vendor transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendTransListTmp table


> [!NOTE]
> <P>To find out where the data in the temp tables comes from, view the cross-references for the VendTransListDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Processing batch jobs](processing-batch-jobs.md)

  


