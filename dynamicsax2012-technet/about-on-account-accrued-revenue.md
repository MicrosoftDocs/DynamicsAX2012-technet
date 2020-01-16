---
title: About on-account accrued revenue
TOCTitle: About on-account accrued revenue
ms:assetid: a5ee6adf-73dc-4e8a-94cf-492f8cff489e
ms:mtpsurl: https://technet.microsoft.com/library/Aa550272(v=AX.60)
ms:contentKeyID: 42517334
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accrued revenue
- profit and loss
- on-account invoicing
audience: Application User
ms.search.region: Global
---

# About on-account accrued revenue 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can accrue revenue on Fixed-price projects and on Time and material projects while a project is in progress. You do this by creating an on-account invoice. The amount of accrued revenue that you select can be related to specific costs or to a specified percentage of the total contract amount. You can post an estimated amount as accrued revenue, and then reverse the estimate when you calculate the actual revenue earned on a project. For more information about how to create an on-account invoice, see [Create on-account invoices for all projects](create-on-account-invoices-for-all-projects.md).

Before you can accrue on-account revenue, you must select the ledger accounts to use for posting accrued revenue in the **Project groups** form. The following table shows postings by project transaction type for on-account accrued revenue.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type</p></th>
<th><p>Posting results</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Post estimate</strong></p></td>
<td><p>If you select <strong>On-account invoicing</strong> in the <strong>Profit and loss</strong> field of the <strong>Project groups</strong> form for Fixed-price projects, the selected account is debited, and the on-account invoice amount is posted to the balance sheet.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reverse estimate</strong></p></td>
<td><p>If you select <strong>On-account invoicing</strong> in the <strong>Profit and loss</strong> field of the <strong>Project groups</strong> form, the account is credited.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Eliminate</strong></p></td>
<td><p>The account is credited.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reverse elimination</strong></p></td>
<td><p>The account is debited.</p></td>
</tr>
</tbody>
</table>


## See also

[About on-account invoicing](about-on-account-invoicing.md)

[Create and post invoice proposals](create-and-post-invoice-proposals.md)

[On-account transactions (form)](https://technet.microsoft.com/library/aa557380\(v=ax.60\))

[Project groups (form)](https://technet.microsoft.com/library/aa590435\(v=ax.60\))

  


