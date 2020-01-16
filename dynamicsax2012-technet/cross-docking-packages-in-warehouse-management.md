---
title: Cross docking packages in Warehouse management
TOCTitle: Cross docking packages in Warehouse management
ms:assetid: 9f6790a8-5bf6-44cf-a1c8-046202e63bfe
ms:mtpsurl: https://technet.microsoft.com/library/Dn887224(v=AX.60)
ms:contentKeyID: 63378892
author: Khairunj
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- package
- cross dock
- cross docking
- crossdock
- Forms.RetailBuyersPushPerPackage
audience: Application User
ms.search.region: Global
---

# Cross docking packages in Warehouse management 


This topic describes features that are available only if you are running Microsoft Dynamics AX 2012 R3 Cumulative Update 8. This topic describes how to use cross-docking in **Warehouse management** to move packages of products through a warehouse while using limited or no storage. Cross-docking is useful if you purchase products from different vendors, the vendors prepack cartons that contain a mix of products or product variants, and you want distribute the cartons to one or more retail stores.

## What setup is required for cross-docking packages?

In general, all of the steps for setting up inbound and outbound processes in **Warehouse management** are required. Setup includes setting up receiving and final shipping locations, work users, and wave templates. However, there are some specific setup steps that are required for cross-docking packages.

The following table describes the prerequisites that are required before you can cross dock packages.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Form</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Released products</strong></p></td>
<td><p>All of the products and product variants that the packages include must be enabled for warehouse management processes.</p>
<p>To enable a product, you need to assign the product to a storage dimension group where the <strong>Use warehouse management processes</strong> check box is selected.</p></td>
</tr>
<tr class="even">
<td><p><strong>Product packages</strong></p></td>
<td><p>You must set up packages of items. A product package is a group of products that you order from a supplier. Packages can help you create lines on purchase orders because you do not have to select products individually. Instead, you can select a package that includes the products, and the products are added to the purchase order. During cross-docking, each package is a license plate, and must be associated with a vendor account. For more information, see <a href="set-up-product-packages.md">Set up product packages</a> and <a href="replenish-inventory-overview.md">Replenish inventory overview</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Warehouses</strong></p></td>
<td><p>Each store that you want to send shipments to has to be set up as a warehouse, and all stores have to belong to the same legal entity. When you cross dock packages, you specify the warehouse (store) that you want to ship the packages to.</p>
<p>You designate a warehouse as a store on the <strong>Warehouses</strong> form, on the <strong>Retail</strong> FastTab, by selecting the <strong>Store</strong> check box.</p>
<p>The warehouses used for inbound and outbound processes must be enabled for warehouse management processes. To enable a warehouse, in the <strong>Warehouses</strong> form, on the <strong>Warehouse management</strong> FastTab, select the <strong>Use warehouse management processes</strong> check box.</p></td>
</tr>
<tr class="even">
<td><p><strong>Locations</strong></p></td>
<td><p>You can set up a location to use as your cross-docking location. When packages are received in the warehouse they are put away in the cross-docking location. The location must be license plate controlled and allow mixed items.</p>
<p>For more information, see <a href="set-up-parameters-to-create-a-warehouse-location.md">Set up parameters to create a warehouse location</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Location directives</strong></p></td>
<td><p>If you want to direct received inventory to a specific location, you can create location directives for the following work order types:</p>
<ul>
<li><p><strong>Purchase orders</strong> – You can set up a location directive for purchase orders to direct where incoming cross-docking items should be put. Typically, this will be an area close to the outbound docks. When you set up the query on the <strong>Location Directive Actions</strong> FastTab in the <strong>Location directives</strong> form, you can ensure that only specific cross-docking purchase order lines are part of the location directive search. One way to do this is to add the <strong>Purch Table Additional Fields</strong> table to the query, add the <strong>Cross dock</strong> field, and then set that field to <strong>Yes</strong>. To make sure that the cross-docking location directive record gets selected, review the <strong>Sequence number</strong> field for your query on the <strong>Location directives</strong> form, and make sure that there are no other queries with a lower <strong>Sequence number</strong> value that would override the conditions set in your query.</p></li>
<li><p><strong>Transfer issue</strong> – This location directive is used in the outbound process for the transfer orders in the cross-docking warehouse. The location directive can filter for lines where cross-docking is selected. When you set up this location directive, do the following:</p>
<ul>
<li><p>On the <strong>Lines</strong> FastTab, select the <strong>Allow split</strong> check box.</p></li>
<li><p>On the <strong>Location Directive Actions</strong> FastTab, in the <strong>Strategy</strong> field, select <strong>License plate guided</strong>.</p></li>
</ul></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Work templates</strong></p></td>
<td><p>You can set up a work template for the <strong>Transfer issue</strong> work order type. For outbound transfer issues, you can group the work for each package that is being cross docked by setting up a work template. One work header is created for each package.</p>
<p>If you want to group the work for packages, the following settings are required:</p>
<ul>
<li><p>The sorting in the query must contain the <strong>Temporary work transactions</strong> table, the derived table, and the <strong>Located license plate ID</strong> field.</p></li>
<li><p>Work breaks must use the same tables as the query. Additionally, select the <strong>Group by this field</strong> check box.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Mobile device menu items</strong></p></td>
<td><p>You must set up a mobile device menu item for the following processes:</p>
<ul>
<li><p><strong>License plate receiving</strong></p></li>
<li><p><strong>Pack to nested license plate</strong></p></li>
</ul>
<p>You must also set up a mobile device menu item for the outbound process, and then assign all the menu items to one or more mobile device menus.</p>
<p></p></td>
</tr>
</tbody>
</table>


## What types of orders are included in the cross-docking process?

The cross-docking process involves purchase orders and transfer orders. The process starts with a purchase order, where you create purchase order lines by selecting the packages that you want to cross dock. In the **Purchase order** form, on the **Purchase order lines** FastTab, click **Purchase order lines**, and select **Create lines from package** to add the products in the packages to the order. The quantity on the purchase order line reflects the total quantity of each item for the number of packages ordered. For example, if you list two packages and the quantity of an item in the package is three, the quantity on the purchase order line is six.

You create transfer orders for cross docking packages by using the **Planned cross docking** form. After you specify the packages and stores, click **Create order** to create the transfer order. Use the standard procedures for handling the transfer order. For more information, see [Working with transfer orders (Retail essentials)](working-with-transfer-orders-retail-essentials.md).

Each package becomes a license plate that can be moved from the inbound location to the outbound location. From the **Purchase order** form, open the **Load planning workbench** and create an inbound load. On the **Loads** tab, click **Ship and receive**, and then select **Create cross-docking packing structure**. This generates a packing structure based on the information in the package. To view the packing structure and the license plate, click **Ship and receive**, and then select **Packing structure**.

## How do I set up receiving for cross-docking?

Packages are treated as nested license plates within a parent license plate. To receive the items, you must use a mobile device menu item that is configured to use the **License plate receiving** work creation process. This lets you use a mobile device to scan the parent license plate and display the total quantity of items on the parent license plates. The nested license plates contain the actual items in the packages but the inventory quantity is on the parent license plate. Therefore, you also need to create a menu item that uses the **Pack to nested license plate** process of work creation. This process moves the inventory to the nested license plates based on the packing structure when you enter the ID of the parent license plate.

## How do I set up the outbound process?

When you release the order to the warehouse to create the pick-and-put work, the **License plate guided** strategy on the location directive is used. The strategy determines where the license plates from the transfer order are and picks the items from those locations. You can do this for multiple license plates. To do this by using a mobile device, the mobile device menu item must be set up to pick license plates for transfer orders. The following table lists the required settings for the mobile device menu item.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Selection</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Mode</strong></p></td>
<td><p><strong>Work</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Use existing work</strong></p></td>
<td><p>Select the check box.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Directed by</strong></p></td>
<td><p><strong>User directed</strong> or <strong>System directed</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Handle by license plate</strong></p></td>
<td><p>Select the check box to let the worker scan the license plate and then move the whole license plate, instead of scanning each item individually.</p></td>
</tr>
</tbody>
</table>


## Can I define the content of the packages that my vendor will deliver?

Yes. You can specify the products and product variants that are delivered in each package.

You define packages in the **Product packages** form. Click **Retail** \> **Setup** \> **Replenishment** \> **Product packages**. Packages can contain multiple products with different stock keeping units (SKUs) and various quantities. For more information, see [Set up product packages](set-up-product-packages.md) and [Replenish inventory overview](replenish-inventory-overview.md).


> [!NOTE]
> <P>A product package number that is linked to a purchase order line is inserted only if the product package definition is specific to that vendor.</P>



The packing structure is created when you plan the load in the **Load planning workbench** form. When you click the **Create cross-docking packing structure** button, the packing structure is automatically created based on the packing profile and the cross-docking plan. In addition, the license plates that are generated as part of the packing structure are associated with the transfer order issue lines. This is to ensure that the correct license plates will be picked for the retail stores in the outbound transfer order process.

## Can I ship partial quantities when cross-docking packages?

Yes. If you want to ship a partial quantity, you can break up the packages by using the process for outbound transfer issues. The connection between the transfer order lines and the packages or license plates is not required.

## Can I use cross-docking in an intercompany environment?

Yes and no. You cannot plan cross-docking based on product packages for intercompany sales orders. However, you can use product cross-docking without the license plate guided strategy on the location directive. Cross-docking packages supports only transfer orders. On the **Planned cross docking** form, you can set up the cross-docking for the package, and then click **Create order** to create a transfer order.

## Which work creation processes should I set up mobile device menu items for?

Set up a mobile device menu item for each of the following work creation processes:

  - **License plate receiving** - Use this mobile device menu item to receive inventory. This creates work to put the parent license plate in the cross-docking location in the warehouse. You can also enable printing for this mobile device menu item so that you can print license plate labels. To set up printing, select the **Print label** check box for the menu item.
    

    > [!TIP]
    > <P>Printed license plates are displayed in the <STRONG>License plate labels</STRONG> form.</P>



  - **Pack to nested license plate** – Use this mobile device menu item to move quantities of inventory from the parent license plate to the nested license plates. Quantities are moved to nested license plates according to the packing structure that is associated with the inbound load.

If you don’t want to automate the outbound process, you also need to set up a mobile device menu item for that. The following settings are required for the outbound process menu item.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Selection</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Mode</strong></p></td>
<td><p><strong>Work</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Use existing work</strong></p></td>
<td><p>Select the check box.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Directed by</strong></p></td>
<td><p><strong>User directed</strong> or <strong>System directed</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Handle by license plate</strong></p></td>
<td><p>Select the check box to let the worker move a license plate without having to scan each product in the license plate.</p></td>
</tr>
<tr class="odd">
<td><p>Work class</p></td>
<td><p>Select a work class that references a <strong>Transfer issue</strong> work order type.</p></td>
</tr>
</tbody>
</table>


## Can I automate the cross-docking process, or do I have to create the work manually?

You can do both. If you want to automate the process, you can select the **Automatically process** check box on the work template that you use for transfer orders. This is also true for product packages with nested license plates.

## Are there situations when I can’t cross dock packages?

Yes, there are. You cannot cross dock packages in the following situations:

  - If purchase order lines are created for products in the same package and the products are assigned to different locations.

  - If you’ve tried to cross dock products, not packages, and one or more of the following has occurred:
    
      - The unit of measure for the products to cross dock differs from the unit of measure specified on the purchase order line.
    
      - The quantity of a product to cross dock differs from the quantity that is specified in the package. For example, this can occur if you change a quantity of a product in a package.
    
      - During the outbound process, the quantity of an item that is being cross docked to a store does not match the quantity specified in the transfer order. This can occur if you remove a quantity of the product when the package is at the cross-docking location.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[Use cross docking to distribute products](use-cross-docking-to-distribute-products.md)

  


