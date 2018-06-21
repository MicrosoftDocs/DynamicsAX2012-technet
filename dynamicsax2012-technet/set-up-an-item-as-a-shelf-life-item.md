---
title: Set up an item as a shelf life item
TOCTitle: Set up an item as a shelf life item
ms:assetid: 49ab1325-94ff-4439-95c0-d9f14954faf7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838734(v=AX.60)
ms:contentKeyID: 50120617
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up an item as a shelf life item [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up an item as a shelf life item. You can assign a shelf life item as an ingredient in a formula to transfer the shelf life information to a finished item.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select a released product, and then click **Edit**, or on the **Action Pane**, click **Product** to create a released product. For more information, see [Key tasks: Define products](key-tasks-define-products.md).

3.  In the **Released product details** form, on the **Action Pane**, on the **Product** tab, click **Dimension group**.

4.  In the **Tracking dimension group** field, select a tracking dimension group for the item. You must select a tracking dimension group for which **Active** and **Primary stocking** check boxes are selected for **Batch number** in the **Tracking dimension groups** form.

5.  Click **OK**.

6.  On the **General** FastTab, in the **Item model group** field, select the identification code of the model group for the item.

7.  Click the **Manage inventory** FastTab.

8.  In the **Shelf life period in days** field, enter the number of days that are added to the batch date of the item to determine the expiration date of the item.
    
    You must enter a non-zero value to set up the item as a shelf life item.
    

    > [!NOTE]
    > <P>This field is available only if the following conditions are met:</P>
    > <UL>
    > <LI>
    > <P>You select a tracking dimension for which the <STRONG>Active</STRONG> and <STRONG>Primary stocking</STRONG> check boxes are selected for <STRONG>Batch number</STRONG> in the <STRONG>Tracking dimension groups</STRONG> form.</P>
    > <LI>
    > <P>You select an item model group in the <STRONG>Item model group</STRONG> field.</P></LI></UL>



## See also

[(PM) Released product details (form)](https://technet.microsoft.com/en-us/library/hh352306\(v=ax.60\))

[Tracking dimension groups (form)](https://technet.microsoft.com/en-us/library/hh209465\(v=ax.60\))

[(PM) Item model groups (form)](https://technet.microsoft.com/en-us/library/hh328695\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

