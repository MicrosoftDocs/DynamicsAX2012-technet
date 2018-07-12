---
title: Posting sales tax amounts for intercompany transactions
TOCTitle: Posting sales tax amounts for intercompany transactions
ms:assetid: cd5a6892-a3e4-4b7c-bdf0-77af6202c5e6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn135228(v=AX.60)
ms:contentKeyID: 53918025
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- source
- sales taxes
- destination
- intercompany transaction
- sales tax posting
- intercompany transactions
audience: Application User
ms.search.region: Global
---

# Posting sales tax amounts for intercompany transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 5 for AX 2012.</P>



This topic explains how you can post sales tax amounts for intercompany transactions to different legal entities, depending on your organization’s requirements. In Microsoft Dynamics AX, you can create intercompany transactions, which are transactions between legal entities in the same organization. Those transactions are posted to general ledger accounts that are consolidated, or combined, into accounts for a single, consolidated legal entity.

For specific journals, when you post an intercompany transaction that includes sales tax amounts, you can select to post the sales tax amount to either the source legal entity or the destination legal entity. Those journals include the **General journal**, **Invoice journal**, and **Invoice approval journal** forms. Sales tax amounts for intercompany transactions in all other journals are posted to the destination legal entity.

To select the legal entity to post sales tax amounts to, use the **Legal entity for intercompany tax posting** field in the **General ledger parameters** form. You can also change the option in the **Legal entity for intercompany tax posting** field in the **General journal**, **Invoice journal**, and **Invoice approval journal** forms.

Before you select whether to post sales taxes to the source or destination legal entity, you should become familiar with the following terms.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Term</p></th>
<th><p>Definition</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Intercompany transaction</p></td>
<td><p>A transaction between legal entities that are part of the same organization that consolidates the accounts of the legal entities.</p></td>
</tr>
<tr class="even">
<td><p>Destination legal entity</p></td>
<td><p>The legal entity that the expense or revenue is being distributed to, or a bank account.</p></td>
</tr>
<tr class="odd">
<td><p>Source legal entity</p></td>
<td><p>The legal entity where the payable to the vendor or the receivable to the customer is recorded.</p></td>
</tr>
</tbody>
</table>


## 1\. Select which legal entity to post sales tax amounts to for intercompany transactions

You can select which legal entity to post sales tax amounts to when the taxes are part of an intercompany transaction. Use the **General ledger parameters** form to select this option.

To indicate the legal entity to post sales tax transactions to, follow these steps:

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click **Sales tax**.

3.  In the **Legal entity for intercompany tax posting** field, select whether to post intercompany tax amounts to the legal entity where the transaction originates or to the legal entity where the intercompany transactions are posted to. Use the information in the following table to decide which legal entity to select.
    
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
    <td><p><strong>Destination</strong></p></td>
    <td><p>Select this option if your organization uses U.S. sales and use tax. (This is your only option if the <strong>Apply U.S. taxation rules</strong> option is selected in the <strong>General ledger parameters</strong> form.)</p>
    <p>Sales tax amounts for intercompany transactions are posted to the legal entity that the expense or revenue is being distributed to.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Source</strong></p></td>
    <td><p>Sales tax amounts for intercompany transactions are posted to the legal entity where the payable to the vendor, the receivable to the customer, or a bank account is recorded.</p></td>
    </tr>
    </tbody>
    </table>
    
    The **Legal entity for intercompany tax posting** field is available only when the **Intercompany accounting** configuration key is selected.
    
    If you are not sure which option to select, contact a tax expert to decide which legal entity should receive the tax amounts, depending on the sales tax regulations in the applicable jurisdictions.

## 2\. Modify or view the legal entity for intercompany tax posting on journals

The option that you selected in the **Legal entity for intercompany tax posting** field in the **General ledger parameters** form is displayed in the journal form when you create an intercompany transaction.

You can change the option in the **Legal entity for intercompany tax posting** field in the **General journal**, **Invoice journal**, and **Invoice approval journal** forms. All other journal forms work as if the tax obligation is set to **Destination**.

To modify the legal entity to post sales tax transactions to, follow these steps:

1.  Open one of the following journal forms:
    
      - **General journal** form – Click **General ledger** \> **Journals** \> **General journal**.
    
      - **Invoice journal** form – Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.
    
      - **Invoice approval journal** form – Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**.

2.  On the **Setup** tab, you can view and change the selection in the **Legal entity for intercompany tax posting** field.

## 3\. (Optional) Print reports to view sales tax data across legal entities

When **Source** is selected in the **Legal entity for intercompany tax posting** field in a journal, you can print the following reports across legal entities:

  - **Statement by dimensions** (LedgerTransStatement)

  - **Ledger transaction list** (LedgerTransListAccount)

  - **Sales tax specification** (TaxTransCode)

  - **Sales tax specification by ledger transaction** (TaxSpecPerLedgerTrans)

  - **Sales tax transactions - details** (TaxTransDetail)

  - **Transaction list by date** (LedgerTransListDate)

If you print the reports from the source legal entity, the expense or revenue account from the destination legal entity is printed on the reports. If you print the reports from the destination legal entity, the transaction is not printed on the reports.

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
<td><p><strong>Intercompany accounting</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To post sales tax amounts for intercompany transactions, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p>Maintain ledger journals and transactions (LedgerJournalsAndTransactionsMaintain)</p></li>
<li><p>Maintain vendor invoices (VendInvoiceVendorInvoicesMaintain)</p></li>
<li><p>Maintain vendor payments (PaymVendorPaymentsMaintain)</p></li>
<li><p>Maintain customer payments (PaymCustomerPaymentsMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


