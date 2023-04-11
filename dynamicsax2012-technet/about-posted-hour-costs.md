---
title: About posted hour costs
TOCTitle: About posted hour costs
ms:assetid: da3b9716-ea4b-4940-bbe1-4bfc0b9c62cd
ms:mtpsurl: https://technet.microsoft.com/library/Aa619858(v=AX.60)
ms:contentKeyID: 36059660
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- hour costs
audience: Application User
ms.search.region: Global
---

# About posted hour costs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Options for posting hour costs are set in the **Project groups** form.

The following table lists where posted hour costs are debited and credited in the ledger.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Option</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Profit and loss</strong></p></td>
<td><p>Costs of hours are debited to the cost account and credited to the payroll allocation account when the journal is posted. This option is mandatory on fixed-price projects, investment projects, and cost projects. When this option is selected, revenue can be accrued on the hour transaction.</p>
<p></p></td>
</tr>
<tr class="even">
<td><p><strong>Balance</strong></p></td>
<td><p>Hours are debited to the cost value account and credited to the payroll allocation account when the journal is posted. This option is available for internal projects and time and material projects.</p></td>
</tr>
<tr class="odd">
<td><p><strong>No ledger</strong></p></td>
<td><p>No posting occurs on ledger accounts when hours are posted from journals. Upon invoicing, hours are debited to the cost account and credited to the payroll allocation account. This option is available for time and material projects and internal projects.</p></td>
</tr>
<tr class="even">
<td><p><strong>Never ledger</strong></p></td>
<td><p>No posting occurs on ledger accounts when hours are posted from journals. This option is mandatory on time projects and optional on time and material projects and internal projects. When this option is selected, revenue can be accrued on the hour transaction. Hour transactions are never posted to ledger accounts on journal posting or upon invoicing.</p></td>
</tr>
</tbody>
</table>


## See also

[About project costs](about-project-costs.md)

[Configuring posting accounts](configuring-posting-accounts.md)

[About posting setup for project transactions](about-posting-setup-for-project-transactions.md)

[About WIP cost value accounts](about-wip-cost-value-accounts.md)

[Project groups (form)](https://technet.microsoft.com/library/aa590435\(v=ax.60\))

[Post costs (form)](https://technet.microsoft.com/library/aa583560\(v=ax.60\))

[Hour transactions (form)](https://technet.microsoft.com/library/aa572825\(v=ax.60\))

  


