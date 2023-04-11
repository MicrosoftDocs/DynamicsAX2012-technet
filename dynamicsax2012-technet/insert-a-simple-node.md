---
title: Insert a Simple node
TOCTitle: Insert a Simple node
ms:assetid: a753fc6b-62f6-41be-916f-184aa2d01246
ms:mtpsurl: https://technet.microsoft.com/library/Aa550305(v=AX.60)
ms:contentKeyID: 36058877
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Insert a Simple node 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Simple node is used to perform simple calculations in the modeling tree.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Select a product model. On the **Action Pane**, click the **Models** tab. In the **Modify** group \> click **Open**.

3.  Select the **Tree** tab in the lower pane.

4.  Right-click the **Modeling tree** node.

5.  Click **New** \>**Simple node**. A new node will appear at the bottom of the modeling tree. If you want to insert a node into a particular position in the tree, drag it from the node list displayed on the left.

6.  In the **Description** field, type a description for the node.

7.  Select the variable that will receive the calculation result in the **Variable** field.

8.  In the lower pane, you can build a mathematical expression – a calculation formula – that specifies the calculation to be performed by the node. The expression consists of one or more lines and each line specifies an operand and an operator. Press CTRL+N to create a new line.

9.  In the **Type** field, select whether the operand specified on this line, that is, the content of the **Operand** field, is a fixed value or a variable.

10. Specify the operand for the expression you are building in the **Operand** field. Depending on the choice made in the **Type** field, the operand can be either a fixed value or one of the product model's variables. If you specify a variable that is an array, notice that you must select the specific array element that you want, not just the name of the variable.

11. In the **Operator** field, specify an operator that connects the current line with the next line to form an expression or a part of the larger expression.

12. Click **Test** to test the code syntax.

13. Click **OK** to save the code.

## See also

[Product model (form)](https://technet.microsoft.com/library/aa574919\(v=ax.60\))

  


