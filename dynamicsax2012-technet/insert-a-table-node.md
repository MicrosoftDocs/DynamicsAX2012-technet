---
title: Insert a Table node
TOCTitle: Insert a Table node
ms:assetid: 74e8f411-9a75-4970-87cb-d5f7ce619780
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550024(v=AX.60)
ms:contentKeyID: 36058159
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Insert a Table node [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the Table node to specify that one or more of the variables for a product model should display the values selected from one or more fields in a specific Microsoft Dynamics AX table.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Double-click a product model.

3.  Click **Product model**.

4.  Select the **Tree** tab in the lower pane.

5.  Right-click the **Modeling tree** node.

6.  Click **New** \> **Table node**. A new node is added to the bottom of the modeling tree. To insert a node into a particular position in the tree, drag it from the node list displayed on the left.

7.  On the **Table value** tab, select the Microsoft Dynamics AX table that values should be retrieved from.

8.  Click the **Look up** tab, and then specify which records in the table that values should come from.

9.  Select either **Value** or **Variable** to determine the type of value to specify in the **Outcomes** field.

10. In the **Field name** field, select any field from the table specified on the **Field:** tab.
    
    A table field that is specified here will be used as a look up-key to locate the information from the selected table.

11. Depending on what you selected in the **Allocation of** field, you can specify a look up-key value in the **Outcomes** field, either as a fixed value or by reference to one of the variables for the product model.

12. Click the **Field:** tab to specify which table fields to retrieve data from and which variables that the values from the table should be assigned to.

13. Enter one line for each table field to transfer a value from. On each line, specify the names of the required table fields in the **Field name** field and of the variables that should receive each table field value in the **Variable** field.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

