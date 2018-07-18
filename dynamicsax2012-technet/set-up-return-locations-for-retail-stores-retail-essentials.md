---
title: Set up return locations for retail stores (Retail essentials)
TOCTitle: Set up return locations for retail stores (Retail essentials)
ms:assetid: ef0ec03c-ebbc-434f-ba68-cd69dc20e2b2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn859571(v=AX.60)
ms:contentKeyID: 63820144
ms.date: 01/14/2015
mtps_version: v=AX.60
---

# Set up return locations for retail stores (Retail essentials) 


This topic explains how to set up return locations. When a customer returns a purchase, the cashier often identifies the reason for the return. You can specify that returned products are assigned to different return locations in inventory, depending on the cashier’s response to the info codes and reason codes that are displayed at the point of sale (POS) on the Microsoft Dynamics AX for Retail POS register.

For example, a customer returns a defective product. When the cashier processes the return transaction, Retail POS displays the info code for returns, and the cashier selects the subcode for defective returns. The returned product is then automatically assigned to a specific return location.

A return location can be a warehouse, a location in a warehouse, or even a particular pallet, depending on the inventory locations that your organization has set up.

**Prerequisites**

Before you can set up return locations, you must set up retail info codes. For more information, see [Set up info codes (Retail essentials)](set-up-info-codes-retail-essentials.md) and [Set up info code groups (Retail essentials)](set-up-info-code-groups-retail-essentials.md).

To set up return locations, follow these steps.

1.  Click **Retail essentials** \> **Channels** \> **Warehouses**.

2.  Select a warehouse, and then, on the **Retail** FastTab, in the **Default return location** field, select an inventory location.
    
    This inventory location is used for returns if the info codes or reason codes are not mapped to return locations.

3.  In the **Default return pallet** field, select a pallet.
    
    This pallet is used for returns if the info codes or reason codes are not mapped to return locations.

4.  Click **Retail essentials** \> **Inventory management** \> **Setup** \> **Return locations**.

5.  In the **Return location** form, click **New** to create a new return location.

6.  Enter a unique name and a description for the return location.
    

    > [!NOTE]
    > <P>If a number sequence has been set up for return locations, the name is entered automatically.</P>



7.  On the **General** FastTab, select the **Print labels** check box to print labels for all the products that are assigned to return locations.

8.  On the **General** FastTab, select the **Block inventory** check box to take the returned products in the default return location out of inventory and prevent them from being sold.

9.  To map specific retail info codes and subcodes to return locations, on the **Map retail info codes** FastTab, click **Add**. Then enter the following information:
    
      - In the **Reason code** field, select an info code for returns.
    
      - In the **Subcode** field, select a subcode for the reason for the return.
    
      - The **Description** field displays a description of the selected info code.
    
      - In the **Store** field, select the store where the info code is used.
    
      - Use the **Warehouse**, **Location**, and **Pallet ID** fields to specify a return location. For example, to specify a particular location in a store, select a store in the **Store** field and a location in the **Location** field.
    
      - Select the **Block inventory** check box to take returned products out of inventory and prevent them from being sold.

10. To map specific sales and marketing reason codes to return locations, on the **Map sales and marketing reason codes** FastTab, click **Add**. Then enter the following information:
    
      - In the **Info code** field, select a reason code for returns.
    
      - The **Description** field displays the description of the selected reason code.
    
      - In the **Store** field, select the store where the reason code is used.
    
      - Use the **Warehouse**, **Location**, and **Pallet ID** fields to specify a return location. For example, to specify a particular pallet in a location in a warehouse, select a warehouse in the **Warehouse** field, a location in the **Location** field, and a pallet in the **Pallet ID** field.
    
      - Select the **Block inventory** check box to take returned products out of inventory and prevent them from being sold.

  


