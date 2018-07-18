---
title: Insert an IF node
TOCTitle: Insert an IF node
ms:assetid: 024803ed-0196-456d-8726-b07cd85901f6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569692(v=AX.60)
ms:contentKeyID: 36055926
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Insert an IF node 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **IF node** is useful when a decision must be based on a single logical condition.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Select a product model \> click **Open**.

3.  Select the **Tree** tab in the lower pane.

4.  Right-click the **Modeling tree** node.

5.  Click **New** \> **IF node**. A new node will appear at the bottom of the modeling tree. To insert a node into a particular position in the tree, drag it from the node list displayed on the left.

6.  Type the IF node description in the **Description** field.

7.  In the **Code** field, write the logical condition that the IF node should be tested for. The condition must be stated in the form of an X++ expression. For a description of X++ expressions, see the Microsoft Dynamics AX Developer’s Guide.

8.  Click **Test** to test the code syntax.

9.  Click **OK** to save the code and close the **IF - condition** form. An IF node will be created and will include two subnodes:
    
      - **THEN node**
    
      - **ELSE node**

10. Under the THEN node and ELSE node, add subnodes that represent the parts of the item configuration that depend on the value of the condition for the IF node.

  


