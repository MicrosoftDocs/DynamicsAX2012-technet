---
title: Vendor balance list with credit limit report (VendBalanceList)
TOCTitle: Vendor balance list with credit limit report (VendBalanceList)
ms:assetid: aa47b4b2-0ed0-4109-acef-f4ba321b11fe
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa589252(v=AX.60)
ms:contentKeyID: 36676490
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendBalanceList
---

# Vendor balance list with credit limit report (VendBalanceList) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print the balance for each vendor in the accounting currency. The balance is based on the value according to the most recent foreign currency revaluation. For each vendor, the vendor balance also shows the credit limit as specified in the **Vendors** form, the balance in the local currency, and any amount by which the credit limit has been exceeded.

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
<td><p><strong>As on</strong></p></td>
<td><p>Enter the date and time as of which the balance list will be generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>Zero balance</strong></p></td>
<td><p>Select this check box to include vendor accounts that have a zero balance.</p></td>
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
<td><p>VendBalanceList</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendBalanceList</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendBalanceList</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Vendor balance list with credit limit</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendTable table

  - VendTrans table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\))

  


