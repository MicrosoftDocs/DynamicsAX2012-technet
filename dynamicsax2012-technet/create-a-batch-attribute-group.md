---
title: Create a batch attribute group
TOCTitle: Create a batch attribute group
ms:assetid: 939ec718-0cf8-4f42-9978-4eeec2fea5ef
ms:mtpsurl: https://technet.microsoft.com/library/Hh209384(v=AX.60)
ms:contentKeyID: 36058584
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a batch attribute group 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create batch attribute groups, which are groups of attributes that may share common characteristics or other similarities. When you assign an attribute group to an item, all attributes in that group apply to the item. Likewise, any changes you make to the group also apply to the items that use it.

1.  Click **Inventory management** \> **Setup** \> **Batch attributes** \> **Batch attribute groups**.

2.  Press CTRL+N to add a new line.

3.  In the **Attribute group** field, enter an identifier for the attribute group.

4.  In the **Description** field, optionally enter a description for the attribute group.

5.  To add attributes to the group, click **Group attributes**. The **Group attributes** form is displayed.
    
      - In the **Attribute** field, select the attribute to add to the group.
    
      - In the **Tolerance action** field, select the action to take when an **Integer** or **Fraction** attribute falls outside the minimum and maximum range.
    
      - In the **Target** field, enter the optimal value for the attribute. This value must be in the minimum and maximum range.

## See also

[About batch attributes](about-batch-attributes.md)

[Batch attributes (form)](https://technet.microsoft.com/library/hh209255\(v=ax.60\))

[Group attributes (form)](https://technet.microsoft.com/library/hh209573\(v=ax.60\))

  


