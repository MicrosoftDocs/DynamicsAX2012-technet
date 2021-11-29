---
title: Batch numbers in Warehouse management
TOCTitle: Batch numbers in Warehouse management
ms:assetid: 46bc4ac0-084f-4102-bc61-83143172b5ff
ms:mtpsurl: https://technet.microsoft.com/library/Dn887221(v=AX.60)
ms:contentKeyID: 63378890
author: Khairunj
ms.date: 11/13/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Batch numbers in Warehouse management 


[!INCLUDE[archive-banner](includes/archive-banner.md)]



> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic provides information about how to allocate batch numbers in **Warehouse management**. The processes that are described require that you’ve installed Microsoft Dynamics AX 2012 R3 Cumulative Update 8. You can define policies that control when batch numbers are allocated by setting up one or more number groups, and then assigning them to products. Depending on your requirements, you can allocate batch numbers during the following processes:

  - When you perform a physical receipt of an item.

  - When you create a line that includes a product on a source document, such as a purchase order.

  - When you want to manually allocate batch numbers to products.

The sections in this topic describe how to enable batch numbering for each of these processes.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

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
<td><p>Number sequences</p></td>
<td><p>You must set up the number sequence to use when allocating batch numbers. For more information, see <a href="set-up-number-sequences-for-warehouse-management.md">Set up number sequences for warehouse management</a>.</p></td>
</tr>
<tr class="even">
<td><p>Mobile device menu items</p></td>
<td><p>You must set up mobile device menu items that use at least one of the following work creation types:</p>
<ul>
<li><p><strong>Purchase order item receiving</strong></p></li>
<li><p><strong>Purchase order item receiving and put away</strong></p></li>
<li><p><strong>Purchase order line receiving</strong></p></li>
<li><p><strong>Purchase order line receiving and put away</strong></p></li>
<li><p><strong>Load item receiving</strong></p></li>
<li><p><strong>Load item receiving and put away</strong></p></li>
</ul>
<p>For more information, see <a href="configure-mobile-devices-for-warehouse-work.md">Configure mobile devices for warehouse work</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Mobile device menu</p></td>
<td><p>You must add the mobile device menu items to a mobile device menu so that the menu items are available to workers. For more information, see <a href="set-up-mobile-device-menus-to-display-work-or-activities.md">Set up mobile device menus to display work or activities</a>.</p></td>
</tr>
</tbody>
</table>


## Allocate batch numbers upon the physical receipt of an item

This process will generate a batch number for the purchase receipt transactions when you receive an item.

To set up a number group to allocate batch numbers when an item is physically received, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Dimensions** \> **Number groups**.

2.  Create a new number group.

3.  Select the following check boxes:
    
      - **Number sequence No.**
    
      - **Only for inventory transactions**
    
      - **On physical update**

## Allocate batch numbers when you create a line that includes a product on a source document

This process will generate a batch number when you create a line that includes a product on a source document, such as a purchase order.

To set up a number group to allocate batch numbers when you create a line on a source document, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Dimensions** \> **Number groups**.

2.  Create a new number group.

3.  Select the following check boxes:
    
      - **Number sequence No.**
    
      - **Only for inventory transactions**

## Allocate batch numbers manually

This process will require a worker to use a mobile device to assign a batch number when receiving a product in the warehouse.

To set up a number group that requires workers to assign batch numbers manually, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Dimensions** \> **Number groups**.

2.  Create a new number group.

3.  Select the following check boxes:
    
      - **Number sequence No.**
    
      - **Manual**

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


## See also

[Set up production processes in a warehouse](set-up-production-processes-in-a-warehouse.md)

  


