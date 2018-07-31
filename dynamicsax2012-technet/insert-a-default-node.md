---
title: Insert a Default node
TOCTitle: Insert a Default node
ms:assetid: 58eb0cd5-062c-4507-9aa9-2ee72a34fd36
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa549073(v=AX.60)
ms:contentKeyID: 36057345
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Insert a Default node 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Default node** to insert standard routes or bills of materials (BOM) into a product model—or you can use it to specify a default route for the product model.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Double-click a product model.

3.  Click **Product model**.

4.  Select the **Tree** tab in the lower pane.

5.  Right-click the **Modeling tree** node.

6.  Click **New** \> **Default node**.
    
    A new Default node appears at the bottom of the modeling tree. To insert a node into a particular position in the tree, drag it from the node list displayed on the left.

7.  In the **Default** form in the **Type** field, select **Default route**, **Route**, or **BOM**.
    
      - If you select either **Route** or **BOM**, your selection in the **Default** field will add either a route or a BOM to the product model.
    
      - If you select **Default route**, the default route you select in the **Default** field will be used as a template when new route nodes are subsequently added to the modeling tree.

8.  Depending on what you selected in the **Type** field, select the route, a bill of materials, or a default route for the product model in the **Default** field.

9.  Click **Test** to test the code syntax.

10. Click **OK** to save the code and close the **Default** form.

  


