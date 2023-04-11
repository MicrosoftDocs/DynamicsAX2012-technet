---
title: (RUS) Calculate the exchange rate difference for a bank account
TOCTitle: (RUS) Calculate the exchange rate difference for a bank account
ms:assetid: 13fa7838-ac2a-4a8b-855c-b53b7cc79c46
ms:mtpsurl: https://technet.microsoft.com/library/JJ711407(v=AX.60)
ms:contentKeyID: 49387224
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate the exchange rate difference for a bank account 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

At the end of each financial reporting period, you must revalue the remaining cash balance in a bank account in currency. All of the receipt and write-off operations that are performed for the funds in the bank account are reflected in the **Bank transactions** form.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  On the **Number sequences** tab, in the **Reference** field, set a number sequence for **Bank – Exchange adjustment**.

3.  Press CTRL+S or close the form.

4.  Click **General Ledger** \> **Setup** \> **Exchange rates** to open the **Exchange rates** form.

5.  On the **Posting** tab, select the ledger account in the **Unrealized loss** and **Unrealized profit** fields for which the exchange adjustment will be posted.

6.  On the **Exchange adjustment** tab, select the codes for expense and revenue in the **Expense code** and **Revenue code** fields. These codes will be used as the tax dimension in a transaction that results in a negative or positive exchange rate difference. The other dimensions will be derived from the original receipt or disbursement of funds for the transaction.

7.  Press CTRL+S or close the form.

8.  Click **Bank** \> **Periodic** \> **Bank** \> **Exchange adjustment** to open the **Exchange adjustment** form.

9.  In the **On date** field, select the revaluation date.

10. In the **From currency** and **To currency** fields, select the range of currency codes that will be used to conduct the revaluation.

11. Click the **Select** button to set up additional criteria for filtering the adjustment.

12. Click **OK**.

13. In the **Exchange adjustment** form, click **OK**. The exchange difference for the selected date is calculated.
    

    > [!NOTE]
    > <P>View the completed transactions in the <STRONG>Bank transactions</STRONG> (modified form).</P>



## See also

[(RUS) Bank transactions (modified form)](https://technet.microsoft.com/library/jj678344\(v=ax.60\))

  


