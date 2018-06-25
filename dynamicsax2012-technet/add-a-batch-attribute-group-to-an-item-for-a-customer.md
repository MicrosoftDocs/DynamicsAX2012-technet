---
title: Add a batch attribute group to an item for a customer
TOCTitle: Add a batch attribute group to an item for a customer
ms:assetid: ac7e416e-d0f1-4f88-ae0f-f357ec54e89e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242696(v=AX.60)
ms:contentKeyID: 36058915
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Add a batch attribute group to an item for a customer [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to add a batch attribute group to an item for a customer. When you assign a group of attributes to an item, all of the attributes included in the group apply to the item for this customer. Any changes that you make to the attributes in the group automatically apply to all items that use that group.


> [!IMPORTANT]
> <P>Before you can add a batch attribute group to an item for a specific customer, you must first add the batch attribute group to the item. For more information, see <A href="add-a-batch-attribute-group-to-an-item.md">Add a batch attribute group to an item</A>.</P>



1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select the item.
    

    > [!NOTE]
    > <P>The item you select must be batch controlled. An item is batch controlled if the <STRONG>Batch number</STRONG> field is set to <STRONG>Active</STRONG> for the item in the Tracking dimension group.</P>



3.  On the **Action Pane**, on the **Manage inventory** tab, in the **Batch attributes** group, click **Customer specific**.

4.  Press CTRL+N to add a new batch attribute group.

5.  In the **Attribute code** field, select **Group**.

6.  In the **Attribute relation** field, select the batch attribute group that you want to add to the item.

7.  In the **Account code** field, select **Table**.

8.  In the **Account selection** field, select the customer’s account.

## See also

[About batch attributes](about-batch-attributes.md)

[Customer specific (form)](https://technet.microsoft.com/en-us/library/hh209393\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

