---
title: (LVA) Generate the VAT declaration as an XML file
TOCTitle: (LVA) Generate the VAT declaration as an XML file
ms:assetid: a75a6b16-5cf3-4017-b4c0-531bedaf92bc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn716013(v=AX.60)
ms:contentKeyID: 62200256
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- XML
- Classes.TaxReport
- Forms.EUSalesList
- Forms.TaxReportVoucher
- Forms.Dialog
- sales tax payments
- VAT declaration
audience: Application User
ms.search.region: Latvia
---

# (LVA) Generate the VAT declaration as an XML file 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can generate a value-added tax (VAT) declaration that contains details about VAT transactions for a specified period, and then export the declaration as an XML file.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 7 or later</p></td>
</tr>
<tr class="even">
<td><p><strong>Country</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Latvia</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><p>Set up XML elements for sales tax report lines. For more information, see <a href="https://technet.microsoft.com/en-us/library/jj721459(v=ax.60)">(LVA) VAT report setup (form)</a>.</p>
<p>Set up sales tax report lines in the <strong>Sales tax reporting codes</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa588316(v=ax.60)">Sales tax reporting codes (form)</a>.</p>
<p>Set up sales tax codes to report lines. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa553257(v=ax.60)">Sales tax codes (form)</a>.</p>
<p>Set up the reporting type for transactions in the <strong>Item sales tax groups</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa615960(v=ax.60)">Item sales tax groups (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Related transaction task</strong></p></td>
<td><p>Generate the EU sales list on a monthly, bimonthly, quarterly, or yearly basis. For more information, see <a href="generate-the-eu-sales-list.md">Generate the EU sales list</a>.</p></td>
</tr>
</tbody>
</table>


## (LVA) Generate the VAT declaration as an XML file

Use the **Sales tax payments** form to view the settled VAT for a specified period. You can transfer the VAT payments to the EU sales list, and then export them as an XML file.

To generate the VAT declaration as an XML file, follow these steps:

1.  Click **General ledger** \> **Reports** \> **External** \> **Sales tax payments**.

2.  In the **Sales tax payments** form, view the settled VAT payments for a specified period. For more information, see [Sales tax payments (form)](https://technet.microsoft.com/en-us/library/aa583763\(v=ax.60\)).

3.  Click **EU sales list**.

4.  On the **Overview** tab, enter the required details for the EU sales list report.

5.  Close the form.

6.  In the **Sales tax payments** form, click **Export VAT XML file**.

7.  In the **File name** field, specify the path and file name for the XML file.

8.  Select the **Mark as reported** check box to indicate that the declaration is submitted to the tax authorities.

9.  In the **Overpaid domestic VAT amount** field, enter the overpaid VAT amount that is paid by the recipient of the items or services.

10. Click **OK** to export the VAT declaration as an XML file.

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To generate the VAT declaration as an XML file, you must be a member of a security role that is described in the following table.</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Role</p></th>
<th><p>Name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Collections manager</p></td>
<td><p>CollectionLetterCollectionsManager</p></td>
</tr>
<tr class="even">
<td><p>Clerk</p></td>
<td><ul>
<li><p>CustInvoiceAccountsReceivableClerk</p></li>
<li><p>VendInvoiceAccountsPayableClerk</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable manager</p></td>
<td><p>CustInvoiceAccountsReceivableManager</p></td>
</tr>
<tr class="even">
<td><p>Accountant</p></td>
<td><p>LedgerAccountant</p></td>
</tr>
<tr class="odd">
<td><p>Accounting manager</p></td>
<td><p>LedgerAccountingManager</p></td>
</tr>
<tr class="even">
<td><p>Accounting supervisor</p></td>
<td><p>LedgerAccountingSupervisor</p></td>
</tr>
<tr class="odd">
<td><p>Sales manager</p></td>
<td><p>TradeSalesManager</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


