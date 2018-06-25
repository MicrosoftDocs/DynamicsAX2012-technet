---
title: Set up a retail product hierarchy (Retail essentials)
TOCTitle: Set up a retail product hierarchy (Retail essentials)
ms:assetid: ce122d50-a117-4d51-a218-a20f9255a5e7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736953(v=AX.60)
ms:contentKeyID: 62200430
ms.date: 08/15/2014
mtps_version: v=AX.60
f1_keywords:
- MsDynAx060.Forms.EcoResCategoryHierarchyListPage
---

# Set up a retail product hierarchy (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up a retail product category hierarchy. You can create a category hierarchy to organize the products that you sell through your retail channels. You can use category hierarchies to group products that are used to create product assortments. You can also use a hierarchy for customer loyalty programs, and to assign product attributes and properties.

You can create one category hierarchy to represent all products and categories in your organization, and then use that category hierarchy for multiple purposes. Alternatively, you can create multiple category hierarchies for special purposes, such as product promotions.

## Set up a retail category hierarchy

Before you can add products and product attributes to the retail product hierarchy, you must create the base category structure. After you create the hierarchy structure, you can add products and complete the hierarchy setup.

1.  Click **Retail essentials** \> **Merchandising** \> **Category hierarchies** \> **Supplemental retail hierarchies**. On the **Supplemental retail hierarchies** list page, on the **Action Pane**, click **Category hierarchy**.

2.  In the **Create a category hierarchy** form, enter a unique name and an optional description for the hierarchy, and then click **Create**.

3.  In the **Category hierarchy** form, on the **Action Pane**, click **New category node** to add the parent and child categories that you use to categorize your products. The first category that you create for a new category hierarchy is always the parent category of all other categories in the hierarchy. Add as many categories and subcategories as your organization requires.

4.  To assign attribute groups to the category, select the category, and then, on the **Category attribute groups** FastTab, click **Add**.

5.  In the **Category attribute groups** form, in the **Attribute groups:** section, select one or more attribute groups, and then click **Select -\>**. When you click an attribute group to select it, the attributes that are included in the attribute group are displayed in the **Attributes:** section. To add the attribute group to the selected category, click **OK**.

6.  In the **Category hierarchy** form, on the **Category attribute groups** FastTab, click **View attributes** to view the list of attributes that are included in an attribute group.

7.  After you finish setting up the category hierarchy, click **Close** to save the category hierarchy and return to the **Supplemental retail hierarchies** list page.

For more information about the fields in the **Supplemental retail hierarchy** form, see [Supplemental retail hierarchies (form)](https://technet.microsoft.com/en-us/library/hh597337\(v=ax.60\)).

## Maintain the retail product hierarchy

After you create the structure of a retail product hierarchy, you can assign products to its categories and subcategories. You can also assign retail-specific attributes and basic product attributes at the category level.

1.  Click **Retail essentials** \> **Merchandising** \> **Category hierarchies** \> **Retail product hierarchy**.

2.  In the **Retail product hierarchy** form, in the left pane, review the tree structure of the product category hierarchy. Select a category, and then, on the **General** FastTab, view the name, friendly name, status, and other details about the category.

3.  To modify the product attributes for a category, select the category, and then click **Edit category hierarchy**. In the **Category hierarchy** form, modify the product categories, and then click **Close**.

4.  Add one or more products from the organization-wide product list to a category. In the **Retail product hierarchy** form, in the left pane, select a category in the tree structure. Then, on the **Products** FastTab, click **Add**. Alternatively, click **Add products** to open the **Add products** form, and then add one or more products to a selected category. If you use the **Add products** form to add products to the category, you can select products from any category hierarchy.

5.  On the **Retail product properties** FastTab, enter default settings for the retail product properties. These settings are automatically inherited by all products that are assigned to the category. However, you can override the settings for an individual product.

6.  On the **Basic product properties** FastTab, enter settings for the base product properties. These settings are automatically inherited by all products that are assigned to the category, across one or more legal entities. However, you can override the settings for an individual product.

7.  On the **Product attribute groups** FastTab, add other attributes to the products in the hierarchy.

8.  On the **Map vendor categories** FastTab, map the vendor’s product categories to the retail product categories in which the vendor is authorized to supply products.

9.  On the **Category attribute values** FastTab, view values for the category attributes.
    
    You add category attributes in the **Category hierarchy** form. For more information, see [Category hierarchy (form)](https://technet.microsoft.com/en-us/library/hh209524\(v=ax.60\)).

## Maintain a supplemental retail hierarchy

Use supplemental hierarchies to categorize a subset of products for a specific purpose, such as special pricing, promotions, or special product discounts. You can create as many retail supplemental hierarchies as you require. You cannot set retail product properties or basic product properties in a supplemental retail hierarchy.

To modify a supplemental retail hierarchy, follow these steps:

1.  Click **Retail essentials** \> **Merchandising** \> **Category hierarchies** \> **Supplemental retail hierarchies**.

2.  On the **Supplemental retail hierarchies** list page, double-click the hierarchy to open it.

3.  Click **Edit category hierarchy** to enable modifications to the **Category hierarchy** form, and then modify the structure of the category hierarchy.

4.  In the left pane, select a category in the tree structure. Then, on the **Products** FastTab, click **Add** to add one product at a time from the organization-wide product list. Alternatively, click **Add products** to open the **Add products** form, and then add one or more products to a selected category. If you use the **Add products** form to add products to the category, you can select products from any category hierarchy.

5.  On the **Product attribute groups** FastTab, add other attributes to the products in the selected category.

6.  On the **Map vendor categories** FastTab, map the vendor’s product categories to the supplemental retail categories in which the vendor is authorized to supply products.

7.  On the **Category attribute values** FastTab, view values for the category attributes.
    
    You add category attributes in the **Category hierarchy** form. For more information, see [Category hierarchy (form)](https://technet.microsoft.com/en-us/library/hh209524\(v=ax.60\)).

## See also

[About retail hierarchies (Retail essentials)](about-retail-hierarchies-retail-essentials.md)

[Retail hierarchy (Retail essentials)](retail-hierarchy-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

