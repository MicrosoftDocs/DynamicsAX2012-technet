---
title: Set up parameters to create a warehouse location
TOCTitle: Set up parameters to create a warehouse location
ms:assetid: 2f7d39ba-6e15-4d3f-a181-23d0e8f559ad
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553157(v=AX.60)
ms:contentKeyID: 62200050
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- warehouse location
- Forms.WHSDockMgmtProfile
- Forms.WHSLocation
- Forms.WHSLocationFormat
- Forms.WHSLocationProfile
- MsDynAx060.Forms.WHSDockMgmtProfile
- MsDynAx060.Forms.WHSLocation
- MsDynAx060.Forms.WHSLocationFormat
- MsDynAx060.Forms.WHSLocationProfile
- dock management profile
- location formats
- location type
audience: Application User
ms.search.region: Global
---

# Set up parameters to create a warehouse location 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic explains how to set up the parameters that are used to create a warehouse location, such as location types, location formats, dock management profiles, location profiles, and warehouse zones.

Warehouse locations correspond to the specific places where inventory can be stored in a particular warehouse. You must create warehouse locations so that you can perform and track inbound and outbound warehouse transactions using Microsoft Dynamics AX.

Before you create a warehouse location, you must define the following:

  - **Location type** ─ The type of warehouse location. For example, you can create a location type for all staging locations.

  - **Location format** ─ The naming convention for a location. You can specify how many segments the name should include, and the length of each segment. You can also specify the separator that is used to separate segments.

  - **Dock management profile** ─ The settings which help you control inventory items for multiple orders, shipments, loads, or waves at the docks when inbound items are received or outbound items are loaded.

  - **Location profile** ─ The settings which specify whether a particular warehouse location is license plate controlled, whether it can be cycle counted, and whether it allows for mixing of inventory batches.

  - **Warehouse zone** ─ A defined area in a warehouse to which you allocate specific inventory items.

In addition to creating a location using the **Locations** form, you can create multiple warehouse locations using the **Location setup wizard**. Locations can be assigned as fixed or permanent locations for specific inventory items.

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
<td><p>Setting</p></td>
<td><p>Set up one or more warehouses in Microsoft Dynamics AX. For more information, see <a href="create-warehouses.md">Create warehouses</a>.</p></td>
</tr>
</tbody>
</table>


## Create a location type

You must set up two mandatory location types for staging and shipping. After you create these location types, you must select them as the default staging and final shipping location types in the **Warehouse management parameters** form.

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Location types**.

2.  Create a new location type.

3.  Enter a unique identifier and description for the location type.

## Create a location format

Use the **Location formats** form to create a format for the ID that is used to identify a specific warehouse location. A location format can contain multiple segments. For example, you can create a format with two segments and use a period as the separator, such as 0000.0000. The first segment indicates the bulk location and the second segment indicates the aisle.

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Location formats**.

2.  Create a new location format.

3.  Enter a unique ID and name for the location format.

4.  On the **Details** FastTab, click **New** to create a new line.

5.  In the **Segment description** field, enter a description for a segment in the location format.

6.  Enter the length of the segment and the separator that is used between segments.

For each segment that you want to add, click **New** to add a new line, and then add a description for the segment, a separator, and the length of the segment. You can preview the completed location format in the **Example** field.

## Create a dock management profile

You set up a dock management profile and assign it to a location profile to manage the mixing of inventory at specific warehouse locations.

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Dock management profiles**.

2.  Create a new dock management profile.

3.  Enter a unique ID and description for the dock management profile.

4.  In the **Inventory types that should not be mixed** field, select the type of source document that determines the types of inventory that should not be mixed. For example, if you select **Order number** in this field, only the inventory from a specified order is stored at the location.

5.  Optional: Select the **Assume empty location for new wave** check box to indicate that there is no inventory stored at a location.

## Create a location profile

You must specify attributes for a warehouse location to determine how a warehouse location is used in an inbound or outbound transaction. For example, you can specify if a location allows negative inventory or cycle counting. You can use location profiles to define the dimensions of a location.

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Location profiles**.

2.  Create a new location profile.

3.  Enter a unique ID and name for the location profile.

4.  On the **General** FastTab, in the **Location format** and **Location type** fields, select a location format and location type.

5.  In the **Dock management profile ID** field, select a dock management profile. The dock management profile contains information about the inventory types that cannot be mixed at a particular warehouse location.

6.  Configure additional settings for the location profile.
    
    The following table lists the fields that you use to configure the additional settings.
    
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
    <td><p><strong>Use license plate tracking</strong></p></td>
    <td><p>Select this check box to use license plate tracking at a location.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Allow negative inventory</strong></p></td>
    <td><p>Select this check box to allow negative inventory of items at the specified location.</p>
    <div class="alert">

    > [!NOTE]
    > <P>Locations that use license plate tracking cannot have negative inventory for items.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Allow mixed items</strong></p></td>
    <td><p>Select this check box to allow the storage of mixed items at the specified location.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you select this check box, you must select the <STRONG>Allow mixed inventory batches</STRONG> check box.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Allow mixed inventory statuses</strong></p></td>
    <td><p>Select this check box to allow the storage of items with different inventory statuses at the specified location.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Allow mixed inventory batches</strong></p></td>
    <td><p>Select this check box to allow the storage of batches of mixed inventory items at the specified location.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Allow cycle counting</strong></p></td>
    <td><p>Select this check box to allow cycle counting at the specified location.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Generate check digit</strong></p></td>
    <td><p>Select this check box to generate a check digit for the specified location. You can use a check digit to authenticate a location for warehouse mobile device transactions.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Override rules for batch days</strong></p></td>
    <td><p>Select this check box to override rules for batch days when the specified inventory is located.</p></td>
    </tr>
    </tbody>
    </table>


7.  On the **Dimensions** FastTab, set up dimensions for the location profile.
    
    The following table lists the fields that you use to configure dimensions.
    
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
    <td><p><strong>Storage unit</strong></p></td>
    <td><p>Select the storage unit that is used to calculate the volume of inventory at the specified location.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Volume utilization percentage</strong></p></td>
    <td><p>Enter the fill percentage of the total volume of inventory at the specified location.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Volumetric method used for inventory location</strong></p></td>
    <td><p>The volumetric method that is used to locate specified inventory based on dimension checks.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Usable dimensions</strong> ─ All volumetric calculations will use the available (usable) dimensions specified in the location profile.</p></li>
    <li><p><strong>Use location volume</strong> ─ All volumetric calculations will use the fill percentage of the actual dimensions that is specified in the <strong>Container utilization percentage</strong> field.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


8.  On the **Dimensions** FastTab, enter the actual and usable dimensions for the location.

## Create a warehouse zone and zone group

Use the **Zones** and **Zone groups** forms to create a warehouse zone and zone group. A zone group is a logical grouping of different warehouse zones. Zones and zone groups are created for reporting.

You must specify a zone when you create a new warehouse location. You can also use zones to create multiple warehouse locations using the **Location setup wizard** form.

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Zone groups**.

2.  Create a new zone group.

3.  Enter a unique ID and name for the zone group.

4.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Zones**.

5.  Enter a unique ID and name for the zone.

6.  In the **Zone group ID** field, select the zone group to which you want to assign the zone.

## Create a location

Use the **Locations** form to create a warehouse location. You must create a user location and select it as the default user location in the **Warehouse management parameters** form. You can filter by warehouses to see the existing warehouse locations.

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Locations**.

2.  Create a new location.

3.  Select the warehouse for which you want to create the location for and enter a unique ID for the location.

4.  In the **Check text** field, enter the text that you want to use to authenticate the location.
    

    > [!NOTE]
    > <P>You can also select the <STRONG>Generate check digits for location</STRONG> check box to generate the check digits for the location.</P>



5.  Select a location profile and a warehouse zone for the location.

6.  In the **Sort code** field, enter the sorting code that is used to sort locations and picking lines.

## Optional: Create locations using the Location setup wizard

Use the **Location setup wizard** form to create multiple warehouse locations. You must specify a location profile, warehouse, and zone to create these locations.

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Location setup wizard**.

2.  Select a warehouse, location profile, and warehouse zone.

3.  Click **Build** to create a warehouse location. Repeat this step with a different location profile to create multiple locations for the same warehouse.

## Optional: Assign a fixed location to a product or product variant

Use the **Fixed locations** form to assign a permanent or fixed location to a product. This is useful when you always stock a particular product in the same location. For example, a grocery store might always stock milk in the same location in its refrigerated section. You can assign multiple fixed locations to the same product and multiple products can have the same fixed location assigned to them. Fixed locations can be used by location directives and inventory replenishment to determine the locations to create work for. Fixed locations are also used when you create and release waves for pick and put operations. For more information, see [Create a location directive](create-a-location-directive.md) and [Set up replenishment](set-up-replenishment.md).


> [!NOTE]
> <P>If you have installed AX 2012 R3 CU8, you can also assign fixed locations to product variants. The <STRONG>Fixed locations</STRONG> form contains a <STRONG>Products</STRONG> tab and a <STRONG>Product variants</STRONG> tab, where you can specify fixed locations for products or product variants. When you specify fixed locations for product variants, you must enter the relevant dimensions for the variant. To ensure that fixed locations are used when work is created, on the location directive you must set up the location directive actions to use them. To make this connection, in the <STRONG>Location directives</STRONG> form, in the <STRONG>Fixed location usage</STRONG> field, you can select <STRONG>Only fixed locations for the product variant</STRONG>.</P>



To specify fixed locations for products or product variants, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Fixed locations**.

2.  Create a new record.

3.  In the **Item number** field, select the item to which you want to assign a fixed location.

4.  Select a warehouse and a site.

5.  In the **Location** field, select a warehouse location, which is used as the fixed location for the selected item.

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

  


