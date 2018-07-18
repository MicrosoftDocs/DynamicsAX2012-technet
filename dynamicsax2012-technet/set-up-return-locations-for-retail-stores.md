---
title: Set up return locations for retail stores
TOCTitle: Set up return locations for retail stores
ms:assetid: 7d718787-8ed7-4d22-9af1-68511a1b413b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn720765(v=AX.60)
ms:contentKeyID: 62231563
ms.date: 05/01/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up return locations for retail stores 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up return locations that are based on retail info codes and sales and marketing reason codes. Cashiers often identify the reason for a return when a customer returns a purchase. You can specify that returned products are assigned to different return locations in inventory based on the cashier’s response to info codes and reason codes that are displayed at the point of sale (POS) on the Retail POS register.

For example, when a customer returns a defective product, the cashier processes the return transaction, Retail POS displays the info code for returns, the cashier selects the subcode for defective returns, and the returned product is automatically assigned to a specific return location.

A return location can be a warehouse, a location within a warehouse, or even a particular pallet, depending on what inventory locations your organization has set up. You can map each return location to one or more info codes in **Retail** and reason codes in **Sales and marketing**.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 R2 and AX 2012 Feature Pack, <EM>info codes</EM> in Retail were called <EM>reason codes</EM>.</P>



**Prerequisites**

Before you can set up return locations, you must set up the following:

  - Retail info codes – Prompts at the POS register that are set up in the **Retail** module. For more information, see [Setting up info codes](setting-up-info-codes.md).

  - Sales and marketing reason codes – Prompts at the POS register that are set up in the **Sales and marketing** module. For more information, see [Set up return reason codes](set-up-return-reason-codes.md).

  - Inventory locations – The places where inventory is kept. For more information, see [About locations](about-locations.md).

To set up return locations, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Warehouses**.

2.  Select a warehouse, and then on the **Retail** FastTab, in the **Default return location** field, select an inventory location.
    
    This is the inventory location for returns whose info codes or reason codes are not mapped to return locations.

3.  In the **Default return pallet** field, select a pallet.
    
    This is the pallet for returns whose info codes or reason codes are not mapped to return locations.

4.  Click **Retail** \> **Setup** \> **Return locations**.

5.  In the **Return location** form, click **New** to create a new return location.

6.  Enter a unique name and a description for the return location.
    

    > [!NOTE]
    > <P>The name is entered automatically if a number sequence has been set up for return locations.</P>



7.  On the **General** FastTab, select the **Print labels** check box to print labels for all the products that are assigned to return locations.

8.  On the **General** FastTab, select the **Block inventory** check box to take the returned products in the default return location out of inventory and prevent them from being sold.

9.  To map specific retail info codes and subcodes to return locations, click **Add** on the **Map retail info codes** FastTab, and then enter the following information:
    
      - In the **Reason code** field, select an info code for returns.
    
      - In the **Subcode** field, select a subcode for the reason for the return.
    
      - The **Description** field displays a description of the selected info code.
    
      - In the **Store** field, select the store where the info code is used.
    
      - Use the **Warehouse**, **Location**, and **Pallet ID** fields to specify a return location. For example, to specify a particular location in a store, select a store in the **Store** field and a location in the **Location** field.
    
      - Select the **Block inventory** check box to take returned products out of inventory and prevent them from being sold.

10. To map specific sales and marketing reason codes to return locations, click **Add** on the **Map sales and marketing reason codes** FastTab, and then enter the following information:
    
      - In the **Info code** field, select a reason code for returns.
    
      - The **Description** field displays the description of the selected reason code.
    
      - In the **Store** field, select the store where the reason code is used.
    
      - Use the **Warehouse**, **Location**, and **Pallet ID** fields to specify a return location. For example, to specify a particular pallet in a location in a warehouse, select a warehouse in the **Warehouse** field, a location in the **Location** field, and a pallet in the **Pallet ID** field.
    
      - Select the **Block inventory** check box to take returned products out of inventory and prevent them from being sold.

## See also

[About info codes (Retail)](about-info-codes-retail.md)

[Set up return reason codes](set-up-return-reason-codes.md)

  


