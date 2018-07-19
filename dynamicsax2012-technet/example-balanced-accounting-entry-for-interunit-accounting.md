---
title: 'Example: Balanced accounting entry for interunit accounting'
TOCTitle: 'Example: Balanced accounting entry for interunit accounting'
ms:assetid: d1904c54-9c4b-438e-add7-419dcf6e0915
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ729758(v=AX.60)
ms:contentKeyID: 49564924
ms.date: 05/01/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Example: Balanced accounting entry for interunit accounting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

If your organization is required to generate a balanced balance sheet by using the values of a financial dimension, you can select that financial dimension in the **Ledger** form. When you enter a financial dimension, every accounting entry must balance both at the total level and at the level of the financial dimension values. If the accounting entry does not balance at the level of the financial dimension values, additional account entries are created automatically to balance the accounting entry.

Automatic transactions are created to balance the entries. These transactions use the main accounts that are identified in the **Accounts for automatic transactions** form.

For example, **Branch**, which is the second segment of the ledger account, is selected as the balancing financial dimension. The following accounting entry is created.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>6100 – MSP – OU_256</p></td>
<td><p>100.00 DR</p></td>
</tr>
<tr class="even">
<td><p>6100 – NY – OU_249</p></td>
<td><p>100.00 DR</p></td>
</tr>
<tr class="odd">
<td><p>2100 – MSP – OU_256</p></td>
<td><p>200.00 CR</p></td>
</tr>
</tbody>
</table>


The following balances are determined:

  - Overall accounting entry = Balanced

  - MSP = 100.00 CR

  - NY = 100.00 DR

The following accounting entries are created automatically, so that this entry balances at the level of the financial dimension values.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Interunit DueFrom – MSP – OU_256</p></td>
<td><p>100.00 DR</p></td>
</tr>
<tr class="even">
<td><p>Interunit DueTo – NY – OU_249</p></td>
<td><p>100.00 CR</p></td>
</tr>
</tbody>
</table>

  


