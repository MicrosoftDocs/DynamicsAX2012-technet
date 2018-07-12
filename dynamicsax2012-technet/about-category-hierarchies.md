---
title: About category hierarchies
TOCTitle: About category hierarchies
ms:assetid: 986653ff-6db6-4eaf-9eb6-b907015a4890
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209418(v=AX.60)
ms:contentKeyID: 36058678
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- category hierarchy
- procurement category
---

# About category hierarchies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains what category hierarchies are and the advantages of using a category hierarchy for procurement versus using a product. Category hierarchies are used to classify products or transactions for reporting and analysis. An organization can create more than one category hierarchy. For example, your organization might create one category hierarchy for classifying products that it buys, and another hierarchy for products that it sells. The number of category hierarchies that your organization uses, and the structure and number of subcategories in each category hierarchy, depend on the reporting needs of your organization.

There are several industry-standard classification systems and commodity code systems for reporting to government agencies or industry organizations. Some of the more common examples are Intrastat, UNSPSC, NAICS, eCl@ss, eOTD, and NIGP. Your system administrator can import all or part of an external classification system into Microsoft Dynamics AX. You can also manually create the categories and commodity codes. For more information about how to import categories and commodity codes, see [Import categories (form)](https://technet.microsoft.com/en-us/library/hh242810\(v=ax.60\)).

After you create a category hierarchy, assign a type to the category hierarchy. The type determines how the category hierarchy appears in Microsoft Dynamics AX. For example, when you assign the **Procurement category hierarchy** type to a hierarchy, the products from this procurement category hierarchy are displayed in procurement forms such as requests for quotations and purchase requisitions.

The following table lists the available category hierarchy types and the general purpose of each type.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category hierarchy type</p></th>
<th><p>Purpose</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Procurement category hierarchy</strong></p></td>
<td><p>Use for procurement catalogs and purchasing activities. Only one active procurement category hierarchy can be defined for an organization.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales category hierarchy</strong></p></td>
<td><p>Use for organizing products for sales activities. Only one active sales category hierarchy can be defined for an organization.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Commodity code hierarchy</strong></p></td>
<td><p>Use for compliance with industry standards and government reporting requirements.</p></td>
</tr>
<tr class="even">
<td><p><strong>Derived financial hierarchy</strong></p></td>
<td><p>Use for organizing financial categories that can be derived from financial dimensions.</p>
  
> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>

</td>
</tr>
</tbody>
</table>


When you create a category hierarchy, you can assign attributes to categories to define characteristics of the category. An example of a category attribute is **Category manager**. When you assign this attribute to a category, you enter the name of the person to contact about products or other items that are assigned to the category.

When you create a procurement category hierarchy, you can assign vendors, products, product attributes, policies, and other parameters to each procurement category. For more information about procurement category hierarchies, see [Procurement categories (form)](https://technet.microsoft.com/en-us/library/hh227365\(v=ax.60\)).

## Advantages of using category hierarchies for procurement versus using products

You can use categories, products, or both for procurement. To decide what to use, consider whether the product is for internal use or for resale; if you need hierarchical reporting for procurement and sales, retail, commodity codes, or derived financial hierarchies; whether the products will be used in manufacturing, and inventory reporting requirements. You should also be aware of differences in how categories and products are processed on purchase order lines and sales order lines, and how they work with two-way and three-way matching policies.

Refer to the following table to help you decide whether to use category hierarchies or products for different situations.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Consideration</p></th>
<th><p>Category hierarchy</p></th>
<th><p>Product</p></th>
<th><p>Notes</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Internal use</p></td>
<td><p>X</p></td>
<td><p></p></td>
<td><p>Categories provide a simpler way to track procurement of goods and services that are used by your organization for internal use. This is the most common reason to use category hierarchies.</p></td>
</tr>
<tr class="even">
<td><p>Hierarchical organization of products</p></td>
<td><p>X</p></td>
<td><p></p></td>
<td><p>For category hierarchies, you can report on upper levels of the hierarchies, and also lower levels. For more information, see <a href="categories-report-proccategory.md">Categories report (ProcCategory)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Procurement and sales</p></td>
<td><p>X</p></td>
<td><p>X</p></td>
<td><p>You can create a category hierarchy for procurement and a category hierarchy for sales, and you can copy categories and commodity codes from one to the other. For more information, see <a href="key-tasks-set-up-and-maintain-procurement-category-hierarchies.md">Key tasks: Set up and maintain procurement category hierarchies</a>.</p>
<p>You can use products for both procurement and for sales. For more information, see <a href="working-with-inventory-management.md">Working with Inventory management</a>.</p></td>
</tr>
<tr class="even">
<td><p>Retail</p></td>
<td><p>X</p></td>
<td><p></p></td>
<td><p>You can create retail category hierarchies. For more information, see <a href="about-retail-hierarchies.md">About retail hierarchies</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Public sector</p></td>
<td><p>X</p></td>
<td><p></p></td>
<td><p>You can create a financial category hierarchy that is derived. For more information, see <a href="set-up-derived-financial-hierarchies-public-sector.md">Set up derived financial hierarchies (Public sector)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Commodity codes</p></td>
<td><p>X</p></td>
<td><p>X</p></td>
<td><p>For category hierarchies, you can import a commodity code hierarchy. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh242810(v=ax.60)">Import categories (form)</a>.</p>
<p>For products, you can assign commodity codes to products. For more information, see <a href="setting-up-and-maintaining-items.md">Setting up and maintaining items</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Commodity codes on purchase orders and sales orders</p></td>
<td><p>X</p></td>
<td><p>X</p></td>
<td><p>For categories, you can enter commodity codes on purchase order lines and sales order lines. For products, the commodity codes on purchase order lines and sales order lines are taken from the item record. For more information, see <a href="http://blogs.msdn.com/b/axsupport/archive/2012/12/21/dynamics-ax-2012-a-common-misconception-about-commodity-codes.aspx">A common misconception about Commodity Codes</a>.</p></td>
</tr>
<tr class="even">
<td><p>Invoice matching policies for two-way and three-way matching</p></td>
<td><p>X</p></td>
<td><p>X</p></td>
<td><p>For category hierarchies, you assign matching policies to each hierarchy level. For more information, see <a href="set-up-policies-for-category-hierarchies.md">Set up policies for category hierarchies</a>.</p>
<p>For products, you assign matching policies to items, item groups, vendors, vendor groups, or vendor-item combinations. For more information, see <a href="set-up-accounts-payable-invoice-matching.md">Set up Accounts payable invoice matching</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Inventory reporting</p></td>
<td><p></p></td>
<td><p>X</p></td>
<td><p>Inventory products support a wider range of inventory reports. For more information, see <a href="inventory-and-warehouse-management-reports.md">Inventory and warehouse management reports</a>.</p></td>
</tr>
<tr class="even">
<td><p>Manufacturing</p></td>
<td><p></p></td>
<td><p>X</p></td>
<td><p>Products provide better tracking of manufacturing-related data than categories do. For more information, see <a href="product-information-management.md">Product information management</a>, <a href="master-planning.md">Master planning</a>, and <a href="production-control.md">Production control</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Multiple legal entities</p></td>
<td><p></p></td>
<td><p>X</p></td>
<td><p>For category hierarchies, you can create different hierarchies for each legal entity. You can import hierarchies from one legal entity to another. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh242810(v=ax.60)">Import categories (form)</a>.</p>
<p>For products, you can create products and release them to all the legal entities that use the same products. For more information, see <a href="setting-up-and-maintaining-products.md">Setting up and maintaining products</a>.</p></td>
</tr>
</tbody>
</table>


## See also

[Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md)

[Key tasks: Set up and maintain procurement category hierarchies](key-tasks-set-up-and-maintain-procurement-category-hierarchies.md)

[Category hierarchy (form)](https://technet.microsoft.com/en-us/library/hh209524\(v=ax.60\))

[Category hierarchy types (form)](https://technet.microsoft.com/en-us/library/hh227389\(v=ax.60\))

[Set up policies for category hierarchies](set-up-policies-for-category-hierarchies.md)

[Procurement categories (form)](https://technet.microsoft.com/en-us/library/hh227365\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

