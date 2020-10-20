---
title: About WIP subscription accounts
TOCTitle: About WIP subscription accounts
ms:assetid: 5a19469d-e7ac-43c6-b84c-2a6f037e7623
ms:mtpsurl: https://technet.microsoft.com/library/Aa549078(v=AX.60)
ms:contentKeyID: 36057351
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- WIP
- subscription account
audience: Application User
ms.search.region: Global
---

# About WIP subscription accounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides an overview of how and where the WIP - Subscription account is applied and what parameter setup is required in the **Line properties** form. Use the account for accruing revenue that is then shown in the WIP statement.

## Account type

Balance

## Availability

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>License code</p></th>
<th><p>Configuration Key</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Service</strong></p></td>
<td><p><strong>Subscription</strong></p></td>
</tr>
</tbody>
</table>


## How the account is applied

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type</p></th>
<th><p>Project type</p></th>
<th><p>Account type</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Fee - subscription</strong></p></td>
<td><p><strong>Time and material</strong></p></td>
<td><p><strong>Balance</strong></p></td>
</tr>
</tbody>
</table>


## Parameter dependencies

Subscription group - Accrued revenue for subscriptions can only be posted if the **Accrue revenue** check box in the **Line properties** form is selected on the subscription group that is attached to the subscription. Furthermore, accrued revenue cannot be posted until the invoice for the subscription has been posted.

## Actions and effects

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Action</p></th>
<th><p>Effect</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Invoicing</p></td>
<td><p>The <strong>WIP - subscription</strong> account is credited with the same amount by which <strong>Accrued revenue - subscription</strong> account is debited.</p>
<p>In this manner, the revenue is moved to the WIP balance sheet from where accrued revenue is posted to the <strong>Accrued revenue - subscription</strong> account.</p></td>
</tr>
<tr class="even">
<td><p>Post accrued revenue</p></td>
<td><p>The <strong>WIP - subscription</strong> account is debited with the same amount that the <strong>Accrued revenue - subscription</strong> account is credited.</p></td>
</tr>
<tr class="odd">
<td><p>Reverse accrual</p></td>
<td><p>When an already-accrued transaction is selected for reversal, the <strong>WIP - subscription</strong> account is credited with the same amount that the <strong>Accrued revenue - subscription</strong> account is debited.</p></td>
</tr>
</tbody>
</table>


## See also

[About work in process (WIP) calculation](about-work-in-process-wip-calculation.md)

[Line properties (form)](https://technet.microsoft.com/library/aa590082\(v=ax.60\))

  


