---
title: (RUS) Set up calculation parameters for amount differences in tax accounting
TOCTitle: (RUS) Set up calculation parameters for amount differences in tax accounting
ms:assetid: 43b7f5ae-703d-4d39-973c-7bbf724ba9bc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923412(v=AX.60)
ms:contentKeyID: 52075372
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- exchange adjustment
- amount differences
- calculation parameters
- set up calculation parameters
---

# (RUS) Set up calculation parameters for amount differences in tax accounting [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Currency revaluation accounts** form to set up calculation parameters for amount differences in tax accounting.

1.  Click **General ledger** \> **Setup** \> **Currency** \> **Currency parameters**.

2.  Select a currency, and then select the **Activate parameters** check box to activate revaluation parameters for the selected currency.

3.  Select the **Amount difference in tax accounting** check box to use the selected currency when the amount difference is calculated in tax accounting.

4.  Click the **Sales/customers** FastTab.
    

    > [!NOTE]
    > <P>This tab is available only when you select <STRONG>Incremental</STRONG> in the <STRONG>Calculation method</STRONG> field in the <STRONG>General ledger parameters</STRONG> form.</P>



5.  In the **Customer posting** grid, in the **Main account** field, select the account that the amount difference from settled transactions is posted to.

6.  In the **Customer tax dimension** field group, in the **Expense code** field, select the expense code. If the amount difference that is produced when the transactions are settled is a loss, this expense code is used to post the amount difference to the appropriate register.

7.  In the **Revenue code** field, select a revenue code. If the amount difference that is produced when the transactions are settled is a profit, this revenue code is used to post the amount difference to the appropriate register.

8.  Click the **Purchases/Vendors** FastTab.
    

    > [!NOTE]
    > <P>This tab is available only when you select <STRONG>Incremental</STRONG> in the <STRONG>Calculation method</STRONG> field in the <STRONG>General ledger parameters</STRONG> form.</P>



9.  In the **Vendor posting** grid, in the **Main account** field, select the account that the amount difference from settled transactions is posted to.

10. In the **Vendor tax dimension** field group, in the **Expense code** field, select an expense code. If the amount difference that is produced when the transactions are settled is a loss, this expense code is used to post the amount difference to the appropriate register.

11. In the **Revenue code** field, select a revenue code. If the amount difference that is produced when the transactions are settled is a profit, this revenue code is used to post the amount difference to the appropriate register.

## See also

[(RUS) About tax liabilities and asset calculation registers](rus-about-tax-liabilities-and-asset-calculation-registers.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

