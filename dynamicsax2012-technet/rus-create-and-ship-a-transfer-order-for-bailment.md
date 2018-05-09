---
title: (RUS) Create and ship a transfer order for bailment
TOCTitle: (RUS) Create and ship a transfer order for bailment
ms:assetid: dd3cb70c-29f3-493d-bee7-a813aba9d129
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923598(v=AX.60)
ms:contentKeyID: 52075440
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and ship a transfer order for bailment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Transfer orders** form to create a transfer order, and use the **Shipment** form to ship the transfer order for bailment. You must create and ship a transfer order to transfer items from storage. For more information, see [(RUS) Create and ship a transfer order to receive an item from storage](rus-create-and-ship-a-transfer-order-to-receive-an-item-from-storage.md).

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Press CTRL+N to create a new transfer order for bailment.

3.  In the **From warehouse** field, select the warehouse of origin for the items. In the **To warehouse** field, select the destination warehouse for the items.
    

    > [!NOTE]
    > <P>You must set up a transit warehouse for the warehouse of origin in the <STRONG>Warehouses</STRONG> form.</P>



4.  On the **General** tab, in the **Type of transfer** field, select **Shipment to external party**.

5.  In the **Partner code** field, select a vendor account for the warehouse owner (bailee).

6.  In the **Agreement ID** field, select the agreement registration number for bailment.

7.  In the **Price group** field, select the price group code. In the **Currency** field, select the currency code as defined by the International Organization for Standardization (ISO).

8.  On the **Setup** tab, in the **Inventory profile** field, select the inventory profile to transfer items for storage.

9.  In the **To inventory profile** field, select the inventory profile that the transfer order is posted to.

10. In the lower pane, in the **Item number** field, select the item number of the item that is shipped for storage.

11. On the **Setup** tab, in the **Unit price** field, enter the price per unit of the item.
    

    > [!NOTE]
    > <P>You can determine the price based on the trade agreement that is registered for bailment.</P>



12. In the **Price unit** field, enter the number of units for the item. In the **Amount** field, enter the total amount of all the units for the item.

13. On the **Dimensions** tab, in the **To inventory dimensions** field group, in the **Inventory profile** field, notice that the value is updated based on one of the following conditions:
    
      - This field is updated with the value in the **To inventory profile** field on the **Setup** tab in the upper pane.
    
      - If the **To inventory profile** field on the **Setup** tab in the upper pane is blank, this field is updated with the value in the **Inventory profile** field in the **Inventory dimensions** field group on the **Dimensions** tab in the lower pane.
        

        > [!NOTE]
        > <P>The inventory profiles that are specified in the <STRONG>Inventory dimensions</STRONG> and <STRONG>To inventory dimensions</STRONG> field groups must have the same kind of activity.</P>



14. Click **Posting** \> **Ship transfer order** to open the **Shipment** form and ship the transfer order for bailment. The general ledger transactions are created based on the inventory profiles that are specified on the transfer order lines.

## See also

[(RUS) Transfer order shipment (modified form)](https://technet.microsoft.com/en-us/library/jj733191\(v=ax.60\))

[(RUS) Transfer orders (modified form)](https://technet.microsoft.com/en-us/library/jj733409\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

