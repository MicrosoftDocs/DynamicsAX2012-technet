---
title: About the Production + profit matching principle
TOCTitle: About the Production + profit matching principle
ms:assetid: 42047a79-91f8-4c74-b97e-c3c561489816
ms:mtpsurl: https://technet.microsoft.com/library/Aa496954(v=AX.60)
ms:contentKeyID: 36056866
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accrued revenue
- profit and loss
- matching principle
audience: Application User
ms.search.region: Global
---

# About the Production + profit matching principle 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Production + profit matching principle, which applies to fixed-price projects only, is used to recognize all costs on a project, plus a percentage of the total estimated profit, as the total revenue for the given period. When the Production + profit matching principle is used and the estimate is posted, the recognized revenue is split into cost and profit. The cost portion of the revenue is posted to the Accrued revenue – production account.

The following is an overview of how and where the Accrued revenue – production and Accrued revenue – profit accounts are applied and the parameter setup that is required in the **Project groups** form.

## Account type

Profit and loss.

## Availability

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>License code</p></th>
<th><p>Configuration code</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Project II</p></td>
<td><p>Work in process</p></td>
</tr>
</tbody>
</table>


## How the accounts are applied

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
<th><p>Statement type</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Fee</p></td>
<td><p>Fixed-price</p></td>
<td><p>Profit and loss</p></td>
</tr>
</tbody>
</table>


## Parameter dependencies

In the **Project groups** form, on the **Estimate** FastTab, select **Production + profit** in the **Matching principle** field.

## Actions and effects

The following table describes the effects of actions that you can perform in the **Estimate** form.

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
<td><p>Post estimate</p></td>
<td><p>For fixed-price projects that us the completed percentage revenue recognition accounting principle, the account is credited with a fee transaction that is created when an estimate is posted.</p></td>
</tr>
<tr class="even">
<td><p>Reverse estimate</p></td>
<td><p>For fixed-price projects that use the completed percentage revenue recognition accounting principle, the account is debited on the reversed fee transaction when the reversed estimate is posted.</p></td>
</tr>
<tr class="odd">
<td><p>Elimination</p></td>
<td><p>For fixed-price projects that use the completed contract revenue recognition accounting principle, the account is credited on the original fee transaction when the elimination is posted.</p></td>
</tr>
<tr class="even">
<td><p>Reverse elimination</p></td>
<td><p>For fixed-price projects that use the completed contract revenue recognition accounting principle, the account is debited on the reversed fee transaction when the reversed elimination is posted.</p></td>
</tr>
</tbody>
</table>


## See also

[Select accrued revenue for posting](select-accrued-revenue-for-posting.md)

[Project groups (form)](https://technet.microsoft.com/library/aa590435\(v=ax.60\))

[Estimate (form)](https://technet.microsoft.com/library/aa590971\(v=ax.60\))

  


