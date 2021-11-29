---
title: 'Key tasks: Order items and services from a catalog'
TOCTitle: 'Key tasks: Order items and services from a catalog'
ms:assetid: 7fe13bf9-be99-49df-8da0-bff0df85235c
ms:mtpsurl: https://technet.microsoft.com/library/Hh271579(v=AX.60)
ms:contentKeyID: 36384210
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- search
- CatCategoryRequest
- CatDisplayProductDetail
- CatDisplayProductList
- CatDisplaySummaryList
- CatDisplayVendorCriterionDetail
- CatDisplayVendorCriterionPreview
- CatDisplayVendorDetail
- CatDisplayVendorList
- CatExternalCatalogConfirmation
- CatExternalCatalogFilter
- CatExternalCatalogPurchase
- CatProcurementError
- CatProductFilter
- CatSearchSummary
- CatVendorFilter
- CatWelcome
- catalog
- indirect purchasing
- non-catalog
- order from a vendor
- procurement site
audience: Application User
ms.search.region: Global
---

# Key tasks: Order items and services from a catalog 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Order products** page in the Employee services portal to order items and services that you use to perform daily work activities. On the **Order products** page, you can complete the following tasks:

  - Search the procurement catalog for items and services by category or keyword, or by browsing the catalog categories.

  - Add items and services to your shopping cart.

  - Create an order by procurement category or vendor for items and services that are not found in the procurement catalog.

  - Order items and services directly from an external website, if your organization allows you to order products directly from a vendor.

  - Create an order for items or services on behalf of someone else, or in a different legal entity or operating unit, if you have the required permissions.
    
    The purchasing policy that is defined for the requester, operating unit, or legal entity that is selected on the menu bar controls the catalog that is displayed on the **Order product** page.


> [!NOTE]
> <P>If a procurement catalog has not been created, or if a catalog purchase policy has not been configured for your organization, no procurement catalog is displayed on the <STRONG>Order products</STRONG> page.</P>



## What do you want to do?

Learn more about...

Search for items and services

Order items and services from a procurement catalog

Order items and services from a category or vendor

Order items and services from a vendor catalog

Create an order for items or services on behalf of someone else

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About ordering products](about-ordering-products.md)

## Search for items and services

On the **Order products** page, you can search for products by product category, keywords, or a combination of category and keywords. You can filter your search results by price or product attribute to quickly find the items or services that you are looking for.

1.  Click **Order Products** on the top link bar.

2.  Follow one of these steps:
    
      - To search by category or keyword, select **All categories** or a specific category in the search field, and then enter one or more keywords in the **Search for items** field. Then click the search button.
    
      - To search in a specific category, click a category under **Categories** on the Quick Launch, and then enter one or more keywords in the **Search for items** field. Then click the search button.

View your search results on the **Products**, **Vendors**, or **External websites** tabs.

Back to top

## Order items and services from a procurement catalog

Use the **Order products** page to search for items and services that you want to order, to view the details of the items and services, and to add your selections to your shopping cart. Only items and services that you are authorized to order are displayed in the procurement catalog.

You can add the items and services from the shopping cart to a purchase requisition to create and submit the order. For more information about creating a purchase requisition for items in your shopping cart, see [Check out products and create a purchase requisition](check-out-products-and-create-a-purchase-requisition.md).

1.  Click **Order Products** on the top link bar.

2.  On the **Order products** page, use the search field to find the product that you want to order. You can also click a category under **Categories** on the Quick Launch.

3.  To view the details of the item or service that you want to order, click the item name in the **Products** list.
    
    –or–
    
    To add the item directly to your shopping cart, click the **Add to cart** button for the product in the list.

4.  On the **Product details** page, view the details of the item or service. You can select the specifications for the item or service, select the quantity that you want to order, and then click **Add to cart** to add the item or service to your shopping cart.
    

    > [!NOTE]
    > <P>You can modify the quantity after you add the item or service to your shopping cart. However, all other specifications for the item or service must be entered on the <STRONG>Product details</STRONG> page.</P>



5.  To add more items or services to your shopping cart, repeat steps 3 and 4.
    
    –or–
    
    To start a new search and add more items or services, repeat steps 2 through 4.

Back to top

## Order items and services from a category or vendor

You may not find the item or service that you want to order in the procurement catalog or in a vendor catalog. In this case, you can submit a request to order the item or service. Select a catalog category, and then enter a description of the item or service that you want to order.

1.  Click **Order Products** on the top link bar, and then click a category under **Categories** on the Quick Launch.

2.  Follow one of these steps:
    
    On the **Products** tab, in the **Can’t find something in the catalog?** section, click **Add an item**.
    

    > [!NOTE]
    > <P>The <STRONG>Can’t find something in the catalog?</STRONG> section appears on the page only if the catalog is configured to let you order items that are not in the procurement catalog.</P>

    
    –or–
    
    To order an item or service from a specific vendor, click the **Vendors** tab, and then click the **Add to cart** button for a vendor in the list.

3.  On the **Order from a vendor or a category** page, enter the name and description of the item or service that you want to order. If you are ordering an item from a selected vendor, the vendor field contains the vendor's account number by default. You can accept the default value, select a different vendor, or leave the field blank.
    

    > [!NOTE]
    > <P>The <STRONG>Vendor account</STRONG> list includes only the vendors that are authorized to supply products for the legal entity and operating unit that are selected on the menu bar.</P>



4.  Select the procurement category that you want to order the item or service from. By default, the category that you selected on the Quick Launch is displayed.

5.  Enter any additional information about the item or service, and then click **Add to cart**. The information that you enter is displayed in the shopping cart.

6.  Repeat steps 2 through 5 to add more items or services to your shopping cart.

For information about how to check out from your shopping cart, see [Check out products and create a purchase requisition](check-out-products-and-create-a-purchase-requisition.md).

Back to top

## Order items and services from a vendor catalog

If your organization allows you to order products directly from a vendor, you can access the vendor's order site directly from the procurement site. When you check out, the items and services that you select from the vendor's catalog are included in your shopping cart on the **Order products** page.


> [!NOTE]
> <P>Depending on how access permissions are set up for the vendor's catalog, you might complete your order on the vendor's order site. If you return to your shopping cart in the Employee services portal to complete your transaction, the vendor's quotation number is displayed for the items or services that you ordered from the vendor's catalog.</P>



1.  Click **Order Products** on the top link bar, and then click a category under **Categories** on the Quick Launch.

2.  On the **External websites** tab, click the link for the vendor catalog that you want to order from. If no vendor catalogs are available for the selected category, this tab is blank.

The vendor's order site is displayed in either a new window or your existing window. Select the items or services that you want to order, and then check out. Depending on how access to the vendor's order site is configured, you either complete your transaction on the vendor's order site, or return to your shopping cart in the Employee services portal.

For information about how to check out from your shopping cart in Microsoft Dynamics AX, see [Check out products and create a purchase requisition](check-out-products-and-create-a-purchase-requisition.md).

Back to top

## Create an order for items or services on behalf of someone else

Before you can order products on behalf of someone else, you must have permissions to create purchase requisitions for other people, or in other legal entities and operating units. As an administrator, use the **Purchase requisitions permissions** form to set up permissions to order products or create purchase requisitions for other people, or in other legal entities and operating units. As a worker, you must use the **Delegates who can order products on your behalf** page to set up permissions to order products or create purchase requisitions on behalf of others.

For more information about how to set up permissions to enter orders for someone else as an administrator, see “Set up permissions for ordering products on behalf of someone else” in the Application User Help in the Microsoft Dynamics AX client. For more information about how to set up permissions to enter orders for someone else, see [Delegate permissions to create purchase requisitions on your behalf](delegate-permissions-to-create-purchase-requisitions-on-your-behalf.md).

1.  Click **Order Products** on the top link bar.

2.  On the menu bar, in the **Order for** menu, click the name of the requester. Then, on the **Legal entity and operating unit** menu, click the legal entity and operating unit for the requester.
    

    > [!NOTE]
    > <P>Only requesters on whose behalf you have permissions to order products appear in the <STRONG>Order for</STRONG> menu. Additionally, you can select the legal entity and operating unit that you want to order from only if you have permissions to order products in more than one legal entity and operating unit. The procurement site displays the products that are available in the legal entity and operating unit that you select.</P>



3.  On the **Order products** page, use the search field to find the product that you want to order. You can also click a category under **Categories** on the Quick Launch.

4.  To view the details of the item or service that you want to order, click the item name in the **Products** list.
    
    –or–
    
    To add the item directly to your shopping cart, click the **Add to cart** button for the product in the list.

5.  On the **Product details** page, view the details of the item or service. You can select the specifications for the item or service, select the quantity that you want to order, and then click **Add to cart** to add the item or service to your shopping cart.
    

    > [!NOTE]
    > <P>You can modify the quantity after you add the item or service to your shopping cart. However, all other specifications for the item or service must be entered on the <STRONG>Product details</STRONG> page.</P>



6.  To add more items or services to your shopping cart, repeat steps 4 and 5.
    
    –or–
    
    To start a new search and add more items or services, repeat steps 2 through 5.

Back to top

## Find related tasks

[Check out products and create a purchase requisition](check-out-products-and-create-a-purchase-requisition.md)

[View and maintain orders and statuses](view-and-maintain-orders-and-statuses.md)

[Rate products and vendors](rate-products-and-vendors.md)

  


