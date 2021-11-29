---
title: 'Examples: Depreciation effects with reversals'
TOCTitle: 'Examples: Depreciation effects with reversals'
ms:assetid: d692ad15-6e1d-4826-a5e1-1669b63e75f7
ms:mtpsurl: https://technet.microsoft.com/library/Gg213705(v=AX.60)
ms:contentKeyID: 36059536
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Examples: Depreciation effects with reversals 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can reverse fixed asset transactions, and the transactions that are associated with a fixed asset. You can also revoke a reversed transaction.

You can reverse or revoke a transaction that was not the most recent transaction posted to the value model or depreciation book for the asset. You should first determine whether any depreciation transactions were posted after the transaction that you are reversing. This is because depreciation is not recalculated when you reverse a transaction. Therefore, depreciation often is overstated or understated after the reversal, as shown in the examples.

To make sure that depreciation is correct when you reverse a transaction, do not continue with the reversal if you receive a message that states that depreciation will not be recalculated. Instead, first reverse the depreciation transaction that was posted after the transaction you tried to reverse, and then continue with the reversal. You will not be warned about depreciation recalculations, and you can continue with the reversal.

The following examples show the calculations that occur if you continue beyond the message without first reversing the depreciation transactions.

## Example 1: Depreciation is overstated

An asset is set up with a 5-year useful life and straight line depreciation (60 depreciation periods). In this example, depreciation is overstated.

## Asset transaction history

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Date</p></th>
<th><p>Transaction type</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>Acquisition</p></td>
<td><p>59,000.00</p></td>
</tr>
<tr class="even">
<td><p>January 1</p></td>
<td><p>Acquisition adjustment</p></td>
<td><p>1,000.00</p></td>
</tr>
<tr class="odd">
<td><p>January 31</p></td>
<td><p>Depreciation (created by using a proposal for one period of depreciation)</p></td>
<td><p>1,000.00</p>
<p>Calculation: Book value (59,000 + 1,000) / Number of depreciation periods remaining (60)</p></td>
</tr>
</tbody>
</table>


## Reversal action

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Date</p></th>
<th><p>Transaction type</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>Acquisition adjustment reversal</p></td>
<td><p>–1,000.00</p></td>
</tr>
</tbody>
</table>


## Depreciation effect

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Date</p></th>
<th><p>Transaction type</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>February 28</p></td>
<td><p>Depreciation (proposal)</p></td>
<td><p>983.05</p>
<p>Calculation: Book value (59,000 - 1,000 depreciation) / Number of depreciation periods remaining (59)</p></td>
</tr>
</tbody>
</table>


Depreciation is overstated by 16.95 (1,000 - 983.05).

## Example 2: Depreciation is understated

An asset is set up with a 5-year useful life and straight line depreciation (60 depreciation periods). In this example, depreciation is understated.

## Asset transaction history

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Date</p></th>
<th><p>Transaction type</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>Acquisition</p></td>
<td><p>59,000.00</p></td>
</tr>
<tr class="even">
<td><p>January 1</p></td>
<td><p>Write-down adjustment</p></td>
<td><p>1,000.00</p></td>
</tr>
<tr class="odd">
<td><p>January 31</p></td>
<td><p>Depreciation (created by using a proposal for one period of depreciation)</p></td>
<td><p>966.67</p>
<p>Calculation: Book value (59,000 - 1,000) / Number of depreciation periods remaining (60)</p></td>
</tr>
</tbody>
</table>


## Reversal action

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Date</p></th>
<th><p>Transaction type</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>Write-down adjustment reversal</p></td>
<td><p>–1,000.00</p></td>
</tr>
</tbody>
</table>


## Depreciation effect

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Date</p></th>
<th><p>Transaction type</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>February 28</p></td>
<td><p>Depreciation (proposal)</p></td>
<td><p>983.62</p>
<p>Calculation: Book value (59,000 - 966.67 depreciation) / Number of depreciation periods remaining (59)</p></td>
</tr>
</tbody>
</table>


Depreciation is understated by 16.95 (983.62 - 966.67).

## See also

[Depreciation methods and conventions](depreciation-methods-and-conventions.md)

[About depreciation](about-depreciation.md)

[Reverse a transaction](reverse-a-transaction.md)

[Fixed asset group/value model (form)](https://technet.microsoft.com/library/aa554698\(v=ax.60\))

[Fixed asset group/depreciation book (form)](https://technet.microsoft.com/library/aa599462\(v=ax.60\))

  


