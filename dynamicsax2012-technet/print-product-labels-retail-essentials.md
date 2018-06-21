---
title: Print product labels (Retail essentials)
TOCTitle: Print product labels (Retail essentials)
ms:assetid: 4c1fec63-c68f-4e6a-881e-92bb074d065b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn716088(v=AX.60)
ms:contentKeyID: 62200350
ms.date: 01/07/2015
mtps_version: v=AX.60
---

# Print product labels (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to generate and print product labels that you can attach to a product or a container. A product label contains all the information about the product, such as the batch number, serial number, and expiration date.

In Retail essentials, you can select a specific size for the product label reports that you print.

When you work with product labels in Retail essentials, you can complete the following tasks:

  - Create labels for products for which the price or comparison price has changed in a store.
    
    To set up Retail essentials to create product labels when prices change, you must assign product label reports to the relevant retail products. The product label reports provide the information that Retail essentials requires to print the labels. You must set up product label reports regardless of the version of Microsoft Dynamics AX 2012 that you are using. For more information about how to assign label reports to products, see [Set up retail products (Retail essentials)](set-up-retail-products-retail-essentials.md).

  - Create product labels manually, either for one product at a time or for categories of retail products.

  - Generate product labels for multiple products at the same time. You can also generate product labels for products that are included in purchase orders or transfer orders, and for released products.

  - Select a specific size for the product labels that you print.

  - Reprint labels at any time.

## Prerequisites

Before you can generate and print product labels, you must set up Microsoft Dynamics AX to enable label printing. The following tasks must be completed:

  - Before you can set up printing for product labels, a system administrator must enable three menu items for Retail essentials. For more information, see [Enable label printing (Retail essentials)](https://technet.microsoft.com/en-us/library/dn774952\(v=ax.60\)).

  - Select options in the **Retail shared parameters** form to specify how labels should be generated for brick-and-mortar stores. For more information about the options in this form, see [Retail shared parameters (form)](https://technet.microsoft.com/en-us/library/hh580625\(v=ax.60\)).

  - Select the reports that can be used to generate labels. The label reports contain information such as bar codes, prices, and relevant dates. Additionally, the label reports specify the size of the labels to print and the orientation of the label page. After label reports are set up in this step, users select which report to use every time that they generate labels.

## Specify which stores to print product labels for

Follow these steps to specify which stores to print labels for. You can select whether to generate labels for all stores or only selected stores. This setting applies to brick-and-mortar stores only.

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **Retail shared parameters**.

2.  In the **Retail shared parameters** form, on the **Labels** tab, select the option to use when labels are generated.

## Set up product label reports

Follow these steps to set up the reports that users can select when they generate labels.

1.  Click **Retail essentials** \> **Inventory management** \> **Setup** \> **Bar codes and labels** \> **Product label reports**.

2.  In the **Product label report setup** form, in the **Report name** field, click the arrow, and then select the product label reports to use. Add as many product label reports as you require for your products.
    

    > [!NOTE]
    > <P>The <STRONG>Report name</STRONG> field contains a list of the reports that are available in the Microsoft Dynamics AX Application Object Tree (AOT). Based on the requirements of the business, you can also create new reports and add them to the list of available reports.</P>



## Generate and print product labels

Follow these steps to generate and print labels that you can attach to a product or a container.

1.  **Navigation Path Not Found**

2.  In the **Product label printing** form, in the **Store number** field, select a store. Then, select the date when the labels become valid.

3.  Click **Create label by product**.
    
    In the **Create labels** form, enter the information to use to filter the list of products.

4.  Click **OK**. Retail essentials creates product label entries for items for which the registered price on the product label has changed.

5.  In the **Product label printing** form, change the values in the **Quantity** column to the number of labels that you require.

6.  Click **Labels to print**.
    
    To view a list of labels that have already been printed, click **Printed labels**.

7.  Click **Print labels**.

8.  Select the printer to use to print the product labels, and then click **OK**.

9.  After the labels are generated, in the **Product label printing** form, in the **Quantity** column, you can view the number of labels that you requested. The **Printed quantity** column displays the number of labels that were printed. Therefore, you can also compare the number that you requested and the number that were printed.

## Print product labels

In addition to generating labels for one product at a time, you can generate labels for multiple products at the same time. You can also generate labels for products that are included in purchase orders or transfer orders, and for released products. You can generate labels for one or more products at the same time from any of the following forms:

  - **Released product details**

  - **Posting product receipt**

  - **Shipment**

  - **Receive**

## Generate product labels for released products

1.  Click **Retail essentials** \> **Merchandising** \> **Released products by category**.

2.  In the **Released product details** form, select a product. Then, on the **Action Pane**, on the **Retail** tab, in the **Functions** group, click **Print product labels**.

3.  In the **Print product labels** form, in the **Report name** field, select the product label report to use to generate product labels.

4.  In the **Store number** field, select the store that is associated with the warehouse that you are printing labels for.

5.  To generate product labels for additional products, click **Add products**. Then, in the **Add products** form, in the list of available products, select the products to add. Click **OK**.
    
    To remove products from the list, in the **Print product labels** form, select the products in the list, and then click **Remove**.

6.  In the **Quantity** field, enter the number of labels to generate for each product line.

7.  In the **Print product labels** form, click **OK** to generate the product labels.

## Generate product labels for products in a purchase order

At any time in the life cycle of a purchase order, you can generate labels for the products that are included in the purchase order.

To generate product labels for products in a purchase order at the time that the products are received, follow these steps:

1.  Click **Retail essentials** \> **Inventory management** \> **All purchase orders**. On the **All purchase orders** list page, double-click a confirmed purchase order in the list, or confirm a purchase order.
    
    To confirm a purchase order, select an open purchase order. Then, on the **Action Pane**, on the **Purchase** tab, in the **Generate** section, click **Confirmation**.

2.  In the **Purchase order** form, on the **Action Pane**, on the **Receive** tab, in the **Generate** section, click **Product receipt**.

3.  In the **Posting product receipt** form, on the **Parameters** tab, select the **Print product labels** check box.

4.  On the **Overview** tab, in the **Product receipt** field, enter the product receipt number for each line, and then click **OK**.
    
    After the receipt is posted, the **Print product labels** form opens.

5.  In the **Print product labels** form, in the **Report name** field, select the product label report to use to generate the product labels for the purchase order line items.
    

    > [!NOTE]
    > <P>Only the line items that are included in the purchase order are included in the list in the form. You can remove selected line items from the list if you don’t want to print product labels for those line items.</P>



6.  In the **Store number** field, select the store that is associated with the warehouse that you are printing labels for.

7.  In the **Quantity** field, enter the number of labels to generate for each line item.

8.  Click **OK** to generate the product labels for the products in the list.

## Generate product labels for products in a transfer order

You can generate product labels for products that are included in a transfer order and include the labels when the products are shipped. You can also generate labels for products that are received from a transfer order.

To generate labels for products that are shipped in a transfer order, follow these steps:

1.  Click **Retail essentials** \> **Inventory management** \> **Transfer orders**.

2.  In the **Transfer orders** form, in the list, select a transfer order that has a transfer status of **Created**. Alternatively, create a new transfer order.
    
    If you select an existing transfer order, on the **Lines** tab, adjust the **Ship date** and **Receipt date** values, if adjustment is required.

3.  Click **Posting**, and then select **Ship transfer order** in the list.

4.  In the **Shipment** form, enter the appropriate information to ship the order, and then, on the **Overview** tab, follow these steps:
    
    1.  In the **Update** field, select the appropriate value in the list. For more information about the various values in the list, see [Transfer order shipment (form)](https://technet.microsoft.com/en-us/library/aa577094\(v=ax.60\)).
    
    2.  Select the **Edit lines** check box, if this option is appropriate. For more information about when to select the **Edit lines** check box, see [Transfer order shipment (form)](https://technet.microsoft.com/en-us/library/aa577094\(v=ax.60\)).
    
    3.  Select the **Print product labels** check box.
    
    4.  Click **OK**.

5.  In the **Print product labels** form, in the **Report name** field, select the product label report to use to generate the product labels for the transfer order line items.
    

    > [!NOTE]
    > <P>Only the line items that are included in the transfer order are included in the list in the form. You can remove selected line items from the list if you don’t want to print product labels for those line items.</P>



6.  In the **Store number** field, select the store that is associated with the warehouse that you are printing labels for.

7.  In the **Quantity** field, enter the number of labels to generate for each line item.

8.  Click **OK** to generate the product labels.

**Generate product labels for products that are received from a transfer order**

To generate labels for products that are received from a transfer order, follow these steps:

1.  Click **Retail essentials** \> **Inventory management** \> **Transfer orders**.

2.  In the **Transfer orders** form, in the list, select a transfer order that has a transfer status of **Shipped**.

3.  Click **Posting**, and then select **Receive** in the list.

4.  In the **Receive** form, enter the appropriate information to ship the order, and then, on the **Overview** tab, follow these steps:
    
    1.  In the **Update** field, select the appropriate value in the list. For more information about the various values in the list, see [Transfer order shipment (form)](https://technet.microsoft.com/en-us/library/aa577094\(v=ax.60\)).
    
    2.  Select the **Edit lines** check box, if this option is appropriate. For more information about when to select the **Edit lines** check box, see [Transfer order shipment (form)](https://technet.microsoft.com/en-us/library/aa577094\(v=ax.60\)).
    
    3.  Select the **Print product labels** check box.
    
    4.  Click **OK**.

5.  In the **Print product labels** form, in the **Report name** field, select the product label report to use to generate the product labels for the transfer order line items.
    

    > [!NOTE]
    > <P>Only the line items that are included in the transfer order are included in the list on the form. You can remove selected line items from the list if you don’t want to print product labels for those line items.</P>



6.  In the **Store number** field, select the store that is associated with the warehouse that you are printing labels for.

7.  In the **Quantity** field, enter the number of labels to generate for each line item.

8.  Click **OK** to generate the product labels.

## See also

[Enable label printing (Retail essentials)](https://technet.microsoft.com/en-us/library/dn774952\(v=ax.60\))

[Print shelf labels (Retail essentials)](print-shelf-labels-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

