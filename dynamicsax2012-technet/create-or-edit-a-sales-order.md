---
title: Create or edit a sales order
TOCTitle: Create or edit a sales order
ms:assetid: 9c48ad87-66d4-43a2-945c-8f78de33035c
ms:mtpsurl: https://technet.microsoft.com/library/Hh271608(v=AX.60)
ms:contentKeyID: 36384240
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EPPBAConfigurator
- EPPCConfigurator
- EPPCTemplateConfiguration
- EPSalesTableCreate
- EPSalesTableEdit
audience: Application User
ms.search.region: Global
---

# Create or edit a sales order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Create sales order** and **Edit sales order** pages to create or edit sales orders for customers. Sales orders are created to register the sale of goods or services to customers, and to track shipments to customers.


> [!NOTE]
> <P>You can also create sales orders when you perform price queries. For more information, see <A href="perform-a-price-query.md">Perform a price query</A>.</P>



You can create a sales order from either the **Sales orders** or **Customers** page.

## Create a sales order from the Sales orders page

1.  Click **Sales** on the top link bar, and then click **Sales orders** on the Quick Launch.

2.  On the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Sales Order**.

3.  On the **Customer** FastTab, enter or select the customer account to create the order for.

4.  Enter or select invoice information, such as the invoice account, currency, and language.

5.  On the **Lines** FastTab, click **Add line**.

6.  Select an item and enter a quantity, and then select inventory dimension information, if they are required.
    

    > [!NOTE]
    > <P>If your company uses the Product Builder module or Product Configurator module and you select an item that has been set up as a modeling-enabled item in the Microsoft Dynamics AX client, you must select the Configure line icon and select additional configuration information for the item.</P>



7.  Repeat steps 5 and 6 to add more items to the order.

8.  On the **Deliver address** FastTab, enter the delivery address details.

9.  View the details of the proposed order. You can click the **View totals** link to view the sales order totals in the **View totals** dialog box.

10. Click **Save and Close** to create and display the sales order.


> [!IMPORTANT]
> <P>Once a sales order is created and saved in Enterprise Portal, users cannot add or delete lines on the sales order.</P>



## Create a sales order from the Customers page

1.  Click **Sales** on the top link bar, and then click **Customers** on the Quick Launch.

2.  Select the customer to create a sales order for.

3.  On the **Action pane**, on the **Sell** tab, in the **New** group, click **Sales Order**.

4.  On the **Customer** FastTab, enter or select invoice information, such as the invoice account, currency, and language.

5.  On the **Lines** FastTab, click **Add line** to add a line item to the sales order.

6.  Select an item and inventory dimension information, if they are required.

7.  On the **Delivery address** FastTab, enter the delivery address details.
    

    > [!NOTE]
    > <P>If your company uses the Product Builder module or Product Configurator module and you select an item that has been set up as a modeling-enabled item in the Microsoft Dynamics AX client, dialog boxes might be displayed, where you must select additional configuration information for the item.</P>



8.  Repeat steps 6 and 7 to add more items to the sales order.

9.  You can click the **Totals** button to view the sales order totals in the **View totals** dialog box.

10. Click **Save and Close** to create the sales order.

## Edit a sales order

1.  Click **Sales** on the top link bar, and then click **Sales orders** on the Quick Launch.

2.  Select the order to modify.

3.  On the **Action Pane**, on the **Sales order** tab, in the **Maintain** group, click **Edit**.
    

    > [!NOTE]
    > <P>Once a sales order is created and saved in Enterprise Portal, users cannot add or delete lines on the sales order. Users can modify existing sales order lines and sales order header information.</P>



4.  Make any changes to the order or line information. Click the **Update** icon for each line that you change.

5.  Click **Save and close** to save the changes.

## See also

[View sales orders and totals](view-sales-orders-and-totals.md)

[Prepare a credit note](prepare-a-credit-note.md)

[Create or edit a return order](create-or-edit-a-return-order.md)

[View return orders](view-return-orders.md)

[Create or edit a sales quotation](create-or-edit-a-sales-quotation.md)

  


