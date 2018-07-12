---
title: About WIP sales value accounts
TOCTitle: About WIP sales value accounts
ms:assetid: 299a79c8-06ce-45bb-b1b1-372cd3583825
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496852(v=AX.60)
ms:contentKeyID: 36056222
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales value account
- WIP
audience: Application User
ms.search.region: Global
---

# About WIP sales value accounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides an overview of how and where the **WIP - sales value** account is applied and what parameter setup is required in the **Project groups** and **Line properties** forms.

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
<td><ul>
<li><p><strong>Hour</strong></p></li>
<li><p><strong>Item</strong></p></li>
<li><p><strong>Expense</strong></p></li>
<li><p><strong>Fee</strong></p></li>
</ul></td>
<td><ul>
<li><p><strong>Fixed-price</strong></p></li>
<li><p><strong>Time and material</strong></p></li>
</ul></td>
<td><p><strong>WIP</strong></p></td>
</tr>
</tbody>
</table>


## Parameter dependencies

For fixed-price projects, in the **Project groups** form, on the **Estimate** FastTab, select **Sales value** in the **Matching principle** field, and select **Completed percentage** in the **Revenue recognition accounting rule** form. For time and material projects, in the **Line properties** form, on the **General** FastTab, select the **Accrue revenue** check box.

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
<td><p>Post journal</p></td>
<td><p>The account is debited on time and material projects if revenue is set to be accrued on the project group and the <strong>Accrue revenue</strong> check box is selected in the <strong>Line properties</strong> form.</p></td>
</tr>
<tr class="even">
<td><p>Invoicing</p></td>
<td><p>The account is credited if accrued revenue exists on the transaction.</p></td>
</tr>
<tr class="odd">
<td><p>Post estimate</p></td>
<td><p>For fixed-price projects with the completed percentage revenue recognition accounting principle, the account is debited with a fee transaction that is created when an estimate is posted.</p></td>
</tr>
<tr class="even">
<td><p>Reverse estimate</p></td>
<td><p>For fixed-price projects with the completed percentage revenue recognition accounting principle, the account is credited on the reversed fee transaction when the reversed estimate is posted.</p></td>
</tr>
<tr class="odd">
<td><p>Elimination</p></td>
<td><p>For fixed-price projects with the completed percentage revenue recognition accounting principle, the account is credited on the original fee transaction when the elimination is posted.</p></td>
</tr>
<tr class="even">
<td><p>Reverse elimination</p></td>
<td><p>For fixed-price projects with the completed percentage revenue recognition accounting principle, the account is debited on the reversed fee transaction when the reversed elimination is posted.</p></td>
</tr>
</tbody>
</table>


## See also

[About work in process (WIP) calculation](about-work-in-process-wip-calculation.md)

[Project groups (form)](https://technet.microsoft.com/en-us/library/aa590435\(v=ax.60\))

[Line properties (form)](https://technet.microsoft.com/en-us/library/aa590082\(v=ax.60\))

  


