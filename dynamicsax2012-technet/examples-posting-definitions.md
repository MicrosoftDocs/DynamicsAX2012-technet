---
title: 'Examples: Posting definitions'
TOCTitle: 'Examples: Posting definitions'
ms:assetid: 0543bf68-6ee4-4f8e-a513-1d30b9be3108
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242107(v=AX.60)
ms:contentKeyID: 36055951
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- examples of posting definitions
- posting definition examples
audience: Application User
ms.search.region: Global
---

# Examples: Posting definitions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you read this topic, you should be familiar with posting definitions and transaction posting definitions. For information, see [About posting definitions](about-posting-definitions.md).


> [!NOTE]
> <P>For information about how to use posting definitions in the public sector, search for the “Examples: Posting definitions (Public sector)” topic.</P>



The following examples can be set up in the **Posting definitions** form. (Click **General ledger** \> **Setup** \> **Posting** \> **Posting definitions**.) Each example contains these sections:

  - Posting definition – Match criteria

  - Posting definition – Generated entries

  - Transactions with the accounts, dimension values, and amounts

  - Ledger entries generated from the posting definition

When a match occurs between the accounts and dimension values in the **Match criteria** pane for the posting definition and the accounts and dimension values on the transaction, ledger entries are generated based on the **Generated entries** pane for the posting definition.


> [!NOTE]
> <P>To associate a posting definition with a specific transaction type, use the <STRONG>Transaction posting definitions</STRONG> form. (Click <STRONG>General ledger</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Posting</STRONG> &gt; <STRONG>Transaction posting definitions</STRONG>.) After you associate a posting definition with a transaction type and select <STRONG>Use posting definitions</STRONG> in the <STRONG>General ledger parameters</STRONG> form, all transactions of the selected transaction type must use posting definitions.</P>



## Example: Purchase order encumbrances

When you enable encumbrance processing by selecting **Enable encumbrance process** in the **General ledger parameters** form, posting definitions must be used to record encumbrances to the general ledger for any accounts that should be reserved. In most cases, all expense accounts are reserved on the balance sheet.

Posting definitions for encumbrances are set up for the **Purchasing** module in the **Posting definitions** form. Then, in the **Purchasing** area of the **Transaction posting definitions** form, you can select the **Purchase order** transaction type to associate the posting definition with purchase orders.

All voucher transactions for purchase order encumbrances must balance, which means that debits must equal credits, in each unique dimension on a voucher.

**Posting definition – Match criteria**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong></p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Account Structure - P&amp;L</p></td>
<td><p>*</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure are part of the matching rule.

**Posting definition – Generated entries**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>300143 - -</p>
<p>(Encumbrance account)</p></td>
<td><p><strong>Same</strong></p></td>
</tr>
<tr class="even">
<td><p>Balance</p></td>
<td><p>300144 - -</p>
<p>(Reserve for encumbrance account)</p></td>
<td><p><strong>Balancing</strong></p></td>
</tr>
</tbody>
</table>


**Transactions with the accounts, dimension values, and amounts**

The accounts and dimension values come from the accounting distributions that you enter for a purchase order line, or they come from the accounts and dimensions that are automatically generated based on the default settings for vendors, items, categories, and dimension templates.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>606400-OU_1-OU_3566-Training</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


**Ledger entries generated from the posting definition**

Generated ledger entries are created to record the encumbrances.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>300143-OU_1-OU_3566-Training</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>300144-OU_1-OU_3566-Training</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


In this example, any account that is part of Account Structure - P\&L matches the posting definition criteria. Therefore, when 606500-OU\_1-OU\_3566-Training is evaluated, generated entries are created for the accounts that are defined in the **Generated entries** pane for the posting definition.

## Example: Budget appropriations

When you enable budget appropriation by selecting **Enable budget appropriation** in the **General ledger parameters** form, posting definitions must be used to record budget register entries to the general ledger. When a budget control configuration is active and is turned on, posting definitions and transaction posting definitions can be used to support the recording of appropriation, revision, transfer, project, fixed asset, and supply and demand forecast entries to the general ledger.

A posting definition for budget register entries that has a budget type of **Original budget**, and that has appropriations enabled, can be set up by selecting the **Budget** module in the **Posting definitions** form. Then, in the **Budget** area of the **Transaction posting definitions** form, you can use budget codes to associate the posting definition with budget register entries that have a budget type of **Original budget**.

When budget appropriations and posting definitions are enabled, the budget register entries are recorded for budget control and in the general ledger.

**Posting definition – Match criteria**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong></p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Account Structure - P&amp;L</p></td>
<td><p>*</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure are part of the matching rule.

**Posting definition – Generated entries**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Account structure</p></td>
<td><p>300145 - -</p>
<p>(Estimated revenue account)</p></td>
<td><p><strong>Same</strong></p></td>
</tr>
<tr class="even">
<td><p>Account structure</p></td>
<td><p>300146 - -</p>
<p>(Appropriation account)</p></td>
<td><p><strong>Balancing</strong></p></td>
</tr>
</tbody>
</table>


**Transactions with the accounts, dimension values, and amounts**

You enter the accounts, dimension values, and amounts for the budget account entry in the **Budget register entry** form. (Click **Budgeting** \> **Common** \> **Budget register entries** \> **All budget register entries**. Click **Budget register entry**.)

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>606400-OU_1-OU_3566-Training</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


**Ledger entries generated from the posting definition**

Generated ledger entries are created to record the original budget in each dimension.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>300145-OU_1-OU_3566-Training</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>300146-OU_1-OU_3566-Training</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


In this example, any account that is part of Account Structure - P\&L matches the posting definition criteria. Therefore, when 606400-OU\_1-OU\_3566-Training is evaluated, the generated ledger entries are created.

## See also

[About posting definitions](about-posting-definitions.md)

[Set up posting definitions](set-up-posting-definitions.md)

[Assign posting definitions to transaction posting types](assign-posting-definitions-to-transaction-posting-types.md)

[Posting definitions (form)](https://technet.microsoft.com/en-us/library/hh227607\(v=ax.60\))

[Transaction posting definitions (form)](https://technet.microsoft.com/en-us/library/hh242550\(v=ax.60\))

  


