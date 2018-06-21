---
title: About accounting distributions and subledger journal entries for free text invoices
TOCTitle: About accounting distributions and subledger journal entries for free text invoices
ms:assetid: d090ccbc-e6a9-4101-9985-347410f74de0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242919(v=AX.60)
ms:contentKeyID: 36059489
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About accounting distributions and subledger journal entries for free text invoices [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Accounting distributions are used to define how an amount will be accounted for, such as how the revenue, tax, or charges will be accounted for on a free text invoice. Every amount that must be accounted for when the free text invoice is journalized will have one or more accounting distributions.

## Accounting distributions for free text invoices

You can use the following buttons in the **Free text invoice** form to view, and possibly modify, the accounting distributions for each amount on the free text invoice.

  - **Distribute amounts** – View and modify the accounting distributions for an individual line and any child lines, such as taxes or charges. You can also view and modify the accounting distributions for the child line directly from the **Sales tax transactions** form or the **Charges transactions** form.
    
      - Modify free text invoice header amounts, such as charges or currency rounding amounts. (On the **Action Pane**, in the **Accounting** group, click **Distribute amounts**.)
    
      - Modify free text invoice line amounts. (In the **Invoice lines** grid, click **Distribute amounts**.)

  - **View distributions** – View the accounting distributions for all lines on the document. You cannot modify the accounting distributions from this view.
    
      - View header and line amounts. (On the **Action Pane**, in the **Accounting** group, click **View distributions**.)

The accounting distributions cannot be split, deleted, or modified for lines that contain stocked items or fixed assets, or for child lines such as charges, taxes, or discounts.


> [!NOTE]
> <P>If the parent line contains an item that is not stocked and the accounting distributions are split, the child line will be split automatically to match the financial dimensions of the parent line. The accounting distributions for the child line cannot be additionally split or deleted, but depending on the setup of the child line, you might be able to modify the ledger account for the accounting distributions of the child line.</P>



When you enter a free text invoice, each amount will be distributed as follows.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of monetary amount</p></th>
<th><p>Where the main account is displayed from</p></th>
<th><p>Order of priority that determines which default financial dimension is displayed</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Free text invoice line</p></td>
<td><p>The ledger account on the free text invoice line.</p></td>
<td><ol>
<li><p>If the main account is an allocation account, use the default value from the allocation account definition.</p></li>
<li><p>If the main account is not an allocation account, use the financial dimension default template on the free text invoice line.</p></li>
<li><p>Use the default financial dimension values on the free text invoice line.</p></li>
<li><p>Use the default financial dimension values from the ledger account in the <strong>Chart of accounts</strong> form.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Free text invoice line for a fixed asset number and value model combination</p>
<div class="alert">

> [!NOTE]
> <P>The main account on the free text invoice line will be the fixed asset disposal account.</P>


</div></td>
<td><p>The ledger account on the free text invoice line.</p></td>
<td><ol>
<li><p>Use the default financial dimension values on the free text invoice line.</p></li>
<li><p>Use the default financial dimension values from the ledger account in the <strong>Chart of accounts</strong> form.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Free text invoice discount amount</p></td>
<td><p>The <strong>Main account for customer discounts</strong> field in the <strong>Cash discounts</strong> form. (Click <strong>Accounts receivable</strong> &gt; <strong>Setup</strong> &gt; <strong>Payment</strong> &gt; <strong>Cash discounts</strong>.)</p></td>
<td><ol>
<li><p>If the main account is an allocation account, use the default value from the allocation account definition.</p></li>
<li><p>If the main account is not an allocation account, use the financial dimension default template on the free text invoice line.</p></li>
<li><p>Use the default financial dimension values on the free text invoice line.</p></li>
<li><p>Use the default financial dimension values from the ledger account in the <strong>Chart of accounts</strong> form.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Free text invoice sales tax amount</p></td>
<td><p>The <strong>Sales tax payable</strong> field in the <strong>Ledger posting groups</strong> form. (Click <strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Sales tax</strong> &gt; <strong>Ledger posting groups</strong>.)</p></td>
<td><ol>
<li><p>Use the financial dimensions that are defined on the free text invoice line amount or the distributions for the charge line amount.</p></li>
<li><p>Use the default financial dimension values on the free text invoice line.</p></li>
<li><p>Use the default financial dimension values from the ledger account in the <strong>Chart of accounts</strong> form.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Free text invoice charge line amount</p></td>
<td><p>The <strong>Credit account</strong> field in the <strong>Charges code</strong> form. (Click <strong>Accounts receivable</strong> &gt; <strong>Setup</strong> &gt; <strong>Charges</strong> &gt; <strong>Charges code</strong>.)</p></td>
<td><ol>
<li><p>If the main account is an allocation account, use the default value from the allocation account definition.</p></li>
<li><p>If the main account is not an allocation account, use the financial dimension default template on the free text invoice line.</p></li>
<li><p>Use the default financial dimension values on the free text invoice line.</p></li>
<li><p>Use the default financial dimension values from the ledger account in the <strong>Chart of accounts</strong> form.</p></li>
</ol></td>
</tr>
</tbody>
</table>


Accounting distributions for taxes cannot be created until taxes are calculated. To calculate sales taxes, you must complete one of the following tasks in the **Free text invoice** form:

  - View the sales tax. (On the **Action Pane**, in the **Details** group, click **Sales tax**.)

  - View the invoice total. (On the **Action Pane**, in the **Details** group, click **Totals**.)

  - View the cash flow. (On the **Action Pane**, in the **Related information** group, click **Cash flow**.)

  - View accounting distributions for the whole free text invoice. (On the **Action Pane**, in the **Accounting** group, click **View distributions**.)

  - View the subledger journal. (On the **Action Pane**, in the **Accounting** group, click **Subledger journal**.)

## Subledger journals for free text invoices

Before you post a free text invoice, you can view the full accounting entry of the invoice, which includes debits and credits, to verify that the invoice is being posted to the correct accounts. This view of the full accounting entry is called a subledger journal.

If the subledger journal entry is incorrect when you preview it before you journalize the free text invoice, you cannot modify the subledger journal entry. Instead, you must modify the accounting distributions or the posting profile. The accounting distributions are used to define one side of the accounting entry, the debit or the credit. The offsetting subledger journal account entry is created from the posting profiles, such as from the customer account or the tax.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

