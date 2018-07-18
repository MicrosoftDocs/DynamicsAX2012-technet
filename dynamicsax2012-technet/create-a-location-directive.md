---
title: Create a location directive
TOCTitle: Create a location directive
ms:assetid: fd0e708b-747e-4944-a5a8-f4174cabad6a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553215(v=AX.60)
ms:contentKeyID: 62221427
ms.date: 04/07/2017
mtps_version: v=AX.60
f1_keywords:
- count
- put
- adjust
- inventory transactions
- pick
- Forms.WHSLocDirTable
- inbound transactions
- location directive
- outbound transactions
audience: Application User
ms.search.region: Global
---

# Create a location directive 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic explains how to create location directives. Location directives are user-defined rules that help identify pick and put locations for inventory movement. For example, in a sales order transaction, a location directive determines where the items will be picked and where the picked items will be put.

You can use location directives to do the following:

  - Put away incoming items.

  - Pick and stage items for outbound transactions.

  - Pick and put raw materials for production.

  - Replenish locations.

## Prerequisites

The following table shows the prerequisites that must be in place before you create a location directive.

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
<td><p>Related setup tasks</p></td>
<td><ul>
<li><p>Click <strong>Warehouse management</strong> &gt; <strong>Setup</strong> &gt; <strong>Warehouse setup</strong> &gt; <strong>Warehouses</strong>. Create a warehouse. On the <strong>Warehouse management</strong> FastTab, select the <strong>Use warehouse management processes</strong> check box.</p></li>
<li><p>Create locations, location types, location profiles, and location formats. For more information, see <a href="set-up-parameters-to-create-a-warehouse-location.md">Set up parameters to create a warehouse location</a>.</p></li>
<li><p>Create sites, zones, and zone groups. For more information, see <a href="create-sites.md">Create sites</a> and <a href="set-up-parameters-to-create-a-warehouse-location.md">Set up parameters to create a warehouse location</a>.</p></li>
</ul>
<p></p></td>
</tr>
</tbody>
</table>


## Create a location directive

To create a location directive, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Location directives**.

2.  In the **Work order type** field, select the type of inventory transaction for which you want to create a location directive.

3.  On the **Location directives** FastTab, click **New** to create a new location directive and specify the details as described in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Sequence number</strong></p></td>
    <td><p>Enter the sequence in which the location directive is processed for the selected work type. You can also modify the sequence, if needed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>Enter a name for the location directive. This field is required.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Work type</strong></p></td>
    <td><p>Select the type of work to be performed. The type of work available is based on the type of inventory transaction that you have selected in the <strong>Work order type</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Site</strong></p></td>
    <td><p>Select the site in which the work should be completed. This field is required.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Warehouse</strong></p></td>
    <td><p>Select the warehouse location in which the work should be completed. This field is required.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Directive code</strong></p></td>
    <td><p>Select the directive code to associate to a work template or replenishment template. To configure a directive code with a work template, see <a href="create-a-work-template.md">Create a work template</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Disposition code</strong></p></td>
    <td><p>Optional: Select a disposition code to redirect the put away of the received items to a location. For more information, see <a href="create-disposition-codes.md">Create disposition codes</a>. This field is available only if you select <strong>Purchase orders</strong> or <strong>Return orders</strong> in the <strong>Work order type</strong> field.</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>If you have Hotfix number 3067743 or AX 2012 Cumulative Update 10 installed, the option is also available for Work orders of type <STRONG>Finished goods put away</STRONG>.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Multiple SKU</strong></p></td>
    <td><p>Optional: Select this check box to use multiple stock keeping units (SKUs).</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>If you use this setting for a location directive of the work type Put, the first location directive line will always be selected by the system irrespective of other restrictions created in the lines.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


4.  Optional: Click **Edit query** to select the locations or to specify any restrictions that apply when you select a specific location directive.

5.  On the **Lines** FastTab, create one or more lines to specify units and to locate or reserve quantity in a warehouse. Fill in the fields as described in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Sequence number</strong></p></td>
    <td><p>Enter the sequence in which the location directive is processed for the selected work type. You can also modify the sequence, if needed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>From quantity</strong></p></td>
    <td><p>Enter the starting quantity of the items for which work should be performed.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>To quantity</strong></p></td>
    <td><p>Enter the ending quantity of the items for which work should be performed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Unit</strong></p></td>
    <td><p>Select the unit of measure for the items.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Locate quantity</strong></p></td>
    <td><p>Select the method that is used to check whether the quantity is in the range that is set in the <strong>From quantity</strong> and <strong>To quantity</strong> fields.</p>
    <p>If the location directive is for an inbound transaction, select one of the following options:</p>
    <ul>
    <li><p><strong>License plate quantity</strong> ─ The license plate quantity.</p></li>
    <li><p><strong>Unitized quantity</strong> ─ The unitized quantity from the specified inventory transaction.</p>
    <p>For example, in a warehouse if you can receive a quantity of 1000 and break it into 10 license plates of 100 each, you can use a quantity of 1000 items instead of the license plate quantity of 100.</p></li>
    <li><p><strong>Remaining quantity</strong> ─ The quantity yet to be received that is specified on the purchase order line.</p></li>
    <li><p><strong>Expected quantity</strong> ─ The total quantity that is specified on the purchase order line.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


6.  Optional: You can select the following additional settings on the **Lines** FastTab.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Restrict by unit</strong></p></td>
    <td><p>Select this check box to restrict the units of measure that are to be considered as valid selection criteria for the location directive lines. When units of measure have been specified, only those items with a unit that matches at least one unit defined for the unit sequence group will be considered as valid for the line selection.</p>
    <p>For example, say that the unit is restricted to pallets and the item is associated with a unit of measures sequence group that includes pallets. In this case the items will be considered a valid choice for the location directive.</p>
    <p>However, the <strong>Restrict by unit</strong> check box does not control the unit or units that are applied on work lines. The unit restriction only restricts the units that are made available via the unit sequence group.</p>
    <p>For example, say that an item is associated with a sequence group that includes both the Pallets and the Pcs units. A unit of measure has been defined with 1 pallet = 100 pcs and the location directive uses Restrict by unit for pallets only. Furthermore a work template has been defined that breaks the work header creation by 50 pcs. In this case work lines of 50 pcs will be created.</p>
    <p>To specify the unit of measure for restriction:</p>
    <ol>
    <li><p>Click <strong>Restrict by unit</strong>. This button is available only when you press <strong>Ctrl+S</strong> after you have selected the <strong>Restrict by unit</strong> check box.</p></li>
    <li><p>In the <strong>Unit</strong> field, select the unit of measure to restrict for the pick and put away process.</p></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>Locate packing quantity</strong></p></td>
    <td><p>Select this check box if a packing unit quantity is specified in the <strong>Sales order</strong> form. If you select this check box, only the locations with this packing unit quantity are selected.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Allow split</strong></p></td>
    <td><p>Select this check box to split the quantity across multiple locations.</p></td>
    </tr>
    </tbody>
    </table>


7.  On the **Location Directive Actions** FastTab, click **New** to select the location or range of locations.

8.  In the **Sequence number** field, the sequence in which the location directive is processed for the selected work type is displayed. You can modify the sequence, if needed.

9.  In the **Name** field, enter the name for the location directive action.

10. Optional: Click **Edit query** to modify the warehouse locations and other criteria.

11. Optional: You can select the following additional settings for a location directive.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Only use item fixed locations</strong></p></td>
    <td><p>Select this check box to include a fixed location for the item that is being put away. For more information about how to assign fixed locations to set up location directives, see the “Optional: Assign a fixed location to an inventory item” section in the <a href="set-up-parameters-to-create-a-warehouse-location.md">Set up parameters to create a warehouse location</a> topic.</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>If you have AX 2012 R3 CU8 installed, this field has been renamed to <STRONG>Only fixed locations for the product</STRONG>, and added as an option in a new field named <STRONG>Fixed location usage</STRONG>. In the field, two additional options are available:</P>
    > <UL>
    > <LI>
    > <P><STRONG>Fixed and non-fixed locations</STRONG> – The location directive will consider all locations.</P>
    > <LI>
    > <P><STRONG>Only fixed locations for the product variant</STRONG> – The location directive will consider only fixed locations for product variants.</P></LI></UL>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Allow negative inventory</strong></p></td>
    <td><p>Select this check box to allow negative inventory at the specified warehouse location.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Batch enabled</strong></p></td>
    <td><p>Select this check box to use batch strategies for the items that are batch enabled.</p></td>
    </tr>
    </tbody>
    </table>


12. In the **Strategy** field, select one of the strategies for the specified location directive.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Consolidate</strong></p></td>
    <td><p>This strategy is used in Microsoft Dynamics AX to consolidate items in a particular location when similar items are already available.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Match packing quantity</strong></p></td>
    <td><p>This strategy is used to verify whether a pick location has the specified packing quantity.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>FEFO batch reservation</strong></p></td>
    <td><p>This strategy is used when inventory is located using a batch expiration date and is allocated for batch reservation. You can only use this strategy for batch enabled items.</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>In Microsoft Dynamics AX 2012 R3 Cumulative Update 9 the FEFO batch reservation strategy is also used when inventory is located using a batch best before date in addition to the expiration date.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Round up to full LP</strong></p></td>
    <td><p>This strategy is used to round up the inventory quantity to match the license plate (LP) quantity that is assigned to the items to be picked. You can only use this strategy for replenishment.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Empty location with no incoming work</strong></p></td>
    <td><p>This strategy is used to locate empty locations. The location is considered empty if it has no physical inventory and no expected incoming work.</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>This option was added in Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


## Next step

After you create location directives, you can associate each directive code with a work template code for work creation.

[Create a work template](create-a-work-template.md)

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

  


