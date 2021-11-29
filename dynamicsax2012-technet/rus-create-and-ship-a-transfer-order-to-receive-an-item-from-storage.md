---
title: (RUS) Create and ship a transfer order to receive an item from storage
TOCTitle: (RUS) Create and ship a transfer order to receive an item from storage
ms:assetid: 3389a5a4-cfa2-43a8-a263-3bed17e38938
ms:mtpsurl: https://technet.microsoft.com/library/JJ853168(v=AX.60)
ms:contentKeyID: 50396448
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and ship a transfer order to receive an item from storage 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Transfer orders** form to create a transfer order. You can use the transfer order to ship items from the source warehouse. After storage, you can receive the items from a bailee by using the **Shipment** form.

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Press CTRL+N to create a new transfer order to receive an item from storage.
    

    > [!NOTE]
    > <P>You must set up a transit warehouse for the warehouse of origin in the <STRONG>Warehouses</STRONG> form.</P>



3.  On the **General** tab, in the **Type of transfer** field, select **Return from external party**.

4.  In the **Partner code** field, select a vendor account for the warehouse owner, or bailee.

5.  In the **Agreement ID** fields, select a contract group and a contract registration number for bailment.

6.  In the **Price group** field, select the price group code for the bailment process. In the **Currency** field, select the currency code, as defined by the International Organization for Standardization (ISO).

7.  On the **Setup** tab, in the **Inventory profile** field, select the inventory profile to receive items from storage.

8.  In the **To inventory profile** field, select the inventory profile that the transfer order is posted to.

9.  In the lower pane, in the **Item number** field, select the item number of the item that is received from storage.

10. On the **Setup** tab, in the **Unit price** field, enter the price per unit of the item.
    

    > [!NOTE]
    > <P>You can determine the price based on the trade agreement that is registered for the bailment process.</P>



11. In the **Price unit** field, enter the number of units for the item. In the **Amount** field, enter the total amount of all of the units for the item.

12. On the **Dimensions** tab, in the **To inventory dimensions** field group, notice that the value in the **Inventory profile** field is updated based on the following conditions:
    
      - If the **To inventory profile** field on the **Setup** tab in the upper pane has a value, the **Inventory profile** field in the **To inventory dimensions** field group is updated with that value.
    
      - If the **To inventory profile** field on the **Setup** tab in the upper pane is blank, the **Inventory profile** field in the **To inventory dimensions** field group is updated with the value in the **Inventory profile** field on the **Dimensions** tab.
        

        > [!NOTE]
        > <P>The inventory profiles that are specified in the <STRONG>Inventory dimensions</STRONG> and <STRONG>To inventory dimensions</STRONG> field groups must have the same kind of activity.</P>



13. Click **Posting** \> **Ship transfer order** to open the **Shipment** form and ship the transfer order, so that you can receive an item from storage. The general ledger transactions are created based on the inventory profiles that are specified on the transfer order lines.

## See also

[Transfer orders (form)](https://technet.microsoft.com/library/aa634530\(v=ax.60\))

[(RUS) Transfer orders (modified form)](https://technet.microsoft.com/library/jj733409\(v=ax.60\))

[(RUS) Transfer order shipment (modified form)](https://technet.microsoft.com/library/jj733191\(v=ax.60\))

[About transfer orders](about-transfer-orders.md)

  


