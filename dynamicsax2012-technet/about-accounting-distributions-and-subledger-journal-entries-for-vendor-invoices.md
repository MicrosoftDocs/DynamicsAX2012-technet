---
title: About accounting distributions and subledger journal entries for vendor invoices
TOCTitle: About accounting distributions and subledger journal entries for vendor invoices
ms:assetid: b8b6b4c1-5d41-458d-9824-405b872d5a71
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242760(v=AX.60)
ms:contentKeyID: 36059112
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- invoices
- vendors
- invoice
- accounting distributions
- accounting distribution
- journal entries
- journal entry
- subledger
---

# About accounting distributions and subledger journal entries for vendor invoices 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Accounting distributions are used to define how an amount will be accounted for, such as how the expense, tax, or charges will be accounted for on a vendor invoice. Every amount that must be accounted for when the vendor invoice is journalized will have one or more accounting distributions.

## Accounting distributions for vendor invoices

You can use the following buttons in the **Vendor invoice** form to view, and possibly modify, the accounting distributions for each amount on the vendor invoice.

  - **Distribute amounts** – View and modify the accounting distributions for an individual line and any child lines, such as taxes or charges. You can also view and modify the accounting distributions for the child line directly from the **Sales tax transactions** form or the **Charges transactions** form.
    
      - Modify vendor invoice header amounts, such as charges or currency rounding amounts. (On the **Action Pane**, on the **Financials** tab, click **Distribute amounts**.)
    
      - Modify vendor invoice line amounts. (In the **Lines** grid, click **Financials** \> **Distribute amounts**.)

  - **View distributions** – View the accounting distributions for all lines on the document. You cannot modify the accounting distributions from this view.
    
      - View header and line amounts. (On the **Action Pane**, on the **Financials** tab, click **View distributions**.)

If the vendor invoice references a purchase order, you can split and modify the accounting distributions for lines that contain an item that is not stocked.

If the vendor invoice line does not reference a purchase order line, you can also delete an accounting distribution.

You cannot split or delete lines, such as charges, taxes, and line discounts. You can modify the ledger account, but you cannot change the amounts or percentages.


> [!NOTE]
> <P>If the parent line contains an item that is not stocked and the accounting distributions are split, the child line will be split automatically to match the financial dimensions of the parent line. The accounting distributions for the child line cannot be additionally split or deleted, but depending on the setup of the child line, you might be able to modify the ledger account for the accounting distributions of the child line.</P>



When you enter a vendor invoice, each amount will be distributed as follows.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of vendor invoice line</p></th>
<th><p>Order of priority that determines where the main account is displayed from</p></th>
<th><p>Order of priority that determines which default financial dimension is displayed</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Stocked product</p></td>
<td><ol>
<li><p>The accounting distribution for the purchase order line.</p></li>
<li><p>The <strong>Main account</strong> field when <strong>Purchase expenditure for product</strong> is selected in the <strong>Posting</strong> form. (Click <strong>Inventory management</strong> &gt; <strong>Setup</strong> &gt; <strong>Posting</strong> &gt; <strong>Posting</strong>.)</p></li>
</ol></td>
<td><ol>
<li><p>If the invoice line references a purchase order line, use the account distribution for the purchase order line.</p></li>
<li><p>Use the default financial dimension values on the vendor invoice.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>A procurement category or a product that is not stocked</p></td>
<td><ol>
<li><p>The accounting distribution for the purchase order line, if the vendor invoice line references a purchase order line.</p></li>
<li><p>The <strong>Main account</strong> field when <strong>Purchase expenditure for expense</strong> is selected in the <strong>Posting</strong> form. (Click <strong>Inventory management</strong> &gt; <strong>Setup</strong> &gt; <strong>Posting</strong> &gt; <strong>Posting</strong>.)</p></li>
</ol></td>
<td><ol>
<li><p>If the invoice line references a purchase order line, use the account distribution for the purchase order line.</p></li>
<li><p>If the main account is an allocation account, use the default value from the allocation account definition.</p></li>
<li><p>Use the default financial dimension values on the vendor invoice.</p></li>
<li><p>Use the financial dimension values from the vendor invoice line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Fixed asset</p></td>
<td><ol>
<li><p>The accounting distribution for the purchase order line, if the vendor invoice line references a purchase order line.</p></li>
<li><p>If <strong>Acquisition</strong> is selected in the <strong>Transaction type</strong> field in the <strong>Vendor invoice</strong> form, the <strong>Main account</strong> field when <strong>Acquisition</strong> is selected in the <strong>Fixed asset posting profiles</strong> form. (Click <strong>Fixed assets</strong> &gt; <strong>Setup</strong> &gt; <strong>Fixed asset posting profiles</strong>.)</p></li>
<li><p>If <strong>Acquisition adjustment</strong> is selected in the <strong>Transaction type</strong> field, the <strong>Main account</strong> field when <strong>Acquisition adjustment</strong> is selected in the <strong>Fixed asset posting profiles</strong> form.</p></li>
</ol></td>
<td><ol>
<li><p>Use the account distribution for the purchase order line, if the invoice line references a purchase order line.</p></li>
<li><p>Use the financial dimension values from the vendor invoice line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Project defined on the vendor invoice line</p></td>
<td><ol>
<li><p>The accounting distribution for the purchase order line, if the invoice line references a purchase order line.</p></li>
<li><p>If <strong>Balance</strong> is selected in the <strong>Post costs - item</strong> field in the <strong>Project groups</strong> form, the <strong>Main account</strong> field when <strong>Cost</strong> is selected in the <strong>Ledger posting setup</strong> form. (Click <strong>Project management and accounting</strong> &gt; <strong>Setup</strong> &gt; <strong>Posting</strong> &gt; <strong>Ledger posting setup</strong>.)</p></li>
<li><p>If <strong>Profit and loss</strong> is selected in the <strong>Post costs - item</strong> field in the <strong>Project groups</strong> form, the <strong>Main account</strong> field when <strong>Cost - item</strong> is selected in the <strong>Ledger posting setup</strong> form.</p></li>
</ol></td>
<td><ol>
<li><p>If the invoice line references a purchase order line, use the account distribution for the purchase order line.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Line discount</p></td>
<td><ol>
<li><p>The accounting distribution for the purchase order line, if the invoice line references a purchase order line.</p></li>
<li><p>The <strong>Main account</strong> field when <strong>Discount</strong> is selected in the <strong>Posting</strong> form. (Click <strong>Inventory management</strong> &gt; <strong>Setup</strong> &gt; <strong>Posting</strong> &gt; <strong>Posting</strong>.)</p></li>
<li><p>If a main account for a discount is not defined on the posting profile, the accounting distribution of the extended price on the purchase order line.</p></li>
</ol></td>
<td><ol>
<li><p>If the invoice line references a purchase order line, use the accounting distribution for the purchase order line.</p></li>
<li><p>Use the financial dimensions from the accounting distributions for the extended price on the vendor invoice line.</p></li>
<li><p>Use the financial dimension values for the vendor invoice line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Purchase charge, which is entered on the <strong>Price and discount</strong> tab of the purchase order line</p></td>
<td><ol>
<li><p>The accounting distribution for the purchase order line, if the invoice line references a purchase order line.</p></li>
<li><p>The accounting distribution of the extended price on the purchase order line.</p></li>
</ol></td>
<td><ol>
<li><p>If the invoice line references a purchase order line, use the account distribution for the purchase order line.</p></li>
<li><p>Use the financial dimensions from the accounting distributions for the extended price on the vendor invoice line.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Line charge</p></td>
<td><ol>
<li><p>The accounting distribution for the purchase order line, if the invoice line references a purchase order line.</p></li>
<li><p>If <strong>Ledger account</strong> is selected in the debit <strong>Type</strong> field in the <strong>Charges code</strong> form, the debit <strong>Account</strong> field in the <strong>Charges code</strong> form. (Click <strong>Accounts payable</strong> &gt; <strong>Setup</strong> &gt; <strong>Charges</strong> &gt; <strong>Charges code</strong>.)</p></li>
<li><p>If <strong>Item</strong> is selected in the debit <strong>Type</strong> field in the <strong>Charges code</strong> form, the accounting distribution for the extended price on the purchase order line.</p></li>
<li><p>If <strong>Customer/Vendor</strong> is selected in the debit <strong>Type</strong> field in the <strong>Charges code</strong> form, the credit <strong>Account</strong> field in the <strong>Charges code</strong> form.</p></li>
</ol></td>
<td><ol>
<li><p>If the invoice line references a purchase order line, use the account distribution for the purchase order line.</p></li>
<li><p>Use the financial dimensions from the accounting distributions for the extended price on the vendor invoice line.</p></li>
<li><p>Use the financial dimension values from the vendor invoice line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Tax, with the following condition:</p>
<ul>
<li><p>The <strong>Apply U.S. taxation rules</strong> check box is selected in the <strong>General ledger parameters</strong> form.</p></li>
</ul></td>
<td><ol>
<li><p>The accounting distribution for the purchase order line, if the invoice line references a purchase order line.</p></li>
<li><p>The accounting distribution of the extended price or charge.</p></li>
</ol></td>
<td><ol>
<li><p>If the invoice line references a purchase order line, use the account distribution for the purchase order line.</p></li>
<li><p>Use the financial dimensions from the accounting distributions for the extended price on the vendor invoice line.</p></li>
<li><p>Use the financial dimension values from the vendor invoice line.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Tax, with the following conditions:</p>
<ul>
<li><p>The <strong>Apply U.S. taxation rules</strong> check box is cleared in the <strong>General ledger parameters</strong> form.</p></li>
<li><p>The <strong>Use tax</strong> field for the sales tax group is cleared in the <strong>Sales tax groups</strong> form.</p></li>
</ul></td>
<td><ol>
<li><p>If the tax amount is recoverable, the <strong>Sales tax receivable</strong> field in the <strong>Ledger posting groups</strong> form. (Click <strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Sales tax</strong> &gt; <strong>Ledger posting groups</strong>.)</p></li>
<li><p>If the tax amount is not recoverable, the extended price or the accounting distribution for the charge.</p></li>
</ol></td>
<td><ol>
<li><p>If the invoice line references a purchase order line, use the account distribution for the purchase order line.</p></li>
<li><p>Use the financial dimensions from the extended price or the accounting distributions for the charge on the vendor invoice line.</p></li>
<li><p>Use the financial dimension values from the vendor invoice line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Tax, with the following conditions:</p>
<ul>
<li><p>The <strong>Apply U.S. taxation rules</strong> check box is cleared in the <strong>General ledger parameters</strong> form.</p></li>
<li><p>The <strong>Use tax</strong> field for the sales tax group is selected in the <strong>Sales tax groups</strong> form.</p></li>
</ul></td>
<td><ol>
<li><p>If the tax amount is recoverable, the <strong>Sales tax receivable</strong> field in the <strong>Ledger posting groups</strong> form. (Click <strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Sales tax</strong> &gt; <strong>Ledger posting groups</strong>.)</p></li>
<li><p>If the tax amount is not recoverable, the <strong>Use tax expense</strong> field in the <strong>Ledger posting groups</strong> form.</p></li>
</ol></td>
<td><ol>
<li><p>If the invoice line references a purchase order line, use the account distribution for the purchase order line.</p></li>
<li><p>Use the financial dimensions from the extended price or the accounting distributions for the charge on the vendor invoice line.</p></li>
<li><p>Use the financial dimension values from the vendor invoice line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Header charge</p></td>
<td><ol>
<li><p>If <strong>Ledger account</strong> is selected in the debit <strong>Type</strong> field in the <strong>Charges code</strong> form, the debit <strong>Account</strong> field in the <strong>Charges code</strong> form. (Click <strong>Accounts payable</strong> &gt; <strong>Setup</strong> &gt; <strong>Charges</strong> &gt; <strong>Charges code</strong>.)</p></li>
<li><p>If <strong>Customer/Vendor</strong> is selected in the debit <strong>Type</strong> field in the <strong>Charges code</strong> form, the credit <strong>Account</strong> field in the <strong>Charges code</strong> form.</p></li>
</ol></td>
<td><ol>
<li><p>If the invoice line references a purchase order line, use the account distribution for the purchase order line.</p></li>
<li><p>If the main account is an allocation account, use the default value from the allocation account definition.</p></li>
<li><p>Use the financial dimension default template values from the vendor invoice header.</p></li>
<li><p>Use the financial dimension values from the vendor invoice line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Header discount</p></td>
<td><ol>
<li><p>The <strong>Main account</strong> field for the <strong>Vendor invoice discount</strong> posting type in the <strong>Accounts for automatic transactions</strong> form. (Click <strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Posting</strong> &gt; <strong>Accounts for automatic transactions</strong>.)</p></li>
</ol></td>
<td><ol>
<li><p>If the invoice line references a purchase order line, use the account distribution for the purchase order line.</p></li>
<li><p>Use the financial dimensions from the accounting distributions for the extended price on the vendor invoice line.</p></li>
<li><p>Use the financial dimension values from the vendor invoice line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
</tbody>
</table>


Accounting distributions for taxes cannot be created until taxes are calculated. To calculate sales taxes, you must complete one of the following tasks in the **Vendor invoice** form:

  - View the invoice total. (On the **Action Pane**, on the **Vendor invoice** tab, in the **Summary** group, click **Totals**.)

  - View the sales tax. (On the **Action Pane**, on the **Financials** tab, click **Sales tax**.)

  - View the subledger journal. (On the **Action Pane**, on the **Financials** tab, click **Subledger journal**.)

  - View accounting distributions for the complete vendor invoice. (On the **Action Pane**, on the **Financials** tab, click **View distributions**.)

  - Place the vendor invoice on hold. (Select the **On hold** check box.)

  - Post the vendor invoice.

## Subledger journals for vendor invoices

Before you post a vendor invoice, you can view the full accounting entry of the invoice, which includes debits and credits, to verify that the invoice is being posted to the correct accounts. This view of the full accounting entry is called a subledger journal.

If the subledger journal entry is incorrect when you preview it before you journalize the vendor invoice, you cannot modify the subledger journal entry. Instead, you must modify the accounting distributions or the posting profile. The accounting distributions are used to define one side of the accounting entry, the debit or the credit. The offsetting subledger journal account entry is created by using the posting profiles, such as from the vendor account or tax.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

