---
title: "What's new: Warehouse management features"
TOCTitle: Warehouse management features
ms:assetid: 4a87b0e7-bf65-45c8-abe1-46f449144b17
ms:mtpsurl: https://technet.microsoft.com/library/Dn716029(v=AX.60)
ms:contentKeyID: 62200285
author: Khairunj
ms.date: 06/08/2015
mtps_version: v=AX.60
---

# What's new: Warehouse management features 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A new module, **Warehouse management**, has been added in Microsoft Dynamics AX 2012 R3. This topic is a high-level overview of the feature areas that are included in the new module, and it also lists the new Warehouse management features that were added in Microsoft Dynamics AX 2012 R3 Cumulative Update 8.


> [!NOTE]
> <P>Microsoft Dynamics AX 2012 R3 includes new Warehouse and Transportation management modules that are enabled by a single configuration key, along with the previously released Warehouse management II module. Users should enable the configuration key for <STRONG>ONLY ONE</STRONG> of these modules, but not both, in a single-instance, single-partition deployment. Although technically feasible, enabling the configuration keys for both of these modules in a single-instance, single-partition deployment is not supported by Microsoft.&nbsp;</P>



## Workflows

Configure inbound and outbound workflows for standardized processes in **Production** and **Inventory management**. For more information, see the following topics:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="setting-up-inbound-processes.md">Setting up inbound processes</a></p></td>
</tr>
<tr class="even">
<td><p><a href="setting-up-outbound-processes.md">Setting up outbound processes</a></p></td>
</tr>
</tbody>
</table>


## Cluster picking

Assign orders to clusters to pick from a single location and configure profiles to control the validation and packing of items into shipping containers. For more information, see the following topic:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="set-up-cluster-picking.md">Set up cluster picking</a></p></td>
</tr>
</tbody>
</table>


## Wave processing

Create and release work through automatic or manual processing of waves. For example, you can use waves to create, process, and release picking work for outbound loads or shipments. For more information, see the following topics:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="set-up-warehouse-parameters-for-wave-processing.md">Set up warehouse parameters for wave processing</a></p></td>
</tr>
<tr class="even">
<td><p><a href="create-a-wave-template.md">Create a wave template</a></p></td>
</tr>
<tr class="odd">
<td><p><a href="wave-processing.md">Wave processing</a></p></td>
</tr>
</tbody>
</table>


## Inventory control

Set up cycle counting thresholds, schedule plans, apply ad-hoc cycle counting, and configure real-time replenishment. For more information, see the following topic:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="cycle-counting.md">Cycle counting</a></p></td>
</tr>
</tbody>
</table>


## Containerization

Set up container groups to sequence packing processes and create templates that support packing strategies. For example, by using automated containerization, you can have containers and picking work created for shipments when a wave is processed. For more information, see the following topic:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="set-up-containerization.md">Set up containerization</a></p></td>
</tr>
</tbody>
</table>


## Mobile devices

Use scanners and other mobile devices to optimize precision in the picking and put-away processes. You can configure the flow for system-directed push strategies and user-directed pull strategies. For more information, see the following topic:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="setting-up-mobile-devices.md">Setting up mobile devices</a></p></td>
</tr>
</tbody>
</table>


## Deferred reservation strategy

Defer reservation details beyond the point of entering an order. The deferred reservation strategy is based on a reservation hierarchy, which you can assign to inventory items. For more information, see the following topic:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="set-up-reservation-hierarchies.md">Set up reservation hierarchies</a></p></td>
</tr>
</tbody>
</table>


## Work

Monitor the processing and the amount of work in a warehouse, push work to dedicated warehouse workers, and trace completed work. For more information, see the following topic:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="set-up-a-work-pool.md">Set up a work pool</a></p></td>
</tr>
</tbody>
</table>


## Integration with the Quality control module

Include quality control in any inbound or outbound processes that you set up for warehouse items. For example, the quality control features enable you to prevent reservation of items that have not passed a quality test. For more information, see the following topics:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="testing-products-sample.md">Testing products (sample)</a></p></td>
</tr>
<tr class="even">
<td><p><a href="inventory-blocking.md">Inventory blocking</a></p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 8

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use cross-docking to move packages of products through a warehouse while using limited or no storage</p></td>
<td><p>Cross-docking is useful if you purchase products from different vendors, the vendors prepack cartons that contain a mix of products or product variants, and you want distribute the cartons to one or more retail stores. This feature works with or without the Warehouse management module.</p>
<p>For more information, see <a href="cross-docking-packages-in-warehouse-management.md">Cross docking packages in Warehouse management</a>.</p></td>
</tr>
<tr class="even">
<td><p>Set up a company policy for sales order fulfillment and create batch jobs to release sales orders and transfer orders to the warehouse</p></td>
<td><p>You need to set up a default company policy for sales order fulfillment rates. The policy controls the percentage of the total price or the quantity of an order that must be reserved physical before a sales order can be released to the warehouse. You can also set up a policy for specific customers. Customer-specific policies override the default policy.</p>
<p>For more information, see <a href="sales-orders-and-fulfillment-rates-in-warehouse-management.md">Sales orders and fulfillment rates in Warehouse management</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Allocate batch numbers in Warehouse management</p></td>
<td><p>You can define policies that control when batch numbers are allocated by setting up one or more number groups, and then assigning them to products. It’s possible to allocate batch numbers when you perform a physical receipt of a product, or when you create a line that includes a product on a source document, such as a purchase order. You can also manually allocate batch numbers to products.</p>
<p>For more information, see <a href="batch-numbers-in-warehouse-management.md">Batch numbers in Warehouse management</a>.</p></td>
</tr>
<tr class="even">
<td><p>Receive items at a different warehouse than expected</p></td>
<td><p>You can set up a mobile device to receive loads or items at a warehouse that differs from the warehouse that was specified on the source document. When you receive the load or item, it’s located at the new warehouse and all related work is created for the new warehouse.</p>
<p>For more information, see <a href="receive-items-at-a-different-warehouse-than-expected.md">Receive items at a different warehouse than expected</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Use product variants in warehouse management processes</p></td>
<td><p>Product variants are defined by product masters with product dimension variations, for example, a single towel in different sizes and colors. Instead of creating multiple products, you create a single product master and use the various combinations of sizes and colors as different product variants. You can use product variants in the following processes:</p>
<ul>
<li><p>To define stocking limits.</p></li>
<li><p>To configure work confirmation and bar code scanning on mobile devices.</p></li>
<li><p>To create replenishment templates.</p></li>
<li><p>To set up rules for converting units of measure.</p></li>
<li><p>To assign fixed warehouse locations.</p></li>
</ul>
<p>For more information, see <a href="define-pack-size-categories-and-location-stocking-limits.md">Define pack size categories and location stocking limits</a>, <a href="configure-mobile-devices-for-warehouse-work.md">Configure mobile devices for warehouse work</a>, <a href="set-up-replenishment.md">Set up replenishment</a>, <a href="set-up-a-unit-sequence-group-and-unit-of-measure-conversions-in-warehouse-management.md">Set up a unit sequence group and unit of measure conversions in Warehouse management</a>, and <a href="set-up-parameters-to-create-a-warehouse-location.md">Set up parameters to create a warehouse location</a>.</p>
<p></p></td>
</tr>
<tr class="even">
<td><p>Use additional production processes in a warehouse</p></td>
<td><p>It’s now possible to use the following production processes in a warehouse:</p>
<ul>
<li><p>Deliver picked materials to the exact locations where the materials are consumed in production.</p></li>
<li><p>Define a specific output location for a production order or a batch order. This enables the warehouse worker to know exactly where to pick up the goods for put away work.</p></li>
<li><p>Generate put away work for warehouse-enabled items when you use the reporting as finish process on the Microsoft Dynamics AX client. (Previously you could only do this from a mobile device.)</p></li>
</ul>
<p>For more information, see blog posts on the <a href="https://blogs.msdn.com/b/axmfg/">Dynamics AX Manufacturing R&amp;D Team blog</a> and <a href="set-up-production-processes-in-a-warehouse.md">Set up production processes in a warehouse</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Use bar code lookup in inbound processes</p></td>
<td><p>Bar code lookup functionality can be used with products and product variants to support several inbound operations that are carried out by warehouse workers on mobile devices.</p>
<p>For more information, see <a href="use-bar-codes-in-warehouse-operations.md">Use bar codes in warehouse operations</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 9

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s New</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Improvements to replenishment</p></td>
<td><p>It’s possible to set up demand replenishment so that it checks whether there’s any demand replenishment work that’s been created in the same location that is not yet finalized. If existing work is found with an appropriate quantity available, the existing work will be used instead of creating new replenishment work. For more information, see <a href="set-up-replenishment.md">Set up replenishment</a>.</p>
<p>There’s also been an improvement in the performance of Min/max replenishment.</p></td>
</tr>
<tr class="even">
<td><p>Lists on the mobile device menu</p></td>
<td><p>It is now possible to display a list of open work items on warehouse mobile devices. The list can be configured to filter on different fields and the user can select any work displayed on the list to be directed to its specific instructions. For more information, see <a href="configure-mobile-devices-for-warehouse-work.md">Configure mobile devices for warehouse work</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enable transfer orders on the packing station</p></td>
<td><p>It is now possible to manually pack transfer orders from the packing station. This is particularly useful in retail environments where you want to pack cartons in order to refill retail stores from a distribution center.</p></td>
</tr>
<tr class="even">
<td><p>Use additional strategies when moving inventory</p></td>
<td><p>Two new locations directive action strategies are now supported for the work order type Inventory movement: <strong>Consolidate</strong> and <strong>Empty location with no incoming work</strong>. For more information, see <a href="create-a-location-directive.md">Create a location directive</a> and the <a href="https://blogs.msdn.com/b/dynamicsaxscm/archive/2015/01/30/put-away-strategies-for-purchase-orders-possibilities-performance-and-improvements-in-cu8.aspx">Dynamics AX SCM R&amp;D Team blog</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Use additional production processes in a warehouse</p></td>
<td><p>You can now report as finished on a mobile device in overproduction scenarios. For more information, see <a href="set-up-production-processes-in-a-warehouse.md">Set up production processes in a warehouse</a>.</p></td>
</tr>
<tr class="even">
<td><p>Batch reservation strategy improvements</p></td>
<td><p>The following improvements have been made to batch reservation strategies:</p>
<ul>
<li><p>The FEFO batch reservation strategy now takes the Best before date and the Expiration date of the batches into account.</p></li>
<li><p>It is now possible to reserve items across different batch numbers when releasing sales orders.</p></li>
</ul>
<p>For more information, see <a href="create-a-location-directive.md">Create a location directive</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Improvements to auto-release to warehouse process</p></td>
<td><p>When using the auto-release to warehouse process it is now possible to consolidate multiple sales orders for the same customer into a single shipment if the <strong>Consolidate shipment at release to warehouse</strong> parameter is set on the <strong>Warehouse</strong> form. For more information, see <a href="sales-orders-and-fulfillment-rates-in-warehouse-management.md">Sales orders and fulfillment rates in Warehouse management</a>.</p></td>
</tr>
<tr class="even">
<td><p>Waves can now contain different order types</p></td>
<td><p>It is now possible to process a wave that includes multiple shipments from both sales and transfer orders. This is useful when you are planning waves according to destinations of shipments.</p></td>
</tr>
</tbody>
</table>

  


