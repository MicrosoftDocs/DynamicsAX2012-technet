---
title: Register item receipts with an item arrival journal
TOCTitle: Register item receipts with an item arrival journal
ms:assetid: 625347b5-95b8-4e2f-924c-53dc4a288c04
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571129(v=AX.60)
ms:contentKeyID: 36057669
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- item receipt registration
- manual registration of item receipts
- registration via input transports
- register item receipts
---

# Register item receipts with an item arrival journal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

You can register receipt of items in two ways: manually or using input transports.

To register items manually, use the **Registration** form. For more information, see [Inventory registration (form)](https://technet.microsoft.com/en-us/library/aa615731\(v=ax.60\)).

To create input transports automatically, use item arrival journals. An item arrival journal can be created as part of arrival management using the **Arrival overview** form or manually from the **Location journal** form.

For more information, see [Arrival overview (form)](https://technet.microsoft.com/en-us/library/hh227654\(v=ax.60\)) and [Location journal (form)](https://technet.microsoft.com/en-us/library/aa584822\(v=ax.60\)).

## Item arrival through item arrival journal

1.  Click **Inventory management** \> **Journals** \> **Item arrival** \> **Item arrival**. Create a journal.

2.  Enter the vendor number, the purchase order reference number, or both on the **Default values** tab.

3.  Indicate the warehouse and select the location of the inbound dock type.

4.  Click **Functions**, and then select **Create lines** to retrieve the purchase order.
    
    If you want to transfer the quantity from the purchase order, click the **Initialize quantity** check box. Microsoft Dynamics AX creates the lines that correspond to the quantity of items that fit on a pallet. The lines are then shown in the Journal lines form.

5.  Enter the **Pallet ID** in the **Journal lines** form. You can do pallet numbering in two ways:
    
      - Use the number on the pallet that has arrived. Type the number of the pallet in the **Pallet ID** field for the line. Microsoft Dynamics AX then creates a new pallet ID.
    
      - Use your own consecutive pallet numbering system. A series of numbers is used for consecutive pallet numbers. Click **Functions**, and then select **Pallet ID** to create a new number.

6.  Enter other inventory dimensions according to the requirements in the item's inventory dimension group.

7.  Check the journal, correct any mistakes, and post it. Following posting, the inventory transaction has Arrived status, and the item is registered at the inbound dock.

## See also

[Start pallet transports](start-pallet-transports.md)

[Complete pallet transports](complete-pallet-transports.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

