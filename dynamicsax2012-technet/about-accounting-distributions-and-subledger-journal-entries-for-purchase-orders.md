---
title: About accounting distributions and subledger journal entries for purchase orders
TOCTitle: About accounting distributions and subledger journal entries for purchase orders
ms:assetid: 2d8ed8c6-78e9-46a3-9054-0798e30709b8
ms:mtpsurl: https://technet.microsoft.com/library/Hh208518(v=AX.60)
ms:contentKeyID: 36056262
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About accounting distributions and subledger journal entries for purchase orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Accounting distributions are used to define how an amount will be accounted for, such as how the expense, asset, tax, or charges will be encumbered on the purchase order or accounted for on the product receipt or vendor invoice.

If you are using Budgeting or encumbrances, every amount that must be accounted for when the purchase order is confirmed will have one or more accounting distributions.

If you are not using Budgeting or encumbrances, every amount that must be accounted for on the product receipts or vendor invoices for the purchase order will have an accounting distribution. However, the accounting distribution might contain incomplete information, such as the ledger account. If the ledger account is incomplete, you might have to correct the ledger account on the purchase order or accounting distribution for the vendor invoice before you can journalize the product receipt and the vendor invoice.

## Accounting distributions for purchase orders

You can use the following buttons in the **Purchase order** form to view, and possibly modify, the accounting distributions for each amount on the purchase order.

  - **Distribute amounts** – View and modify the accounting distributions for an individual line and any child lines, such as taxes or charges. You can also view and modify the accounting distributions for the child line directly from the **Sales tax transactions** form or the **Charges transactions** form.
    
      - Modify purchase order header amounts, such as charges or currency rounding amounts. (On the **Action Pane**, on the **Purchase** tab, in the **Accounting** group, click **Distribute amounts**.)
    
      - Modify purchase order line amounts. (In the **Purchase order lines** grid, click **Financials** \> **Distribute amounts**.)

  - **View distributions** – View the accounting distributions for all lines on the document. You cannot modify the accounting distributions from this view.
    
      - View header and line amounts. (On the **Action Pane**, on the **Financials** tab, in the **Accounting** group, click **View distributions**.)

You can split accounting distributions for purchase order lines that contain items that are not stocked.

You cannot split, modify, or delete the purchase order lines in the following situations:

  - The purchase order line contains stocked items.

  - The purchase order line contains fixed assets.

  - The purchase order line includes charges, taxes, or discounts.


> [!NOTE]
> <P>If the parent line contains an item that is not stocked and the accounting distributions are split, the child line will be split automatically to match the financial dimensions of the parent line. The accounting distributions for the child line cannot be additionally split or deleted, but depending on the setup of the child line, you might be able to modify the ledger account for the accounting distributions of the child line.</P>



When you enter a purchase order, each line will be distributed as follows.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of purchase order line</p></th>
<th><p>Order of priority that determines where the default main account is displayed from</p></th>
<th><p>Order of priority that determines which default financial dimension is displayed</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Stocked item</p></td>
<td><ol>
<li><p>The <strong>Main account</strong> field when <strong>Purchase expenditure for product</strong> is selected in the <strong>Posting</strong> form. (Click <strong>Inventory management</strong> &gt; <strong>Setup</strong> &gt; <strong>Posting</strong> &gt; <strong>Posting</strong>.)</p></li>
</ol></td>
<td><ol>
<li><p>Use the financial dimension values from the purchase order line.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>A procurement category, or an item that is not stocked</p></td>
<td><ol>
<li><p>The <strong>Main account</strong> field when <strong>Purchase expenditure for expense</strong> is selected in the <strong>Posting</strong> form. (Click <strong>Inventory management</strong> &gt; <strong>Setup</strong> &gt; <strong>Posting</strong> &gt; <strong>Posting</strong>.)</p></li>
</ol></td>
<td><ol>
<li><p>If the <strong>Allocation</strong> check box is selected for the main account in the <strong>Main accounts - chart of accounts: %1</strong> form, use the main account from the <strong>To account</strong> field in the <strong>Allocation rule</strong> form. (Click <strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Chart of accounts</strong> &gt; <strong>Chart of accounts</strong>. Select a main account and then click <strong>Edit</strong>. Select <strong>Companies</strong> in the <strong>Select the level of main account to display</strong> field and select the <strong>Allocation</strong> check box. Click <strong>Allocation terms</strong>.)</p></li>
<li><p>Use the financial dimension default template on the purchase order line.</p></li>
<li><p>Use the financial dimension values that are defined on the purchase order line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Fixed asset</p></td>
<td><ol>
<li><p>If <strong>Acquisition</strong> is selected in the <strong>Transaction type</strong> field on the <strong>Fixed assets</strong> tab of the purchase order line, the <strong>Main account</strong> field when <strong>Acquisition</strong> is selected in the <strong>Fixed asset posting profiles</strong> form. (Click <strong>Fixed assets</strong> &gt; <strong>Setup</strong> &gt; <strong>Fixed asset posting profiles</strong>.)</p></li>
<li><p>If <strong>Acquisition adjustment</strong> is selected in the <strong>Transaction type</strong> field on the <strong>Fixed assets</strong> tab of the purchase order line, the <strong>Main account</strong> field when <strong>Acquisition adjustment</strong> is selected in the <strong>Fixed asset posting profiles</strong> form.</p></li>
</ol></td>
<td><ol>
<li><p>Use the financial dimension values that are defined on the purchase order line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Project defined on the purchase order line</p></td>
<td><ol>
<li><p>If <strong>Balance</strong> is selected in the <strong>Post costs - item</strong> field in the <strong>Project groups</strong> form, the <strong>Main account</strong> field when <strong>Cost</strong> is selected in the <strong>Ledger posting setup</strong> form. (Click <strong>Project management and accounting</strong> &gt; <strong>Setup</strong> &gt; <strong>Posting</strong> &gt; <strong>Ledger posting setup</strong>.)</p></li>
<li><p>If <strong>Profit and loss</strong> is selected in the <strong>Post costs - item</strong> field in the <strong>Project groups</strong> form, the <strong>Main account</strong> field when <strong>Cost - item</strong> is selected in the <strong>Ledger posting setup</strong> form.</p></li>
</ol></td>
<td><ol>
<li><p>Use the financial dimension values that are defined on the purchase order line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Line discount</p></td>
<td><ol>
<li><p>The <strong>Main account</strong> field when <strong>Discount</strong> is selected in the <strong>Posting</strong> form. (Click <strong>Inventory management</strong> &gt; <strong>Setup</strong> &gt; <strong>Posting</strong> &gt; <strong>Posting</strong>.)</p></li>
<li><p>If a discount main account is not defined on the posting profile, the accounting distribution for the extended price on the purchase order line.</p></li>
</ol></td>
<td><ol>
<li><p>Use the financial dimension values on the accounting distributions for the extended price on the purchase order line.</p></li>
<li><p>Use the financial dimensions that are defined on the purchase order line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Purchase charge, entered on the <strong>Price and discount</strong> tab of the purchase order line</p></td>
<td><ol>
<li><p>The accounting distribution of the extended price on the purchase order line.</p></li>
</ol></td>
<td><ol>
<li><p>Use the financial dimension values on the extended price of the accounting distributions for the purchase order line.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Line charge</p></td>
<td><ol>
<li><p>If <strong>Ledger account</strong> is selected in the debit <strong>Type</strong> field in the <strong>Charges code</strong> form, the debit <strong>Account</strong> field in the <strong>Charges code</strong> form. (Click <strong>Accounts payable</strong> &gt; <strong>Setup</strong> &gt; <strong>Charges</strong> &gt; <strong>Charges code</strong>.)</p></li>
<li><p>If <strong>Item</strong> is selected in the debit <strong>Type</strong> field in the <strong>Charges code</strong> form, the accounting distributions for the extended price on the purchase order line.</p></li>
<li><p>If <strong>Customer/Vendor</strong> is selected in the debit <strong>Type</strong> field in the <strong>Charges code</strong> form, the credit <strong>Account</strong> field in the <strong>Charges code</strong> form.</p></li>
</ol></td>
<td><ol>
<li><p>Use the financial dimension values on the accounting distributions for the extended price on the purchase order line.</p></li>
<li><p>Use the accounting distributions from the purchase order line amount.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Tax, with the following condition:</p>
<ul>
<li><p>The <strong>Apply U.S. taxation rules</strong> check box is selected in the <strong>General ledger parameters</strong> form.</p></li>
</ul></td>
<td><ol>
<li><p>The extended price or the accounting distributions for the charge.</p></li>
</ol></td>
<td><ol>
<li><p>Use the financial dimension values on the extended price for the purchase order line or the accounting distributions for the charge.</p></li>
<li><p>Use the financial dimension values that are defined on the purchase order line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Tax, with the following conditions:</p>
<ul>
<li><p>The <strong>Apply U.S. taxation rules</strong> check box is cleared in the <strong>General ledger parameters</strong> form.</p></li>
<li><p>The <strong>Use tax</strong> check box for the sales tax group is cleared in the <strong>Sales tax groups</strong> form.</p></li>
</ul></td>
<td><ol>
<li><p>If the tax amount is recoverable, the <strong>Sales tax receivable</strong> field in the <strong>Ledger posting groups</strong> form. (Click <strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Sales tax</strong> &gt; <strong>Ledger posting groups</strong>.)</p></li>
<li><p>If the sales tax amount is not recoverable, the extended price or the accounting distribution for the charge.</p></li>
</ol></td>
<td><ol>
<li><p>Use the financial dimension values on the extended price for the purchase order line or the accounting distributions for the charge.</p></li>
<li><p>Use the financial dimension values that are defined on the purchase order line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Tax, with the following conditions:</p>
<ul>
<li><p>The <strong>Apply U.S. taxation rules</strong> check box is cleared in the <strong>General ledger parameters</strong> form.</p></li>
<li><p>The <strong>Use tax</strong> check box for the sales tax group is selected in the <strong>Sales tax groups</strong> form.</p></li>
</ul></td>
<td><ol>
<li><p>If the tax amount is recoverable, the <strong>Sales tax receivable</strong> field in the <strong>Ledger posting groups</strong> form. (Click <strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Sales tax</strong> &gt; <strong>Ledger posting groups</strong>.)</p></li>
<li><p>If the tax amount is not recoverable, the <strong>Use tax expense</strong> field in the <strong>Ledger posting groups</strong> form.</p></li>
</ol></td>
<td><ol>
<li><p>Use the financial dimension values on the extended price for the purchase order line or the accounting distributions for the charge.</p></li>
<li><p>Use the financial dimension values defined that are defined on the purchase order line.</p></li>
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
<li><p>If the main account is an allocation account, use the default main account from the allocation terms.</p></li>
<li><p>Use the financial dimension default template from the purchase order header.</p></li>
<li><p>Use the financial dimension values from the purchase order header.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Header discount</p></td>
<td><ol>
<li><p>The <strong>Main account</strong> field for the <strong>Vendor invoice discount</strong> posting type in the <strong>Accounts for automatic transactions</strong> form. (Click <strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Posting</strong> &gt; <strong>Accounts for automatic transactions</strong>.)</p></li>
</ol></td>
<td><ol>
<li><p>Use the financial dimension values on the accounting distributions for the extended price on the purchase order line.</p></li>
<li><p>Use the financial dimension values from the purchase order line.</p></li>
<li><p>Use the default financial dimension values from the main account in the <strong>Main accounts - chart of accounts: %1</strong> form.</p></li>
</ol></td>
</tr>
</tbody>
</table>


Accounting distributions for taxes cannot be created until taxes are calculated. To calculate sales taxes, you must complete one of the following tasks in the **Purchase order** form:

  - View the sales tax. (On the **Action Pane**, on the **Purchase** tab, click **Sales tax**.)

  - View the purchase order total. (On the **Action Pane**, on the **Purchase order** tab, in the **View** group, click **Totals**.)

  - View the cash flow forecast. (On the **Action Pane**, on the **Invoice** tab, click **Cash flow forecasts**.)

  - View distributions. (On the **Action Pane**, on the **Purchase** tab, in the **Accounting** group, click **View distributions**.)

  - View the subledger journal. (On the **Action Pane**, on the **Purchase** tab, in the **Accounting** group, click **Subledger journal**.)
    

    > [!NOTE]
    > <P>This button is available only if the <STRONG>Enable encumbrance process</STRONG> check box is selected in the <STRONG>General ledger parameters</STRONG> form.</P>



## Subledger journals for purchase orders

Subledger journals are available on a purchase order only if encumbrances are enabled for commitment accounting. (Click **General ledger** \> **Setup** \> **General ledger parameters**. Click **Ledger**. On the **Accounting rules** FastTab, select the **Use posting definitions** check box and the **Enable encumbrance process** check box.) Before you confirm a purchase order, you can view the full accounting entry, which includes debits and credits, to verify that the encumbrance is being posted to the correct accounts. This view of the full accounting entry is called a subledger journal entry. You can do this in the **Purchase order** form by clicking the **Purchase** tab on the **Action Pane**. In the **Accounting** group, click **Subledger journal**.

If the subledger journal entry is incorrect when you preview it before you confirm the purchase order, you cannot modify the subledger journal entry. Instead, you must modify the posting definition that is used by the purchase order. The ledger account from the accounting distribution is used in the posting definition, together with the amount and whether the amount is a debit or a credit. The posting definition compares that ledger account to the account in the **Match account number** field in the **Posting definitions** form. If the amounts match, the ledger accounts to create the subledger journal entry will be displayed in the **Generated entries** field group. If there is no match, the amount on the distribution is not encumbered.

  


