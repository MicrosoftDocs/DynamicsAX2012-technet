---
title: Define inbound warehouse processes based on container types
TOCTitle: Define inbound warehouse processes based on container types
ms:assetid: 298ae871-813c-4d19-a9f1-01a91b64b514
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Mt740364(v=AX.60)
ms:contentKeyID: 73212215
ms.date: 07/20/2016
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Define inbound warehouse processes based on container types 


## Create a container type

By associating a container type – with a license plate, you can control the storage policies, based on the container type.

1.  Click **Warehouse management** \> **Setup** \> Containers \> **Container types**.

2.  Click **New** to create a record.

3.  If you are using volumetric location load calculation, be sure to enter the physical dimensions that are related to the container type. When **Flexible volume dimensions** is selected, the volume depends on the container volume plus the inventory that is put into the container. When **Flexible volume dimensions** is cleared, the volume is considered fixed and does not depend on the inventory that is put into the container. This setting does not affect existing containerization processes.If you are using stocking limits, use the Unit field. Unit conversions between container types can be used as a ratio to calculate storage capacity within locations.

## Define the allowed container type groups

If locations should be prevented from holding different kinds of container types, use the **Allowed container type groups** page.If you want to limit locations to specific container types, the records that are defined on this page must be associated with a location profile.

1.  Click **Warehouse management** \> **Setup** \> **Containers** \> **Allowed container type groups**.

2.  Click **New** to create a record.

3.  If you select **Allow unspecified container types**, license plates that are not associated with a container type can be put into the locations.

4.  Under **Details**, click **New**, and then select the container types.

## Define a location profile

When you assign an allowed container type group to a location profile, license plates can be stored only if allowed container types are associated with them.You can enable this functionality only when **Use license plate tracking** is selected.

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Location profiles**.

2.  Click **New** to create a record.

3.  Select **Use license plate tracking**.

4.  In the **Allowed container type group** field, assign a container type group

## Define location stocking limits

As part of the location stocking limits functionality, the **Container types** option can be used to enable searches for available location capacity that is based on the number of license plates. This includes the use of internal unit conversions between the various container types.

The **Container types** information is evaluated first, as part of the location stocking limits functionality. If no constraints are found, the settings at the product level are used. To prevent the product-level settings from being used, you can create a record where **Allow unlimited quantity** is selected.You cannot change the value in the **Unit** field. The default value is based on the unit that is assigned to the container type.

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Location stocking limits**.

2.  On the **Container types** tab, click **New** to create a record.

3.  In the **Warehouse** field, select the warehouse to define stocking limits for.

4.  Select a location profile ID.

5.  Select the **Allow unlimited quantity** check box to indicate that the location quantity is unlimited. If this check box is cleared, you must specify the container type and quantity that can be stocked in the location.

6.  Assign a container type.

7.  The **Unit** field is updated automatically, based on the container type that you selected.

8.  In the **Quantity** field, enter the quantity for the stocking limit, based on the selected container type.
    

    > [!NOTE]
    > <P>Depending on the existing unit conversions between the container type units, locations can store a greater variety of container types. Please note that it will only be possible to define one of the units in the location stocking limits, the unit conversion will be used to handle the other related units.</P>



For example, we have defined two units that have the following unit conversion:

1-PL = 2∙1/2-PL

We now create two container types, each of which is associated with one of the units.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Container type</p></th>
<th><p>Unit</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Shipping carrier</strong></p></td>
<td><p>Enter a unique identifier (ID) for the shipping carrier.</p></td>
</tr>
<tr class="even">
<td><p><strong>Use carrier</strong></p></td>
<td><p>Select this check box to use the specified shipping carrier for shipment.</p></td>
</tr>
</tbody>
</table>


We also define a location stocking limit for the container types, as shown here.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Container type</p></th>
<th><p>Quantity</p></th>
<th><p>Unit</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1/1-Pallet</p></td>
<td><p>2</p></td>
<td><p>1-PL</p></td>
</tr>
</tbody>
</table>


The following table shows the resulting combinations of location loads.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Number of 1/1-Pallets</p></th>
<th><p>Number of ½-Pallets</p></th>
<th><p>Maximum location load</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>2</p></td>
<td><p>0</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>1</p></td>
<td><p>0</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>1</p></td>
<td><p>1</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>1</p></td>
<td><p>2</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>0</p></td>
<td><p>1</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>0</p></td>
<td><p>2</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>0</p></td>
<td><p>3</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>0</p></td>
<td><p>4</p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


## Define how a default container type is assigned

The logic for assigning a container type to a license plate can be controlled through default values. The user can change the default values on the mobile device.

Conceptually, the defaulting starts from here:**Existing License plate container type** \> **Mobile device menu items** \> **Unit sequence groups** \> **Warehouse** \> **Warehouse management parameters** \> **\[Blank\]**

To define the default container type from the warehouse management parameters, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse management parameters**.

2.  On the **General** tab, look up License plates.

3.  In the **Default container type** field, assign a container type.

To define the default container type from the warehouse, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Warehouses**

2.  Select or create a warehouse.

3.  Look up Warehouse management.

4.  In the **Inventory** field group, in the **Default container type** field, assign a container type.

To define the default container type from the unit sequence group, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Unit sequence group**

2.  Select or create a unit sequence group.

3.  Select or add line details.

4.  In the **Default container type** field, assign a container type.

To define the default container type from mobile device menu items, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Mobile device menu items**

2.  Select or create an inbound mobile device menu item.

3.  Select **Use default data**.

4.  Click **Default data**.

5.  Use the container type as part of the **Default data field** value, and assign a value in the **Hardcoded value** field.

## Define the container type display option on the mobile device pages

For each inbound mobile device menu item, you can control whether the container type should be shown. The association of the default container type with the license plate occurs even if the container type is not shown.

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Mobile device menu items**

2.  Select or create an inbound mobile device menu item.

3.  To show the container type as part of the mobile device page, select **Display container type**.

  


