---
title: (RUS) Set up fixed asset posting profiles
TOCTitle: (RUS) Set up fixed asset posting profiles
ms:assetid: 81ba6188-0198-42b1-95d9-561459e10025
ms:mtpsurl: https://technet.microsoft.com/library/JJ678423(v=AX.60)
ms:contentKeyID: 49387653
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up fixed asset posting profiles 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up posting profiles for fixed assets. Posting profiles define the ledger accounts that are used in the value model for each fixed asset transaction.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets** \> **Setup** \> **Fixed asset posting profiles**.

2.  On the **Overview** tab, press CTRL+N to create a new fixed asset posting profile.

3.  In the **Posting profile** field, enter the name of the posting profile.

4.  In the **Description** field, enter the description of the posting profile.

5.  On the left pane, in the **Select** field, select any one of the following options:
    
      - **Depreciation** – Calculation of depreciation of a fixed asset.
    
      - **Depreciation revaluation** – Revaluation of depreciation calculated for a fixed asset.
    
      - **Major repairs** – Conducting major repairs for a fixed asset.
    
      - **Putting into operation** – Putting a fixed asset into operation.
    
      - **Cost revaluation** – Revaluate the cost of a fixed asset.
    
      - **Leaving (sale)** – Disposal sale of the fixed asset.
    
      - **Leaving (dismantlement)** – Disassembly of a fixed asset.
    
      - **Partial take-down** – Partial disposal of a fixed asset.
    
      - **Currency cost revaluate** – Revaluation of a fixed asset based on currency cost.
    
      - **Currency depreciation revaluate** – Revaluation of depreciation calculated for a fixed asset in currency.
    
      - **Others** – Other fixed asset transactions.

6.  On the **Ledger accounts** tab, in the **Groupings** field, select the grouping used for the posting profile from the following options:
    
      - **Table** – Select this option to retrieve fixed asset data (value) from the table.
    
      - **Group** – Select this option to retrieve a defined depreciation group from the fixed asset group.
    
      - **All** – Select this option for all fixed asset transactions.
    
      - **Accounting** – Select this option to retrieve a defined value model.

7.  In the **Account/Group number** field, select the value model, group, or fixed asset object that the posting profile will be used for.

8.  In the **Ledger account** and **Offset account** fields, select the account number (debit) and the offset account (credit) for the transactions.

9.  Click **Options** and then click **Leaving (sale)** or **Leaving (dismantlement)** to open the **Sales** form or the **Dismantlement** form.

10. Press CTRL+N to create a new line.

11. In the **Valid for** field, select the grouping that will be used for the posting profile from the following options:
    
      - **Table** – Select this option to retrieve fixed asset data (value) from the table.
    
      - **Group** – Select this option to retrieve a defined depreciation group from the fixed asset group.
    
      - **All** – Select this option to for all fixed asset transactions.
    
      - **Accounting** – Select this option to retrieve a defined value model.

12. In the **FA relation** field, select the value model, group, or fixed asset object that will be used for the posting profile.

13. In the **Post value** field, select the amount to post to the specified account.

14. In the **Sale value type** field, select the type of amount that will be posted from the following options:
    
      - **All** – Any amount
    
      - **Loss** – The amount of loss
    
      - **Gain** – The amount of gain

15. In the **Ledger account** and **Offset account** fields, select the account numbers of the ledger account (debit) and the offset account (credit) for the transactions.

16. Select the **Storno** check box if you have to create a rental repayment transaction as a reversal transaction.

17. Press CTRL+S or close the forms.

## See also

[(RUS) Fixed asset posting profiles (form)](https://technet.microsoft.com/library/jj853200\(v=ax.60\))

  


