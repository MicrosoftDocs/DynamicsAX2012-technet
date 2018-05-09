---
title: (RUS) Post rounded amounts during inventory closing
TOCTitle: (RUS) Post rounded amounts during inventory closing
ms:assetid: 95165e0f-ab6b-42c5-95c4-b4a7c2a94b58
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678503(v=AX.60)
ms:contentKeyID: 49387731
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Post rounded amounts during inventory closing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



If the adjustment amount for an inventory transaction is less than the value of the minimum throughput adjustment specified during inventory closing, you can write off the difference to a profit or loss account set up for the item posting.


> [!NOTE]
> <P>For more information, see "Set up profit and loss accounts for posting rounded amounts at inventory closing" in the Applications and Business Processes Help.</P>



You can set up special ledger accounts for posting rounding differences at inventory settlement. These accounts are also used to perform cost price adjustments and to post item counting results.

Example for ledger transaction posting with a rounding difference:

Using the FIFO Inventory Model, if Account Rounding – Loss is 91.99 and Account Rounding – Profit is 91.98, then the transaction would be posted in the ledger as follows:

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Date</p></th>
<th><p>Transaction description</p></th>
<th><p>Transaction</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>05.05.08</p></td>
<td><p>Receipt in the Transaction journal - item, 2 units at 10 rubles each, to warehouse A.</p></td>
<td><p>D 10 K 20 20 r.</p></td>
</tr>
<tr class="even">
<td><p>05.05.08</p></td>
<td><p>Transfer 2 units from warehouse A to warehouse B.</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p>03.05.08</p></td>
<td><p>Receipt in the Transaction journal - item, 2 units of 10.03 rubles each, to warehouse B.</p></td>
<td><p>D 10 K 20 10,06 r.</p></td>
</tr>
<tr class="even">
<td><p>05.31.08</p></td>
<td><p>Inventory closing. Minimum throughput adjustment = 0.10 ruble. Inventory rounding loss.</p></td>
<td><p>D 10 K 91.99 -0,06 r.</p></td>
</tr>
</tbody>
</table>


If, in the above example, there was an inventory rounding profit, then the transaction would be posted as follows: D 10 K 91.98 0,06 r.

At the completion of the process, the rounded value amounts can be allocated to financial results, costs, or inventory cost price.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

