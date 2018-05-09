---
title: Set up reservation hierarchies
TOCTitle: Set up reservation hierarchies
ms:assetid: b731eb87-e7d5-4c7d-a83d-dd7522d0a8af
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553195(v=AX.60)
ms:contentKeyID: 62200144
ms.date: 02/27/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.WHSInventTableReservationHierarchy
- Forms.WHSReservationHierarchy
- reservation hierarchies
- reservation hierarchy
---

# Set up reservation hierarchies 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



A reservation hierarchy is used to defer reservation details beyond the point in the ordering process where you enter the order. The hierarchy is based on the storage and tracking dimensions of items, such as inventory status and license plate.

This topic describes how to create or change a reservation hierarchy and how to assign hierarchies to items. It also provides guidelines for setting up dimension groups and the **Inventory status** and **License plate** dimensions.

## Automatic retrieval of information for the warehouse processes

Site, warehouse, and inventory status information is required for the ordering process, however details such as the location can be provided after you have made reservations for an order. For example, based on the reservation hierarchy, the optimal locations for picking can be retrieved by the warehouse management system.

**Example**

You reserve an item from a specific site and warehouse, with a specific inventory status. The released product on the order line is associated with a reservation hierarchy that includes **Site**, **Warehouse**, **Inventory status**, **Location**, and **License plate**. When the order entry is completed, you do not have to manage the warehouse-specific details of the ordering process. Based on the reservation hierarchy and the status of the site, warehouse, and inventory on the sales order, the warehouse management system identifies what location and license plate to pick from.

## The order of elements in the reservation hierarchy

The elements in a reservation hierarchy determine which dimensions must be recognized when the actual reservation occurs. Each dimension is required for the reservation and the order of the elements in the hierarchy is important when you make the reservation. However, you do not always have to provide all dimensions in the hierarchy because the reservation system can identify and provide dimensions that are missing in the required order of the hierarchy.

**Example**

You want to reserve an item with a specific inventory status. In this case, you can specify **Site**, **Warehouse**, and **Inventory status**. A reservation cannot be based on, for example, only site and inventory status. Because items with the same inventory status might be located in different warehouses on a site, the warehouse ranks higher in the hierarchy than inventory status. However, the site and the inventory status that you specify will be sufficient information for the reservation system to determine a warehouse which has the items on-hand.

## Dimensions required for order entry

The location of an item is identified by the warehouse management system. Typically the dimensions in the hierarchy listed below the location are determined in the warehouse process, for example during picking. You do not need to provide the location and the dimensions that is listed below the location when you enter an order. However, if you want to make a dimension that is below a location required for the ordering process, this dimension must be moved above the location in the hierarchy.

**Example**

You have a product that customers usually order from the same batch number and the **Batch number** should be determined when the order is entered. In this case, the **Batch number** dimension must be listed above the location in the reservation hierarchy.

## Set up an inventory reservation hierarchy

The reservation hierarchy uses the tracking and storage dimensions that are associated with released products. You associate the dimensions with products through the storage and tracking dimension groups.

When setting up a reservation hierarchy, you must observe a set of rules regarding the dimensions and the order of the dimensions that must be included in the hierarchy. For example, warehouse cannot rank above site. When you set up the hierarchy, you will receive error messages if you try to create a hierarchy that is not supported.

For more information about how to associate a product with a storage dimension group and a tracking dimension group, see [About inventory dimensions and dimension groups](about-inventory-dimensions-and-dimension-groups.md).

To set up an inventory reservation hierarchy, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Inventory** \> **Reservation hierarchy**.

2.  Click **New** to create a new reservation hierarchy.

3.  Enter a name for the reservation hierarchy.

4.  In the **Selected** group, select the dimensions that you want to remove from the reservation hierarchy.

5.  Click **\>** to move a selected dimension to the **Available** group.
    
    The dimensions **Site**, **Warehouse**, **Inventory status**, **Location**, and **License plate** are all required levels in a reservation hierarchy. Additional dimensions, such as **Batch number** and **Serial number**, only need to be included if they are used in the associated tracking dimension group.

6.  Select a dimension and then click **Move up** or **Move down** to move the dimension levels up or down in the hierarchy.

## Assign a reservation hierarchy to a released product

To assign a reservation hierarchy to a released product, a storage dimension group and a tracking dimension group must be assigned to the product. Also, the physical tracking and storage dimensions that are listed for the product in the **Storage dimension groups** and the **Tracking dimension groups** must correspond to the dimension fields in the reservation hierarchy. The dimension fields in the reservation hierarchy are listed in the **Inventory reservation hierarchy** form.

For more information about how to assign a storage and tracking dimension group to released products, see the guidelines in the “Create and assign a storage dimension group” and “Optional: Create and assign a tracking dimension group” sections.

To assign a reservation hierarchy to a product, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  On the **Action Pane**, click **Set up**, and then click **Reservation hierarchy**.

3.  In the **Assign a reservation hierarchy to the item** form, in the **Reservation hierarchy** field, select a reservation hierarchy.

## Change a reservation hierarchy for items with transactions

If an item has no transactions, you can change the reservation hierarchy for the item by using the guidelines in the previous section to assign a reservation hierarchy to a released product. For more information, see “Assign a reservation hierarchy to a released product”. However, if an item has transactions, you must follow this procedure to change the hierarchy.

Before you change a hierarchy, all transactions on the item must be completed, which means that all items must be purchased or sold.


> [!NOTE]
> <P>Do not change reservation hierarchies if one of the warehouses has negative inventory. This may lead to data corruption.</P>



For more information about how to assign a storage and tracking dimension group to released products, see the guidelines in the “Create and assign a storage dimension group” and “Optional: Create and assign a tracking dimension group” sections.

To change a reservation hierarchy for items with transactions, follow these steps:

1.  Click **Warehouse management** \> **Periodic** \> **Change item hierarchy**.

2.  Click **Select**, select the items for which the hierarchy should be changed, and then click **OK**.

3.  In the **Name** field, select the new reservation hierarchy, and then click **OK**.

## Create and assign a storage dimension group

If you want to use the warehouse management processes and apply a reservation hierarchy, you must set up at least one storage dimension group with at least one storage dimension. The storage dimension group must be assigned to a released product.

To create a storage dimension group, follow these steps:

1.  Click **Product information management** \> **Setup** \> **Dimension groups** \> **Storage dimension groups**.

2.  Click **New** to create a new storage dimension group.

3.  Enter a name and a description.

4.  Select the **Use warehouse management processes** check box to enable Warehouse management for products that are associated with this group. When you select this check box, a set of check boxes are selected in the fields for each dimension. For more information about the fields in the form, see [Storage dimension groups (form)](https://technet.microsoft.com/en-us/library/hh209317\(v=ax.60\)).

To assign a storage dimension group to a released product, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  On the **Action Pane**, in the **New** group, click **Product** to create a new product. For more information about how to create a new product, see [Key tasks: Define products](key-tasks-define-products.md).

3.  Select the product, and on the **Action Pane**, in the **Set up** group, click **Dimension groups**. In the **Storage dimension group** field, select a storage dimension group.

## Optional: Create and assign a tracking dimension group

Tracking dimensions are optional for reservation hierarchies.

To create a tracking dimension group, follow these steps:

1.  Click **Product information management** \> **Setup** \> **Dimension groups** \> **Tracking dimension groups**.

2.  Click **New** to create a new tracking dimension group.

3.  Enter a name and a description. For more information about the fields in the form, see [Tracking dimension groups (form)](https://technet.microsoft.com/en-us/library/hh209465\(v=ax.60\)).

To assign a tracking dimension group to a released product, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  On the **Action Pane**, in the **New** group, click **Product** to create a new product. For more information about how to create a new product, see [Key tasks: Define products](key-tasks-define-products.md).

3.  Select the product, and on the **Action Pane**, in the **Set up** group, click **Dimension groups**. In the **Tracking dimension group** field, select a tracking dimension group.

## Set up inventory status

The inventory status dimension can be used to divide items into categories, such as Available and Not available. You can create an unlimited number of statuses. You can set the default for the inventory status to apply for all items or to apply only for items in a particular warehouse. You can also set the inventory status to apply to a particular customer or vendor.

To create inventory statuses, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Inventory** \> **Inventory status**.

2.  Click **New** to create a new inventory status.

3.  If you want to create a status that sets the availability of items to Not available, select the **Inventory blocking** check box. If this check box is not selected, the item is not on hand.

4.  Enter names in the **Inventory status** and **Name** fields. Repeat this step to create additional statuses. For statuses that are used to make items available for the inbound and outbound processes, do not select the **Inventory blocking** check box.

To configure inventory status for all items, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse management parameters**.

2.  Click the **General** link, and expand the **Inventory status** FastTab.

3.  In the **Default inventory status ID** field, select a status to be suggested as a default for items on sales or transfer order lines.

4.  If you want the default status to be applied automatically on sales or transfer order lines, select **Use default status for sales orders and transfer orders**.

To configure inventory status for items in a particular warehouse, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Warehouses**.

2.  Select a warehouse and expand the **Warehouse management** FastTab.

3.  In the **Default inventory status ID** field, select a status to be suggested as a default for items for this particular warehouse.

For more information about inventory status, see [Set up an inventory status](set-up-an-inventory-status.md).

## Set up license plates

License plates are unique numbers that you can assign to a warehouse entity, such as a pallet, bin, cart, or an individual item, for tracking inventory.

To set up license plates, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **License plates**.

2.  Click **New** to create a license plate and enter a name in the **License plate** field.

3.  Repeat this step to create additional license plates.

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
<td><p><strong>Configuration key</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

