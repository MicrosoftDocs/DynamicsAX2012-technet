---
title: Procurement catalogs overview
TOCTitle: Procurement catalogs overview
ms:assetid: 00ab1ea0-9655-49c2-a5f1-dd9d1da57db7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242092(v=AX.60)
ms:contentKeyID: 36055918
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- procurement
- procurement catalog
- procurement catalogs
- purchasing
---

# Procurement catalogs overview 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, purchasing professionals can create and maintain catalogs that company employees can use when they order items and services for internal use. The use of catalogs for indirect procurement has the following advantages:

  - Employees can quickly and easily find items or services that they need, and create purchase requisitions for those items or services.

  - Procurement professionals can enforce purchasing policies and guarantee that employees order only approved items and services.

When you create a procurement catalog, you complete the following tasks:

  - Determine which categories you want to be displayed to your employees on the procurement site. You can use your procurement category hierarchy to create your catalog, or you can manually define your catalog categories. If you want to use a procurement category hierarchy, the hierarchy must be configured before you create the catalog.

  - Determine which products you want your employees to be able to order. You can import catalog data for products directly from your vendors, manually add products to your catalog categories, or use the products that are already assigned to the procurement categories.

  - Determine what level of detail you want to provide for your products. You can add attributes and set up product relationships to provide a more guided order experience to your employees.

  - Determine whether employees can order products directly from an external vendor. If you want to provide access to external vendor catalogs, you must configure the access parameters for the vendor's catalog site, and then add a link to the vendor's catalog site to the procurement catalog.

  - Determine how many procurement catalogs you require. Access to a procurement catalog is determined by the catalog policy rule that you configure for the legal entity and operating unit that an employee is assigned to. For more information about how to configure a catalog policy rule, see [Set up a procurement catalog policy rule](set-up-a-procurement-catalog-policy-rule.md).

## Creating a procurement catalog

The process for creating a new catalog includes multiple steps. The following diagram illustrates the process flow and identifies the role that is responsible for each step.

![ProcurementCatalog\_ProcessFlow](images/Hh242092.ProcurementCatalog_ProcessFlow(AX.60).gif "ProcurementCatalog_ProcessFlow")

## Prerequisites

The following table describes the tasks that must be completed before a purchasing professional can create a procurement catalog.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Role</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up a procurement category hierarchy</p></td>
<td><p>Purchasing manager</p></td>
<td><p>Procurement category hierarchies classify items or transactions for reporting and analysis. By using a procurement category hierarchy, companies can strategically manage categories, products, vendors, and other procurement factors from a central location. One procurement category hierarchy is defined for a whole organization.</p>
<p>You can create your catalog's navigation structure by copying the procurement category hierarchy into a procurement catalog. The procurement categories that are copied become the catalog categories, and the vendors, products, and attributes that are associated with the procurement categories are automatically included in your catalog.</p>
<p>After you copy the procurement category hierarchy into the catalog, you can modify the structure of the catalog categories to fit the requirements of your procurement site. You can also specify the products, vendors, external vendor catalog sites, and so on, that you want to be displayed on the site.</p>
<p>For more information about how to set up the procurement category hierarchy, see <a href="key-tasks-set-up-a-category-hierarchy.md">Key tasks: Set up a category hierarchy</a>.</p></td>
</tr>
<tr class="even">
<td><p>Set up vendors</p></td>
<td><p>Purchasing manager</p></td>
<td><p>Before you can add a vendor's products to a procurement catalog, the vendor must be registered in Microsoft Dynamics AX and included in the vendor master. The vendor must also be associated with a procurement category that is included in the procurement catalog.</p>
<p>For more information about how to register vendors in Microsoft Dynamics AX, see <a href="manage-vendor-requests-overview.md">Manage vendor requests overview</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Add products to the product master</p></td>
<td><p>Purchasing manager</p></td>
<td><p>Before you can add products to a procurement catalog, the products must be included in the product master in Microsoft Dynamics AX. To add products to the product master, you can either import product data from vendor catalogs, or enter product data manually in the <strong>Product details</strong> form or the <strong>Released product details</strong> form. After you add a product to the product master, you must also assign it to a procurement category. Only products that are assigned to procurement categories can be added to your procurement catalog.</p>
<p>For more information about how to import product date from a vendor, see <a href="import-a-catalog-from-a-vendor.md">Import a catalog from a vendor</a>. For more information about how to manually add procurement products to Microsoft Dynamics AX, see <a href="key-tasks-define-products.md">Key tasks: Define products</a>.</p></td>
</tr>
<tr class="even">
<td><p>Define product relationships (optional)</p></td>
<td><p>Purchasing manager</p></td>
<td><p>Product relationships identify how products relate to each other. By using product relationships, you can encourage employees to select a preferred set of products and enforce tighter control over employee spending. For example, you may want to associate a computer with a specific monitor that is a good value. In this way, when an employee selects the computer, the preferred monitor is offered. Product relationships can be defined by the vendor, or you can define them in the product master.</p>
<p>For more information about how to define product relationships, see <a href="set-up-product-relationship-types.md">Set up product relationship types</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Add attributes (optional)</p></td>
<td><p>Purchasing manager</p></td>
<td><p>By setting up attributes, you can specify the level of detail that you want to maintain for the products in your catalog. Attributes are details that your organization wants to track for a particular product or category. Examples of attributes include the SKU number, product version, color, and size.</p>
<p>Attributes can be assigned to a procurement category. All the products that are assigned to a procurement category inherit the attributes that are assigned to that category. After a category and its products are assigned to a catalog, all attributes for that product are displayed on the procurement site.</p>
<p>For more information about how to define attributes, see <a href="set-up-attributes-and-attribute-types.md">Set up attributes and attribute types</a>.</p></td>
</tr>
<tr class="even">
<td><p>Add vendors and products to procurement categories</p></td>
<td><p>Purchasing manager</p></td>
<td><p>When the procurement category hierarchy is created for your organization, each procurement category can be associated with specific vendors, products, and so on. If a catalog is created by using the procurement category hierarchy, these associations can be copied automatically to the catalog. The same restrictions can then be enforced at the catalog level and on the procurement site.</p>
<p>For more information about how to add vendors and products with procurement categories, see <a href="key-tasks-set-up-and-maintain-procurement-category-hierarchies.md">Key tasks: Set up and maintain procurement category hierarchies</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Configure access to external vendor catalog sites</p></td>
<td><p>Purchasing manager</p></td>
<td><p>You can set up access to external vendor catalogs so that your users can order products directly from a vendor's catalog site. You configure access to the vendor’s external vendor's catalog site based on data that the vendor provides. You validate the configurations and activate the catalog configurations in Microsoft Dynamics AX.</p>
<div>

> [!NOTE]
> <P>Before you can configure access to an external vendor's catalog site, the vendor must be registered in Microsoft Dynamics AX.</P>


</div>
<p>For more information about how to configure access to external vendor catalogs, see <a href="set-up-an-external-vendor-catalog.md">Set up an external vendor catalog</a>.</p></td>
</tr>
</tbody>
</table>


## Setting up a catalog

After the prerequisites have been met, you can set up a catalog. You can create one catalog that is used by your whole organization. Access to the catalog is controlled by your purchasing policy rules. Alternatively, you can create multiple catalogs that are used by different divisions in your organization.

The following table describes the tasks that must be completed to set up a catalog.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Role</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a new catalog</p></td>
<td><p>Purchasing manager</p></td>
<td><p>When you create a catalog, you specify a name and description for the catalog. You also define how you want to create the navigation structure, define whether the catalog is updated manually or automatically, and specify the catalog owner.</p>
<p>For more information about how to set up a procurement catalog, see <a href="key-tasks-create-procurement-catalogs.md">Key tasks: Create procurement catalogs</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create the navigation categories for the procurement site</p></td>
<td><p>Purchasing manager</p></td>
<td><p>The structure that you define for the navigation categories determines what users see in the navigation pane on your procurement site. You can create the navigation structure manually or by copying your organization's procurement category hierarchy.</p>
<p>Products can be associated with multiple categories so that users can more easily find what they are looking for. For example, power cords for laptop computers can be included in both the computer hardware category and the office supplies category.</p>
<p>For more information about how to set up navigation categories for catalogs, see <a href="key-tasks-create-procurement-catalogs.md">Key tasks: Create procurement catalogs</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Add products to the catalog</p></td>
<td><p>Purchasing manager</p></td>
<td><p>If you use the procurement category hierarchy to create your catalog, products that are associated with those procurement categories are automatically added and mapped to the catalog categories. You can add more products by using the <strong>Products</strong> tab in the <strong>Catalogs</strong> form. Products that are added to the catalog by using the procurement category hierarchy cannot be removed. However, you can hide products that you do not want to appear on your procurement site.</p>
<p>If you manually create your catalog categories, you must manually add the products that you want to appear in each catalog category. Any product that is manually added can be removed from a catalog category.</p>
<p>For more information about how to add products to a procurement catalog, see <a href="key-tasks-create-procurement-catalogs.md">Key tasks: Create procurement catalogs</a>.</p></td>
</tr>
<tr class="even">
<td><p>Add access to external vendor catalog sites (optional)</p></td>
<td><p>Purchasing manager</p></td>
<td><p>If you allow employees to order items and services directly from a vendor, you can add a link to the vendor’s external catalog site to either your procurement categories or selected catalog categories.</p>
<p>For more information about how to set up access to external vendor catalog sites, see <a href="set-up-an-external-vendor-catalog.md">Set up an external vendor catalog</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Publish the catalog to the procurement site</p></td>
<td><p>Purchasing manager or Purchasing agent</p></td>
<td><p>Before a catalog can be displayed on the procurement site, you must define a catalog policy rule for the catalog, set the catalog's status to <strong>Active</strong>, and publish the catalog. You can also inactivate catalogs that you no longer want to be available to your users on the procurement site.</p>
<p>For more information about how to publish a procurement catalog, see <a href="key-tasks-create-procurement-catalogs.md">Key tasks: Create procurement catalogs</a>.</p></td>
</tr>
<tr class="even">
<td><p>Synchronize product search data</p></td>
<td><p>Purchasing manager or Purchasing agent</p></td>
<td><p>To build a more efficient and effective search engine, ensure you synchronize the product search data with Enterprise portal. You must synchronize the product search data with Enterprise portal for every update.</p></td>
</tr>
</tbody>
</table>


## See also

[Key tasks: Create procurement catalogs](key-tasks-create-procurement-catalogs.md)

[Imported vendor catalogs overview](imported-vendor-catalogs-overview.md)

[External vendor catalogs overview](external-vendor-catalogs-overview.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

