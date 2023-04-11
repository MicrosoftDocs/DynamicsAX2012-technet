---
title: 'Key tasks: Set up a category hierarchy'
TOCTitle: 'Key tasks: Set up a category hierarchy'
ms:assetid: 4612aa8c-96b2-4d9e-8b85-3f1bbf0b62bb
ms:mtpsurl: https://technet.microsoft.com/library/Hh242386(v=AX.60)
ms:contentKeyID: 36056900
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- category
- category hierarchy
- create category
- new category
audience: Application User
ms.search.region: Global
---

# Key tasks: Set up a category hierarchy 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Category hierarchies are used to classify products, vendors, and other data for reporting and analysis. Each hierarchy consists of a parent category and a structure of subcategories, which are also named the child categories. An organization may have more than one category hierarchy. For example, there may be a category hierarchy of commodity codes that are used for sales, and another category hierarchy for categorizing procurement activities. You can import commodity codes from a standard industry classification system, or you can manually create a category hierarchy to meet the business requirements for your organization.

## What do you want to do?

Learn more about...

Set up a category hierarchy

Assign a category hierarchy type

Manually add categories to a hierarchy

Delete or inactivate a category

Activate a category

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About category hierarchies](about-category-hierarchies.md)

## Set up a category hierarchy

Use this procedure to create a category hierarchy and set up the parent category. After you create the parent category, you can create child categories manually or you can import categories.


> [!NOTE]
> <P><STRONG>Category hierarchy</STRONG> cannot be changed by changing the company in the <STRONG>Buying legal entity</STRONG> field because <STRONG>Category hierarchy</STRONG> extends across all companies. If you add a node to the <STRONG>Category hierarchy</STRONG>, that node will be visible to all companies because the <STRONG>Category hierarchy</STRONG> is not company-dependent. The information on the FastTabs beneath <STRONG>Buying legal entity</STRONG>, all display information that relates to that specific company in the <STRONG>Buying legal entity</STRONG> field.</P>



1.  Click **Product information management** \> **Setup** \> **Categories** \> **Category hierarchies**. On the **Action Pane**, click **Category hierarchy**.

2.  In the **Create a category hierarchy** form, enter a unique name and an optional description in the form, and then click **Create**. By default, a new category hierarchy is set to **Active** status.

3.  In the **Category hierarchy** form, on the **Action Pane**, click **New category node**.
    

    > [!IMPORTANT]
    > <P>The first category that you create for a new category hierarchy is always the parent category of all other categories in the hierarchy.</P>



4.  On the **General** FastTab, enter a name and optional commodity code for the category.

5.  Select the **Classify as tangible product** check box to indicate that products that are assigned to the category are tangible items only, not services.

6.  In the **Description** field, enter a detailed description of the category that helps employees understand the purpose of the category. This description is displayed in a tooltip when the category is selected in a transaction.

7.  In the **Friendly name** field, enter an optional short name for the category.

8.  In the **Keywords** field, enter words to help identify this category in a search of category names in Enterprise Portal for Microsoft Dynamics AX. You can enter multiple keywords separated by a colon or semicolon.

9.  On the **Category attributes** FastTab, click **Add** to assign attributes to the category. For example, you assign an attribute of **Manager** to a category. The data type for this attribute is **Text**. For each category, you enter the name of a category manager as the value for this attribute. For information about how to create category attributes, see [Set up attributes and attribute types](set-up-attributes-and-attribute-types.md).

10. On the **Commodity codes** FastTab, add subcategories from imported commodity codes. For information about imported commodity codes, see [Import categories (form)](https://technet.microsoft.com/library/hh242810\(v=ax.60\)).

11. On the **Assign project categories** FastTab, select a project category as the default category that is associated with the selected project category.
    

    > [!NOTE]
    > <P>The <STRONG>Assign project categories</STRONG> FastTab is only available for procurement and sales category hierarchy types. For more information about category hierarchy types, see <A href="https://technet.microsoft.com/library/hh227389(v=ax.60)">Category hierarchy types (form)</A>.</P>



Back to top

## Assign a category hierarchy type

Use this procedure to assign a type to a category hierarchy. The type that you assign determines how the category hierarchy appears in Microsoft Dynamics AX. For example, if you assign the procurement category type to a hierarchy, the products from this procurement category hierarchy are displayed in procurement forms such as requests for quotations and purchase requisitions.

You can assign more than one type to the same category hierarchy. For example, use the same category hierarchy for sales and procurement activities and for products.

1.  Click **Product information management** \> **Setup** \> **Categories** \> **Category hierarchy types**.

2.  In the **Category hierarchy types** form, click **New**.

3.  In the **Category hierarchy type** field, select a hierarchy type.

4.  In the **Category hierarchy** field, select a category hierarchy.

Back to top

## Manually add categories to a hierarchy

Use these procedures to manually add categories to a category hierarchy. You must create the parent category before you can add other categories to a category hierarchy. After you create the parent category, you can use this procedure to add child categories.

1.  Click **Product information management** \> **Setup** \> **Categories** \> **Category hierarchies**.

2.  On the **Category hierarchies** list page, select the category hierarchy that you want to add child categories to, and then on the **Action Pane**, click **Edit**.

3.  In the **Category hierarchy** form, in the left pane, click the name of the category to which you want to add a child category.

4.  On the **Action Pane**, click **New category node**.

5.  On the **General** FastTab, enter a name and optional commodity code for the category.

6.  Select the **Classify as tangible product** check box to indicate that products assigned to the category are tangible items only, not services.

7.  In the **Description** field, enter a detailed description of the category that helps employees understand the purpose of the category. This description is displayed in a tooltip when the category is selected in a transaction.

8.  In the **Friendly name** field, enter an optional short name for the category.

9.  In the **Keywords** field, enter words to help identify this category in a search of category names in Enterprise Portal for Microsoft Dynamics AX. You can add multiple keywords separated by colons or semicolons.

10. On the **Category attributes** FastTab, click **Add** to assign attributes to the category. Alternatively, select the **Inherit category attributes from parent category:** check box to assign the same attributes to a category that you assign to the parent of the category.

11. On the **Commodity codes** FastTab, add commodity codes from the list of imported commodity codes. For information about how to import commodity codes, see [Import categories (form)](https://technet.microsoft.com/library/hh242810\(v=ax.60\)).

12. On the **Assign project categories** FastTab, select a project category as the default category that is associated with the selected project category.
    

    > [!NOTE]
    > <P>The <STRONG>Assign project categories</STRONG> FastTab is only available for procurement and sales category hierarchy types. For more information about category hierarchy types, see <A href="https://technet.microsoft.com/library/hh227389(v=ax.60)">Category hierarchy types (form)</A>.</P>



Back to top

## Delete or inactivate a category

Use these procedures to delete or inactivate a category in a category hierarchy. You can delete a category only if there are no records, such as commodity codes, products, or transactions, that reference the category. If records are associated with a category, you can inactivate the category to make the category unavailable for transactions.

When you delete a category that has child categories, the child categories are also deleted. When you inactivate a category that has child categories, the child categories are also inactivated.

1.  Click **Product information management** \> **Setup** \> **Categories** \> **Category hierarchies**. Open the category hierarchy that contains the category that you want to delete.

2.  In the **Category hierarchy** form, in the left pane, click the name of the category that you want to delete.

3.  On the **Action Pane**, click **Delete**, and then confirm the deletion.

4.  If records are associated with the category, an error message will be displayed. To make the category unavailable for other records, click **Inactivate** on the **Action Pane**. The records that are already associated with the category retain the association with the category.

Back to top

## Activate a category

Use these procedures to activate a category in a category hierarchy to make the category available for transactions. When you activate a category that has child categories, you can activate only the category, or you can activate both the category and all its child categories. If you activate a child category, any inactive parent categories that are associated with the child category are also automatically activated.

1.  Click **Product information management** \> **Setup** \> **Categories** \> **Category hierarchies**.

2.  On the **Category hierarchies** list page, open the category hierarchy that contains the category that you want to activate.

3.  In the **Category hierarchy** form, in the left pane, click the name of the category that you want to activate.

4.  On the **Action Pane**, click **Activate**, and then confirm the activation.

Back to top

## Find form help

[Category hierarchy (form)](https://technet.microsoft.com/library/hh209524\(v=ax.60\))

[Category hierarchy types (form)](https://technet.microsoft.com/library/hh227389\(v=ax.60\))

[Procurement categories (form)](https://technet.microsoft.com/library/hh227365\(v=ax.60\))

## Find related tasks

[Key tasks: Set up and maintain procurement category hierarchies](key-tasks-set-up-and-maintain-procurement-category-hierarchies.md)

  


