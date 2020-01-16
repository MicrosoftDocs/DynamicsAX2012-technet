---
title: About WIP invoice on-account accounts
TOCTitle: About WIP invoice on-account accounts
ms:assetid: 79df0853-2ff2-476a-815c-49a7e3ed4aa1
ms:mtpsurl: https://technet.microsoft.com/library/Aa550063(v=AX.60)
ms:contentKeyID: 42517328
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- invoice
- on-account
- WIP
audience: Application User
ms.search.region: Global
---

# About WIP invoice on-account accounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create an on-account invoice for work in process (WIP) on a project. The amount that you select for the WIP invoice can be related to specific costs or to a specified percentage of the total contract amount. You can select an estimated amount on the invoice, and then reverse the estimate when you calculate the actual invoice amount earned on a project. For more information about how to create an on-account invoice, see [Create on-account invoices for all projects](create-on-account-invoices-for-all-projects.md).

## Postings for an on-account invoice

Before you can create a WIP on-account invoice, you must select ledger accounts in the **Project groups** form to use for posting the invoice. The postings by project transaction type for an on-account invoice are shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction</p></th>
<th><p>Posting results</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Invoice</strong></p></td>
<td><p>The account is credited when you create an invoice for a Time and material project.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice on account</strong></p></td>
<td><p>The account is credited when you create an on-account invoice for a project.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Post estimate</strong></p></td>
<td><p>The account is credited on Fixed-price projects if you select <strong>Profit and loss</strong> in the <strong>On-account invoicing</strong> field in the <strong>Project groups</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reverse estimate</strong></p></td>
<td><p>The account is debited on Fixed-price projects if you select <strong>Profit and loss</strong> in the <strong>On-account invoicing</strong> field in the <strong>Project groups</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Eliminate</strong></p></td>
<td><p>The account is debited.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reverse elimination</strong></p></td>
<td><p>The account is credited.</p></td>
</tr>
</tbody>
</table>


## See also

[Configuring work in process (WIP) accounts](configuring-work-in-process-wip-accounts.md)

[About on-account invoicing](about-on-account-invoicing.md)

[Create and post invoice proposals](create-and-post-invoice-proposals.md)

[Project groups (form)](https://technet.microsoft.com/library/aa590435\(v=ax.60\))

[On-account transactions (form)](https://technet.microsoft.com/library/aa557380\(v=ax.60\))

  


