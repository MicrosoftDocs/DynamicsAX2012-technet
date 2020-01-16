---
title: About WIP cost value item accounts
TOCTitle: About WIP cost value item accounts
ms:assetid: be16ac73-105c-4bfe-a35a-6b5c134035ae
ms:mtpsurl: https://technet.microsoft.com/library/Aa498877(v=AX.60)
ms:contentKeyID: 36059164
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- WIP
- cost value item
audience: Application User
ms.search.region: Global
---

# About WIP cost value item accounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic contains an overview of how and where the **WIP - cost value - item** account is applied and the parameter setup that is required in the **Project groups** and **Line properties** forms.

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
<td><p><strong>Item</strong></p></td>
<td><p><strong>Fixed-price</strong></p></td>
<td><p><strong>WIP</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Time and material</strong></p></td>
<td><p><strong>Consumption</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Investment</strong></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Parameter dependencies

In the **Project groups** from, on the **Ledger** tab, for time and material projects, select **Balance** in the **Journalizing** fields. In the **Line properties** form, on the **General** FastTab, select the **Capitalize cost** check box.

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
<td><p>When posting item journals, the account is debited if <strong>Balance</strong> is selected on the project group.</p></td>
</tr>
<tr class="even">
<td><p>Post cost</p></td>
<td><p>If transactions are moved from the status <strong>Profit and loss</strong> to <strong>Balance</strong> the account is debited.</p>
<p>If transactions are moved from the status <strong>Balance</strong> to <strong>Profit and loss</strong> the account is credited.</p></td>
</tr>
<tr class="odd">
<td><p>Invoicing</p></td>
<td><p>The account is credited when time and material project invoices are posted provided that the transaction status is set to <strong>Balance</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Post estimate</p></td>
<td><p>For investment projects and fixed-price projects with the completed contract revenue recognition accounting principle the account is debited when items are posted.</p></td>
</tr>
<tr class="odd">
<td><p>Reverse estimate</p></td>
<td><p>For fixed-price projects with the completed contract revenue recognition accounting principle, the account is credited when items are posted.</p>
<p>For investment projects the account is debited when items are posted.</p></td>
</tr>
<tr class="even">
<td><p>Elimination</p></td>
<td><p>The account is credited.</p></td>
</tr>
<tr class="odd">
<td><p>Reverse elimination</p></td>
<td><p>The account is debited.</p></td>
</tr>
</tbody>
</table>


## See also

[About work in process (WIP) calculation](about-work-in-process-wip-calculation.md)

[Project groups (form)](https://technet.microsoft.com/library/aa590435\(v=ax.60\))

[Line properties (form)](https://technet.microsoft.com/library/aa590082\(v=ax.60\))

  


