---
title: Insert a BOM node
TOCTitle: Insert a BOM node
ms:assetid: fe8135aa-3b35-4315-bbb6-a7ceb4cedc34
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa573446(v=AX.60)
ms:contentKeyID: 36060118
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Insert a BOM node [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The bill of materials (BOM) node is useful for adding individual BOM lines to a product model. To add a complete BOM from the **Bills of materials** form, you should use a **Default node** instead.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Double-click a product model line.

3.  Click **Product model**.

4.  Select the **Tree** tab in the lower pane.

5.  Right-click the **Modeling tree** node.

6.  Click **New** \> **BOM node**. A new node will appear at the bottom of the modeling tree. To insert a node into a particular position in the tree, drag it from the node list displayed on the left.

7.  In the **BOM line** form, the same fields as in a standard BOM line in the **Bills of materials** form are displayed. In addition, there are two extra fields that control how values are assigned to each data field on the BOM line. Select one of the following options:
    
      - **Value** – Type a fixed value in the BOM line field. The fixed value can be a numeric value or some other type of data, depending on which field you are in.
    
      - **Variable** – Type the name of one of the variables for the product model in the BOM line field. When the item is configured, this field is completed with the value of the selected variable.

8.  Complete the rest of the fields in the **BOM line** form. For their descriptions, see [BOM (form)](https://technet.microsoft.com/en-us/library/aa587282\(v=ax.60\)).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

