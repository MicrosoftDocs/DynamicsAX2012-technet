---
title: Set up a unit sequence group and unit of measure conversions in Warehouse management
TOCTitle: Set up a unit sequence group and unit of measure conversions in Warehouse management
ms:assetid: ae12b249-8eb6-48bd-acd6-193d8cd43f5d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553191(v=AX.60)
ms:contentKeyID: 62200137
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.WHSUOMSeqGroupTable
- unit of measure sequence
- unit of measure sequences
- unit sequence group
- unit sequence groups
audience: Application User
ms.search.region: Global
---

# Set up a unit sequence group and unit of measure conversions in Warehouse management 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



The unit sequence group defines the sequence of units that can be used in warehouse operations. The sequence determines the order of units in which warehouse work is generated and it is applied when work is created for quantities on a purchase order line or transfer order line. The unit sequence group should include units of measure that range from the smallest to the largest unit and can be used for the product in warehouse operations.

This topic contains guidelines for the following tasks:

  - Setup of a unit sequence group.

  - License plate grouping and prerequisites for using license plate grouping when registering orders with a mobile device.

  - Use of units for cycle counting.

  - Setup of the default units for registering receipt for purchase, transfer, or production order lines with a mobile device.

  - Definition of a unit sequence group for released products and setup of a unit conversion for the product.


> [!NOTE]
> <P>If you have installed Microsoft Dynamics AX 2012 R3 Cumulative Update 8, you can also define unit of measure conversions for product variants. For more information, see the “Unit of measure conversions for product variants” section later in this topic.</P>



## Set up a unit sequence group

The smallest unit in a sequence group that you associate with an item must match the inventory unit that is defined for the corresponding product.

To view the inventory unit of a product, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select a released product. On the **Action Pane**, in the **Maintain** group, click **Edit**.

3.  On the **Manage inventory** FastTab, view the unit in the **Unit** field.

To set up a unit sequence group, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Unit sequence groups**.

2.  Click **New**.

3.  Enter an ID and a name for the unit sequence group.

4.  On the **Line details** FastTab, click **New** to create the sequence lines. In the **Line number** field, the lines will be assigned numbers that indicate the search hierarchy for units of measure. The list should start with the smallest unit.

5.  In the **Unit** field, select a unit.
    
    For more information about the remaining fields in the form, see the following sections in this topic.

## License plate grouping

You can specify if receipts of less than or more than one pallet should be grouped into one license plate or divided into a license plate for each unit.

**Define license plate grouping**

Use the following guidelines to define license plate grouping.

1.  In the **License plate packing type** field, enter a unique identifier (ID) for a license plate packing type that is added to the license plate number.

2.  Use the **License plate grouping** check box to define if quantities of items that are larger than a pallet should be grouped into a single license plate for the receipt or if a separate license plate should be requested for each quantity of the unit that you receive.
    
    To determine how quantities are distributed, see the license plate grouping example.
    
    License plates are grouped according to the highest and the lowest unit of the unit sequence group.
    
      - Select the check box to have units grouped into one license plate.
    
      - Clear the check box to use individual license plates for each unit quantity.

3.  If you want to use the license plate grouping to process work with a mobile device, license plate grouping must be active on the menu item for receipt.
    
    1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Mobile device menu items**.
    
    2.  Select a menu item for receipt. For example, select a menu item where **Purchase order item receiving and put away** is selected in the **Work creation process** field. On the **General** FastTab, select **License plate grouping**.

**Example of license plate grouping**

This example shows how quantities are divided based on the license plate grouping that is set up on the unit sequence group.

The following table shows how the unit sequence group is set up.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Unit of measure</p></th>
<th><p><strong>License plate grouping</strong> check box</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Each (ea)</p></td>
<td><p>Selected</p></td>
</tr>
<tr class="even">
<td><p>Dozen (Dozen)</p></td>
<td><p>Selected</p></td>
</tr>
<tr class="odd">
<td><p>Pallet (PL)</p></td>
<td><p>Not selected</p></td>
</tr>
</tbody>
</table>


You register the receipt for the quantity of 224 eaches on a purchase order line using a mobile device. You must complete the registration as follows:

1.  Press **OK** to register the 224 eaches, and then register a license plate for one pallet.

2.  Confirm the registration of the license plate, and then register a license plate for one more pallet.

3.  Confirm the registration of the second license plate, and then register a license plate for two dozen.

The quantity is distributed as follows:

  - Two license plates with one pallet on each license plate

  - One license plate with two dozen

The following table shows how the unit sequence group is set up if the quantity that you receive is 223.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Unit of measure</p></th>
<th><p><strong>License plate grouping</strong> check box</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Each (ea)</p></td>
<td><p>Selected</p></td>
</tr>
<tr class="even">
<td><p>Dozen (Dozen)</p></td>
<td><p>Not selected</p></td>
</tr>
<tr class="odd">
<td><p>Pallet (PL)</p></td>
<td><p>Not selected</p></td>
</tr>
</tbody>
</table>


You must complete the registration as follows:

1.  Press **OK** to register the 223 eaches, and then register a license plate for one pallet.

2.  Confirm the registration of the license plate, and then register a license plate for one more pallet.

3.  Confirm the registration of the second license plate, and then register a license plate for one dozen.

4.  Confirm the registration of a license plate for one dozen, and then register a license plate for the remaining eleven eaches.

The quantity is distributed as follows:

  - Two license plates with one pallet on each license plate

  - One license plate with one dozen

  - One license plate with eleven eaches

This is the conversion of the units that are used in the example:

  - 12 eaches (ea) = 1 dozen (Dozen)

  - 100 eaches (ea) = 1 pallet (PL)

## Use units for cycle counting

To use units for cycle counting, follow these steps:

1.  In the **Unit sequence groups** form, create a unit sequence group ID. For more information, see the “Set up a unit sequence group” section earlier in this topic.

2.  Select the **Use unit for cycle counting** check box to use the unit for cycle counting. Repeat this step for the units in the unit sequence group that you want to use.
    
    The selected units will be available for a warehouse worker using a mobile device to count available inventory. You can select a maximum of four units in the sequence group. If you select more than four units, they will not be shown on the mobile device.

## Set the default units for a mobile device

To set the default units for a mobile device, follow these steps:

1.  In the **Unit sequence groups** form, create a unit sequence group ID. For more information, see the “Set up a unit sequence group” section earlier in this topic.

2.  To set a unit as the default unit for items on a purchase order line, transfer order line, or production order line, select the following check boxes:
    
      - **Default unit for purchase and transfer** - The default unit is displayed when you use a mobile device to register purchase order and transfer order lines.
    
      - **Default unit for production** - The default unit is displayed when you use a mobile device to register production order lines.

## Define unit sequence groups for released products

If you want to use the released product in warehouse work processes, the unit sequence group is required information for a released product. You can apply an item without a unit sequence group ID on a purchase order or transfer order line. However, when you enable an item to generate warehouse work, you must specify a unit sequence group ID. If you validate a product with warehouse management enabled, you will get an error if the unit sequence ID is not defined for the product.

To enable an item to generate warehouse work, you must select the **Use warehouse management processes** check box on the item’s storage dimension group. For more information, see the “Create and assign a storage dimension group” section in [Set up reservation hierarchies](set-up-reservation-hierarchies.md).

To define unit sequence groups for products, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Double-click a product. On the **Action Pane**, in the **Maintain** group, click **Edit**.

3.  On the **Warehouse management** FastTab, in the **Unit sequence group ID** field, select a unit sequence ID.

To use a unit sequence group for released products, a unit conversion must be set up between the units that are used in the unit sequence group:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select a released product. On the **Action Pane**, in the **Set up** group, select **Unit conversions**. For more information about unit conversion setup for products, see [Unit conversions (form)](https://technet.microsoft.com/en-us/library/hh209285\(v=ax.60\)).
    

    > [!NOTE]
    > <P>If you have AX 2012 R3 CU8 installed, you can also set up unit of measure conversions for product variants. For more information, see the “Unit of measure conversions for product variants” section in this topic.</P>



## Unit of measure conversions for product variants

You can set up conversion rules that control how units of measure are converted to different units of measure for product masters and released products. For example, this is useful when you receive products in one unit of measure, such as eaches, and want to handle them in another unit of measure, such as pallets. If you’ve installed AX 2012 R3 CU8, you can also define conversion rules for product variants. The process of setting up unit of measure conversions for product variants, and then subsequent behavior, is the same as for product masters and released products. For more information, see the earlier sections in this topic, and [Set up units and unit conversions (Retail essentials)](set-up-units-and-unit-conversions-retail-essentials.md).

In **Warehouse management**, unit of measure conversions are used to define the number of products that can fit on a pallet or in a container. This is useful when handling product variants because different sizes or configurations of a product can create different packing quantities. For example, a pallet of large bath towels will have a different quantity than a pallet of small hand towels.

To use unit of measure conversions for a product, you must select the **Enable unit of measure conversions** check box on the product master. When you select this check box, two things occur:

  - Only product variants are displayed in the **Unit conversions** form for the product.

  - Microsoft Dynamics AX performs a series of validations. There are some restrictions to using unit of measure conversions with product variants. The following table describes the restrictions for using unit of measure conversions for product variants.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Restriction</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The product master and all related product variants must be enabled for use in warehouse management processes.</p></td>
<td><p>Unit of measure conversions for product variants apply only to processes in <strong>Warehouse management</strong>. Therefore, all of the released products and product variants must be enabled for use in <strong>Warehouse management</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Open transactions must not exist for the product.</p></td>
<td><p>This ensures that any previous transactions are not affected by the new unit of measure conversion rules.</p></td>
</tr>
<tr class="odd">
<td><p>Unit of measure conversions are not defined for the product master.</p></td>
<td><p>To ensure consistent conversions, you cannot define unit of measure conversions for the product master and related product variants. The two are mutually exclusive.</p></td>
</tr>
<tr class="even">
<td><p>All units for the product must be the same.</p></td>
<td><p>The sales unit, purchase unit, inventory unit, and product unit must be the same for the product. This ensures that the conversions on all source documents are not affected by the variant unit of measure conversion.</p>
<div class="alert">

> [!TIP]
> <P>Because the units must always be the same, the system will display an error if you try to change one of the units when the <STRONG>Enable unit of measure conversions</STRONG> check box is selected. To change a unit, you must clear the check box, change all of the units to the new unit, and then select the check box again. When you re-enable a product variant for unit of measure conversions, the same restrictions apply. For example, transactions must not exist, and conversion rules must not be defined for the product master.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Not all workflows support unit of measure conversions for product variants.</p></td>
<td><p>The following warehouse management processes support unit of measure conversions for product variants:</p>
<ul>
<li><p>Purchase order item receiving</p></li>
<li><p>Load item receiving</p></li>
<li><p>Transfer order line number receiving</p></li>
<li><p>Transfer order item receiving</p></li>
<li><p>Purchase order line number receiving</p></li>
<li><p>Sales order picking</p></li>
<li><p>Transfer order picking</p></li>
<li><p>Cycle counting</p></li>
<li><p>Movement by template</p></li>
<li><p>Manual movements</p></li>
</ul></td>
</tr>
</tbody>
</table>


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


## See also

[Unit conversions (form)](https://technet.microsoft.com/en-us/library/hh209285\(v=ax.60\))

[Unit conversions](unit-conversions.md)

  


