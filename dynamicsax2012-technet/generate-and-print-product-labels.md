---
title: Generate and print product labels
TOCTitle: Generate and print product labels
ms:assetid: 92bb0377-2ec2-4d62-a481-033a1681cb8d
ms:mtpsurl: https://technet.microsoft.com/library/Hh597174(v=AX.60)
ms:contentKeyID: 39519234
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailPrintLabels
audience: Application User
ms.search.region: Global
description: Learn how to generate and print product labels with Microsoft Dynamics AX 2012. Detailed guide for creating labels manually or in bulk, and setting up reports.
---

# Generate and print product labels 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to generate and print product labels that you can attach to a product or a container. A product label contains all the information about the product, including the batch number, serial number, and expiration date.

When you work with labels in Retail, you can do the following:

  - Create labels for products for which the price or comparison price has changed in a store.
    
    To set up Retail to create product labels when prices change, you must assign product label reports to the relevant retail products. The product label reports provide the information that Retail needs to print the labels. You must set up product label reports no matter what version of Microsoft Dynamics AX 2012 you are using.

  - Create product labels manually, either for one product at a time or for categories of retail products.

  - In AX 2012 R3, generate product label files for multiple products at the same time.

  - Select a specific size for the product labels that you print.

  - Reprint labels at any time.


> [!NOTE]
> <P>The procedure for completing this task has changed for <STRONG>Retail</STRONG> in Microsoft Dynamics AX 2012 R3. For more information, see the section later in this topic.</P>



## Prerequisites

Before you can generate and print product labels, you must set up Microsoft Dynamics AX to enable label printing. The following tasks must be completed:

  - Select options in the **Retail shared parameters** form to specify how labels should be generated for brick-and-mortar stores. For more information about the options in this form, see [Retail shared parameters (form)](https://technet.microsoft.com/library/hh580625\(v=ax.60\)).

  - Select the reports that can be used to generate labels. The label reports contain information such as bar codes, prices, and relevant dates, and also specify the size of the labels to print and the orientation of the label page. After label reports are set up in this step, users select which report to use every time they generate labels.

## Specify which stores to print labels for

Follow these steps to specify which stores you want to print labels for. You can select whether to generate labels for all stores or only selected stores. This setting only applies to brick-and-mortar stores.

1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail shared parameters**.

2.  In the **Retail shared parameters** form, on the **Labels** tab, select the option to use when generating labels.

## Set up product label reports

Follow these steps to set up the reports that users can select when they generate labels:

1.  Click **Retail** \> **Setup** \> **Bar codes and labels** \> **Product label reports**.

2.  In the **Product label report setup** form, in the **Report name** field, click the arrow and select the product label reports to use. Add as many product label reports as you require for your products.
    

    > [!NOTE]
    > <P>The <STRONG>Report name</STRONG> field contains a list of the reports that are available in the Application Object Tree (AOT). Based on the requirements of the business, you can also create new reports and add them to the list of available reports.</P>



## Generate and print product labels

To generate and print labels that you can attach to a product or a container, follow these steps:

1.  Click **Retail** \> **Periodic** \> **Bar codes and labels** \> **Print product labels**.

2.  In the **Product label printing** form, in the **Store number** field, select a store. Then, select the date when the labels become valid.

3.  Depending on the version of the product that you are using, do one of the following:
    
      - In AX 2012 R3 click **Create label by product**.
    
      - Otherwise, click **Create**, and then click **Create label by product**.
    
    In the **Create labels** form, enter the information to filter the list of products.

4.  Click **OK**. Retail creates product label entries for items for which the registered price on the product label has changed.

5.  In the **Product label printing** form, change the values in the **Quantity** column to print the number of labels that you need.

6.  Depending on the version of the product that you are using, to view a list of the labels that will be printed do one of the following:
    
      - In AX 2012 R3 click **Labels to print**.
    
      - Otherwise, click **Transactions**, and then click **Labels to print**.
    
    To view a list of labels that have already been printed, click **Printed labels**.

7.  Depending on the version of the product that you are using, to generate labels, do one of the following:
    
      - In AX 2012 R3 click **Print labels**.
    
      - Otherwise, click **Print**, and then click **Print labels**.

8.  Select the printer to use to print the product labels, and then click **OK**.

9.  After the labels are generated, in the **Product label printing** form, you can view the quantity of labels that you requested in the **Quantity** column, and compare it with the quantity that was printed in the **Printed quantity** column.

## Print product labels in Retail in Microsoft Dynamics AX 2012 R3

In AX 2012 R3, in addition to generating labels for one product at a time, you can now generate product labels for multiple products at the same time. You can also generate labels for products that are included in purchase orders or transfer orders, and for released products. You can generate labels for one or more products at the same time from any of the following forms:

  - **Released products**

  - **Released product details**

  - **Purchase order**

  - **Posting product receipt**

  - **Shipment**

  - **Receive**

## Generate product labels for released products

You can generate labels for one or more selected products that have been released to legal entities. To generate labels for released products, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**. On the **Released products** list page, select one or more product rows.
    
    –or–
    
    Click **Product information management** \> **Common** \> **Released products**. On the **Released products** list page, double-click on a product in the list.
    
    –or–
    
    Click **Retail** \> **Common** \> **Products** \> **Released products by category**. On the **Released product details** list page, select one or more product rows.

2.  On the **Action Pane**, on the **Retail** tab, in the **Functions** group, click **Print product labels**.

3.  In the **Print product labels** form, in the **Report name** field, select the product label report to use to generate the product labels.

4.  To generate product labels for additional products, click **Add products**. Then, in the **Add products** form, select the products that you want to add from the list of available products. Click **OK**.
    
    To remove products from the list, in the **Print product labels** form, select the products in the list, and then click **Remove**.

5.  In the **Store number** field, select the store to print the labels for.

6.  In the **Quantity** field, enter the number of labels that you want to generate for each product in the list.

7.  In the **Print product labels** form, click **OK** to generate the product labels.

## Generate product labels for products in a purchase order

You can generate the labels for products that are included in a purchase order at any time in the purchase order life cycle.

**Generate product labels for products in a purchase order**

To generate product labels for products that are included in a purchase order, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **All purchase orders** list page, double-click a purchase order.

2.  In the **Purchase order** form, on the **Action Pane**, on the **Retail** tab, click **Print product labels**.

3.  In the **Print product labels** form, in the **Report name** field, select the product label report to use to generate the product labels for the purchase order line items.
    

    > [!NOTE]
    > <P>Only the line items that are included in the purchase order are included in the list in the form. You can remove selected line items from the list if you don’t want to print product labels for those line items.</P>



4.  In the **Store number** field, select the store that is associated with the warehouse that you are printing labels for.

5.  In the **Quantity** field, enter the number of labels that you want to generate for each line item.

6.  Click **OK** to generate the product labels for the products in the list.

**Generate product labels for products in a purchase order when you generate a product receipt**

To generate product labels for products that are included in a purchase order at the time that the products are received, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **All purchase orders** list page, double-click a confirmed purchase order in the list or confirm a purchase order.
    
    To confirm a purchase order, select an open purchase order. Then, on the **Action Pane**, on the **Purchase** tab, in the **Generate** section, click **Confirmation**.

2.  In the **Purchase order** form, on the **Action Pane**, on the **Receive** tab, in the **Generate** section, click **Product receipt**.

3.  In the **Posting product receipt** form, on the **Parameters** tab, select the **Print product labels** check box.

4.  On the **Overview** tab, in the **Product receipt** field, enter the product receipt number for each line, and then click **OK**.
    
    After the receipt is posted, the **Print product labels** form opens.

5.  In the **Print product labels** form, in the **Report name** field, select the product label report to use to generate the product labels for the purchase order line items.
    

    > [!NOTE]
    > <P>Only the line items that are included in the purchase order are included in the list on the form. You can remove selected line items from the list if you don’t want to print product labels for those line items.</P>



6.  In the **Store number** field, select the store that is associated with the warehouse that you are printing labels for.

7.  In the **Quantity** field, enter the number of labels that you want to generate for each line item.

8.  Click **OK** to generate the product labels for the products in the list.

## Generate product labels for products in a transfer order

You can generate product labels for products that are included in a transfer order and include them when the products are shipped. You can also generate product labels for products that are received from a transfer order.

**Generate product labels for products in a transfer order**

To generate labels for products that are shipped in a transfer order, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  In the **Transfer orders** form, select a transfer order in the list that has a transfer status of **Created**, or create a new transfer order.
    
    If you select an existing transfer order, on the **Lines** tab, adjust the **Ship date** and the **Receipt date**, if you need to.

3.  Click **Posting**, and then select **Ship transfer order** in the list.

4.  In the **Shipment** form, enter the appropriate information to ship the order, and then, on the **Overview** tab, do the following:
    
    1.  In the **Update** field, select the appropriate value from the list. For more information about the different values in the list, see [Transfer order shipment (form)](https://technet.microsoft.com/library/aa577094\(v=ax.60\)).
    
    2.  Select the **Edit lines** check box, if appropriate. For more information about when to select the **Edit lines** check box, see [Transfer order shipment (form)](https://technet.microsoft.com/library/aa577094\(v=ax.60\)).
    
    3.  Select the **Print product labels** check box.
    
    4.  Click **OK**.

5.  In the **Print product labels** form, in the **Report name** field, select the product label report to use to generate the product labels for the transfer order line items.
    

    > [!NOTE]
    > <P>Only the line items that are included in the transfer order are included in the list on the form. You can remove selected line items from the list if you don’t want to print product labels for those line items.</P>



6.  In the **Store number** field, select the store that is associated with the warehouse that you are printing labels for.

7.  In the **Quantity** field, enter the number of labels that you want to generate for each line item.

8.  Click **OK** to generate the product labels.

**Generate product labels for products received from a transfer order**

To generate labels for products that are received from a transfer order, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  In the **Transfer orders** form, select a transfer order that has a transfer status of **Shipped**.

3.  Click **Posting**, and then select **Receive** from the list.

4.  In the **Receive** form, enter the appropriate information to ship the order, and then, on the **Overview** tab, do the following:
    
    1.  In the **Update** field, select the appropriate value from the list. For more information about the different values in the list, see [Transfer order shipment (form)](https://technet.microsoft.com/library/aa577094\(v=ax.60\)).
    
    2.  Select the **Edit lines** check box, if appropriate. For more information about when to select the **Edit lines** check box, see [Transfer order shipment (form)](https://technet.microsoft.com/library/aa577094\(v=ax.60\)).
    
    3.  Select the **Print product labels** check box.
    
    4.  Click **OK**.

5.  In the **Print product labels** form, in the **Report name** field, select the product label report to use to generate the product labels for the transfer order line items.
    

    > [!NOTE]
    > <P>Only the line items that are included in the transfer order are included in the list in the form. You can remove selected line items from the list if you don’t want to print product labels for those line items.</P>



6.  In the **Store number** field, select the store that is associated with the warehouse that you are printing labels for.

7.  In the **Quantity** field, enter the number of labels that you want to generate for each line item.

8.  Click **OK** to generate the product labels.

## See also

[Create and print labels overview](create-and-print-labels-overview.md)

[Released product details (form) (Retail)](https://technet.microsoft.com/library/hh580615\(v=ax.60\))

[Create a purchase order](create-a-purchase-order.md)

[Purchase order (form)](https://technet.microsoft.com/library/aa557983\(v=ax.60\))

[Purchase posting (form)](https://technet.microsoft.com/library/aa587152\(v=ax.60\))

[Set up transfer order lines](set-up-transfer-order-lines.md)

[Receive transfer orders](receive-transfer-orders.md)

[Transfer order shipment (form)](https://technet.microsoft.com/library/aa577094\(v=ax.60\))

[Receive (form)](https://technet.microsoft.com/library/aa552649\(v=ax.60\))

  


