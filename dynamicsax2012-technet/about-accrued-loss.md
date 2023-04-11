---
title: About accrued loss
TOCTitle: About accrued loss
ms:assetid: 49039c88-b84e-4fe9-9966-2665a6929285
ms:mtpsurl: https://technet.microsoft.com/library/Aa497004(v=AX.60)
ms:contentKeyID: 36056936
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- profit and loss
- foreseeable losses
- accrued loss
audience: Application User
ms.search.region: Global
---

# About accrued loss 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

For fixed-price and investment projects, you can choose to recognize losses during estimation. If you recognize losses, you must specify the category to use for accruing losses in the **Project groups** form.

This topic provides an overview of how and on what statement types the Accrued loss account is applied and the parameter setup that is required in the **Project groups** form.

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
<th><p>Statement type</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expense</p></td>
<td><p>Fixed-price</p>
<p>Investment</p></td>
<td><p>Profit and loss</p></td>
</tr>
</tbody>
</table>


## Parameter dependencies

In the **Project groups** form, on the **Estimate** FastTab, select the **Foreseeable losses** check box.

## Actions and effects

The following table describes the effects of actions that you perform on the **Estimate** form.

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
<td><p>For fixed-price projects that use the completed contract revenue recognition accounting principle, if there is a foreseeable loss on the project, the account is debited with an expense transaction. For investment projects, if the total cost exceeds the maximum capitalization, the account is debited with an expense transaction for the difference as a loss.</p></td>
</tr>
<tr class="even">
<td><p>Reverse estimate</p></td>
<td><p>For investment projects and fixed-price projects that use the completed contract revenue recognition accounting principle, the account is credited.</p></td>
</tr>
<tr class="odd">
<td><p>Elimination</p></td>
<td><p>For fixed-price projects that use the completed contract revenue recognition accounting principle, the accrued loss account is not affected because the loss is recognized during estimation.</p></td>
</tr>
<tr class="even">
<td><p>Reverse elimination</p></td>
<td><p>For fixed-price projects that use the completed contract revenue recognition accounting principle, the accrued loss account is not affected because the loss is recognized during estimation and did not affect the original elimination.</p></td>
</tr>
</tbody>
</table>


## See also

[Project groups (form)](https://technet.microsoft.com/library/aa590435\(v=ax.60\))

[Estimate (form)](https://technet.microsoft.com/library/aa590971\(v=ax.60\))

  


