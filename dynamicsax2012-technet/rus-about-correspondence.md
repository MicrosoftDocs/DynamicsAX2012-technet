---
title: (RUS) About Correspondence
TOCTitle: (RUS) About Correspondence
ms:assetid: 9a9f73ab-4f91-4867-8cc2-e5e1b899e9ec
ms:mtpsurl: https://technet.microsoft.com/library/JJ923566(v=AX.60)
ms:contentKeyID: 52075413
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Russia
- correspondence
- corresponding accounts
audience: Application User
ms.search.region: Russia
---

# (RUS) About Correspondence 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Correspondence of accounts is an approach to continuous and interrelated registration of business transactions in corresponding general ledger accounts, based on the double-entry bookkeeping system. Ledger vouchers are represented by using the Russian accounting standards with corresponding accounts.

You can enter multidimensional transactions in the ledger journals and other modules. In most cases, transactions that are created automatically from other modules are multidimensional. These transactions should be changed to two-dimensional, which could involve splitting ledger transactions. In this case, the following correspondence cases are specified.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of correspondence</p></th>
<th><p>Before correspondence</p></th>
<th><p>After correspondence</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>One–to–one</p></td>
<td><p>Account A 200 (debit transaction)</p>
<p>Account B 200 (credit transaction)</p></td>
<td><p>Account A – Account B 200</p>
<p>(two transactions)</p></td>
</tr>
<tr class="even">
<td><p>One–to–many</p></td>
<td><p>Account A 200 (debit transaction)</p>
<p>Account B 160 (credit transaction)</p>
<p>Account C 40 (credit transaction)</p></td>
<td><p>Account A – Account B 160</p>
<p>Account A – Account C 40</p>
<p>(four transactions)</p></td>
</tr>
<tr class="odd">
<td><p>Many–to–one</p></td>
<td><p>Account A 200 (debit transaction)</p>
<p>Account B 160 (debit transaction)</p>
<p>Account C 360 (credit transaction)</p></td>
<td><p>Account A – Account C 200</p>
<p>Account B – Account C 160</p>
<p>(four transactions)</p></td>
</tr>
<tr class="even">
<td><p>Many–to–many</p></td>
<td><p>Account A 200 (debit transaction)</p>
<p>Account B 160 (debit transaction)</p>
<p>Account C 260 (credit transaction)</p>
<p>Account D 100 (credit transaction)</p></td>
<td><p>Individual processing</p>
<p>(multiple transactions)</p></td>
</tr>
</tbody>
</table>


When the **Use corresponding mechanism** check box in the **General ledger parameters** form is cleared, no correspondence relationships are created between transactions.

When the **Use corresponding mechanism** check box is selected, each new accounting transaction that is created consists of a set of two-way corresponding transactions. When the accounting transactions are posted, the corresponding relationship is defined automatically.

If non-corresponding accounts already exist before the account correspondence mechanism is enabled, they are not linked automatically. You must define relationships for these transactions manually.

## See also

[(RUS) General ledger parameters (modified form)](https://technet.microsoft.com/library/jj923603\(v=ax.60\))

  


