---
title: Free text invoice report (FreeTextInvoice)
TOCTitle: Free text invoice report (FreeTextInvoice)
ms:assetid: 048f3909-135a-4d57-bcad-9b60070e921d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208615(v=AX.60)
ms:contentKeyID: 36056409
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustPostInvoiceJob
- SSRS_Reports.Reports.FreeTextInvoice
- MsDynAx060.Forms.CustPostInvoiceJob
---

# Free text invoice report (FreeTextInvoice) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Free text invoice** report displays pricing and correction information for a free text invoice. The free text invoice is printed when you post the invoice. If you print the invoice before you post it, the name of the report is **Pro forma invoice**.

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
<td><p><strong>Billing classification</strong></p></td>
<td><p>Select one or more billing classifications to include on the report.</p>
<div>

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Posting</strong></p></td>
<td><p>If this check box is selected, the free text invoices that are selected will be posted when you click <strong>OK</strong>.</p>
<div>

> [!NOTE]
> <P>To print a pro forma invoice, clear this check box and select the <STRONG>Print invoice</STRONG> check box.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Print</strong></p></td>
<td><p>Select an option for when the invoices are printed:</p>
<ul>
<li><p><strong>Current</strong> – Print each invoice as it is updated.</p></li>
<li><p><strong>After</strong> – Print after all the invoices have been updated.</p></li>
</ul>
<div>

> [!NOTE]
> <P>To print an invoice, you must select the <STRONG>Print invoice</STRONG> check box.</P>
> <P>If you set up the system in the <STRONG>Form sorting parameters</STRONG> form to sort by a particular parameter, such as the invoice account, select <STRONG>After</STRONG> in the <STRONG>Print</STRONG> field.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Print invoice</strong></p></td>
<td><p>Select this check box to print the free text invoice.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Use print management destination</strong></p></td>
<td><p>Select this check box to print the invoice or pro forma invoice using print management destinations. Clear the check box to use the default printer settings, instead.</p></td>
</tr>
<tr class="even">
<td><p><strong>Send e-mail</strong></p></td>
<td><p>Select this check box to send the PDF and XML files of the free text invoice as email attachments to a customer after the invoice is posted. This check box is available only if you select the <strong>Enable CFD (electronic invoices)</strong> check box in the <strong>Electronic invoice parameters</strong> form.</p>
<div>

> [!NOTE]
> <P>(MEX) This control is available only to legal entities whose primary address is in Mexico.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Credit correction</strong></p></td>
<td><p>Select this check box to display a credit correction, such as a credit note, as a debit in the voucher transactions. The negative credit (debit) corrects the previous, incorrect transaction.</p>
<div>

> [!NOTE]
> <P>This method of correcting entries is known as Storno.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Credit limit type</strong></p></td>
<td><p>Select the appropriate option for the credit limit:</p>
<ul>
<li><p><strong>None</strong> – A credit limit check is not required.</p></li>
<li><p><strong>Balance</strong> – The customer balance is checked against the credit limit.</p></li>
<li><p><strong>Balance + packing slip or product receipt</strong> – The customer balance and deliveries are checked against the credit limit.</p></li>
<li><p><strong>Balance+All</strong> – The customer balance, deliveries, and open orders are checked against the credit limit.</p></li>
</ul>
<div>

> [!NOTE]
> <P>If you select <STRONG>None</STRONG> and the <STRONG>Mandatory credit limit</STRONG> check box is selected for the customer in the <STRONG>Customers</STRONG> form, the customer balance is checked against the credit limit.</P>


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
<td><p>FreeTextInvoice</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\Reports\FreeTextInvoice</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>FreeTextInvoice</p>
<p>FreeTextInvoiceCopy</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Common</strong> &gt; <strong>Free text invoices</strong> &gt; <strong>All free text invoices</strong>. Click <strong>Post</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - FreeTextInvoiceTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the FreeTextInvoiceDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Set up print management for a transaction](set-up-print-management-for-a-transaction.md)

[Print management setup (form)](https://technet.microsoft.com/en-us/library/hh209383\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

