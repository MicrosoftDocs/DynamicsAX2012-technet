---
title: About WIP production accounts
TOCTitle: About WIP production accounts
ms:assetid: 6f933708-e8d2-4f47-999e-e519dc620807
ms:mtpsurl: https://technet.microsoft.com/library/Aa571295(v=AX.60)
ms:contentKeyID: 36058048
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- WIP
- production account
audience: Application User
ms.search.region: Global
---

# About WIP production accounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic contains an overview of how and where the **WIP - production** account is applied and the parameter setup that is required in the **Project groups** form.

The **WIP - production** account is used with the **WIP - profit** account. You can use these two accounts as an alternative to using the **WIP - sales value** account.

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
<td><p>Work in Process</p></td>
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

In the **Project groups** form, on the **Estimate** FastTab, select **Completed percentage** in the **Revenue recognition accounting rule** field and **Production + profit** in the **Matching principle** field.

## Actions and effects

The following table describes the effects that particular actions have on fixed-price projects that use the completed percentage revenue recognition accounting principle.

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
<td><p>The account is debited with a fee transaction that is created when an estimate is posted.</p></td>
</tr>
<tr class="even">
<td><p>Reverse estimate</p></td>
<td><p>The account is credited on the reversed fee transaction when the reversed estimate is posted.</p></td>
</tr>
<tr class="odd">
<td><p>Eliminate</p></td>
<td><p>The account is credited on the original fee transaction when the elimination is posted.</p></td>
</tr>
<tr class="even">
<td><p>Reverse elimination</p></td>
<td><p>The account is debited on the reversed fee transaction when the reverse elimination is posted.</p></td>
</tr>
</tbody>
</table>


## See also

[About work in process (WIP) calculation](about-work-in-process-wip-calculation.md)

[Project groups (form)](https://technet.microsoft.com/library/aa590435\(v=ax.60\))

  


