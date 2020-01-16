---
title: Print shelf labels (Retail essentials)
TOCTitle: Print shelf labels (Retail essentials)
ms:assetid: a7ab2dcb-fd55-44a4-9ccf-1400dce81d7c
ms:mtpsurl: https://technet.microsoft.com/library/Dn736927(v=AX.60)
ms:contentKeyID: 62200404
author: Khairunj
ms.date: 12/17/2014
mtps_version: v=AX.60
---

# Print shelf labels (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to generate and print shelf labels to put on a store rack or shelf where items are displayed or stored. A shelf label can contain information about a product, for example the product name, size, and color. However, a shelf label can’t contain the batch number, serial number, or expiration date.

You can generate shelf labels when the price or comparison price of a product has changed in a store. To do this, you must assign shelf label reports to the relevant retail products, either individually or by category. The shelf label reports provide the information that Retail essentials needs to print the labels. For more information about how to assign shelf label reports to products, see [Set up retail products (Retail essentials)](set-up-retail-products-retail-essentials.md).

You can generate shelf labels for all products or only for released products; for one product at a time or for categories of products. You can also generate shelf labels for the products that are included in a purchase order or a transfer order.

## Prerequisites

The following tasks must be completed before you can generate and print shelf labels:

  - Before you can set up printing for shelf labels, a system administrator must enable menu items for Retail essentials. For more information, see Enable label printing (Retail essentials).

  - Select options in the **Retail shared parameters** form to specify how labels should be generated for brick-and-mortar stores. (On the area page, under **Channels**, click **Setup** \> **Retail shared parameters**.) For more information about the options in this form, see [Retail shared parameters (form)](https://technet.microsoft.com/library/hh580625\(v=ax.60\)).

  - Select the reports that can be used to generate labels. For more information, see the following section, “Set up shelf label reports.”

## Set up shelf label reports

Before you print shelf labels, you must select the reports that can be used to generate labels. The label reports contain information such as bar codes, prices, and other relevant data, and also specify the size of the labels to print and the orientation of the label page. After label reports are set up in this step, users select which report to use every time they generate labels.

1.  Click **Retail essentials** \> **Inventory management** \> **Setup** \> **Bar codes and labels** \> **Shelf label reports**.

2.  In the **Shelf label report setup** form, in the **Report name** field, select the shelf label report to use. The **Report name** field contains a list of the reports that are available. Add as many shelf label reports as you need for your products.
    

    > [!NOTE]
    > <P>Based on the requirements of the business, you can also create new reports and add them to the list of reports that are available.</P>



## Print shelf labels from the Shelf label printing form

Use the procedures in this section to generate, print, and view shelf labels from the **Shelf label printing** form.

## Generate and print the labels

1.  Click **Retail essentials** \> **Inventory management** \> **Setup** \> **Bar codes and labels** \> **Print shelf labels**.

2.  In the **Shelf label printing** form, in the **Store number** field, select a store. Select the date that the labels become valid.

3.  Click **Create label by product**. In the **Create labels** form, enter information about the store and products, and then click **OK**.

4.  In the **Shelf label printing** form, in the **Quantity** field, enter or modify the number of labels to print for the product.

5.  Click **Print labels**.

6.  Select the printer to use to print the shelf labels, and then click **OK**.
    
    After the labels are printed, the number of labels that were printed is displayed in the **Printed quantity** field.

## View the labels

You can view a list of labels for which printing is pending or a list of labels that have already been printed. To view shelf labels, follow these steps:

1.  Click **Retail essentials** \> **Inventory management** \> **Setup** \> **Bar codes and labels** \> **Print shelf labels**.

2.  In the **Shelf label printing** form, click **Labels to print** to view a list of labels that are set up to be printed. Click **Printed labels** to view a list of labels that have already been printed.

## Print shelf labels from other forms

First, follow the steps in the “Prerequisites” and “Set up shelf label reports” sections earlier in this topic. Then, you can generate shelf labels for one or more products at the same time from any of the following forms:

  - **Released product details**

  - **Purchase order**

  - **Transfer orders**

## Generate shelf labels for released products

1.  Click **Retail essentials** \> **Merchandising** \> **Released products by category**.

2.  In the **Released product details** form, select a product, and then, on the **Action Pane**, on the **Retail** tab, in the **Functions** group, click **Print shelf labels**.

3.  In the **Print shelf labels** form, in the **Report name** field, select the shelf label report to use to generate the shelf labels for the selected product.

4.  To generate shelf labels for additional products, click **Add products**. Then, in the **Add products** form, select the products that you want to add, and then click **Add**. Click **OK** to add the selected products to the **Print shelf labels** form.
    
    To remove products from the list, in the **Print shelf labels** form, select the products in the list, and then click **Remove**.

5.  In the **Quantity** field, enter the number of labels that you want to generate for each product.

6.  Click **Print labels**.

7.  Select the printer to use to print the shelf labels, and then click **OK**.
    
    After the labels are printed, the number of labels that were printed is displayed in the **Printed quantity** field.

## Generate shelf labels for products in a purchase order

You can generate the labels for products in a purchase order at any time in the purchase order life cycle.

1.  Click **Retail essentials** \> **Inventory management** \> **All purchase orders**. On the **All purchase orders** list page, double-click a purchase order that is assigned an approval status of **Confirmed**, or confirm a purchase order.
    

    > [!NOTE]
    > <P>To confirm a purchase order, create a new purchase order or select an open purchase order. Then on the <STRONG>Action Pane</STRONG>, on the <STRONG>Purchase</STRONG> tab, in the <STRONG>Generate</STRONG> section, click <STRONG>Confirm</STRONG>.</P>



2.  In the **Purchase order** form, on the **Action Pane**, on the **Receive** tab, in the **Generate** section, click **Product receipt**.

3.  In the **Posting product receipt** form, on the **Parameters** tab, select the **Print shelf labels** check box.

4.  On the **Overview** tab, in the **Update** field, enter the product receipt number for each line, and then click **OK**.
    
    After the receipt is posted, the **Print shelf labels** form opens.

5.  In the **Print shelf labels** form, in the **Report name** field, select the shelf label report to use to generate the shelf labels for the products in the purchase order lines.
    
    Only the products that are included in the purchase order are included in the list on the form. You can remove selected products from the list if you don’t want to print shelf labels for them.

6.  In the **Quantity** field, enter the number of labels that you want to generate for each product.

7.  Click **Print labels**.

8.  Select the printer to use to print the shelf labels, and then click **OK**.
    
    After the labels are printed, the number of labels that were printed is displayed in the **Printed quantity** field.

## Generate shelf labels for products in a transfer order

You can generate shelf labels for products that you ship in a transfer order. You can also generate shelf labels for products that are received from a transfer order.

For information about how to create a transfer order, see [Set up transfer order lines](set-up-transfer-order-lines.md). For information about how to receive a transfer order, see [Receive transfer orders](receive-transfer-orders.md).

**Generate shelf labels for products shipped in a transfer order**

1.  Click **Retail essentials** \> **Inventory management** \> **Transfer orders**.

2.  In the **Transfer orders** form, select a transfer order in the list that has a transfer status of **Created**, or create a new transfer order.
    
    If you select an existing transfer order, on the **Overview** tab, change the **Ship date** field and the **Receipt date** field, if you need to.

3.  On the top menu, click **Posting** \> **Ship transfer order**.

4.  In the **Shipment** form, enter the appropriate information to ship the order, and then on the **Overview** tab, do the following:
    
      - In the **Update** field, select the appropriate value for the shipment.
        
        For more information about the different values in the drop down list, see [Transfer order shipment (form)](https://technet.microsoft.com/library/aa577094\(v=ax.60\)).
    
      - Select the **Edit lines** check box if appropriate.
        
        For more information about when to select the **Edit lines** check box, see [Transfer order shipment (form)](https://technet.microsoft.com/library/aa577094\(v=ax.60\)).
    
      - On the **General** tab, select the **Print shelf labels** check box.
    
      - Click **OK**.

5.  In the **Print shelf labels** form, in the **Report name** field, select the shelf label report to use to generate the shelf labels for the transfer order line items.
    
    Only the line items that are included in the transfer order are included in the list in the **Transfer orders** form. You can remove line items from the list if you don’t want to print shelf labels for them.

6.  In the **Quantity** field, enter the number of labels that you want to generate for each line item.

7.  Click **Print labels**.

8.  Select the printer to use to print the shelf labels, and then click **OK**.
    
    After the labels are printed, the number of labels that were printed is displayed in the **Printed quantity** field.

**Generate shelf labels for products received from a transfer order**

1.  Click **Retail essentials** \> **Inventory management** \> **Transfer orders**.

2.  In the **Transfer orders** form, select a transfer order in the list that has a transfer status of **Shipped**.

3.  On the top menu, click **Posting** \> **Receive**.

4.  In the **Receive** form, enter the appropriate information to ship the order, and then, on the **Overview** tab, do the following:
    
      - In the **Update** field, select the appropriate value for the shipment.
        
        For more information about the different values in the drop down list, see [Transfer order shipment (form)](https://technet.microsoft.com/library/aa577094\(v=ax.60\)).
    
      - Select the **Edit lines** check box if appropriate.
        
        For more information about when to select the **Edit lines** check box, see [Transfer order shipment (form)](https://technet.microsoft.com/library/aa577094\(v=ax.60\)).
    
      - On the **General** tab, select the **Print shelf labels** check box.
    
      - Click **OK**.

5.  In the **Print shelf labels** form, in the **Report name** field, select the shelf label report to use to generate the shelf labels for the transfer order line items.
    
    Only the line items that are included in the transfer order are included in the list in the **Transfer orders** form. You can remove selected line items from the list if you don’t want to print shelf labels for them.

6.  In the **Quantity** field, enter the number of labels that you want to generate for each line item.

7.  Click **Print labels**.

8.  Select the printer to use to print the shelf labels, and then click **OK**.
    
    After the labels are printed, the number of labels that were printed is displayed in the **Printed quantity** field.

## See also

Enable label printing (Retail essentials)

[Print product labels (Retail essentials)](print-product-labels-retail-essentials.md)

[Create a purchase order](create-a-purchase-order.md)

  


