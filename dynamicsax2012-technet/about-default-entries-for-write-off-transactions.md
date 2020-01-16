---
title: About default entries for write-off transactions
TOCTitle: About default entries for write-off transactions
ms:assetid: a42e5380-1991-4005-bfbb-70fedab0199d
ms:mtpsurl: https://technet.microsoft.com/library/Hh209464(v=AX.60)
ms:contentKeyID: 36058816
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- balances
- transactions
- collections
- balance
- collection
- transaction
- customer
- customers
- write off
- writeoff
- write-off
audience: Application User
ms.search.region: Global
---

# About default entries for write-off transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following tables show the default entries that are used when a write-off transaction is created by clicking **Write off** in the **Collections** form or on the **All customers** or **Open customer invoices** list pages. You can change this information in the journal before the transaction is posted.

## Journal

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Default entry</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p>The <strong>Write-off journal</strong> field value in the <strong>Accounts receivable parameters</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Description</strong></p></td>
<td><p><strong>Write off transactions for %1 %2</strong>.</p></td>
</tr>
</tbody>
</table>


## Customer write-off journal lines

If the marked transactions contain multiple combinations of currency code, financial dimensions, and posting profile, a separate journal line is created for each combination.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Default entry</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>The date that you enter when you click <strong>Write off</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Account type</strong></p></td>
<td><p><strong>Customer</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Account</strong></p></td>
<td><p>The customer account that is displayed in the <strong>Collections</strong> form or on a list page.</p></td>
</tr>
<tr class="even">
<td><p><strong>Description</strong></p></td>
<td><p><strong>Write off transactions for %1 %2</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Debit</strong> or <strong>Credit</strong></p></td>
<td><p>The amount is the total of the open (not settled) transactions for the customer, for transactions that have the same currency, financial dimensions, and posting profile.</p>
<p>If the total of the amounts is a debit, a credit is created.</p>
<p>If the total of the amounts is a credit, a debit is created.</p></td>
</tr>
<tr class="even">
<td><p><strong>Offset account type</strong></p></td>
<td><p><strong>Ledger</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Offset account</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p><strong>Posting profile</strong></p></td>
<td><p>The posting profile that is used for the transaction that is being written off.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales tax group</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p><strong>Item sales tax group</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="odd">
<td><p><strong>Reason code</strong></p></td>
<td><p>The reason code that you enter when you click <strong>Write off</strong>. The default entry is taken from the <strong>Reason code</strong> field in the <strong>Accounts receivable parameters</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Posting profile</strong></p></td>
<td><p>The <strong>Posting profile</strong> field value from the transaction or transactions that are being written off.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Method of payment</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment specification</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="odd">
<td><p><strong>Prepayment journal voucher</strong></p></td>
<td><p>Cleared</p></td>
</tr>
<tr class="even">
<td><p><strong>Bank transaction type</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="odd">
<td><p>All remaining fields</p></td>
<td><p>Default entries are the same as they are when a new journal line is created in the <strong>Journal voucher</strong> form.</p>
<p>No payment fee lines are created.</p></td>
</tr>
</tbody>
</table>


## General ledger write-off journal lines

If the marked transactions contain multiple combinations of currency code, financial dimensions, and posting profile, a separate journal line is created for each combination.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Default entry</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>The date that you enter when you click <strong>Write off</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Account type</strong></p></td>
<td><p><strong>Ledger</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Account</strong></p></td>
<td><p>The write-off account from the posting profile that is specified in the <strong>Posting profile</strong> field in the <strong>Ledger and sales tax</strong> area of the <strong>Accounts receivable parameters</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Description</strong></p></td>
<td><p><strong>Write off transactions for %1 %2</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Debit</strong> or <strong>Credit</strong></p></td>
<td><p>The amount is the total of the open (not settled) transactions for the customer, for transactions that have the same combination of currency code, financial dimensions, and posting profile. If the <strong>Separate sales tax</strong> check box in the <strong>Accounts receivable parameters</strong> form is not selected, the amount includes sales tax.</p>
<p>If the amount on the customer write-off journal line is a debit, a credit is created.</p>
<p>If the amount on the customer write-off journal line is a credit, a debit is created.</p></td>
</tr>
<tr class="even">
<td><p><strong>Offset account type</strong></p></td>
<td><p><strong>Ledger</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Offset account</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales tax group</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="odd">
<td><p><strong>Item sales tax group</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p><strong>Reason code</strong></p></td>
<td><p>The reason code that you enter when you click <strong>Write off</strong>. The default entry is taken from the <strong>Reason code</strong> field in the <strong>Accounts receivable parameters</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Posting profile</strong></p></td>
<td><p>The <strong>Posting profile</strong> field value in the <strong>Accounts receivable parameters</strong> form.</p>
<p>A write-off account must be set up in the posting profile. For more information, see <a href="set-up-collections.md">Set up collections</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Method of payment</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="odd">
<td><p><strong>Payment specification</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p><strong>Prepayment journal voucher</strong></p></td>
<td><p>Cleared</p></td>
</tr>
<tr class="odd">
<td><p><strong>Bank transaction type</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p><strong>Financial dimensions</strong></p></td>
<td><p>The financial dimensions from the marked transactions.</p></td>
</tr>
<tr class="odd">
<td><p>Fixed asset <strong>Transaction type</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p>All remaining fields</p></td>
<td><p>Default entries are the same as they are when a new journal line is created in the <strong>Journal voucher</strong> form.</p>
<p>No payment fee lines are created.</p></td>
</tr>
</tbody>
</table>


## Sales tax write-off journal lines

A sales tax write-off journal line is created only if the **Separate sales tax** check box in the **Accounts receivable parameters** form is selected. If the marked transactions contain multiple combinations of sales tax payable account, financial dimensions, and sales tax code, a separate journal line is created for each combination.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Default entry</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>The date that you enter when you click <strong>Write off</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Account type</strong></p></td>
<td><p><strong>Ledger</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Account</strong></p></td>
<td><p>The sales tax payable account from the original transactions.</p></td>
</tr>
<tr class="even">
<td><p><strong>Description</strong></p></td>
<td><p><strong>Write off transactions for %1 %2</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Debit</strong> or <strong>Credit</strong></p></td>
<td><p>The amount is the total of the tax amounts for the open (not settled) transactions for the customer, for transactions that have the same combination of sales tax payable account, financial dimensions, and sales tax code.</p>
<p>If the amount on the customer write-off journal line is a debit, a credit is created.</p>
<p>If the amount on the customer write-off journal line is a credit, a debit is created.</p></td>
</tr>
<tr class="even">
<td><p><strong>Offset account type</strong></p></td>
<td><p><strong>Ledger</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Offset account</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales tax group</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="odd">
<td><p><strong>Item sales tax group</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p><strong>Reason code</strong></p></td>
<td><p>The reason code that you enter when you click <strong>Write off</strong>. The default entry is taken from the <strong>Reason code</strong> field in the <strong>Accounts receivable parameters</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Posting profile</strong></p></td>
<td><p>The <strong>Posting profile</strong> field value in the <strong>Accounts receivable parameters</strong> form.</p>
<p>A write-off account must be set up in the posting profile. For more information, see <a href="set-up-collections.md">Set up collections</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Method of payment</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="odd">
<td><p><strong>Payment specification</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p><strong>Prepayment journal voucher</strong></p></td>
<td><p>Cleared</p></td>
</tr>
<tr class="odd">
<td><p><strong>Bank transaction type</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p><strong>Financial dimensions</strong></p></td>
<td><p>The financial dimensions from the original sales tax transactions.</p></td>
</tr>
<tr class="odd">
<td><p>Fixed asset <strong>Transaction type</strong></p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p>All remaining fields</p></td>
<td><p>Default entries are the same as they are when a new journal line is created in the <strong>Journal voucher</strong> form.</p>
<p>No payment fee lines are created.</p></td>
</tr>
</tbody>
</table>


## See also

[Collections and credit in Accounts receivable](collections-and-credit-in-accounts-receivable.md)

[Collections (form)](https://technet.microsoft.com/library/hh209726\(v=ax.60\))

[Key tasks: Collections](key-tasks-collections.md)

[Set up collections](set-up-collections.md)

[Waive, reinstate, or reverse interest or fees](waive-reinstate-or-reverse-interest-or-fees.md)

  


