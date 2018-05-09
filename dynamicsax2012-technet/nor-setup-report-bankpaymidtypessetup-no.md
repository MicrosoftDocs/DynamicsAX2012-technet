---
title: (NOR) Setup report (BankPaymIdTypesSetup_NO)
TOCTitle: (NOR) Setup report (BankPaymIdTypesSetup_NO)
ms:assetid: c26923f7-b0ef-4480-ac2c-8bdc2585ec99
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433517(v=AX.60)
ms:contentKeyID: 36941299
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankPaymIdTypesSetup_NO
---

# (NOR) Setup report (BankPaymIdTypesSetup\_NO) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Setup** report displays details of customer payments together with the payment ID type and method of payment that is used to make the customer payment. This report is used by accountants, accounting managers, accounting supervisors, accounts receivable centralized payments clerks, accounts receivable clerks, accounts receivable managers, collections agents, collections managers, compliance managers, and financial controllers. This report is used to inquire into the status of collections and invoice processes and cash processes to maintain invoice policies, cash policies, and collections policies.


> [!NOTE]
> <P>(NOR) This report is available only to legal entities whose primary address is in Norway.</P>



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
<td><p><strong>Payment ID type</strong></p></td>
<td><p>The payment identification type.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment ID length</strong></p></td>
<td><p>The number of characters in the payment identification number.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer account</strong></p></td>
<td><p>The customer account number.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer group</strong></p></td>
<td><p>The customer group number.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Method of payment</strong></p></td>
<td><p>The customer method of payment.</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The country/region of the customer.</p></td>
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
<td><p>BankPaymIdTypesSetup_NO</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankPaymIdTypesSetup_NO</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankPaymIdTypesSetup_NO</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Setup</strong> &gt; <strong>Payment</strong> &gt; <strong>Payment ID</strong>. In the <strong>Payment ID</strong> form, click <strong>Print</strong> &gt; <strong>Setup</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankCustPaymIdTable table

  - CustGroup table

  - CustParameters table

  - CustPaymModeTable table

  - CustTable table

  - DirPartyTable table

  - LogisticsCountryRegionPaymentIdType\_NO

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(NOR) Set up and maintain payment IDs](nor-set-up-and-maintain-payment-ids.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

