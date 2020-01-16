---
title: 'Key tasks: Create procurement catalogs'
TOCTitle: 'Key tasks: Create procurement catalogs'
ms:assetid: 9be99b02-2681-42a0-95d9-c5c558385118
ms:mtpsurl: https://technet.microsoft.com/library/Hh209429(v=AX.60)
ms:contentKeyID: 36058720
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- catalogs
- purchase
- procurement catalog
- procurement catalogs
- catalog
- purchasing
audience: Application User
ms.search.region: Global
---

# Key tasks: Create procurement catalogs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Create and maintain catalogs that company employees can use when they order items and services for internal use. To set up a catalog and make it available to employees, you must complete the following tasks:

  - Determine how you want users to navigate through the catalog on the procurement site.

  - Select the products that users can view and the vendors from whom users can order.

  - If users are permitted to order directly from a vendor, add access to external vendor catalog sites.

  - Activate and publish the catalog, and configure the catalog policy rule so that users can view the catalog on the procurement site.

  - Maintain the catalog by publishing changes to products or catalogs, and adding product images to the catalog.

## What do you want to do?

Learn more about...

Configure the overall catalog settings

Configure individual catalog categories

Copy a catalog

Activate or inactivate a catalog

Preview and publish a catalog

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Procurement catalogs overview](procurement-catalogs-overview.md)

[Imported vendor catalogs overview](imported-vendor-catalogs-overview.md)

[External vendor catalogs overview](external-vendor-catalogs-overview.md)

## Configure the overall catalog settings

Use this procedure to create a new catalog and configure the settings that apply to the whole catalog.

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, on the **Action Pane**, click **Catalog**.

3.  In the **Create catalog** dialog box, enter the catalog name, and then follow one of these steps:
    
      - If you want the navigation structure for your catalog to be created automatically, select the **Populate catalog using procurement category hierarchy:** check box. All products, attributes, and vendors that are assigned to the procurement categories are automatically added to the catalog.
    
      - If you want to create the navigation structure for your catalog manually, clear the **Populate catalog using procurement category hierarchy:** check box. You can then add products, attributes, and vendors to your catalog manually.

4.  In the **Catalogs** form, on the **Action Pane**, on the **Catalog** tab, click **Edit**.

5.  In the left pane, click the catalog's root node. Then, on the **Catalog settings** FastTab, follow these steps:
    
    1.  Enter a description for the catalog.
    
    2.  Select the default update type for the whole catalog. The following options are available:
        
          - **Static** – Manually control product updates to your catalog.
        
          - **Dynamic** – Automatically pass product updates from your product master to your procurement site.
        
          - **Both** – Set the default update type to either **Static** or **Dynamic** for individual categories.

6.  In the **Owner** field, select the catalog owner.

7.  Make sure that the **Catalog status** field is set to **Inactive**. The catalog should have a status of **Inactive** until you are ready to publish it.

8.  In the **Number of search results to display per page** field, enter the maximum number of search results that are displayed per page on the procurement site.

9.  On the **Price range** FastTab, add filters for price ranges. Users can then filter search results by price when they look for products in the catalog on the procurement site.
    

    > [!NOTE]
    > <P>You can also add price range filters for individual categories.</P>



10. On the **Presentations** FastTab, click **Edit**, and then enter the welcome text that you want to appear on the **Order products** site in Enterprise Portal for Microsoft Dynamics AX.

11. On the **Product relation types** FastTab, click **Add**, and then add the product relationships for the products in your catalog. Use the **Move up** and **Move down** buttons to set the order of precedence that is used when search results are displayed.

Back to top

## Configure individual catalog categories

After you configure the settings that apply to the whole catalog, you can configure settings that apply to each catalog category. Before you begin, you can review the catalog's current menu tree and manually add categories to the catalog’s menu tree.

### Review the catalog's navigation hierarchy

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, double-click the catalog that you want to view.

3.  In the **Catalogs** form, in the left pane, select a category, and review the catalog's navigation hierarchy.

### Add a new category to the catalog's menu tree

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, double-click the catalog to which you want to add a category.

3.  In the **Catalogs** form, on the **Action Pane**, on the **Catalog** tab, click **Edit**.

4.  In the left pane, select the parent category to which you want to add the new category.

5.  On the **Action Pane**, on the **Catalog** tab, click **New child**.

6.  On the **Navigation category settings** FastTab, enter a name and description for the new category.


> [!NOTE]
> <P>If you chose to manually set up your catalog navigation structure, you must complete these steps to set up all catalog categories.</P>



### Activate, inactivate, modify, or delete a catalog category

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, double-click the catalog that you want to work with.

3.  In the **Catalogs** form, on the **Action Pane**, on the **Catalog** tab, click **Edit**.

4.  If you want to maintain a category in your procurement catalog, but you do not want the category to be displayed on the procurement site, select the category in the left pane, and then on the **Action Pane**, click **Disable**. When you disable a category, all subcategories that are assigned to the category are also disabled.

5.  To activate a disabled category so that it is displayed on the procurement site, select the category in the left pane, and then on the **Action Pane**, click **Enable**.

6.  To delete a category that you do not want to be displayed on your procurement site, select the category in the left pane, and then on the **Action Pane**, click **Delete**.
    

    > [!NOTE]
    > <P>When you delete the category node, you also delete any child nodes of the category node, and any products that are associated with the nodes.</P>



7.  To modify a category or subcategory, select it in the left pane, and then on the **Navigation category settings** FastTab, enter a new name and description for the category. You can also change the configuration of the categories.

### Configure the navigation category options for each category

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, double-click the catalog that you want to configure.

3.  In the **Catalogs** form, on the **Action Pane**, on the **Catalog** tab, click **Edit**.

4.  If you want the name, description, and all translated text from the procurement category to be used for a catalog category on the procurement site, select the category in the left pane, and then on the **Navigation category settings** FastTab, select the **Map text** check box.
    
    If this check box is selected, updates that are made to these fields appear in the **Catalogs** form. The updates also appear on the procurement site when the catalog is published.
    

    > [!NOTE]
    > <P>This check box is available only when the catalog navigation categories are created automatically from the procurement category hierarchy.</P>



5.  In the **Default update type** field, select one of the following options:
    
      - **Static** – Manually control product updates to the selected category.
    
      - **Dynamic** – Automatically pass product updates for the selected category from the product master to your procurement site.
    

    > [!NOTE]
    > <P>This field is available only if the <STRONG>Default update type</STRONG> field in the <STRONG>Catalog settings</STRONG> FastTab is set to <STRONG>Both</STRONG>.</P>



6.  If the category is only a shortcut category, select the **Shortcut display category** check box.
    
    You can use shortcut categories to display navigational shortcuts for a specific category on the procurement site. You can then display a subcategory of products under multiple parent categories. For example, you can display the subcategory for computer mouse devices under both the category for computer hardware and the category for office supplies.
    
    For more information about how to set up a shortcut category, see the procedure “Set up a shortcut navigation category” in this topic.

7.  In the **Target navigation category** field, select the catalog category that will open when the user clicks the navigation shortcut category on the procurement site.

8.  Select the **Hide all sub-categories** check box to limit the number of navigational procurement categories that appear on the procurement site for the selected category.

9.  Select the **Show order from category** check box if users are permitted to order products from the selected category on the procurement site when they cannot find the product that they want in the catalog.

10. In the **Default browsing page** field, select the page that is displayed by default when the user clicks the category on the procurement site.

### Set up a shortcut navigation category

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, double-click the catalog that you want to configure.

3.  In the **Catalogs** form, on the **Action Pane**, on the **Catalog** tab, click **Edit**.

4.  In the left pane, select the parent category to which you want to add your navigation shortcut.

5.  On the **Action Pane**, on the **Catalog** tab, click **New child**.

6.  On the **Navigation category settings** FastTab, enter a new name and description for the navigation shortcut.

7.  Select the **Shortcut display category** check box.

8.  In the **Target navigation category** field, select the category that you want to open when the user clicks the navigation shortcut on the procurement site.
    

    > [!NOTE]
    > <P>The navigation shortcut appears as a category node in the left pane. However, when the catalog is published, the category node appears as a link on the procurement site.</P>



### Add products to a category

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, double-click the catalog that you want to configure.

3.  In the **Catalogs** form, in the left pane, select the category to which you want to manually add products. Then click the **Products** FastTab.
    

    > [!NOTE]
    > <P>If you used the procurement category hierarchy to create your catalog structure, products that are assigned to the procurement categories are displayed on the <STRONG>Products</STRONG> FastTab.</P>



4.  On the **Products** FastTab, click **Add**.

5.  In the **Add products** form, select the products that you want to add to the category, click **Select -\>**, and then click **OK**.

6.  To modify the details for a selected product, do the following:
    
    1.  On the **Products** FastTab, select a product, and then click **Details**.
    
    2.  In the **Product details** form, on the **Action Pane**, click **Edit**, and then change the details. For example, you can modify the product’s attributes, add related products, and modify the product description.

7.  If you do not want a product to be displayed on the procurement site, follow one of these steps:
    
      - For products that were automatically added to the **Products** FastTab from the procurement category, click **Hide**.
    
      - For products that you added manually to the **Products** FastTab, click **Remove**.

8.  To display a product that was previously hidden on the procurement site, select the product, and then click **Show**. This button can be used only for products that were automatically added to the catalog category from the procurement category.

### Add vendors to a category

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, double-click the catalog that you want to configure.

3.  In the **Catalogs** form, in the left pane, select the category to which you want to manually add vendors, and then click the **Vendors** FastTab.
    

    > [!NOTE]
    > <P>If you used the procurement category hierarchy to create your catalog structure, all vendors that are assigned to the procurement categories are displayed on the <STRONG>Vendors</STRONG> FastTab.</P>



4.  On the **Vendors** FastTab, click **Add**.

5.  In the **Add new vendors** form, select the vendors that you want to add to the category, click **Select -\>**, and then click **OK**.

6.  On the **Vendors** FastTab, click **Details** to view the details for a selected vendor in the **Vendors** form.

7.  If you do not want a vendor to be displayed on the procurement site, follow one of these steps:
    
      - For vendors that were automatically added to the **Vendors** FastTab from the procurement category, click **Hide**.
    
      - For vendors that you added manually to the **Vendors** FastTab, click **Remove**.

8.  To display a vendor that was previously hidden on the procurement site, select the vendor, and then click **Show**. This button can be used only for vendors that were automatically added to the catalog category from the procurement category.

### Add access to external vendor catalogs

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, double-click the catalog that you want to configure.

3.  In the **Catalogs** form, in the left pane, select the category to which you want to manually add access to an external vendor catalog, and then click the **External catalog links** FastTab.
    

    > [!NOTE]
    > <P>If you used the procurement category hierarchy to create your catalog structure, all external vendor catalogs that are assigned to the procurement categories are displayed on the <STRONG>External catalog links</STRONG> FastTab.</P>



4.  On the **External catalog links** FastTab, click **Add**.

5.  In the **Add new external catalog link** form, select the external vendor catalogs that users can access for the category on the procurement site, click **Select -\>**, and then click **OK**.

6.  On the **External catalog links** FastTab, click **Details**. On the **External catalogs** list page, you can modify the configuration settings for the selected external vendor catalog. Any changes that you make to the configuration settings for an external vendor catalog are updated on the procurement site when the catalog updates are published.

7.  If you do not want a link to an external vendor catalog to be displayed on the procurement site, follow one of these steps:
    
      - For external vendor catalog links that were automatically added to the catalog category from the procurement category, click **Hide**
    
      - For external vendor catalog links that you manually added to the **External catalog links** FastTab, click **Remove**.

8.  To display an external vendor catalog link that was previously hidden on the procurement site, click **Show**. This button applies only to external vendor catalog links that were automatically added to the catalog category from the procurement category.

Back to top

 

## Copy a catalog

Use this procedure to create a new catalog by copying an existing catalog. When you copy a catalog, all catalog categories and associated products are copied to the new catalog. You can then modify the new catalog to meet your requirements.


> [!NOTE]
> <P>When you create a new catalog by copying an existing catalog, there is no relationship between the new catalog and the catalog that you copied. The two catalogs are independent of each other.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, select the catalog that you want to copy.

3.  On the **Action Pane**, on the **Catalog** tab, in the **New** group, click **Copy catalog**.

4.  After the new catalog is created, double-click the new catalog to open it. You can then make any changes that are required.

Back to top

## Activate or inactivate a catalog

To make a catalog available on your procurement site, you must activate it and make sure that it is assigned to a catalog policy rule. You can also inactivate any catalogs that you no longer want to be available to your users.

For more information about how to set up catalog policy rules, see [Set up a procurement catalog policy rule](set-up-a-procurement-catalog-policy-rule.md).

### Activate a catalog

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, select the catalog that you want to activate.

3.  On the **Action Pane**, in the **Publish** group, click **Activate catalog**.

### Inactivate a catalog

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, select the catalog that you want to inactivate.

3.  On the **Action Pane**, in the **Publish** group, click **Inactivate catalog**.
    

    > [!NOTE]
    > <P>When a catalog is inactivated, pending transactions that are already in progress, and that include products from the catalog, are processed. Products from the inactivated catalog that are currently in the shopping cart are no longer valid, and the user is notified that the product is no longer available for order.</P>



Back to top

## Preview and publish a catalog

When you create a catalog, you can preview it on the procurement site before you make it available to your employees. Only the catalog owner can preview the catalog.

To make the catalog available to your employees on the procurement site for the first time, you must publish the catalog. After the catalog has been published, any updates that are made to the catalog are published to the procurement site. The updates are published either automatically or manually, depending on the option that is selected for the catalog in the **Default update type** field in the **Catalogs** form. The following default update types are available for catalogs:

  - **Dynamic** – Catalogs are automatically updated whenever a change is made to the catalog.

  - **Static** – Catalogs must be manually updated.

  - **Both** – Catalogs that include product categories that have a default update type of **Static** must be manually updated when these categories are updated. Catalogs that include product categories that have a default update type of **Dynamic** are automatically updated whenever a change is made to the catalog.

Use these procedures to preview your catalog on the procurement site, and to manually update catalogs that have a default update type of **Static**.

### Preview a catalog

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, select the catalog that you want to preview.

3.  On the **Action Pane**, in the **Publish** group, click **Preview catalog**.

The catalog opens in the Employee services portal in Enterprise Portal.

### Publish or update a catalog

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Procurement catalogs**.

2.  On the **Procurement catalogs** list page, double-click the catalog that you want to publish or update.

3.  In the **Catalogs** form, update products, vendors, external catalog links, and other options as necessary.

4.  If your catalog has a status of **Inactive**, on the **Action Pane**, in the **Publish** group, click **Activate catalog**.

5.  On the **Action Pane**, in the **Publish** group, click **Publish catalog**.

View your catalog, and verify the catalog data in the Employee services portal in Enterprise Portal.

Back to top

## Find form help

[Catalogs (form)](https://technet.microsoft.com/library/hh209683\(v=ax.60\))

[Procurement catalogs (list page)](https://technet.microsoft.com/library/hh227514\(v=ax.60\))

[Add new external catalog link (form)](https://technet.microsoft.com/library/hh227381\(v=ax.60\))

[Add new vendors (form)](https://technet.microsoft.com/library/hh209492\(v=ax.60\))

[Add products (form)](https://technet.microsoft.com/library/hh208984\(v=ax.60\))

## Find related tasks

[Set up product relationship types](set-up-product-relationship-types.md)

[Import a catalog from a vendor](import-a-catalog-from-a-vendor.md)

[Set up an external vendor catalog](set-up-an-external-vendor-catalog.md)

  


