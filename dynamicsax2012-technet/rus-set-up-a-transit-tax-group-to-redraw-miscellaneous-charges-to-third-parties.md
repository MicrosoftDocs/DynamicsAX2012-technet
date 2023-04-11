---
title: (RUS) Set up a transit tax group to redraw miscellaneous charges to third parties
TOCTitle: (RUS) Set up a transit tax group to redraw miscellaneous charges to third parties
ms:assetid: 4cd4d69d-f81e-4537-b0e7-ed08eb043205
ms:mtpsurl: https://technet.microsoft.com/library/JJ733217(v=AX.60)
ms:contentKeyID: 49685185
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a transit tax group to redraw miscellaneous charges to third parties 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up a transit tax group so that you can redraw charges to third parties. This tax group is used in the invoice that is created during the redraw debt transaction.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

2.  Press CTRL+N to create a new sales tax group. For more information, see [Sales tax groups (form)](https://technet.microsoft.com/library/aa498345\(v=ax.60\)).

3.  On the **General** FastTab, in the **Transit tax group** field, select the sales tax group that has an exempt tax code that is used to redraw the charges.
    

    > [!NOTE]
    > <P>You must also specify the corresponding transit tax group for other sales tax groups.</P>



4.  On the **Setup** FastTab, in the **Sales tax code** field, select the sales tax code.

5.  Select the **Exempt** check box to indicate that sales tax is not calculated for the selected sales tax code.

## See also

[(RUS) Set up a transit account to redraw miscellaneous charges to third parties](rus-set-up-a-transit-account-to-redraw-miscellaneous-charges-to-third-parties.md)

  


