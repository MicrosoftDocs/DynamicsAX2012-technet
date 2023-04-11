---
title: About WIP accrued loss accounts
TOCTitle: About WIP accrued loss accounts
ms:assetid: e3aebc21-dbb7-4d3e-9ad6-666ce4d83b7c
ms:mtpsurl: https://technet.microsoft.com/library/Aa551379(v=AX.60)
ms:contentKeyID: 36059725
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- WIP
- accrued loss
- foreseeable loss
audience: Application User
ms.search.region: Global
---

# About WIP accrued loss accounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic contains an overview of how and where the **WIP - accrued loss** account is applied and the parameter setup that is required in the **Project groups** form.

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
<td><p><strong>Expense</strong></p></td>
<td><p><strong>Fixed-price</strong></p></td>
<td><p><strong>WIP</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Investment</strong></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Parameter dependencies

In the **Project groups** form, on the **Estimate** FastTab, select the **Foreseeable losses** check box.

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
<td><p>Post estimate</p></td>
<td><p>For fixed-price projects with the completed contract revenue recognition accounting principle, the account is credited with an expense transaction if there is a foreseeable loss on the project.</p>
<p>For investment projects, the account is credited with an expense transaction if the total capitalized cost exceeds the maximum capitalization.</p></td>
</tr>
<tr class="even">
<td><p>Reverse estimate</p></td>
<td><p>For investment projects and fixed-price project with the completed contract revenue recognition accounting principle, the account is debited.</p></td>
</tr>
<tr class="odd">
<td><p>Elimination</p></td>
<td><p>For fixed-price projects with the completed contract revenue recognition accounting principle, the account is debited.</p></td>
</tr>
<tr class="even">
<td><p>Reverse elimination</p></td>
<td><p>For fixed-price projects with the completed contract revenue recognition accounting principle, the account is credited.</p></td>
</tr>
</tbody>
</table>


## See also

[About work in process (WIP) calculation](about-work-in-process-wip-calculation.md)

[Project groups (form)](https://technet.microsoft.com/library/aa590435\(v=ax.60\))

  


