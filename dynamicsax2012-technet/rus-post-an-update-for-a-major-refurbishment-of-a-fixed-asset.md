---
title: (RUS) Post an update for a major refurbishment of a fixed asset
TOCTitle: (RUS) Post an update for a major refurbishment of a fixed asset
ms:assetid: f7b986da-0b64-48c3-bd3e-2e8cf05d4a04
ms:mtpsurl: https://technet.microsoft.com/library/JJ923614(v=AX.60)
ms:contentKeyID: 52075455
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- repair
- update
- fixed asset
- fixed asset repair
audience: Application User
ms.search.region: Russia
---

# (RUS) Post an update for a major refurbishment of a fixed asset 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Capital improvements is a special asset category that includes capital renovations, improvements, technical updates, additional construction, and the acquisition of additional equipment for a fixed asset. When you update capital improvements, calculated depreciation is not revalued. However, the depreciated cost and service life of the fixed asset change. When major repair work is performed on a fixed asset, bonus depreciation is applicable for the asset on or after the major repair transaction date. You can create a transaction for a major repair of a fixed asset, and specify the bonus depreciation and bonus start date. The start date of the bonus depreciation can be the same as the major repair transaction date, or it can be the next depreciation date.

You must complete the following tasks before you can post an update for a major repair of a fixed asset:

  - Create dimensions for depreciation. For more information, see [Create a financial dimension](create-a-financial-dimension.md).

  - Set up expense codes. For more information, see [(RUS) Create expense and income codes](rus-create-expense-and-income-codes.md).

  - Set up bonus depreciation. For more information, see [(RUS) Set up bonus depreciation](rus-set-up-bonus-depreciation.md).

  - Set up depreciation groups. For more information, see [(RUS) Set up depreciation groups](rus-set-up-depreciation-groups.md).

## Create a journal for a major repair of a fixed asset

1.  Click **Fixed assets (Russia)** \> **Journals** \> **FA journal**.

2.  Press CTRL+N to create a fixed asset (FA) journal.

3.  In the **Name** field, select a journal name.

4.  In the **Description** field, view or modify the description of the journal.

5.  Click **Lines**.

6.  Press CTRL+N to create a journal line.

7.  In the **Transaction date** field, select the date to update the transaction.

8.  In the **Transaction type** field, select **Major repairs**.

9.  In the **FA inventory number** field, select the fixed asset number.

10. In the **Value model** field, select the fixed asset value model.

11. In the **Reason code** field, select a reason code.

12. In the **Reason comment** field, update the reason for the major repair of the fixed asset.

13. Click **OK**. The improvement lines for the asset are displayed in the journal.

14. In the **Description** field, select transaction text.

15. In the **Debit** or **Credit** field, enter the transaction amount.

16. In the **Offset account type** field, select the offset account type.

17. In the **Offset account** field, select the offset account number.
    

    > [!NOTE]
    > <P>You can also click <STRONG>Group operations</STRONG> &gt; <STRONG>Major repairs</STRONG> to create transactions for several fixed assets.</P>



18. Click **Post** \> **Post** to post the journal.

## Update a value model for a fixed asset

1.  Click **Fixed assets (Russia)** \> **Common** \> **Fixed assets**.

2.  Select a fixed asset, and then click **Value models**.

3.  Click **FA lifetime history**.

4.  Click **New**, and then in the **Date** field, select the lifetime change date.

5.  In the **New lifetime** and **New factor** fields, enter a lifetime and factor for the fixed asset.

6.  In the **Depreciation method** and **Depreciation subgroup** fields, select a depreciation method and subgroup.

7.  In the **Reason code** field, select a reason code.

8.  In the **Reason comment** field, update the reason for the transaction.

## See also

[(RUS) FA balances (form)](https://technet.microsoft.com/library/jj711559\(v=ax.60\))

[(RUS) FA value models (form)](https://technet.microsoft.com/library/jj856113\(v=ax.60\))

  


