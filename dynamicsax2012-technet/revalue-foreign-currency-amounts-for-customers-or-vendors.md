---
title: Revalue foreign currency amounts for customers or vendors
TOCTitle: Revalue foreign currency amounts for customers or vendors
ms:assetid: 580d037b-650b-4c5f-84f6-a6193cc907bd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa549065(v=AX.60)
ms:contentKeyID: 36057338
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Revalue foreign currency amounts for customers or vendors [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you revalue foreign currency amounts, you must set up profit and loss ledger accounts for foreign currency revaluations. Click **General ledger** \> **Setup** \> **Currency** \> **Currency revaluation accounts**. Select main accounts for the four types of exchange rate posting in the **Posting** column.


> [!NOTE]
> <P>To estimate the financial effect of the revaluation that you are about to perform, you can run a simulation of the foreign currency revaluation in the customer <STRONG>Simulation</STRONG> or vendor <STRONG>Simulation</STRONG> form. For more information, see <A href="simulate-a-foreign-currency-revaluation.md">Simulate a foreign currency revaluation</A>.</P>



1.  Click **Accounts receivable** \> **Periodic** \> **Foreign currency revaluation**.
    
    –or–
    
    Click **Accounts payable** \> **Periodic** \> **Foreign currency revaluation**.

2.  Click **Foreign currency revaluation**.

3.  Select values in the following fields:
    
      - **Method**
    
      - **Considered date**
    
      - **Date of rate**
    
      - **Use posting profile from**

4.  Enter values in the other fields as required.

5.  Select the **Print** check box to print a report that shows the balances before and after the foreign currency revaluation. This printout also shows the summary of all changes, by currency.

6.  Click **OK** to revalue the foreign currency amounts and print the report.


> [!NOTE]
> <P>This report is available only when you revalue foreign currency amounts. Therefore, make sure that you print the report every time that you revalue foreign currency amounts.</P>



## See also

[About foreign currency revaluations for open customer transactions](about-foreign-currency-revaluations-for-open-customer-transactions.md)

[About foreign currency revaluations for open vendor transactions](about-foreign-currency-revaluations-for-open-vendor-transactions.md)

[Prepare a legal entity for a currency conversion](prepare-a-legal-entity-for-a-currency-conversion.md)

[Finish the currency conversion](finish-the-currency-conversion.md)

[Customer foreign currency revaluation (form)](https://technet.microsoft.com/en-us/library/aa586009\(v=ax.60\))

[Customer foreign currency revaluation periodic job (class form)](https://technet.microsoft.com/en-us/library/aa574761\(v=ax.60\))

[Vendor foreign currency revaluation (form)](https://technet.microsoft.com/en-us/library/aa500833\(v=ax.60\))

[Vendor foreign currency revaluation periodic job (class form)](https://technet.microsoft.com/en-us/library/aa554435\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

