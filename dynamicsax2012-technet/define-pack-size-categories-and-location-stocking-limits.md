---
title: Define pack size categories and location stocking limits
TOCTitle: Define pack size categories and location stocking limits
ms:assetid: f36c836e-799b-4ace-b3b6-190d6967b9b7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553212(v=AX.60)
ms:contentKeyID: 62200187
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.WHSLocationLimit
- Forms.WHSPackSizeCategory
- location stocking limit
- location stocking limits
- pack size categories
- pack size category
---

# Define pack size categories and location stocking limits [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



Use this topic to create pack size categories and associate the pack size categories with one or more location stocking limits. You can also associate a pack size category directly with a specific item. Based on the stocking limit and pack size category settings for a location, you can determine the storage capacity of a warehouse.

## Create a pack size category

To create a pack size category, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Pack size categories**.

2.  Click **New** to create a new pack size category.

3.  Enter a unique identifier (ID) and descriptive name for the pack size category.

## Define location stocking limits

To define location stocking limits, follow these steps:


> [!NOTE]
> <P>If you’re running Microsoft Dynamics AX 2012 R3 Cumulative Update 8, you can also define location stocking limits for product variants. The <STRONG>Location stocking limits</STRONG> form has been divided into two tabs: one for <STRONG>Products</STRONG>, and one for <STRONG>Product variants</STRONG>. You set up location stocking limits for product variants the same way as for products, but with one small difference. When you set up location stocking limits for product variants, you need to enter the appropriate dimensions for the variants. The dimensions are configuration, size, and color.</P>



1.  Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Location stocking limits**.

2.  Click **New** to create a new location stocking limit.

3.  In the **Warehouse** field, select the warehouse for which you want to define stocking limits.

4.  Select a location ID or a location profile ID.

5.  Select a pack size category ID or an item number. You can associate a pack size category ID with an item in the **Released product details** form on the **Warehouse management** FastTab.

6.  Select the **Allow unlimited quantity** check box to indicate that the location quantity is unlimited. If this check box is cleared, you need to specify the unit and quantity of the item to be stocked in the location.

7.  In the **Unit** field, select a unit of measure for the item that you are defining stocking limits for. If you don’t select a unit of measure, the quantity that you validate against is the item’s inventory unit.

8.  In the **Quantity** field, enter the quantity for the stocking limit in the selected unit of measure.

## Assign inventory items to a pack size category

To assign inventory items to a pack size category, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select a product, and then click **Edit**.

3.  In the **Released product details** form, expand the **Warehouse management** FastTab.

4.  In the **Pack size category ID** field, select a pack size category ID.

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

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

