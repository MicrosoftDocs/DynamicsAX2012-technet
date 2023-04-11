---
title: Set up boxing logic
TOCTitle: Set up boxing logic
ms:assetid: 93bd146a-50ba-423c-adae-d39436197216
ms:mtpsurl: https://technet.microsoft.com/library/Dn715973(v=AX.60)
ms:contentKeyID: 62200120
author: tonyafehr
ms.date: 05/01/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up boxing logic 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Boxing logic is a part of the process of releasing items for picking and grouping items on a picking route. If an item requires packaging, then boxing logic can help determine the smallest box for the items to most efficiently fit into. Boxing logic is designed to select a suitably-sized box, and optimize the maximum capacity of that box, for the set of items on a picking route.

After you set up boxing logic, you can define the dimensions and boxing requirements of an item. The picking and shipping functions will then determine whether multiple items can be boxed together dependent on the box size requirements. For example, if you have 10 items to be shipped to the same address, it may be optimal to pack them all together in a medium-sized box, instead of having them shipped separately in 10 small boxes. A box name will be assigned to the picking route, and the picking routes will be split per box. Alternatively, if you do not want items to be boxed, such as items that have already been suitably package, then select the **Ship alone** check box for the item. This means that the item is already suitably packaged by itself and should not be put into another box.

Boxing logic automatically finds the most efficient way of boxing items and factors in weight, volume, and dimensions. For example, 90 items would be packed together in a single appropriately-sized box together with packing materials, instead of three boxes of 30 items.

If the limit of items of a certain dimension per box is 100, and 120 items are picked, then boxing logic automatically boxes 100 items together in one large box and 20 items together in a smaller box.

The maximum lines per picking list could be less than what is on the order. Items can be selected for picking according to user-defined specifications. For example, if a courier collects items to be shipped at 14:00, then you can specify that the corresponding picking list will be distributed at noon. Alternatively, if items that shipped by air have a higher priority, you can prioritize picking lists that only contain those items.

## This task is part of a bigger process

For more information, see [Release items to warehouse by using the picking workbench](release-items-to-warehouse-by-using-the-picking-workbench.md).

## Enable boxing logic

Use boxing logic for grouping items on a picking route and for specifying the physical dimensions of the boxes used for packing. The packing materials, weight, and volume are validated during boxing calculations. If you do not require items to be packed, for example if the items are already appropriately packed, then select **Ship alone**.

To enable boxing logic, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  On the **General** tab, in the **Boxing logic** group, select the **Boxing logic for picking workbench** check box.

3.  Click **Inventory management** \> **Setup** \> **Boxing logic** \> **Box definitions**.

4.  Select the **Active** check box to enable the box definition.

5.  Click **Product information management** \> **Common** \> **Released products**.

6.  Select a product. Click **Edit**.

7.  On the **Deliver** FastTab, select the **Apply boxing logic for picking work bench** check box.

8.  On the **Manage inventory** FastTab, ensure that you have specified the correct physical dimensions.

9.  If you do not want the items boxed, then select the **Ship alone** check box.
    
    To define items as non-boxed, go to **Product information management** \> **Common** \> **Released products**. Select an item and click **Edit**. On the **Deliver** FastTab, clear the **Apply boxing logic for picking work bench** check box. If an item is not set up for using boxing logic, then no suggestions will be made for the item, and this will allow the shipping functions to handle those items separately.

10. You can also select **Direct delivery**, and the warehouse which the items should be directly delivered to.

## Set up box definitions

To box an item by using boxing logic you must define the dimensions of a box on the **Box definitions** form, and define how you want the item to be packed. First, configure the definitions of a box, and name the definitions in a way that makes sense to you, for example, BoxSmall, BoxMedium, BoxLarge. Next, describe the box, for example, BoxLarge might be described as, Largest Box. In addition to defining a box, you can also define maximum utilization, which is the maximum percentage of the volume of the box that can be used for payload. The rest of the volume of the box will be consumed by insulation material.

1.  Click **Inventory management** \> **Setup** \> **Boxing logic** \> **Box definitions**.

2.  Click **New** and enter a name for the box.

3.  Enter a brief description.

4.  On the **Dimensions** FastTab, enter the measurements of the box.

5.  Select the **Active** check box to enable boxing logic.

## Related tasks

[Set up the picking workbench](set-up-the-picking-workbench.md), [Release items to warehouse by using the picking workbench](release-items-to-warehouse-by-using-the-picking-workbench.md).

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
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>The following roles have access to boxing logic:</p>
<ul>
<li><p>Sales clerk (full control)</p></li>
<li><p>Sales manager (full control)</p></li>
<li><p>Warehouse manager (view access only)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


