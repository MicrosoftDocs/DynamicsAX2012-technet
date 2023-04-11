---
title: Set up the pricing precision for a potency item
TOCTitle: Set up the pricing precision for a potency item
ms:assetid: 9859e3ac-b293-415b-90d8-89f1f2c8a097
ms:mtpsurl: https://technet.microsoft.com/library/JJ838743(v=AX.60)
ms:contentKeyID: 50120626
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up the pricing precision for a potency item 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to define the degree of purchase pricing precision for a specified potency item. The pricing precision value is used to round off the adjusted purchase price. By default, purchase prices have two digits following the decimal point. When a purchase price is divided by the target potency value, the resulting absolute value might have more than two digits following the decimal point. In such cases, the resulting value is automatically rounding up or down, as appropriate. To avoid this scenario, you must set up a purchase pricing precision value for the specified potency item in the **Released product details** form.

1.  Click **Product information management** \> **Common** \> **Released products**. Select a released product line. On the **Action Pane**, on the **Product** tab, in the **Maintain** group, click **Edit**.

2.  Click the **Purchase** FastTab.

3.  In the **Pricing precision** field, enter the purchase pricing precision value to use.
    

    > [!NOTE]
    > <P>You can enter any integer value from 0 (zero) through 5 as the pricing precision value.</P>



## See also

[(PM) Released product details (form)](https://technet.microsoft.com/library/hh352306\(v=ax.60\))

  


