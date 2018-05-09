---
title: (RUS) Create a calculation item and assign an inventory unit to the item
TOCTitle: (RUS) Create a calculation item and assign an inventory unit to the item
ms:assetid: a09b6968-9fa0-472d-8d2b-17ab71ef665b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733262(v=AX.60)
ms:contentKeyID: 49685229
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create a calculation item and assign an inventory unit to the item 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a calculation item, assign an inventory unit to the item, and set up the price and free storage days for the item. You can calculate the storage service amount for items by using the calculation item and the inventory unit that is assigned to the item. You must select the owner, inventory profile, and batch number dimensions in the dimension group that is assigned to the calculation item and the item that is in storage. For more information, see [Dimensions display (form)](https://technet.microsoft.com/en-us/library/aa556972\(v=ax.60\)).

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Click **Product** to create a new calculation item for the service item group.

3.  In the **Product type** field, select **Item**, and then enter the required details.

4.  Click **OK** to close the form.

5.  Select an item, and then click **Edit** to open the **Released product details** form.

6.  Click the **General** FastTab, and then, in the **Item model group** field, select an item model group that can have a negative physical inventory when the item is picked.
    

    > [!NOTE]
    > <P>You must select the <STRONG>Physical negative inventory</STRONG> check box on the <STRONG>Setup</STRONG> tab in the <STRONG>Item model groups</STRONG> form.</P>



7.  Click the **Manage inventory** FastTab, and then, in the **Batch number group** field, select a batch number group for the calculation item.

8.  Click the **Manage costs** FastTab, and then, in the **Unit** field, select the inventory unit for the calculation of the storage service amount.

9.  On the **Sell** tab, in the **Trade agreements** action group, click **Create trade agreements** to create a price/discount agreement journal. For more information, see [Price/discount agreement journals (form)](https://technet.microsoft.com/en-us/library/aa556469\(v=ax.60\)).

10. In the **Price/discount agreement journals** form, click **Lines** to create the trade agreement lines. For more information, see [Journal lines, price/discount agreement (form)](https://technet.microsoft.com/en-us/library/aa553463\(v=ax.60\)).

11. In the **Relation** field, select **Price (sales)**.

12. In the **Price** field, enter the price per unit of the item.

13. In the **Free days** field, enter the number of days for which the storage service amount of items is not calculated.

14. Post the journal.

15. In the **Released product details** form, on the **Sell** tab, click **Sales price** to view the details of the price or discount and the free days that were created for bailment.

## See also

[Release products (form)](https://technet.microsoft.com/en-us/library/hh227553\(v=ax.60\))

[(RUS) Set up tracking dimensions for an inventory owner](rus-set-up-tracking-dimensions-for-an-inventory-owner.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

