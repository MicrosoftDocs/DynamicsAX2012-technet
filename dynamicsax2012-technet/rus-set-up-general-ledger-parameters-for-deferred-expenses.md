---
title: (RUS) Set up general ledger parameters for deferred expenses
TOCTitle: (RUS) Set up general ledger parameters for deferred expenses
ms:assetid: 269d3d1b-1d81-4ee4-a4f8-60fe3adfd986
ms:mtpsurl: https://technet.microsoft.com/library/JJ711485(v=AX.60)
ms:contentKeyID: 49387302
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up general ledger parameters for deferred expenses 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Although you can generate deferred expenses manually in the deferrals module, you can also generate these expenses automatically from other system modules when, for example, you dispose of an asset at a loss, or calculate deferred expenses over norm. Deferral write-off is performed automatically during each period based on an amount that is defined by the write-off period and the expense amount. You can calculate deferred expenses for an infinite number of models, using both simultaneous and independent deferrals calculations for tax, regular, and business accounts.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click the **Deferrals** tab.

3.  In the **Posting profile** field, select the posting profile that is to be used as the default for deferrals.
    

    > [!NOTE]
    > <P>The selected posting profile is displayed automatically on the deferral voucher when it is registered.</P>



4.  In the **Round-off** field, enter the default round-off amount for the deferrals write-off methods. For example, if you specify the figure 0.01, values are rounded to two decimal places.

5.  Under the **Default financial dimensions** field group, select the default financial dimension.

6.  In the **Base value model** field, select a base value model as the default for deferrals.

7.  Click the **Number sequences** tab.

8.  In the **Number sequence code field** field, select the number sequence code for the **Deferral ID**.

9.  Press CTRL+S or close the form.

  


