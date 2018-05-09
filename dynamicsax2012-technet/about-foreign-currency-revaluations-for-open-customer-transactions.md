---
title: About foreign currency revaluations for open customer transactions
TOCTitle: About foreign currency revaluations for open customer transactions
ms:assetid: 132c47fd-ea28-473d-ba08-c366a97c1573
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496596(v=AX.60)
ms:contentKeyID: 36056045
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About foreign currency revaluations for open customer transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The theoretical value, or book value, of open customer transactions in foreign currencies varies over time, based on fluctuations in the exchange rates.

To update the value of your accounts receivable, and to conform with generally accepted accounting principles (GAAP) in the United States, run the periodic job for foreign currency revaluations. The job uses a new exchange rate to revalue the amounts that were open, or not settled, on a specified date. The differences between the original posted amounts and the revalued amounts are posted to the ledger. The differences are also posted to customer accounts as unrealized transactions of the foreign currency revaluation. Transactions that had foreign currency revaluations on a more recent date are not revalued.

Before you revalue foreign currency amounts on open customer transactions for a specific date, you can run a simulation of the foreign currency revaluation for the same date and method. You can then view the potential financial effect of a revaluation.

When you post the foreign currency revaluation, you can view and print a report that shows the following information:

  - The balances of customer accounts that have transactions that had foreign currency revaluations. Balances are shown in the original currency and the accounting currency. In other words, the balances before and after the foreign currency revaluation are shown.

  - The amount of the foreign currency revaluation for each customer.

  - The total amount of the transactions of the foreign currency revaluation for each currency.

A record is kept every time that you run the periodic job for foreign currency revaluations. You can query and view the ledger transaction and the customer transactions that the foreign currency revaluation generated.

For more information about foreign currency revaluation, see the following topics.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Topic</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="simulate-a-foreign-currency-revaluation.md">Simulate a foreign currency revaluation</a></p></td>
<td><p>Provides information about how to run a simulation of a foreign currency revaluation.</p></td>
</tr>
<tr class="even">
<td><p><a href="revalue-foreign-currency-amounts-for-customers-or-vendors.md">Revalue foreign currency amounts for customers or vendors</a></p></td>
<td><p>Provides information about how to revalue foreign currency amounts.</p></td>
</tr>
<tr class="odd">
<td><p><a href="view-the-transactions-of-a-foreign-currency-revaluation.md">View the transactions of a foreign currency revaluation</a></p></td>
<td><p>Provides information about how to view the transactions of a foreign currency revaluation.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

