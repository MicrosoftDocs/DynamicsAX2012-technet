---
title: About WIP cost value accounts
TOCTitle: About WIP cost value accounts
ms:assetid: d3be32e9-05d1-46cb-b897-77c8bed00b95
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551083(v=AX.60)
ms:contentKeyID: 36059514
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- WIP
- cost value account
audience: Application User
ms.search.region: Global
---

# About WIP cost value accounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic contains an overview of how and where the **WIP - cost value** account is applied and the parameter setup that is required in the **Project groups** and **Line properties** forms.

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
<td><p><strong>Hour</strong></p></td>
<td><p><strong>Time and material</strong></p></td>
<td><p><strong>WIP</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Expense</strong></p></td>
<td><p><strong>Fixed-price</strong></p></td>
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

In the **Project groups** form, on the **Journalizing** FastTab, select **Balance** in the **Journalizing** fields. In the **Line properties** form, on the **General** FastTab, select the **Capitalize cost** check box.

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
<td><p>The account is debited if the transaction ledger status is <strong>Balance</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Post cost</p></td>
<td><p>If transactions are moved from the status <strong>No ledger</strong> or <strong>Profit and loss</strong> to <strong>Balance</strong>, the account is debited. If transactions are moved from the status <strong>Balance</strong> to <strong>Profit and loss</strong> or <strong>No ledger</strong>, the account is credited.</p></td>
</tr>
<tr class="odd">
<td><p>Invoicing</p></td>
<td><p>If the transaction ledger status is <strong>Balance</strong>, the account is credited when time and material project invoices are posted.</p></td>
</tr>
<tr class="even">
<td><p>Post estimate</p></td>
<td><p>For investment projects and fixed-price projects with the completed contract revenue recognition accounting principle the account is credited when items, hours and expenses are posted if the <strong>Capitalize cost</strong> check box is selected in the <strong>Line properties</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p>Reverse estimate</p></td>
<td><p>For investment projects and fixed-price projects with the completed contract revenue recognition accounting principle, the account is debited.</p></td>
</tr>
<tr class="even">
<td><p>Eliminate</p></td>
<td><p>If the transaction ledger status is <strong>Balance</strong>, the account is credited.</p></td>
</tr>
<tr class="odd">
<td><p>Reverse elimination</p></td>
<td><p>If the transaction ledger status is <strong>Balance</strong>, the account is credited.</p></td>
</tr>
</tbody>
</table>


## See also

[About work in process (WIP) calculation](about-work-in-process-wip-calculation.md)

[Project groups (form)](https://technet.microsoft.com/en-us/library/aa590435\(v=ax.60\))

  


