---
title: Create a quantity and margin template
TOCTitle: Create a quantity and margin template
ms:assetid: 2019258b-5f9b-45be-979e-00d75de80c80
ms:mtpsurl: https://technet.microsoft.com/library/Hh208469(v=AX.60)
ms:contentKeyID: 36056158
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a quantity and margin template 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up quantity and margin template criterion, such as price margin amounts and percentages, to be attached to a commodity pricing template.

1.  Click **Inventory management** \> **Setup** \> **Commodity pricing** \> **Pricing template**.

2.  Select the commodity pricing template to which the new quantity and margin template must be attached.

3.  Click the **Quantity and margin template** button.

4.  To set up information for an item relationship:
    
    1.  In the **Item code** field, select **Table** for an item or **Group** for an item group.
    
    2.  In the **Item relation** field, select the specific item or item group.

5.  To set up information for a customer relationship:
    
    1.  In the **Account code** field, select **Table** for a customer, **Group** for a customer group, or **All** for all customers.
    
    2.  In the **Customer relation** field, select the specific customer or customer group.
        

        > [!NOTE]
        > <P>If you select <STRONG>All</STRONG> for the account code, this field is not applicable.</P>



6.  In the **Order quantity** field, enter the item quantity if it differs from the default. The default is the batch quantity on the current active and approved formula.

7.  Enter or change any remaining information that is required to identify the template.

## See also

[About commodity pricing](about-commodity-pricing.md)

[Commodity pricing template (form)](https://technet.microsoft.com/library/hh209282\(v=ax.60\))

[Quantity and margin template (form)](https://technet.microsoft.com/library/hh227366\(v=ax.60\))

  


