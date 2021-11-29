---
title: Set up a retail hierarchy
TOCTitle: Set up a retail hierarchy
ms:assetid: 2851f267-1356-414d-a333-2670885ae512
ms:mtpsurl: https://technet.microsoft.com/library/Hh580593(v=AX.60)
ms:contentKeyID: 39519077
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- channel navigation
- channel navigation hierarchy
- retail hierarchies
- navigation hierarchy
- retail hierarchy
audience: Application User
ms.search.region: Global
---

# Set up a retail hierarchy 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You can create a product hierarchy to organize the products that you sell through your retail channels. You can use product hierarchies to group products that are used to create product assortments. You can also use retail product hierarchies for customer loyalty programs, and to assign product attributes and properties.

When you create a retail product hierarchy, you must assign a category hierarchy type to identify the purpose of the category hierarchy. You can create one category hierarchy to represent all products and categories in your organization, and then use that category hierarchy for multiple purposes. Alternatively, you can create multiple category hierarchies for special purposes, such as product promotions.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3. See the section later in this topic.</P>



## Set up a category hierarchy and assign a hierarchy type

Before you can add products and product attributes to the retail product hierarchy, you must create the base category structure, and then assign a category type to the category hierarchy. After you create the hierarchy structure, you can add products and complete the hierarchy setup from the **Retail** area page.

1.  Click **Product information management** \> **Setup** \> **Categories** \> **Category hierarchies**. On the **Category hierarchies** list page, on the **Action Pane**, click **Category hierarchy**.

2.  In the **Create a category hierarchy** form, enter a unique name and an optional description for the hierarchy, and then click **Create**. By default, the **Active** status of the new category hierarchy is set to **Yes**.

3.  In the **Category hierarchy** form, on the **Action Pane**, click **New category node** to add the parent and child categories that you use to categorize your products. The first category that you create for a new category hierarchy is always the parent category of all other categories in the hierarchy. Add as many categories and subcategories as your organization requires.

4.  Depending on your version of the program, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R2: On the **Category attribute groups** FastTab, click **Add** to assign attribute groups to the category. Click **View attributes** to view the list of attributes that are included in the attribute group.
        

        > [!IMPORTANT]
        > <P>You can assign attribute groups to a category only if the category hierarchy has been assigned to a category type of <STRONG>Retail product hierarchy</STRONG>, <STRONG>Supplemental retail hierarchy</STRONG>, <STRONG>Retail vendor product hierarchy</STRONG> or <STRONG>Retail channel navigation hierarchy</STRONG>.</P>

    
      - Otherwise, on the **Category attributes** FastTab, click **Add** to assign attributes to the category.

5.  On the **Commodity codes** FastTab, add subcategories from a file that contains imported commodity codes. For more information about how to import commodity codes, see [Import categories (form)](https://technet.microsoft.com/library/hh242810\(v=ax.60\)).

6.  After you finish setting up the category hierarchy, click **Close** to save the category hierarchy and return to the **Category hierarchies** list page.

7.  On the **Category hierarchies** list page, select the retail product hierarchy that you created, and then, on the **Action Pane**, in the **Set up** group, click **Associate hierarchy type**.

8.  In the **Category hierarchy types** form, click **New** to add a new row.

9.  In the **Category hierarchy type** field, select one of the following types of category hierarchy:
    
      - **Retail product hierarchy** – Select this hierarchy type to create the main retail product hierarchy for your organization. You can assign this category type to only one category hierarchy.
    
      - **Supplemental retail hierarchy** – Select this hierarchy type to create an additional retail product hierarchy. For example, you can use supplemental hierarchies for special pricing and promotions or for loyalty programs. You can create as many retail supplemental hierarchies as you require. You do not have to create retail supplemental hierarchies.
    
      - **Retail vendor product hierarchy** – Select this hierarchy type if you import product data from retail vendors, and you have received a product category hierarchy from a vendor. You can create as many retail vendor product hierarchies as you require. You do not have to create retail vendor product hierarchies.
    
      - **Retail channel navigation hierarchy** – Select this hierarchy type to use the category hierarchy as the navigation structure for your online store catalog.
        

        > [!NOTE]
        > <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>



10. In the **Category hierarchy** field, select the category hierarchy to assign to the selected category hierarchy type.

For more information about the fields in the **Category hierarchy** form, see [Category hierarchy (form)](https://technet.microsoft.com/library/hh209524\(v=ax.60\)).

## Maintain the retail product hierarchy

After you create the structure of the retail product hierarchy, you can assign products to the individual categories and subcategories. You can also assign retail-specific attributes and basic product attributes at the category level.

1.  Click **Retail** \> **Setup** \> **Category hierarchies** \> **Retail product hierarchy**.

2.  In the **Retail product hierarchy** form, in the left pane, review the tree structure of product categories. On the **General** FastTab, view the name, friendly name, status, and other details about the category.

3.  Click **Edit category hierarchy** to open the **Category hierarchy** form, and then modify the structure of the category hierarchy.

4.  In the left pane, select a category in the tree structure. Then, on the **Products** FastTab, click **Add** to add one or more products from the organization-wide product list. Alternatively, click **Add products** to open the **Add products** form, and then add one or more products to a selected category. If you use the **Add products** form to add products to the category, you can select products from any category hierarchy.

5.  On the **Retail product properties** FastTab, enter default settings for the retail product properties. These settings are automatically inherited by all products that are assigned to the category. However, you can override the settings for an individual product.

6.  On the **Basic product properties** FastTab, enter settings for the base product properties. These settings are automatically inherited by all products that are assigned to the category, across one or more legal entities. However, you can override the settings for an individual product.

7.  On the **Product attributes** FastTab, add other attributes to the products in the hierarchy.

8.  On the **Map vendor categories** FastTab, map the vendor’s product categories to the retail product categories in which the vendor is authorized to supply products.

9.  On the **Category attribute values** FastTab, view values for the category attributes.
    
    You add category attributes in the **Category hierarchy** form. For more information, see [Category hierarchy (form)](https://technet.microsoft.com/library/hh209524\(v=ax.60\)).

## Maintain a retail supplemental hierarchy

Use supplemental hierarchies to categorize a subset of products for a specific purpose, such as special pricing, promotions, or special product discounts. You can create as many retail supplemental hierarchies as you require. You cannot set retail product properties or basic product properties in a retail supplemental hierarchy.

1.  Click **Retail** \> **Setup** \> **Category hierarchies** \> **Supplemental retail hierarchies**.

2.  On the **Supplemental retail hierarchies** list page, on the **Action Pane**, in the **New** group, click **Category hierarchy** to create a new category hierarchy. To modify an existing category hierarchy, double-click the hierarchy in the list.

3.  Click **Edit category hierarchy** to open the **Category hierarchy** form, and then modify the structure of the category hierarchy.

4.  In the left pane, select a category in the tree structure. Then, on the **Products** FastTab, click **Add** to add one product at a time from the organization-wide product list. Alternatively, click **Add products** to open the **Add products** form, and then add one or more products or product variants to a selected category. If you use the **Add products** form to add products to the category, you can select products from any product hierarchy.

5.  On the **Product attributes** FastTab, add other attributes to the products in the hierarchy.

6.  On the **Map vendor categories** FastTab, map the vendor’s product categories to the supplemental retail categories in which the vendor is authorized to supply products.

7.  On the **Category attribute values** FastTab, view values for the category attributes.
    
    You add category attributes in the **Category hierarchy** form. For more information, see [Category hierarchy (form)](https://technet.microsoft.com/library/hh209524\(v=ax.60\)).

## New or changed for Microsoft Dynamics AX 2012 R2

In Microsoft Dynamics AX 2012 R2, you can create a navigation category hierarchy for a retail channel that can be used to set up a category structure for products that you offer through an online store. You define the category hierarchy, and then assign products, product attribute groups, and attribute values to the categories. Then, assign the category hierarchy to an online store. When the online store is published, the category structure that is defined in the category hierarchy is displayed in the online store.

If you change a category in a navigation category hierarchy that is assigned to a retail channel or a retail product catalog, you must follow these additional steps:

  - If you add or delete a category node, republish the channel and the catalog that use the category hierarchy.

  - If you activate or inactivate a category, republish the channel and the catalog that use the category hierarchy.

  - If you change the name of a category, republish the channel that uses the category hierarchy.


> [!NOTE]
> <P>Before you can publish an online store, you must create a navigation category hierarchy for a retail channel and assign it to the online store. For more information about how to set up an online store, see <A href="set-up-an-online-store.md">Set up an online store</A>.</P>



### Maintain a retail channel navigation hierarchy

1.  Click **Retail** \> **Setup** \> **Category hierarchies** \> **Retail channel navigation hierarchies**.

2.  On the **Retail channel navigation hierarchies** list page, on the **Action Pane**, in the **New** group, click **Category hierarchy** to create a new channel navigation hierarchy and enter a name and description for the category hierarchy. To modify an existing category hierarchy, select the category hierarchy in the list.

3.  Click **Edit** to open the **Category hierarchy** form, and then modify the structure of the category hierarchy.

4.  In the left pane, select a category in the tree structure. Then, on the **Products** FastTab, click **Add** to add one product at a time from the products list. Alternatively, click **Add products** to open the **Add products** form, and then add one or more products to a selected category. If you use the **Add products** form to add products to the category, you can select products from any retail product hierarchy or supplemental hierarchy.

5.  On the **Product attribute groups** FastTab, click **Add** to assign attribute groups to the category.

6.  Click **View attributes** to view the list of attributes that are included in the attribute group.

7.  Close the **Category hierarchy** form.

### Add presentation text, images, or videos to a category hierarchy or specific categories

1.  On the **Retail channel navigation hierarchies** list page, double-click a category hierarchy.

2.  In the left pane, select the root node or a specific category node.

3.  Click **Edit presentation text** to open the **Catalog product presentation** form, and then click **Edit** to enter your text.
    
    You can add presentation text to add category data that shoppers can see when they browse in the online store.

4.  Click **Images** to open the **Images** form, and then enter the URL for where the image is stored. You can also view the images that you already added and select one image to be the default image. The default image is displayed for the category in the online store.

5.  Click **Videos** to open the **Videos** form, and then enter the URL for where the video is located. You can also view the videos that you already added and select one video to be the default video. The default video is displayed for the category in the online store

## See also

[About retail hierarchies](about-retail-hierarchies.md)

[Retail product hierarchy (form)](https://technet.microsoft.com/library/hh597208\(v=ax.60\))

[Supplemental retail hierarchies (form)](https://technet.microsoft.com/library/hh597337\(v=ax.60\))

[Set up a retail vendor hierarchy](set-up-a-retail-vendor-hierarchy.md)

[Set up retail attribute groups](set-up-retail-attribute-groups.md)

[Category hierarchy (form)](https://technet.microsoft.com/library/hh209524\(v=ax.60\))

[Set up an online store](set-up-an-online-store.md)

  


