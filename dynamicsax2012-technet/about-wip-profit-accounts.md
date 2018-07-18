---
title: About WIP profit accounts
TOCTitle: About WIP profit accounts
ms:assetid: b4dd35af-1c4b-4fb3-b4ff-61a475ba181c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550459(v=AX.60)
ms:contentKeyID: 36059080
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- WIP
- profit account
audience: Application User
ms.search.region: Global
---

# About WIP profit accounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic contains an overview of how and where the **WIP - profit** account is applied and the parameter setup that is required in the **Project groups** form.

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
<td><p><strong>Fee</strong></p></td>
<td><p><strong>Fixed-price</strong></p></td>
<td><p><strong>WIP</strong></p></td>
</tr>
</tbody>
</table>


## Parameter dependencies

For fixed-price projects, in the **Project groups** form, on the **Estimate** FastTab, select **Production + profit** in the **Matching principle** field, and select **Completed percentage** in the **Revenue recognition accounting rule** field.

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
<td><p>For fixed-price projects with the completed percentage revenue recognition accounting rule, the account is debited with a fee transaction that is created when an estimate is posted.</p></td>
</tr>
<tr class="even">
<td><p>Reverse estimate</p></td>
<td><p>For fixed-price projects with the completed percentage revenue recognition accounting rule, the account is credited on the reversed fee transaction when the reversed estimate is posted.</p></td>
</tr>
<tr class="odd">
<td><p>Elimination</p></td>
<td><p>For fixed-price projects with the completed percentage revenue recognition accounting rule, the account is credited on the original fee transaction when the elimination is posted.</p></td>
</tr>
<tr class="even">
<td><p>Reverse elimination</p></td>
<td><p>For fixed-price projects with the completed percentage revenue recognition accounting rule, the account is debited on the original fee transaction when the reversed elimination is posted.</p></td>
</tr>
</tbody>
</table>


## See also

[About work in process (WIP) calculation](about-work-in-process-wip-calculation.md)

[Project groups (form)](https://technet.microsoft.com/en-us/library/aa590435\(v=ax.60\))

  


