---
title: (IND) Set up the SION
TOCTitle: (IND) Set up the SION
ms:assetid: 57aab86b-e72f-41a0-936b-227233b3b4f9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677829(v=AX.60)
ms:contentKeyID: 49385793
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- SION
- SION form
- set up sion
---

# (IND) Set up the SION [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up Standard Input Output Norms (SION), and to assign product groups and products from a bill of materials (BOM) to the SION.


> [!NOTE]
> <P>You cannot delete a product group in the SION if products in the product group are assigned to the SION.</P>



1.  Click **Inventory management** \> **Setup** \> **EXIM** \> **SION**.

2.  In the **SION** form, click **New**.

3.  On the **Overview** FastTab, in the **Product group** field, select a product group for the SION.

4.  In the **Start date/time** field, enter the effective date for the assignment of the product group to the SION.

5.  In the **End date/time** field, enter an expiration date for the product group assignment. If you do not want the assignment to expire, leave the field blank.

6.  On the **Lines** FastTab, enter the SION number of the item.

7.  In the **Item number** field, select an item from the product group.

8.  In the **BOM number** field, select the number of the BOM that is assigned to the item.

9.  In the **Unit** field, select the unit of measurement for the item. The **Unit** field is updated automatically with the value that is defined for the selected item.

10. In the **Quantity** field, select the quantity of finished items for which the input goods are specified in the SION document. The default value is 1.

11. On the **Lines** FastTab, click **SION Items**.

12. In the **SION Items** form, add products to the product group that you are assigning to the SION. For more information, see [(IND) SION (form)](https://technet.microsoft.com/en-us/library/jj710966\(v=ax.60\)).

13. Optional: You can copy the SION to another product group. On the **Overview** FastTab, click **Copy**, and then select the product group to copy the SION to. For more information, see [(IND) Copy a product group in the SION](ind-copy-a-product-group-in-the-sion.md).

## See also

[(IND) Set up the SION items](ind-set-up-the-sion-items.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

