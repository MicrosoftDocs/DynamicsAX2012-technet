---
title: Set up production processes in a warehouse
TOCTitle: Set up production processes in a warehouse
ms:assetid: b23d32c3-125c-4eab-b034-98f5359c9c0b
ms:mtpsurl: https://technet.microsoft.com/library/Dn745529(v=AX.60)
ms:contentKeyID: 62336120
author: tonyafehr
ms.date: 06/08/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up production processes in a warehouse 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic provides an overview of how to set up production processes in **Warehouse management**. The sections describe the setup that is needed for releasing a production order, reserving raw materials, and creating work for picking raw materials and putting away finished goods. Additionally, this topic contains information about how to configure a mobile device to start production and report quantities as finished.

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
<td><p>Items and warehouses</p></td>
<td><p>All items and warehouses must be enabled for warehouse management processes.</p></td>
</tr>
<tr class="even">
<td><p>Bill of materials</p></td>
<td><p>The finished good must be associated with a bill of materials and a route.</p></td>
</tr>
<tr class="odd">
<td><p>Route</p></td>
<td><p>The item and the resource that will produce the item must be associated with a route.</p></td>
</tr>
<tr class="even">
<td><p>Location</p></td>
<td><p>Locations must be created in the warehouse where the production will occur.</p></td>
</tr>
</tbody>
</table>


## Production waves, reserving raw materials, and releasing production orders

**The type of work** uses the functionality in the **Production control** module for creating production orders. For more information, see [About the production process](about-the-production-process.md). However, some additional setup is required if you use warehouse management processes for production. This section provides an overview of the additional setup that is needed for creating picking work and reserving raw materials.

**Production waves**

After a production order is created and estimated, it can be released to production. When an order is released, the lines in the bill of materials (BOM) for the item that is being produced can be assigned to a production wave. Only BOM lines with a reserved quantity can be assigned to a production wave. Picking work is created for production orders by a wave template, which uses the work template and location directives to create the work for the wave lines. Production waves do not contain shipments or loads. As with other types of waves, you can automate the creation, assignment, processing, and release of picking work for production orders. For more information, see [Create a wave template](create-a-wave-template.md).

**Reserving raw materials**

The difference between production waves and kanban or shipment waves is that you can allow production waves to be released to the warehouse without fully reserving inventory. Waves for shipments and kanbans require that all items or materials be reserved before a wave can be released to the warehouse to create work. For example, if enough materials are available to start a production, but not enough to complete it, you can wait until the remaining materials arrive.

You can specify the requirements for reservations in the **Reservation** field in the **Production orders** form. This is where you set the reservation requirement for a specific production order. You can also specify the default reservation requirement for all production orders in the **Reservation** field in the **Production control parameters** form. The **Reservation** field options are as follows:

  - **Require full reservation** – Select this option if you want to create wave lines and picking work only if all of the materials that are required by a production order can be reserved when the order is released. If all of the materials are not available, wave lines and work are not created. However, the status of the order will change to **Released**.

  - **Allow partial reservation** – Select this option if you want to create wave lines even though some of the materials that are required by a production order are not available when the order is released. If the materials become available later, you can release the order again by using the **Release to warehouse** button.


> [!NOTE]
> <P>If enough materials are already at the resource when the wave is processed, picking work is not created. This same is true if the user specified a location on the BOM line, the inventory that is in the specified location is consumed, and no picking work is created.</P>



**Releasing production orders**

In the **Production orders** form, you can use the following buttons to release an order:

  - **Release** – Release the order to the warehouse and create wave lines for the BOM items. You can also create the associated production documents, such as job cards and route cards.

  - **Release to warehouse** - Create a wave line for any reserved quantity on the BOM lines that is not already associated with a wave line. This button is used when the production order has a status of **Released**, and you must release additional materials to the warehouse.

## Specify the default location where finished goods are staged

You must specify the default location in the warehouse where finished goods are staged before they are put away to inventory.

To specify the default location to stage finished goods, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Warehouses**.

2.  Select or create a new warehouse.

3.  On the **Inventory and warehouse management** tab, in the **Default production finished goods location** field, select the default location to use for finished goods.

## Specify the input location for the resource that will consume the materials

You must specify input location for the resource that will be used in the production process. You specify the input location on the resource group that the resource is assigned to. The resource group must be at a site that is enabled for warehouse management processes.

To specify an input location for a resource, follow these steps:

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource groups**.

2.  On the **General** tab, select the input warehouses and locations in the **Locations** field group.

3.  The remaining steps for this procedure also apply to other resource groups. For more information, see [Set up and define resource groups for operations resources](set-up-and-define-resource-groups-for-operations-resources.md).

## Set up a wave template to process production or kanban waves

You must set up a wave template to define the order in which the picking work is created for the production. You can set up the wave template to create work automatically when a line is created for a wave, or when a worker processes a wave.

To set up a wave template for production waves or kanban waves, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Waves** \> **Wave templates**.

2.  Click **New** to create a new wave template.

3.  In the **Wave template type** field, select one of the following options.
    
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
    <td><p><strong>Production orders</strong></p></td>
    <td><p>Use the wave template to move materials for production orders to the input location for the resource that is used in production.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Kanban</strong></p></td>
    <td><p>Use the wave template to move materials for kanban orders.</p></td>
    </tr>
    </tbody>
    </table>


4.  The remaining steps for this procedure also apply to other wave templates. For more information, see [Create a wave template](create-a-wave-template.md).

## Specify where to pick raw materials from, and where to put away finished goods

You must set up location directives to specify the locations from which to pick the raw materials for a production and the input location to put them in.

To specify locations for picking raw materials and putting them in an input location, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Location directives**.

2.  In the **Work order type** field, select the type of inventory transaction to create a location directive for.
    

    > [!NOTE]
    > <P>If you have installed Microsoft Dynamics AX 2012 R3 Cumulative Update 8, you can direct raw materials to the operation that will consume them on a route. For more information, see the “Direct raw materials to the operations that consume them” section later in this topic.</P>
    > <P>In AX 2012 R3 CU8, the <STRONG>Production order put away</STRONG> and <STRONG>Batch order put away</STRONG> work order types are replaced by <STRONG>Finished goods put away</STRONG> and <STRONG>Co-product and by-product put away</STRONG>. These work order types function in the same way as the work order types that they replaced.</P>

    
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
    <td><p><strong>Raw material picking</strong></p></td>
    <td><p>Use to determine the location where the raw materials for a production order are picked from.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Production order put away</strong></p></td>
    <td><p>Use to determine the location where the finished goods will be put away in inventory.</p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Batch order put away</strong></p></td>
    <td><p>Use to determine the location where the finished batches will be put away in inventory.</p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Kanban picking</strong></p></td>
    <td><p>Use to determine the location where the raw materials for a kanban order are picked from.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Kanban picking</strong></p></td>
    <td><p>Use to determine the location where the finished goods will be put away in inventory.</p></td>
    </tr>
    </tbody>
    </table>


3.  The remaining steps for this procedure also apply to other location directives. For more information, see [Create a location directive](create-a-location-directive.md).

## Define how to create work for raw material picking and finished good put away

You must set up a work template to create the work for picking the raw materials for a production and for putting away the finished good in inventory.


> [!NOTE]
> <P>If you have installed AX 2012 R3 CU8, you can create and direct work as follows:</P>
> <UL>
> <LI>
> <P>Direct raw materials to the route operation that consumes them. For more information, see the “Direct raw materials to the operations that consume them” section in this topic.</P>
> <LI>
> <P>Create put away work for a finished good, co-product, or by-product when you report a production or batch as finished. For more information, see the “Direct work to put away finished goods from the last operation on a production route” section in this topic.</P></LI></UL>
> <P>In AX 2012 R3 CU8, the <STRONG>Production order put away</STRONG> and <STRONG>Batch order put away</STRONG> work order types are replaced by <STRONG>Finished goods put away</STRONG> and <STRONG>Co-product and by-product put away</STRONG>. These work order types function in the same way as the work order types that they replaced.</P>



To set up a work template for raw material picking and finished good put away, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Work** \> **Work templates**.

2.  In the **Work order type** field, select the type of warehouse transaction to create a work template for.
    
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
    <td><p><strong>Raw material picking</strong></p></td>
    <td><p>Create picking work for a production order.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Production order put away</strong></p></td>
    <td><p>Create put away work for a production order.</p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Batch order put away</strong></p></td>
    <td><p>Create put away work for a batch order.</p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Kanban picking</strong></p></td>
    <td><p>Create picking work for a kanban order.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Kanban picking</strong></p></td>
    <td><p>Create put away work for a kanban order.</p></td>
    </tr>
    </tbody>
    </table>


3.  The remaining steps for this procedure also apply to other work templates. For more information, see [Create a work template](create-a-work-template.md).

## Direct raw materials to the operations that consume them

If you have installed AX 2012 R3 CU8, you can direct raw materials to the operation that will consume them on a route. For example, this is useful when you have a large facility where operations are performed in different rooms. The following table describes the information that is required for setup.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Setup</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>BOM line</strong></p></td>
<td><p>You must associate items that are included in the bill of materials for the released product with the operation that will consume them. This makes the connection between the raw material or item and the route.</p>
<p>You assign the bill of material item to the operation in the <strong>BOM line</strong> form, on the <strong>General</strong> tab, by selecting the operation in the <strong>Oper. No.</strong> field.</p>
<p>If you do not relate materials to operations, the materials are delivered to the input location for the resource for the first operation on the route. By relating raw materials to operations, you indicate that the material is used only for the operation. This is independent of the resource that performs the operation. Materials are always delivered first to the primary operation.</p></td>
</tr>
<tr class="even">
<td><p><strong>Route</strong></p></td>
<td><p>On the route, you must specify the resource requirement for a resource or resource group. This connects the resource or resource group to the route. On the resource group, you specify the input warehouse and input location. If you specify an input location on the resource, this will override the input location on the resource group.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Warehouses</strong></p></td>
<td><p>Optional: You can specify the default input location for the warehouse in the <strong>Warehouses</strong> form. For more information, see the “Specify the default location where finished goods are staged” section in this topic.</p>
<p>This input location is used only if an input warehouse is not specified for the resource group that is selected as a resource requirement for the route. This location will be applied if no input location has been specified for the resource group that is assigned to the first operation on the route.</p></td>
</tr>
<tr class="even">
<td><p><strong>Work classes</strong></p></td>
<td><p>You must create a work class for the raw materials work order type. You assign the work class to the work template and the mobile device menu item for raw material picking.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Work templates</strong></p></td>
<td><p>You must set up a work template for raw material picking. In the <strong>Work templates</strong> form, when you select <strong>Raw material picking</strong> in the <strong>Work order type</strong> field, sorting criteria is added to the query, and a grouping is added to the work breaks for the template. You cannot change these. For the work break sorting order, mandatory sorting criteria must be higher than non-mandatory sorting criteria.</p></td>
</tr>
</tbody>
</table>


## Configure a mobile device to start productions, and report quantities as finished

After the raw materials have been moved to the input location for the resource that will consume them, you can start the production order. You can do this by using the **Production orders** form or by using a mobile device. To start a production order on a mobile device, the device must be configured appropriately. For more information, see [Configure mobile devices for warehouse work](configure-mobile-devices-for-warehouse-work.md).

To report goods as finished, the mobile device can be configured to do the following:

  - Report a quantity of the production as finished, and create put away work that another worker will perform.

  - Report a quantity of the production as finished, and put away the finished good immediately. The worker who reports the quantity as finished will also put away the goods in inventory.

The put away location can be determined by the worker or by Microsoft Dynamics AX, as follows:

  - The worker reports the production as finished, and can decide where to put the finished good. Using this method requires a mobile device menu item that is set up to be user directed.

  - The worker reports the production as finished, and is directed to put the finished good in a location. Using this method requires a mobile device menu item that is set up to be system directed.


> [!NOTE]
> <P>If you are using Microsoft Dynamics AX 2012 R3 Cumulative Update 9 it’s possible to enable overproduction scenarios when reporting as finished with a mobile device. To do this, select the <STRONG>Validate feedback quantity</STRONG> and <STRONG>Accept surplus production</STRONG> parameters on the <STRONG>Production parameters</STRONG> form. If these parameters are selected, the report as finished process will complete even if the quantity is greater than the start quantity as long as it’s not greater than the start quantity plus the accepted surplus quantity.</P>



## Direct work to put away finished goods from the last operation on a production route

If you are running AX 2012 R3 CU8, you can set up a work template to create work to put away finished goods and co-products and by-products from the last operation on a particular production route. For example, this is useful when you have more than one production route in a warehouse.

You can create put away work for finished goods by using either a mobile device or using the Microsoft Dynamics AX client to report a production as finished.

The following table lists the required setup. For each step, the key is the **Work order type** field. Depending on whether you need to put away finished goods, or co-products or by-products, select either **Finished goods put away** or **Co-product and by-product put away**.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Prerequisite</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Work classes</strong></p></td>
<td><p>You need to create work classes for finished goods put-away, and co-product and by-product put away. You specify the work class on the work template.</p></td>
</tr>
<tr class="even">
<td><p><strong>Work templates</strong></p></td>
<td><p>You need to set up a work template to create the put away work. You have to assign the work class to the pick and put lines for each work order type. For more information, see <a href="create-a-work-template.md">Create a work template</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Location directives</strong></p></td>
<td><p>Set up a location directive for each work order type. For more information, see <a href="create-a-location-directive.md">Create a location directive</a>.</p>
<div class="alert">

> [!TIP]
> <P>You can set up the query on the <STRONG>Location directives</STRONG> FastTab to put away finished goods, co-products, and by-products in specific locations. When you select a work order type, the query is optimized for the selected type. Use the criteria to direct the put away work to a location.</P>
> <P><STRONG>Example</STRONG></P>
> <P>This example shows how to set up location directive queries to put away co-products and by-products in specific locations.</P>
> <OL>
> <LI>
> <P>On the <STRONG>Range</STRONG> tab, add the following criteria to the query:</P>
> <OL>
> <LI>
> <P><STRONG>Table</STRONG> – Select <STRONG>Production co-by products</STRONG></P>
> <LI>
> <P><STRONG>Derived table</STRONG> – Select <STRONG>Production co-by products</STRONG>.</P>
> <LI>
> <P><STRONG>Derived table</STRONG> – Select <STRONG>Production co-by products</STRONG>.</P>
> <LI>
> <P><STRONG>Field</STRONG>- Select <STRONG>Production type</STRONG>.</P>
> <LI>
> <P><STRONG>Criteria</STRONG> – Select or By-<STRONG>Co-product</STRONG></P></LI></OL>
> <LI>
> <P>To direct the put away work to a specific location, set up the query on the <STRONG>Location directive actions</STRONG> FastTab.</P>
> <LI>
> <P>Enter the criteria for the warehouse and location, and then click <STRONG>Add</STRONG>.</P>
> <OL>
> <LI>
> <P><STRONG>Field</STRONG> - Select <STRONG>Location profile ID</STRONG>.</P>
> <LI>
> <P><STRONG>Criteria</STRONG> – Select the location profile.</P></LI></OL></LI></OL>


</div></td>
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
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


