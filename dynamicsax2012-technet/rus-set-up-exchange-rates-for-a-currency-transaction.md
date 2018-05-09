---
title: (RUS) Set up exchange rates for a currency transaction
TOCTitle: (RUS) Set up exchange rates for a currency transaction
ms:assetid: cabeed29-c429-4d52-91af-1ec69198f5d8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ856181(v=AX.60)
ms:contentKeyID: 50407020
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up exchange rates for a currency transaction 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Currency revaluation accounts** form to set up the loss or gain calculation for currency exchange. For more information, see [(RUS) Currency revaluation accounts (modified form)](https://technet.microsoft.com/en-us/library/jj852149\(v=ax.60\)).

1.  Click **General ledger** \> **Setup** \> **Currency** \> **Currency parameters**.

2.  In the **Legal entities** field, select a company.

3.  On the **General** FastTab, in the **Ledger posting** grid, select the main accounts to post the exchange rate profits or losses to.

4.  On the **Sales/customers** FastTab, in the **Customer posting** grid, select the main accounts to post the exchange rates profits or losses to.

5.  In the **Expense code** field, select the expense code that corresponds to the transaction for an exchange rate adjustment that occurs when transactions are settled for a customer. You can settle the transaction when the exchange rate adjustment is a loss.

6.  In the **Revenue code** field, select the revenue code that corresponds to the transaction for an exchange rate adjustment that occurs when transactions are settled for a customer. You can settle the transaction when the exchange rate adjustment is a profit.

7.  On the **Purchases/Vendors** FastTab, in the **Vendor posting** grid, select the main accounts for vendor posting.

8.  In the **Revenue code (currency conversion)** field, select the revenue code for a currency conversion transaction if the exchange adjustment is a profit.

9.  In the **Expense code (currency conversion)** field, select the revenue code for a currency conversion transaction if the exchange adjustment is a loss.

10. On the **Purchases/Advance holders** FastTab, select the relevant main accounts for advance holder posting.

11. In the **Expense code** field, select the expense code that corresponds to the transaction for an exchange rate adjustment that occurs when transactions are settled for an advance holder. You can settle the transaction when the exchange rate adjustment is a loss.

12. In the **Revenue code** field, select the revenue code that corresponds to the transaction for an exchange rate adjustment that occurs when transactions are settled for an advance holder. You can settle the transaction when the exchange rate adjustment is a profit.

## See also

[(RUS) Set up a bank account for a currency transaction](rus-set-up-a-bank-account-for-a-currency-transaction.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

