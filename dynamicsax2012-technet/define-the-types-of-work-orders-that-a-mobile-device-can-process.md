---
title: Define the types of work orders that a mobile device can process
TOCTitle: Define the types of work orders that a mobile device can process
ms:assetid: 58229dec-28ad-4707-b918-b39a76a4a26e
ms:mtpsurl: https://technet.microsoft.com/library/Dn553164(v=AX.60)
ms:contentKeyID: 62200073
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- menu
- mobile
- RF
- warehouse
- work
- menu item
- mobile device
- work template
- work user
- work class
audience: Application User
ms.search.region: Global
---

# Define the types of work orders that a mobile device can process 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to set up the work classes that specify the work orders that a mobile device can process if the menu item will process existing work. For example, a work order could include purchase orders, transfers and receipts, replenishment, or return orders. The menu item will only process work for the specified type of work order. For example, if you configure a Pallet Picking menu item to process a PalletPick work class, the worker cannot process this work class and a Loading work class.

## Define the types of work orders that a mobile device can process

To set up a work class, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Work** \> **Work classes**.

2.  Click **New** to create a new work class.

3.  In the **Work class ID** field, enter a unique identifier for the work class.

4.  In the **Work order type** field, select the work order that the work class will enable processes for. For example, select **Purchase orders** to create a work class for processing work, such as item receiving for purchase orders.

5.  In the **Description** field, enter a description of the work class.

6.  On the **Valid put location types** FastTab, in the **Location type** field, select a put away location type. For more information, see [Set up parameters to create a warehouse location](set-up-parameters-to-create-a-warehouse-location.md).

## Next step

The next step in the process of setting up mobile devices is to create menu items to define the actual work that can be done by using a mobile device.

## Related tasks

[Set up mobile device menus to display work or activities](set-up-mobile-device-menus-to-display-work-or-activities.md)

[Define the look and feel of mobile device displays](define-the-look-and-feel-of-mobile-device-displays.md)

[Set up mobile device user accounts for workers](set-up-mobile-device-user-accounts-for-workers.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


