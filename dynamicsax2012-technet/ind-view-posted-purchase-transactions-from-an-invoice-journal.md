---
title: (IND) View posted purchase transactions from an invoice journal
TOCTitle: (IND) View posted purchase transactions from an invoice journal
ms:assetid: 6c38ef75-0dbd-47e2-aabf-41191296abae
ms:mtpsurl: https://technet.microsoft.com/library/JJ677899(v=AX.60)
ms:contentKeyID: 49385866
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) View posted purchase transactions from an invoice journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The steps that you take to create a journal line for excise transactions in the **Invoice journal** form are similar to those you use to create journal lines in the **General journal** form.

For example, you can create a journal line in the **Invoice pool excl. posting** form for a Small Scale Industry (SSI) vendor. The invoice date is used for the calculation because the **Vendor calculation date type** field is set as the **Invoice date** in the **General ledger parameters** form. For more information, [(IND) View product receipts for posted purchase invoices using an invoice journal](ind-view-product-receipts-for-posted-purchase-invoices-using-an-invoice-journal.md).

The formula for the calculation of excise transactions is defined in the **Formula designer** form as shown in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tax code</p></th>
<th><p>Taxable basis</p></th>
<th><p>Calculation expression</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>BED</p></td>
<td><p>Line amount</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>AED</p></td>
<td><p>Excl. line amount</p></td>
<td><p>+[BED]</p></td>
</tr>
</tbody>
</table>


The journal line is entered in the invoice journal, validated, and then posted.

The following example shows how excise transactions are calculated in the invoice journal.

  - BED = (10,000.00 \* 5%) = 500.00

  - AED = (500.00 \* 2%) = 10.00

The amount origin and the tax amounts calculated are displayed in the **Temporary sales tax transactions** form.


> [!NOTE]
> <P>For more information see <A href="https://technet.microsoft.com/library/aa591455(v=ax.60)">Temporary sales tax transactions (form)</A>.</P>



An excise duty of 510.00 is calculated based on the excise rates set on the invoice date. When the journal is posted, the RG23A Part II register is updated with the excise tax amount.

The following voucher entries are created when the journal is posted.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Purchase receipt account</p></td>
<td><p>10,000.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>BED recoverable account</p></td>
<td><p>500.00</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>AED recoverable account</p></td>
<td><p>10.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Vendor account</p></td>
<td><p></p></td>
<td><p>10,510.00</p></td>
</tr>
</tbody>
</table>


## See also

[(IND) Journal voucher - Invoice journal (modified form)](https://technet.microsoft.com/library/jj664791\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/library/jj664487\(v=ax.60\))

[(IND) General ledger parameters (modified form)](https://technet.microsoft.com/library/jj677901\(v=ax.60\))

  


