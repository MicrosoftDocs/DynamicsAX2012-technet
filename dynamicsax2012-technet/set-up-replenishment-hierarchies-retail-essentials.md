---
title: Set up replenishment hierarchies (Retail essentials)
TOCTitle: Set up replenishment hierarchies (Retail essentials)
ms:assetid: d3c364c2-e9e7-4ee0-ba6d-be384412f4da
ms:mtpsurl: https://technet.microsoft.com/library/Dn736957(v=AX.60)
ms:contentKeyID: 62200435
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up replenishment hierarchies (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up replenishment hierarchies. When you replenish inventory, you can group the stores that are replenished in one or more hierarchies. The groups can be based on how the stores are organized, the size of the stores, the inventory turnover rate of stores, or the type of stores.

To set up a replenishment hierarchy, follow these steps:

1.  Click **Retail essentials** \> **Channels** \> **Organization hierarchies**.

2.  Click **New** to create a new hierarchy.

3.  In the **Name** field, enter a unique name for the replenishment hierarchy.

4.  On the **Purposes** FastTab, click **Assign purpose**.

5.  In the **Organization hierarchy purposes** form, in the **Purposes** field, select **Retail replenishment**, and then click **Add**. Then select the organization hierarchy that you created in step 3.

6.  Close the **Organization hierarchy purposes** form, and then, in the **Organization hierarchies** form, click **View**.

7.  In the **Hierarchy designer -** form, on the **Action Pane**, click **Edit** to create a visual representation of the retail hierarchy.

8.  In the **Modify** group, click **Insert**, click the type of organization to which the retail hierarchy belongs, and then click the organization to insert.

9.  In the **Modify** group, click **Insert**, click **Retail channel**, and then click the channel to insert.

10. If you want to save the hierarchy so that you can complete it later, click **Save as draft**.
    
    If you have finished designing the hierarchy, click **Publish and close**.

Now, whenever you replenish inventory by using cross docking or buyer’s push, you can choose a hierarchy of stores to replenish.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Replenish inventory overview (Retail essentials)](replenish-inventory-overview-retail-essentials.md)

[Set up replenishment rules (Retail essentials)](set-up-replenishment-rules-retail-essentials.md)

[Use cross docking to distribute products (Retail essentials)](use-cross-docking-to-distribute-products-retail-essentials.md)

[Use buyer's push to distribute products (Retail essentials)](use-buyer-s-push-to-distribute-products-retail-essentials.md)

  


