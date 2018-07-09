---
title: Add batch attribute values to an inventory batch for potency items
TOCTitle: Add batch attribute values to an inventory batch for potency items
ms:assetid: c4631261-6544-4d85-b86c-6147b77223e6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838748(v=AX.60)
ms:contentKeyID: 50120631
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Add batch attribute values to an inventory batch for potency items [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to add batch attribute values to the inventory batch for an item. You can either add all the batch attributes values for the item or add a subset of those values. For more information, see [(PM) Batches (form)](https://technet.microsoft.com/en-us/library/hh209252\(v=ax.60\)).

1.  Click **Inventory management** \> **Inquiries** \> **Dimensions** \> **Batches**.

2.  To display the potency base attribute assigned to the item, select an inventory batch, and then click **Inventory batch attributes**.

3.  Click **Add** to add a new batch attribute.

4.  In the **Attribute** field, select an attribute to add to the inventory batch. You cannot use the same attribute more than once in a specified inventory batch.

5.  In the **Attribute value** field, enter a numeric value for the batch attribute. The batch attribute value must be in the minimum and maximum range defined for the item in the **Batch attributes by item** form.
    

    > [!NOTE]
    > <P>You can also click <STRONG>Load item attributes</STRONG> to load the predefined batch attribute values for the item.</P>



6.  Close the form.
    
    When you close the form, the **Available quantity**, **Active quantity**, **Base attribute**, **Base value**, and **Actual value** fields in the **Batches** form are updated based on the inventory batch attributes that you added in this procedure.

## See also

[Inventory batch attributes (form)](https://technet.microsoft.com/en-us/library/hh209284\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

