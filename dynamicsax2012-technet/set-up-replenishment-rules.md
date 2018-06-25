---
title: Set up replenishment rules
TOCTitle: Set up replenishment rules
ms:assetid: be36cde2-fc8a-4264-b3cb-0c68ac20bb19
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597225(v=AX.60)
ms:contentKeyID: 39519298
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up replenishment rules [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You can create replenishment rules to define multiple parameters for replenishment. Rules can apply to specific retail channels or specific replenishment hierarchies. The default weight and default percentage that are used in the replenishment rules are based on the replenishment weight that is defined on the **Retail** tab in the **Warehouses** form.

You can also define a new or separate weight and percentage for each channel or hierarchy. The new values take precedence over the default weight and percentage.


> [!NOTE]
> <P>You can include a retail channel in a replenishment hierarchy that is included in a replenishment rule. In this case, warehouses that are not identified as stores are excluded from calculation and the resulting quantities that are distributed.</P>
> <P>To identify a warehouse as a store, select the <STRONG>Store</STRONG> check box on the <STRONG>Retail</STRONG> tab in the <STRONG>Warehouses</STRONG> form.</P>



1.  Click **Retail** \> **Setup** \> **Replenishment** \> **Replenishment rules**.

2.  In the **Replenishment rules** form, select a replenishment rule, or click **New** to create a new rule.

3.  If you are creating a new replenishment rule, type a name in the **Replenishment rule** field and a description in the **Description** field.

4.  On the **Lines** FastTab, click **Add**. Then, in the **Type** field, select one of the following options:
    
      - **Replenishment hierarchy** – Select this option if the replenishment rule applies to a replenishment hierarchy. Then, in the **Name** field, select a hierarchy.
    
      - **Channel** – Select this option if the replenishment rule applies to a retail channel. Then, in the **Name** field, select a channel.

5.  In the **Weight** field, specify a weight for the hierarchy or channel.

6.  Repeat steps 4 and 5 for each line that you want to add.

## See also

[Replenish inventory overview](replenish-inventory-overview.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

