---
title: (CAN) Calculate financial statement balances for GIFI codes when multiple fiscal years are open
TOCTitle: (CAN) Calculate financial statement balances for GIFI codes when multiple fiscal years are open
ms:assetid: 2f0519ee-9c5e-4b9e-a64c-4938fc88c3d0
ms:mtpsurl: https://technet.microsoft.com/library/Aa552722(v=AX.60)
ms:contentKeyID: 36056290
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Canada
---

# (CAN) Calculate financial statement balances for GIFI codes when multiple fiscal years are open 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you are using General Index of Financial Information (GIFI) codes for Canadian financial statements, and more than one fiscal year is open, you must create clearing accounts. This will simulate the closing of the prior fiscal year to calculate accurate balance sheet amounts for the current date on financial statements. For example, if the current date is March 21, 2012, and you have not closed the 2011 fiscal year, following this procedure simulates closing the prior fiscal year:

1.  Create a clearing account. For this example, title the account *Prior Year Earnings.* The account number should not be in the range of accounts that is included on financial statements and should not have a GIFI code associated with it.
    

    > [!NOTE]
    > <P>The clearing accounts are temporary and are used only to transfer amounts temporarily for this process.</P>



2.  Create a second clearing account. Title the account *Prior Year Additions to Retained Earnings*. The account number should not be in the range of accounts that is included on financial statements, but it must have a retained earnings GIFI code associated with it.

3.  Post the prior year earnings.
    
      - Debit the **Prior Year Earnings** clearing account. Make sure that the balance sheet does not include the **Prior Year Earnings** clearing account.
    
      - Credit the **Prior Year Additions to Retained Earnings** account. Make sure that the balance sheet includes the **Prior Year Additions to Retained Earnings** clearing account in the retained earnings section.

4.  Print the financial statements.

5.  When you close the books, credit the **Prior Year Earnings** clearing account and debit the **Prior Year Additions to Retained Earnings** account.

  


