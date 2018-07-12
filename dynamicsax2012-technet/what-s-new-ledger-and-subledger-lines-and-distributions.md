---
title: "What's new: Ledger and subledger lines and distributions"
TOCTitle: Ledger and subledger lines and distributions
ms:assetid: a7a697ad-25fc-4861-8830-fb756a92df96
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527213(v=AX.60)
ms:contentKeyID: 59623342
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Ledger and subledger lines and distributions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Accounting distributions and subledger journal entries are the foundation of the new accounting framework. Accounting distributions let a user define how amounts on a source document affect account balances, such as ledger accounts in **General ledger** or projects. A subledger journal entry is the accounting entry that is created for a source document. The subledger journal entry remains in the subledger and can be previewed before a source document is journalized.

The addition of subledger journal entries means that additional performance optimization and summarization rules can be defined for the transfer of subledger journal entries to **General ledger**. The transfer process can be defined so that it occurs synchronously or asynchronously. During the transfer process, a user has the option to summarize the subledger journal entries for similar source documents to reduce the amount of data in **General ledger**.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>Optional. You might not use this feature, depending on how you run your business. The functionality is always enabled, but if your business requires no modifications to default ledger accounts, you do not have to use the functionality.</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>Accounts payable</p>
<p>Accounts receivable</p>
<p>Travel and expense</p>
<p>Procurement and sourcing</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Technical decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

Before you journalize a source document, you can preview the accounting entry to verify that the amounts are being journalized to the correct ledger accounts. This view of the accounting entry is known as a subledger journal entry.

You cannot modify subledger journal entries directly. To modify subledger journal entries, you must correct the accounting distributions, posting profile, or posting definitions. Accounting distributions are used to define how an amount is accounted for. For example, an accounting distribution specifies the revenue or expense ledger account that an amount is posted to in **General ledger**. The primary information about an accounting distribution is the amount on the source document line and the ledger account for which that amount is distributed.

When there are common patterns that you use to distribute amounts on a source document line, you can use a template that contains combinations of percentage and dimension values. The information in the template is used to create the accounting distributions for amounts on a source document line.

## Special considerations

  - You cannot split accounting distributions for stocked items or fixed assets.

  - Existing posting profiles are used, so that additional setup is not required.

  - You can set up asynchronous and summarization options.

  - New terminology is used in Microsoft Dynamics AX 2012, as the following table shows.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Definition</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Post</p></td>
<td><p>Journalize</p></td>
<td><p>To record a documented business event in the subledger journal.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Post</p></td>
<td><p>To record the monetary value of an economic event in a specific account, or to summarize and reclassify general and subsidiary journal account entries into general and subsidiary ledger account entries.</p></td>
</tr>
<tr class="odd">
<td><p>Transaction</p></td>
<td><p>Source document</p></td>
<td><p>An original record that provides evidence that one or more business events occurred.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Journal entry</p></td>
<td><p>A record of a business event.</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Transaction</p></td>
<td><p>A social or physical economic exchange action.</p></td>
</tr>
</tbody>
</table>


## Comparison with AX 2009

The functionality for accounting distributions and subledger journal entries is new in AX 2012. This functionality has been implemented in the following source documents:

  - Purchase requisitions

  - Purchase orders

  - Product receipts (previously known as PO packing slips)

  - Vendor invoices

  - Free text invoices

  - Travel requisitions

  - Expense reports

## Functionality

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Preview the accounting entry of a source document before you journalize the entry in the subledger and transfer it to <strong>General ledger</strong>.</p></td>
<td><p>Users had limited visibility of what was actually journalized and transferred to <strong>General ledger</strong>.</p></td>
<td><p>The full accounting entry is displayed in all currencies before the entry is journalized and transferred to <strong>General ledger</strong>.</p></td>
<td><p>The requirement for period-end adjustments that use a general journal is minimized.</p></td>
</tr>
<tr class="even">
<td><p>Use a template to define accounting distributions.</p></td>
<td><p>Not available</p></td>
<td><p>Templates can be created for financial dimension values, but not for the main account, to create accounting distributions.</p></td>
<td><p>Data entry is simplified.</p></td>
</tr>
<tr class="odd">
<td><p>Distribute an amount by using various allocation factors.</p></td>
<td><p>Not available</p></td>
<td><p>An amount can be distributed by amount, by percentage, by quantity, or equally.</p></td>
<td><p>A user can define the allocation factor that is used to distribute an amount.</p></td>
</tr>
<tr class="even">
<td><p>Have the flexibility to define a batch for each source document type, so that you can transfer to <strong>General ledger</strong>.</p></td>
<td><p>Batches were available but had to be manually assigned to each source document.</p></td>
<td><p>Batches are automatically created or defined by a user, and are automatically assigned to a source document type.</p></td>
<td><p>Processing is postponed to maximize responsiveness, and to minimize the time and effort that are required for data entry.</p></td>
</tr>
<tr class="odd">
<td><p>Define how the amount on one source document line can be accounted to more than one ledger account.</p></td>
<td><p>Not available</p></td>
<td><p>Users do not have to enter a separate source document line for each operating unit. Instead, one line is created, and the accounting distribution is split.</p></td>
<td><p>The amount of data entry is reduced, because operations, not accounting, determine how a source document is recorded.</p></td>
</tr>
<tr class="even">
<td><p>Define accounting distributions on an upstream source document.</p></td>
<td><p>Not available</p></td>
<td><p>Accounting distributions that are defined on a purchase requisition are used to determine the accounting distributions for all downstream source documents (purchase orders, product receipts, and vendor invoices).</p></td>
<td><p>Accounting consistency and accuracy are improved across the life cycle of the business event.</p></td>
</tr>
<tr class="odd">
<td><p>Support accounting for intercompany transactions.</p></td>
<td><p>Accounting for intercompany transactions was available only in journals.</p></td>
<td><p>If a source document supports intercompany transactions, the appropriate due to/due from account entries are created in the subledger journal entry.</p></td>
<td><p>The appropriate intercompany accounting entries are consistently created for any source document that supports intercompany transactions.</p></td>
</tr>
<tr class="even">
<td><p>Integrate accounting distributions and project accounting.</p></td>
<td><p>Not available</p></td>
<td><p>Source documents that support project accounting can use the accounting distributions to define how the amount is distributed to projects.</p></td>
<td><p>Operations, not project accounting, determine how a source document is recorded.</p></td>
</tr>
<tr class="odd">
<td><p>Validate and reserve budget, based on the accounting distribution information.</p></td>
<td><p>Not available</p></td>
<td><p>A user can define budget control rules, and then use those rules when he or she enters source documents.</p></td>
<td><p>You can make sure that purchases are within budget.</p></td>
</tr>
</tbody>
</table>


## More information

For more information, see the following topics:

  - [About accounting distributions and subledger journal entries for vendor invoices](about-accounting-distributions-and-subledger-journal-entries-for-vendor-invoices.md)

  - [About accounting distributions and subledger journal entries for purchase orders](about-accounting-distributions-and-subledger-journal-entries-for-purchase-orders.md)

  - [About accounting distributions and subledger journal entries for free text invoices](about-accounting-distributions-and-subledger-journal-entries-for-free-text-invoices.md)

  


