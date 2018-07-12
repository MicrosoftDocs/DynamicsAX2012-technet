---
title: Insert a Switch node
TOCTitle: Insert a Switch node
ms:assetid: a227c9d5-6d6c-48f6-b8e4-ac3a54c30eb2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571824(v=AX.60)
ms:contentKeyID: 36058794
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Insert a Switch node 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Switch node is useful when you have to test for several different outcomes of a certain variable. A Switch node is meaningless without one or more subnodes. The subnodes must be added manually. There are two node types that you can add to a Switch node:


> [!NOTE]
> <P>This information applies only to Product builder.</P>



  - **Case node** – Specifies case values that should be compared to the switch value.

  - **Default node** – Specifies that none of the case values are equal to the switch value.

Insert a switch node as follows:

1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Double-click a product model.

3.  Click **Product model**.

4.  Select the **Tree** tab in the lower pane.

5.  Right-click the **Modeling tree** node.

6.  Click **New** \> **Switch node**. A new node is added to the bottom of the modeling tree.

7.  To insert a node into a particular position in the tree, drag it from the node list displayed on the left.

8.  In the **Description** field in the **Switch node** form, describe what the Switch node does.

9.  In the **Switch value** field, select the switch value that will be compared to the case values defined in the subnodes for the Switch node.

10. Click **Test** to test the code syntax.

11. Click **OK** to save the code.

12. To add one or more subnodes to the Switch node, right-click the Switch node and select **New** to add a **Case node** or **Default node** subnode.
    

    > [!NOTE]
    > <P>You can add multiple case nodes, but it is only necessary to add one or zero default nodes.</P>



13. Define the actions that will be performed by each node and subnode until your Switch node is complete.

  


