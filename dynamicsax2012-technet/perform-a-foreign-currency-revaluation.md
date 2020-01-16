---
title: Perform a foreign currency revaluation
TOCTitle: Perform a foreign currency revaluation
ms:assetid: f98eeac2-160b-4bcc-938b-5cbbad1a137a
ms:mtpsurl: https://technet.microsoft.com/library/Aa499830(v=AX.60)
ms:contentKeyID: 39519383
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- foreign currency revaluation
- currency revaluation
audience: Application User
ms.search.region: Global
---

# Perform a foreign currency revaluation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you use multiple currencies, the exchange rate for the original transaction currency might differ from the exchange rate that is used during the conversion to the accounting currency. To recognize these differences in the exchange rate, you might have to adjust the amounts in the main accounts. The process that is used to make those adjustments is called a foreign currency revaluation.

## Set up main accounts for foreign currency revaluations

Before you can complete a foreign currency revaluation for a main account, you must set up the main accounts so that foreign currency revaluation adjustments can be posted to them.

1.  Click **General ledger** \> **Common** \> **Main accounts**.

2.  Select a main account that includes transaction amounts in foreign currencies. The main account must also have one of the following main account types:
    
      - **Profit and loss**
    
      - **Revenue**
    
      - **Expense**
    
      - **Balance sheet**
    
      - **Asset**
    
      - **Liability**

3.  On the **Action Pane**, click **Edit**.

4.  On the **General** FastTab for the selected main account, select the **Foreign currency revaluation** check box.

5.  Repeat steps 2 through 4 for each main account that includes transaction amounts in foreign currencies.
    

    > [!NOTE]
    > <P>You must select every main account that has transaction amounts or balances in foreign currencies. Otherwise, a specific foreign currency revaluation might not include all possible adjustments.</P>



## Complete a foreign currency revaluation

Use the **Foreign currency revaluation** form to complete a foreign currency revaluation for the general ledger. When the revaluation is finished, balances that are in the accounting currency are updated to use current exchange rates.

1.  Click **General ledger** \> **Periodic** \> **Foreign currency revaluation**.

2.  Specify the starting and ending main accounts, dates, and currency codes to include in the revaluation.

3.  Select the **Adjust profit and loss accounts** check box to revalue the balances for accounts that have a main account type of **Profit and loss**.

4.  Select the **Adjust balance sheet accounts** check box to revalue the balances for accounts that have a main account type of **Balance sheet**.

5.  Click **OK** to revalue the main accounts.

## See also

[Ledger foreign currency revaluation (form)](https://technet.microsoft.com/library/aa573388\(v=ax.60\))

  


