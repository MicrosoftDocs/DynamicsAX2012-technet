---
title: Set up replenishment rules (Retail essentials)
TOCTitle: Set up replenishment rules (Retail essentials)
ms:assetid: 4836c22e-741c-4284-badd-1e41f53bc498
ms:mtpsurl: https://technet.microsoft.com/library/Dn716085(v=AX.60)
ms:contentKeyID: 62200348
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up replenishment rules (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up rules for replenishing inventory in stores. You can create replenishment rules to define inventory distribution that uses buyer’s push or cross-docking. Rules can apply to specific retail stores or specific replenishment hierarchies.


> [!NOTE]
> <P>You can include a retail store in a replenishment hierarchy that is included in a replenishment rule. In this case, warehouses that are not identified as stores are excluded from calculations and the resulting quantities that are distributed.</P>
> <P>To identify a warehouse as a store, select the <STRONG>Store</STRONG> check box on the <STRONG>Retail</STRONG> FastTab in the <STRONG>Warehouses</STRONG> form.</P>



To set up replenishment rules for a store or a replenishment hierarchy, follow these steps:

1.  Click **Retail essentials** \> **Inventory management** \> **Setup** \> **Replenishment** \> **Replenishment rules**.

2.  In the **Replenishment rules** form, select a replenishment rule, or click **New** to create a new rule.

3.  If you are creating a new replenishment rule, type a name in the **Replenishment rule** field and a description in the **Description** field.

4.  On the **Lines** FastTab, click **Add**. Then, in the **Type** field, select one of the following options:
    
      - **Replenishment hierarchy** – Select this option if the replenishment rule applies to a replenishment hierarchy. Then, in the **Name** field, select a hierarchy.
    
      - **Channel** – Select this option if the replenishment rule applies to a retail store. Then, in the **Name** field, select a channel.

5.  In the **Weight** field, specify a weight for the hierarchy or channel.
    
    The default weight and default percentage that are used in replenishment rules are based on the replenishment weight that is defined on the **Retail** FastTab in the **Warehouses** form. You can also define a new or separate weight and percentage for each channel or hierarchy. The new values take precedence over the default weight and percentage.

6.  Repeat steps 4 and 5 for each line that you want to add.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Replenish inventory overview (Retail essentials)](replenish-inventory-overview-retail-essentials.md)

  


