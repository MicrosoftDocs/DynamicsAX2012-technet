---
title: (CZE) Set up balance sheet definitions
TOCTitle: (CZE) Set up balance sheet definitions
ms:assetid: ad3d41d5-dc4d-4796-985d-15e179960984
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677649(v=AX.60)
ms:contentKeyID: 49384953
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CZE) Set up balance sheet definitions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can specify how asset and liability transaction amounts are displayed on the balance sheet report by using the **Balance sheet definition** form.

1.  Click **General ledger** \> **Setup** \> **Balance sheet definition**.

2.  Press CTRL+N to create a balance sheet definition.

3.  In the **Line type** field, select **Assets** or **Liabilities** to specify how asset or liability transactions are displayed on the balance sheet report.

4.  In the **Description** field, enter a short description for the asset or liability transaction.

5.  In the **Line** field, enter a unique number for the report line.

6.  In the **Header** grid, in the **Mark** field, enter a description for the report line.

7.  In the **Rounding form** field, select the rounding method to use to round the amount. For more information, see [(CZE) Balance sheet definition (form)](https://technet.microsoft.com/en-us/library/jj710630\(v=ax.60\)).

8.  In the **Gross** grid, select the **Invert sign** check box to reverse the signs of the amounts before report line amounts are added together and displayed on the report.

9.  In the **Total** field, enter the line number.
    
    –or–
    
    In the **Group of accounts** field, enter the starting numbers of the accounts. The sum of the balances is displayed on the report. For example, if you enter 1502 in this field, the sum of the balances of accounts that have 1502 as the first four digits is displayed on the report. You can enter a maximum of four digits in this field.
    
    –or–
    
    In the **Main account** field, select a main account number.

10. Press CTRL+N to add lines in the **Gross** grid. The transaction amounts of the specified line numbers, groups of accounts, or main accounts are added together and displayed on the report.

11. If you selected **Assets** in the **Line type** field, specify values in the **Total**, **Group of accounts**, or **Main account** field in the **Adjustments** grid. Press CTRL+N to add lines in the **Adjustments** grid. The transaction amounts of the specified line numbers, groups of accounts, or main accounts are added together and displayed on the report.

## See also

[(CZE) Generate the balance sheet report](cze-generate-the-balance-sheet-report.md)

[(CZE) Balance sheet report (LedgerBalanceSheet)](cze-balance-sheet-report-ledgerbalancesheet.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

