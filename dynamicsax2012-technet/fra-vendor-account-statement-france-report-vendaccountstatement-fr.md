---
title: (FRA) Vendor account statement (France) report (VendAccountStatement_FR)
TOCTitle: (FRA) Vendor account statement (France) report (VendAccountStatement_FR)
ms:assetid: a6a4411a-50ae-468e-b48a-18f269fb91ae
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh456297(v=AX.60)
ms:contentKeyID: 36997723
ms.date: 04/25/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendAccountStatement_FR
- (FRA)
- Vendor account statement report
---

# (FRA) Vendor account statement (France) report (VendAccountStatement\_FR) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Vendor account statement (France)** report displays the details of account statements for vendors for a period that you specify. The beginning balance of a vendor statement is displayed in the **Credit EUR** column if the opening balance is more than 0 (zero) and in the **Debit EUR** column if the opening balance is less than 0 (zero). This report includes information such as the vendor name, vendor address, terms of payment, transaction date, voucher number, invoice number, due date, and invoice amount. This report is typically used by chief financial officers, accountants, accounting managers, accounting clerks, accounting supervisors, and financial controllers to inquire about the statuses of vendor invoices.


> [!NOTE]
> <P>(FRA) This report is available only to legal entities whose primary address is in France.</P>



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
<td><p><strong>From date</strong></p></td>
<td><p>Select the starting date of the reporting period. The opening balance that is displayed in the report is derived from this date.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date of the reporting period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Assessment date</strong></p></td>
<td><p>Select the date until which only open transactions within the reporting period are included in the report. The settled transactions that occur after the assessment date are considered to be open transactions when they are included in the report.</p>
<p>If you don’t specify a date, the assessment is conducted for the transactions up to the date that is specified in the <strong>To date</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Only open</strong></p></td>
<td><p>Select this check box to include only open transactions in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Show subtotals per account</strong></p></td>
<td><p>Select this check box to print subtotals for each ledger account in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Posting profile</strong></p></td>
<td><p>The posting profile that determines which transactions to include in the report. The information in this field is determined by your selections when you create a query.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Currency</strong></p></td>
<td><p>The currency that determines which transactions to include in the report. The information in this field is determined by your selections when you create a query.</p></td>
</tr>
<tr class="even">
<td><p><strong>Voucher</strong></p></td>
<td><p>The related voucher number that determines which transactions to include in the report. The information in this field is determined by your selections when you create a query.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>The transaction date that determines which transactions to include in the report. The information in this field is determined by your selections when you create a query.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor account</strong></p></td>
<td><p>The vendor account number to generate the report for. The information in this field is determined by your selections when you create a query.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Group</strong></p></td>
<td><p>The vendor group to generate the report for. The information in this field is determined by your selections when you create a query.</p></td>
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
<td><p>VendAccountStatement_FR</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendAccountStatement_FR</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendAccountStatement_FR</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Vendor</strong> &gt; <strong>Vendor account statement (France)</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TmpCustVendAccountStatement\_FR table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendAccountStatementDP_FR.processReport class.</P>



  - VendTable

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

