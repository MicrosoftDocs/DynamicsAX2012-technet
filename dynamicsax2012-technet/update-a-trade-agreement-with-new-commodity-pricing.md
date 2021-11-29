---
title: Update a trade agreement with new commodity pricing
TOCTitle: Update a trade agreement with new commodity pricing
ms:assetid: 1f76d8db-5177-4121-907d-0438e42dfc53
ms:mtpsurl: https://technet.microsoft.com/library/Hh208465(v=AX.60)
ms:contentKeyID: 36056153
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Update a trade agreement with new commodity pricing 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to update pricing information for commodity pricing items that are included in sales price trade agreements. You must run the commodity pricing batch before you can use this procedure.

1.  Click **Inventory management** \> **Periodic** \> **Commodity pricing** \> **Price margin update**.

2.  In the **Pricing calculation** field, select the commodity pricing batch to use in the update.

3.  Click the **Lines** button to display the **Price margin update-lines** form.

4.  After you have reviewed the pricing details, mark the items that have trade agreements and that you want to update with the new pricing.
    
    1.  Select the item or items to be marked.
    
    2.  Click the **Functions** button and select **Mark for update**.

5.  Update the related trade agreements for the marked items:
    
    1.  Click the **Update trade agreements** button.
    
    2.  Click **OK** to add the changes to the **Price/discount agreement journals** form.
    
    3.  Post the pricing changes to the journal.
        

        > [!IMPORTANT]
        > <P>The new pricing becomes effective only after you post the journal.</P>



## See also

[About commodity pricing](about-commodity-pricing.md)

[Price/discount agreement journals (form)](https://technet.microsoft.com/library/aa556469\(v=ax.60\))

[Price margin update (form)](https://technet.microsoft.com/library/hh227659\(v=ax.60\))

[Price margin update-lines (form)](https://technet.microsoft.com/library/hh242671\(v=ax.60\))

  


