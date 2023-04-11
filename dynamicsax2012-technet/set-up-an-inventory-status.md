---
title: Set up an inventory status
TOCTitle: Set up an inventory status
ms:assetid: f01e485d-1fa0-422d-b3b7-b5bed97db353
ms:mtpsurl: https://technet.microsoft.com/library/Dn553211(v=AX.60)
ms:contentKeyID: 62200183
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- site
- inventory dimension
- Forms.WHSParameters
- Forms.WHSAccountItemStatusDefault
- Forms.WHSInventStatus
- MsDynAx060.Forms.WHSParameters
- inventory status
- default item status
- MsDynAx060.Forms.WHSAccountItemStatusDefault
- warehouse management parameter
- MsDynAx060.Forms.WHSInventStatus
- warehouses
audience: Application User
ms.search.region: Global
---

# Set up an inventory status 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



An inventory status is one of the dimensions in the storage dimension group. You can use inventory statuses to complete the following tasks:

  - Create an inventory status for on-hand inventory, inbound transactions, and outbound transactions.

  - Create an inventory status and specify it as the default inventory status for warehouse transactions.

  - Change an inventory status for items before arrival, during arrival, or when the items are put away during inventory movement.

  - Use an inventory status for the pricing of items when they are returned and to plan item coverage during master planning.

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
<td><p>Enable warehouse processing for a storage dimension group</p></td>
<td><ol>
<li><p>Click <strong>Product information management</strong> &gt; <strong>Setup</strong> &gt; <strong>Dimension groups</strong> &gt; <strong>Storage dimension groups</strong>.</p></li>
<li><p>Select a storage dimension group, and select the <strong>Use warehouse management processes</strong> check box.</p>
<p>If the <strong>Use warehouse management processes</strong> check box is selected for an item in the <strong>Storage dimension groups</strong> form, the inventory status dimension automatically becomes active along with the site, warehouse, location, and license plate storage dimensions. For more information about mandatory inventory dimensions and dimension groups, see <a href="about-mandatory-inventory-dimensions.md">About mandatory inventory dimensions</a> and <a href="about-inventory-dimensions-and-dimension-groups.md">About inventory dimensions and dimension groups</a>.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Create an inventory status

Inventory status can be categorized as available or unavailable. You can use the inventory blocking parameter to block items with an unavailable inventory status. Items with a blocked status are considered physical inventory and cannot be used in a production order, sales order, transfer order, or outbound transaction.

You can use warehouse items with available or unavailable inventory statuses for inbound work. For example, create an available status named “Ready,” an unavailable status named “Damaged,” and a blocked status named “Blocked.” When you create a purchase order for received or returned items, if any items are damaged or broken, you can change the inventory status of those items to “Damaged” on the purchase order line. After receiving these items, the status is automatically set to “Blocked.” If you scan these damaged items using a mobile device, Microsoft Dynamics AX uses location directives and work templates to display information about an appropriate location or range of locations to put away these items. For returned items, an issue type of reservation is created in the **Inventory transactions** form.

For outbound work, use items with an available inventory status. If you have items with a status of broken, and master planning is run on these items, the items are considered missing and inventory is automatically replenished.

To create an inventory status, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Inventory** \> **Inventory status**.

2.  Click **New** to create an inventory status.

3.  Optional: Select the **Inventory blocking** check box to indicate that items with this inventory status are unavailable for issue or consumption.

4.  Enter an identifier (ID) and name for the inventory status.

## Optional: Set up a default inventory status

After you have set up an inventory status you can set the default inventory status for a site, item, and warehouse. You can change the default status on the mobile device or on the purchase order, sales order, or transfer order line.


> [!NOTE]
> <P>If the <STRONG>Inventory blocking</STRONG> check box is selected in the <STRONG>Inventory status</STRONG> form, you cannot select the default inventory status on the purchase or sales order line.</P>



To set up a default inventory status for a customer or vendor item, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Inventory** \> **Default item status**.

2.  Click **New** to create a default item status and select an item.

3.  Optional: In the **Module** field, modify the module.

4.  In the **Account number** field, select a customer account or vendor account if you have selected the module as **Customer** or **Vendor**.

5.  In the **Default inventory status ID** field, select the default inventory status for the selected item.

To set up a default inventory status for a site, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Sites**.

2.  Click **New** to create a new site. For information, see [Create sites](create-sites.md).

3.  On the **Warehouse management** FastTab, in the **Default inventory status ID** field, select the status to be displayed by default on the purchase order lines, sales order lines, and transfer order lines.

To set up a default inventory status for items in all warehouses, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse management parameters**.

2.  In the left pane, click **General**.

3.  In the **General** area, on the **Inventory status** FastTab, select the default inventory status to be displayed for items in the purchase order line.

4.  Select the **Use default status for sales orders and transfer orders** check box to automatically display the default status on sales order lines and transfer order lines.

To set up a default inventory status for a warehouse, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Warehouses**.

2.  Click **New** to create a new warehouse. For more information, see [Create warehouses](create-warehouses.md).

3.  On the **Warehouse management** FastTab, in the **Default inventory status ID** field, select the default status to be displayed for items from a particular warehouse.

4.  Optional: In the **Remove reservations and markings** field, select the inventory status that is automatically used when you receive items, or when there is a marking set between the purchase order and sales order during mobile device scanning. Select one of the following options:
    
      - **None** ─ The inventory status for the received items cannot be changed.
    
      - **Reservations** ─ The inventory status can be changed for reserved items without markings.
    
      - **Markings and reservations** ─ The inventory status of the received items can be changed. Additionally, the markings set between sales orders and purchase orders are removed and the on-hand inventory reservations are removed.

## Optional: Plan coverage for items with an available inventory status

To plan coverage for items with an available inventory status, select the **Coverage plan by dimension** check box for a storage dimension in the **Storage dimension groups** form. When you open the **Item Coverage Wizard**, items with an available status are displayed in the **Status** page. To create coverage settings for these items, select the inventory status ID for the available inventory statuses. Based on the coverage settings, you can calculate the item requirements and forecast the supply and demand of available items during master planning. You cannot create an item coverage setup with a blocked inventory status. Alternatively, use the **Item coverage** form to create or modify the item coverage parameters. For more information, see [About coverage settings](about-coverage-settings.md), [Use a wizard to create item coverage settings](use-a-wizard-to-create-item-coverage-settings.md), and [Item coverage (form)](https://technet.microsoft.com/library/aa619147\(v=ax.60\)).

## Next step

[Create disposition codes](create-disposition-codes.md)

## Related tasks

[Set up reservation hierarchies](set-up-reservation-hierarchies.md)

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

  


