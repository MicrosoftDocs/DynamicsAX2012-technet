---
title: Create or modify an inbound load
TOCTitle: Create or modify an inbound load
ms:assetid: 95d43aca-d158-4ec9-8d86-1f0906ed5a06
ms:mtpsurl: https://technet.microsoft.com/library/Dn553181(v=AX.60)
ms:contentKeyID: 62524891
author: Khairunj
ms.date: 06/25/2014
mtps_version: v=AX.60
f1_keywords:
- shipping carrier
- inbound load
- load planning
- load planning workbench
- transportation function
audience: Application User
ms.search.region: Global
---

# Create or modify an inbound load 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic explains how to create or modify an inbound load. You can use a purchase order to create an inbound load automatically or manually. You can also modify an existing inbound load by adding a new purchase order line.

Load planning is one of the transportation functions performed by transportation coordinators. The inbound load process starts when there is a demand for specific items that have to be shipped from a vendor location to a company’s warehouse location.

## This task is part of a bigger process

The following illustration shows how creating an inbound load relates to other tasks in the transportation planning for inbound loads.

For an overview of the process, see [Business process: Planning transportation for inbound loads](business-process-planning-transportation-for-inbound-loads.md).

![Process flow for inbound load transportation](images/Dn553181.Businessprocessflowforinboundloadtransportation(AX.60).jpg "Process flow for inbound load transportation")

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
<th><p>Prerequisites</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Related setup tasks</p></td>
<td><ul>
<li><p>In the <strong>Released product details</strong> form, create an item, and then select the <strong>Use transportation management processes</strong> check box. For more information, see <a href="create-items.md">Create items</a> and <a href="key-tasks-release-products.md">Key tasks: Release products</a>.</p></li>
<li><p>In the <strong>Warehouses</strong> form, create a warehouse, and then select the <strong>Use warehouse management processes</strong> check box. For more information, see <a href="create-warehouses.md">Create warehouses</a>.</p></li>
<li><p>Set up a load template. For more information, see <a href="set-up-a-load-template.md">Set up a load template</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Create an inbound load automatically by using a purchase order

To create an inbound load automatically by using a purchase order, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse management parameters**.
    
    –or–
    
    Click **Transportation management** \> **Setup** \> **Transportation management parameters**.

2.  Click **Loads**, and then select the **Automatically create at purchase order entry** check box.

3.  Create a purchase order. An inbound load will be created automatically. For more information, see [Create a purchase order](create-a-purchase-order.md).

## Create an inbound load manually by using a purchase order or purchase order line

To create an inbound load manually by using a purchase order or a purchase order line, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse management parameters**.
    
    –or–
    
    Click **Transportation management** \> **Setup** \> **Transportation management parameters**.

2.  Click **Loads**, and then clear the **Automatically create at purchase order entry** check box.

3.  Click **Transportation management** \> **Inquiries** \> **Load planning workbench**.
    
    –or–
    
    Click **Warehouse management** \> **Common** \> **Load planning workbench**.

4.  On the **Purchase order lines** tab, select a purchase order line for which you want to create an inbound load.

5.  On the **Action Pane**, click **To new load** to create a new load for a PO line, or click **Entire order to new load** to create a new load with details from the purchase order.

6.  In the **Load template assignment** form, select a load template identifier (ID) to define a trailer type for the load.

7.  Click **OK** to confirm the load. In the **Load planning workbench** form, on the **Load lines** tab, you can view the details for the new loads.

## Optional: Split a purchase order line to create multiple loads

To split a purchase order line to create multiple loads, follow these steps:

1.  In the **Load planning workbench** form, on the **Purchase order lines** tab, select a line, and then click **To new load**.

2.  In the **Load template assignment** form, select a load template ID, and in the **Quantity** field, reduce the quantity of items to split the purchase order line.

3.  Click **OK** to create a load with the reduced quantity. In the **Load planning workbench** form, on the **Purchase order lines** tab, you can view a new purchase order line with the remaining quantity.

## Optional: Add a purchase order or purchase order line to an existing inbound load

To add a new purchase order or purchase order line to an existing inbound load, follow these steps:

1.  In the **Load planning workbench** form, on the **Purchase order lines** tab, select a purchase order line

2.  On the **Action Pane**, click **To existing load** to add the load line to an existing load, or click **Entire order to existing load** to add details from the purchase order to the selected load.

3.  Click **OK** to confirm the load. In the **Load planning workbench** form, on the **Load lines** tab, you can view two lines for the load ID, where the first line is the new purchase order line.

## Next step

[Assign a rate and route to a load](assign-a-rate-and-route-to-a-load.md)

## Related tasks

[Consolidate multiple shipments into a load](consolidate-multiple-shipments-into-a-load.md)

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and then select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


