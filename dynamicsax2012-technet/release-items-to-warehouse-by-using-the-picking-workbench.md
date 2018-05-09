---
title: Release items to warehouse by using the picking workbench
TOCTitle: Release items to warehouse by using the picking workbench
ms:assetid: b92ba4c6-b43d-4329-b356-db632de2ffa0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn715978(v=AX.60)
ms:contentKeyID: 62200146
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- shipping
- picked
- wave
- packing
- pick
- automatically reserve
- logic
- boxing
- ProShip
---

# Release items to warehouse by using the picking workbench 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to organize picking operations by using the picking workbench. The picking workbench helps streamline the picking process by letting you customize the number of picking lists per batch, this is also known as a picking wave. You can also customize the maximum number of lines per picking list. A picking wave encompasses a single warehouse, whereas the picking list per batch is the number of orders that one person can pick at a time.

When you run the picking workbench, Microsoft Dynamics AX will search for sales orders that match the criteria entered and then try to reserve inventory that is not already reserved. Picking lists will only be created for items that can be reserved.


> [!NOTE]
> <P>Picking lines for a picking list are generated based on the remaining quantity of items that can be physically reserved on the sales lines. If there is a Deliver now quantity entered on the sales line, it will not be used, it will be cleared.</P>



For a picking batch, you can specify attributes such as the maximum orders per batch, lines to include, delivery dates, modes of delivery, payment methods, and warehouse for order selection. After you create a picking batch, you can review the pick lines and print the picking lists. When you create a picking batch, inventory will be automatically reserved, unless the inventory was already reserved when the sales order was created. The process of creating picking lists can also be run in batch mode, which means that you could run a standard daily schedule. In addition, the picking workbench can be used with boxing logic. For more information about how to use boxing logic, see the “Optional: Use boxing logic” section later in this topic.

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
<td><p>Setup</p></td>
<td><ul>
<li><p>Configure the picking workbench setup and workbench profiles. For more information, see <a href="set-up-the-picking-workbench.md">Set up the picking workbench</a>.</p></li>
<li><p>If you want to use boxing logic, see <a href="set-up-boxing-logic.md">Set up boxing logic</a>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Data</p></td>
<td><ul>
<li><p>Ensure that there are sales orders available.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Run a picking workbench session

To run a picking workbench session, follow these steps:

1.  Click **Inventory management** \> **Common** \> **Picking workbench**.

2.  Click **New** to create a new workbench session.

3.  Optional: Enter a **Description** for the session.

4.  On the **Criteria** FastTab, enter search criteria. Search criteria can be set up manually or initialized from a workbench profile. After initialized from a profile, search parameters can be modified without affecting the profile that is used to start a picking session. To use a profile, select the template from the **Profile** field.

5.  After you have entered the search criteria, click **Generate picking batches**.

## Print the picking lists

To print the picking list, follow these steps:

1.  **Navigation Path Not Found**

2.  Expand the **Batches** FastTab.

3.  Optional: Select a user ID in the **Assigned to** field.

4.  Click **Print batch** to print the picking lists in the batch.

5.  When the picking lists have been printed, select the **Complete** check box.

6.  When all of the picking batches in a picking session have been printed, then the picking session can be marked as **Complete**.

## Troubleshoot picking lists

If items on a sales order line are not added to a picking list, it could be due to the following reasons:

  - The item could not be reserved because there is no inventory available.

  - The item’s model group allows for negative inventory, however, negative quantities cannot be reserved.

  - The item already appears on another picking list, which means that an output order exists for the item.

## Optional: Use boxing logic

You can define the dimensions and weight capacity of packing boxes in the **Packing box** form. This will ensure that multiple items can be boxed efficiently on the picking workbench, according to size, weight, depth, volume, or special requirements. For example, if there are four small, lightweight items to be shipped to the same address, you can maximize efficiency by boxing the four items in a single medium-sized box instead of four small boxes.

To use boxing logic, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Boxing logic** \> **Box definitions**.

2.  Click **New**.

3.  In the **Box name** field, enter a name, such as SmlCanned, in the **Box name** field.

4.  Describe the box and its contents in the **Description** field, for example “Small box of canned items”.

5.  Expand the **Dimensions** FastTab.

6.  In the **Box measurements** area, enter information about the dimensions of the box.

7.  In the **Maximum utilization** field, enter the percentage of the volume of the box that you want to dedicate to the item. This does not include the packaging materials.

## Related tasks

[Set up the picking workbench](set-up-the-picking-workbench.md)

[Set up boxing logic](set-up-boxing-logic.md)

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
<td><p>The main functionality of the picking workbench requires the <strong>Trade</strong> configuration key only. If you also enable the <strong>Call center</strong> configuration key, the <strong>Expedite</strong> and <strong>Payment method</strong> criteria options will also be enabled.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>The following roles have access to the picking workbench:</p>
<ul>
<li><p>Buying agent (full control)</p></li>
<li><p>Sales clerk (full control)</p></li>
<li><p>Shipping clerk (full control)</p></li>
<li><p>Warehouse manager (view access only)</p></li>
<li><p>Warehouse worker (view access only)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

