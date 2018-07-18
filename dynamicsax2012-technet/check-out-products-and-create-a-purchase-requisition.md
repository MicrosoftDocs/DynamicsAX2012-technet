---
title: Check out products and create a purchase requisition
TOCTitle: Check out products and create a purchase requisition
ms:assetid: b8fc0992-bb8d-4c5f-8c22-914ae7b6922b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271635(v=AX.60)
ms:contentKeyID: 36384267
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- CatCart
- PurchReqNewDialog
- PurchReqWizard
- PurchReqWizardConfirmation
audience: Application User
ms.search.region: Global
---

# Check out products and create a purchase requisition 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To create an order for items and services that you have added to your shopping cart, select the items in the cart. You can then either create a new order or add the items to an existing order. When the order is created, the selected line items are removed from the shopping cart.


> [!NOTE]
> <P>In Enterprise Portal for Microsoft Dynamics AX 2012 R2, you can create and modify requisitions for which the purpose is consumption or replenishment. However, on the Employee services site, you can view requisitions regardless of purpose, but you can only create and modify requisitions for which the purpose is consumption. For more information, see <A href="about-purchase-requisitions-enterprise-portal.md">About purchase requisitions (Enterprise Portal)</A>.</P>



When you check out from a shopping cart, you can perform the following tasks:

  - Review the items that you added to your shopping cart. If an item is not valid, it cannot be added to an order.

  - Create a purchase requisition for selected line items by using the Checkout Wizard.

  - Create a purchase requisition by adding selected line items to a new purchase requisition, without using the Checkout Wizard.

  - Add selected line items to an existing purchase requisition that has not yet been submitted for processing.

  - Delete line items that you no longer want to order.
    

    > [!NOTE]
    > <P>A vendor may impose restrictions that prevent you from deleting line items that were added from the vendor's catalog. For example, you may not be able to delete an individual line item if multiple line items were included on a single vendor quotation. Instead, you may have to delete all items that have the same vendor quotation number, and then add back the items and services that you want to order.</P>




> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



## Review items and services in a shopping cart

When you add items and services to your shopping cart, Microsoft Dynamics AX automatically validates the items against the purchasing policies that are defined for the legal entity and operating unit in which you are ordering. You can select only valid items for checkout. For invalid line items, you may have to complete additional actions before you can check out and create a purchase requisition. Additionally, you cannot check out items that are ordered from a vendor catalog if the vendor quotation for the items or services has expired.

When you add items and services to your shopping cart, Microsoft Dynamics AX revalidates all line items in the shopping cart. If an existing line item is no longer valid, the item is marked as invalid.

1.  Click **Order products** on the top link bar, and then click **My shopping cart** on the Quick Launch.

2.  In your shopping cart, verify that the items and services that you added are valid. Valid line items are marked with a green check mark icon. Invalid line items are marked with a red exclamation mark icon.

3.  If a line item is invalid, follow these steps:
    
    1.  View the data that is displayed in the message bar for the invalid line item.
    
    2.  If the line item is no longer available for ordering, select the line item, and then click **Delete**.
    
    3.  If more information is required for the line item, such as a questionnaire or a statement of work, click the name of the line item. Then, on the **Item details** page, add the required information or complete any required actions for the line item.

## Check out items and services and create purchase requisitions

After you order items and services from a procurement catalog or vendor catalog, and complete the transaction in Enterprise Portal for Microsoft Dynamics AX, you must create a purchase requisition. You must then submit the purchase requisition for review and approval before you can receive the items or services that you ordered.

If you rarely create purchase requisitions, you can use the Checkout Wizard to help you create a purchase requisition. The Checkout Wizard provides detailed instructions for each step of the process. You cannot use the Checkout Wizard to add line items to an existing purchase requisition.

If you do not need guided help when you create purchase requisitions, you can add items and services directly from your shopping cart to a purchase requisition when you check out. You can also add line items to an existing purchase requisition if the purchase requisition has a status of **Draft**.

Before you check out items from your shopping cart, you can set the checkout options to indicate whether you want to use the Checkout Wizard.

## Set your checkout options

By default, the Checkout Wizard is activated when you first check out items from your shopping cart. If you do not want to use the Checkout Wizard to create purchase requisitions, you must inactivate the wizard before you check out your items.

1.  Click **Order products** on the top link bar, and then click **My shopping cart** on the Quick Launch.

2.  In your shopping cart, on the **Action Pane**, on the **Shopping cart** tab, click **Checkout options**.

3.  In the **Checkout options** dialog box, select the **Yes** check box to activate the Checkout Wizard, or clear the check box to inactivate the wizard.

4.  Click **OK** to save your settings.

## Check out items and services by using the Checkout Wizard

1.  Click **Order products** on the top link bar, and then click **My shopping cart** on the Quick Launch.
    

    > [!NOTE]
    > <P>Your shopping cart must contain items or services before you can check out. For more information about how to search for items and services in a catalog, and how to add items and services to your shopping cart, see <A href="key-tasks-order-items-and-services-from-a-catalog.md">Key tasks: Order items and services from a catalog</A>.</P>



2.  In your shopping cart, select the items and services that you want to order.

3.  On the **Action pane**, on the **Shopping cart** tab, in the **Checkout** group, click **Order**.

4.  On the **General information** page of the Checkout Wizard, enter a name for the purchase requisition and a business justification reason, if a reason is required. Then click **Next**.

5.  Review the line items that are being added to your purchase requisition. If any lines are incomplete, click **Details** to open the **Edit purchase requisition line details** page, and then enter any information that is required. After you enter all required information, save and close the page.

6.  On the **Line items** page of the Checkout Wizard, review the line items, and then click **Submit** to submit the purchase requisition for review.
    

    > [!NOTE]
    > <P>If you click <STRONG>Cancel</STRONG> instead of <STRONG>Submit</STRONG>, the Checkout Wizard is canceled, and the selected items and services remain in your shopping cart.</P>



7.  On the **Complete** page, you can view the ID number that is assigned to the purchase requisition.

The purchase requisition is assigned a status of **In review**, and the selected items and services are removed from your shopping cart. You can view the status of the purchase requisition on the **Order products** page. Click **My Orders** on the Quick Launch, and then click the link for the item to view the details of the purchase requisition.

## Check out items and services and create a purchase requisition

1.  Click **Order products** on the top link bar, and then click **My shopping cart** on the Quick Launch.
    

    > [!NOTE]
    > <P>Your shopping cart must contain items or services before you can check out. For more information about how to search for items and services in a catalog, and how to add items and services to your shopping cart, see <A href="key-tasks-order-items-and-services-from-a-catalog.md">Key tasks: Order items and services from a catalog</A>.</P>



2.  In your shopping cart, select the items and services that you want to order.

3.  On the **Action pane**, on the **Shopping cart** tab, in the **Checkout** group, click **Order**.

4.  On the **Checkout items** page, enter a name for the purchase requisition and a business justification reason, if a reason is required. Then click **Create**.
    
    After the purchase requisition is created, the selected line items are removed from the shopping cart.

5.  On the **Complete** page, you can view the ID number that is assigned to the purchase requisition.

6.  Click the link for the purchase requisition ID.

7.  On the **View purchase requisitions** page, review the details for the purchase requisition. Click **Edit** to modify or enter any additional information that is required for the purchase requisition header or lines.

8.  Follow one of these steps:
    
      - If the purchase requisition is ready for review, click **Submit** to submit the purchase requisition and initiate the review process.
    
      - If you want to save the purchase requisition in **Draft** status so that you can submit it later, click **Save and close** or **Close**.

## Check out items and services and add them to an existing purchase requisition

1.  Click **Order products** on the top link bar, and then click **My shopping cart** on the Quick Launch.
    

    > [!NOTE]
    > <P>Your shopping cart must contain items or services before you can check out. For more information about how to search for items and services in a catalog, and how to add items and services to your shopping cart, see <A href="key-tasks-order-items-and-services-from-a-catalog.md">Key tasks: Order items and services from a catalog</A>.</P>



2.  In your shopping cart, select the items and services that you want to order.

3.  On the **Action pane**, on the **Shopping cart** tab, in the **Checkout** group, click **Add to existing order**.
    
    The **Add to existing order** page displays purchase requisitions that have a status of Draft. To view the details of a selected purchase requisition, click **Details**.

4.  Select the purchase requisition that you want to add the selected line items to, and then click **OK**.
    

    > [!NOTE]
    > <P>You can add items to purchase requisitions on the Employee services site only when the requisition purpose is consumption.</P>



5.  On the **Complete** page, you can view the ID number that is assigned to the purchase requisition.

6.  Click the link for the purchase requisition ID.

7.  On the **View purchase requisition** page, review the details of the purchase requisition and purchase requisition lines. Click **Edit** to enter any additional information.

8.  If the purchase requisition is ready for review, click **Submit**. To return to the **Shopping cart** page, click **Close**.

For more information about how to create and submit a purchase requisition in Enterprise Portal, see [Create and maintain purchase requisitions](create-and-maintain-purchase-requisitions.md).

## See also

[Key tasks: Order items and services from a catalog](key-tasks-order-items-and-services-from-a-catalog.md)

[View and maintain orders and statuses](view-and-maintain-orders-and-statuses.md)

[About purchase requisitions (Enterprise Portal)](about-purchase-requisitions-enterprise-portal.md)

  


