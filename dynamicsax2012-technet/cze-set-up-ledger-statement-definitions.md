---
title: (CZE) Set up ledger statement definitions
TOCTitle: (CZE) Set up ledger statement definitions
ms:assetid: 8c7e75f7-bba0-45ca-8019-489078239591
ms:mtpsurl: https://technet.microsoft.com/library/JJ677606(v=AX.60)
ms:contentKeyID: 49384909
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic
---

# (CZE) Set up ledger statement definitions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can specify how ledger transaction amounts are displayed on the ledger statement report by using the **Ledger statement definition** form.

1.  Click **General ledger** \> **Setup** \> **Ledger statement definition**.

2.  Press CTRL+N to create a ledger statement definition.

3.  In the **Description** field, enter a short description for the report line. This description is displayed on the report.

4.  In the **Ledger statement** grid, in the **Line** field, enter a unique number for the report line.

5.  In the **Mark** field, enter a description for the report line.

6.  In the **Rounding form** field, select the rounding method to use to round the amount. For more information, see [(CZE) Ledger statement definition (form)](https://technet.microsoft.com/library/jj710663\(v=ax.60\)).

7.  In the **Ledger statement definition** grid, select the **Invert sign** check box to reverse the sign of the amounts before report line amounts are added together and displayed on the report.

8.  In the **Total** field, enter the line number.
    
    –or–
    
    In the **Group of accounts** field, enter the starting numbers of the accounts. The sum of the balances in the accounts is displayed on the report. For example, if you enter 1502 in this field, the sum of the balances of accounts that have 1502 as the first four digits are displayed on the report. You can enter a maximum of four digits in this field.
    
    –or–
    
    In the **Main account** field, select a main account number.

9.  Press CTRL+N to add lines. The transaction amounts of the specified line numbers, groups of accounts, or main accounts are added together and displayed on the report.

## See also

[(CZE) Ledger statement report (LedgerStatement)](cze-ledger-statement-report-ledgerstatement.md)

[(CZE) Generate the ledger statement report](cze-generate-the-ledger-statement-report.md)

  


