---
title: Generate and print shelf labels
TOCTitle: Generate and print shelf labels
ms:assetid: add049cf-c6e0-4daf-8d0d-c7b178b8d31d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597209(v=AX.60)
ms:contentKeyID: 39519281
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailPrintLabels
---

# Generate and print shelf labels [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to generate and print shelf labels to put on a store rack or shelf where items are displayed or stored. A shelf label can contain all the information about the product, for example the product name, size, and color. However, a shelf label can’t contain information such as the batch number, serial number, or expiration date.

When you work with labels in Retail, you can do the following:

  - Create shelf labels when the price or comparison price of a product has changed in a store.
    
    To set up Retail to create shelf labels when prices change, you must assign shelf label reports to the relevant retail products. The shelf label reports provide the information that Retail needs to print the labels. You must set up shelf label reports no matter what version of Microsoft Dynamics AX 2012 you are using.

  - Create shelf labels manually, either for one product at a time or for categories of retail products.

  - In AX 2012 R3, you can generate shelf labels for multiple products at the same time. You can also generate shelf labels for products that are included in purchase orders, transfer orders and for released products.

  - Select a specific size for the shelf labels that you print.

  - Reprint labels at any time.


> [!NOTE]
> <P>The procedure for completing this task has changed for <STRONG>Retail</STRONG> in Microsoft Dynamics AX 2012 R3. For more information, see the section later in this topic.</P>



## Prerequisites

Before you can generate and print shelf labels, you must set up Microsoft Dynamics AX to enable label printing. The following tasks must be completed:

  - Select options in the **Retail shared parameters** form to specify how labels should be generated for brick-and-mortar stores. For more information about the options in this form, see [Retail shared parameters (form)](https://technet.microsoft.com/en-us/library/hh580625\(v=ax.60\)).

  - Select the reports that can be used to generate labels. The label reports contain information such as bar codes, prices, and relevant data, and also specify the size of the labels to print and the orientation of the label page. After label reports are set up in this step, users select which report to use every time they generate labels.

## Specify which stores to print labels for

Follow these steps to specify which stores you want to print labels for. You can select whether to generate labels for all stores or only selected stores. This setting only applies to brick-and-mortar stores.

1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail shared parameters**.

2.  In the **Retail shared parameters** form, on the **Labels** tab, select the option to use when generating labels.

## Set up shelf label reports

Follow these steps to set up the reports that users can select when they generate labels:

1.  Click **Retail** \> **Setup** \> **Bar codes and labels** \> **Shelf label reports**.

2.  In the **Shelf label report setup** form, on the **Overview** tab, in the **Report name** field, select the shelf label report to use. Add as many shelf label reports as you require for your products.
    

    > [!NOTE]
    > <P>The <STRONG>Report name</STRONG> field contains a list of the reports that are available in the AOT. Based on the requirements of the business, you can also create new reports and add them to the list of reports that are available in the AOT.</P>



For more information about how to assign shelf label reports to products, see [Set up retail products](set-up-retail-products.md).

## Generate and print shelf labels

To generate and print labels that you can attach to a shelf where items are displayed or stored, follow these steps:

1.  Click **Retail** \> **Periodic** \> **Bar codes and labels** \> **Print shelf labels**.

2.  In the **Shelf label printing** form, in the **Store number** field, select a store. Select the date that the labels become valid.

3.  Depending on the version of the product that you are using, do one of the following:
    
      - In AX 2012 R3 click **Create label by product**.
    
      - Otherwise, click **Create**, and then click **Create label by product**.
    
    In the **Create labels** form, enter the information to filter the list of products.

4.  Click **OK**. Retail creates shelf label entries for products for which the registered shelf label price has changed.

5.  In the **Shelf label printing** form, change the value in the **Quantity** column to print the number of labels that you need.

6.  Depending on the version of the product that you are using, to view a list of the labels that will be printed do one of the following:
    
      - In AX 2012 R3 click **Labels to print**.
    
      - Otherwise, click **Transactions**, and then click **Labels to print**.
    
    To view a list of labels that have already been printed, click **Printed labels**.

7.  Depending on the version of the product that you are using, to generate labels, do one of the following:
    
      - In AX 2012 R3 click **Print labels**.
    
      - Otherwise, click **Print**, and then click **Print labels**.

8.  Select the printer to use to print the shelf labels, and then click **OK**.

9.  After the labels are generated, in the **Shelf label printing** form, you can view the quantity of labels that you requested in the **Quantity** column, and compare it with the quantity that was printed in the **Printed quantity** column.

## Print shelf labels in Retail in Microsoft Dynamics AX 2012 R3

In Retail in AX 2012 R3, you can generate shelf labels for multiple products at the same time. You can also generate shelf labels for products that are included in purchase orders, transfer orders and for released products. You can generate shelf labels for one or more products at the same time from any of the following forms:

  - **Released products**

  - **Released product details**

  - **Purchase order**

  - **Posting product receipt**

  - **Shipment**

  - **Receive**

## Generate shelf labels for released products

1.  Click **Product information management** \> **Common** \> **Released products**. On the **Released products** list page, select one or more product rows.
    
    –or–
    
    Click **Product information management** \> **Common** \> **Released products**. On the **Released products** list page, double-click a product in the list.
    
    –or–
    
    Click **Retail** \> **Common** \> **Products** \> **Released products by category**. On the **Released product details** list page, select one or more product rows.

2.  On the **Action Pane**, on the **Retail** tab, in the **Functions** group, click **Print shelf labels**.

3.  In the **Print shelf labels** form, in the **Report name** field, select the shelf label report to use to generate the shelf labels.

4.  To generate shelf labels for additional products, click **Add products**. Then, in the **Add products** form, select the products that you want to add from the list of available products, and then click **OK**.
    
    To remove products from the list, in the **Print shelf labels** form, select the products in the list, and then click **Remove**.

5.  In the **Store number** field, select the store to print the labels for.

6.  In the **Quantity** field, enter the number of labels that you want to generate for each line item.

7.  In the **Print shelf labels** form, click **OK** to generate the shelf labels.

## Generate shelf labels for products in a purchase order

You can generate the labels for products that are included in a purchase order at any time in the purchase order life cycle.

**Generate shelf labels for products in a purchase order**

To generate shelf labels for products that are included in a purchase order, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **All purchase orders** list page, double-click a purchase order in the list.

2.  In the **Purchase order** form, on the **Action Pane**, on the **Retail** tab, click **Print shelf labels**.

3.  In the **Print shelf labels** form, in the **Report name** field, select the shelf label report to use to generate the shelf labels for the purchase order line items.
    

    > [!NOTE]
    > <P>Only the line items that are included in the purchase order are included in the list on the form. You can remove selected line items from the list if you don’t want to print shelf labels for those line items.</P>



4.  In the **Store number** field, select the store that is associated with the warehouse that you are printing labels for.

5.  In the **Quantity** field, enter the number of labels that you want to generate for each line item.

6.  Click **OK** to generate the shelf labels for the products in the list.

**Generate shelf labels for products in a purchase order when you generate a product receipt**

To generate shelf labels for products that are included in a purchase order at the time that the products are received, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **All purchase orders** list page, double-click a purchase order in the list that is assigned an approval status of **Confirmed** or confirm a purchase order.
    
    To confirm a purchase order, create a new purchase order or select an open purchase order. Then, on the **Action Pane**, on the **Purchase** tab, in the **Generate** section, click **Confirmation**.

2.  In the **Purchase order** form, on the **Action Pane**, on the **Receive** tab, in the **Generate** section, click **Product receipt**.

3.  In the **Posting product receipt** form, in the **Parameters** tab, select the **Print shelf labels** check box.

4.  On the **Overview** tab, in the **Product receipt** field, enter the product receipt number for each line, and then click **OK**.
    
    After the receipt is finished posting, the **Print shelf labels** form opens.

5.  In the **Print shelf labels** form, in the **Report name** field, select the shelf label report to use to generate the shelf labels for the purchase order line items.
    

    > [!NOTE]
    > <P>Only the line items that are included in the purchase order are included in the list on the form. You can remove selected line items from the list if you don’t want to print shelf labels for those line items.</P>



6.  In the **Store number** field, select the store that is associated with the warehouse that you are printing labels for.

7.  In the **Quantity** field, enter the number of labels that you want to generate for each line item.

8.  Click **OK** to generate the shelf labels for the products in the list.

## Generate shelf labels for products that are included in a transfer order

You can generate shelf labels for products that are included in a transfer order and include them when the products are shipped. You can also generate shelf labels for products that are received from a transfer order.

**Generate shelf labels for products shipped in a transfer order**

To generate labels for products that are shipped in a transfer order, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  In the **Transfer orders** form, select a transfer order in the list that has a transfer status of **Created**, or create a new transfer order.
    
    If you select an existing transfer order, on the **Lines** tab, adjust the **Ship date** and the **Receipt date** if you need to.

3.  Click **Posting**, and then select **Ship transfer order** from in the list.

4.  In the **Shipment** form, enter the appropriate information to ship the order, and then, on the **Overview** tab, do the following:
    
      - In the **Update** field, select the appropriate value from the list. For more information about the different values in the drop down list, see [Transfer order shipment (form)](https://technet.microsoft.com/en-us/library/aa577094\(v=ax.60\)).
    
      - Select the **Edit lines** check box if appropriate. For more information about when to select the **Edit lines** check box, see [Transfer order shipment (form)](https://technet.microsoft.com/en-us/library/aa577094\(v=ax.60\)).
    
      - Select the **Print shelf labels** check box.
    
      - Click **OK**.

5.  In the **Print shelf labels** form, in the **Report name** field, select the shelf label report to use to generate the shelf labels for the transfer order line items.
    

    > [!NOTE]
    > <P>Only the line items that are included in the transfer order are included in the list in the form. You can remove selected line items from the list if you don’t want to print shelf labels for those line items.</P>



6.  In the **Store number** field, select the store that is associated with the warehouse that you are printing labels for.

7.  In the **Quantity** field, enter the number of labels that you want to generate for each line item.

8.  Click **OK** to generate the shelf labels for the products.

**Generate shelf labels for products received from a transfer order**

To generate labels for products that are received from a transfer order, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  In the **Transfer orders** form, select a transfer order that has a transfer status of **Shipped**.

3.  Click **Posting**, and then select **Receive** from the list.

4.  In the **Receive** form, enter the appropriate information to ship the order, and then, on the **Overview** tab, do the following:
    
      - In the **Update** field, select the appropriate value from the list. For more information about the different values in the drop down list, see [Transfer order shipment (form)](https://technet.microsoft.com/en-us/library/aa577094\(v=ax.60\)).
    
      - Select the **Edit lines** check box if appropriate. For more information about when to select the **Edit lines** check box, see [Transfer order shipment (form)](https://technet.microsoft.com/en-us/library/aa577094\(v=ax.60\)).
    
      - Select the **Print shelf labels** check box.
    
      - Click **OK**.

5.  In the **Print shelf labels** form, in the **Report name** field, select the shelf label report to use to generate the shelf labels for the transfer order line items.
    

    > [!NOTE]
    > <P>Only the line items that are included in the transfer order are included in the list in the form. You can remove selected line items from the list if you don’t want to print shelf labels for those line items.</P>



6.  In the **Store number** field, select the store that is associated with the warehouse that you are printing labels for.

7.  In the **Quantity** field, enter the number of labels that you want to generate for each line item.

8.  Click **OK** to generate the shelf labels for the products.

## See also

[Create and print labels overview](create-and-print-labels-overview.md)

[Shelf label printing (form)](https://technet.microsoft.com/en-us/library/hh597343\(v=ax.60\))

[Shelf label report setup (form)](https://technet.microsoft.com/en-us/library/hh580621\(v=ax.60\))

[Released product details (form) (Retail)](https://technet.microsoft.com/en-us/library/hh580615\(v=ax.60\))

[Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\))

[Purchase posting (form)](https://technet.microsoft.com/en-us/library/aa587152\(v=ax.60\))

[Transfer order shipment (form)](https://technet.microsoft.com/en-us/library/aa577094\(v=ax.60\))

[Receive (form)](https://technet.microsoft.com/en-us/library/aa552649\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

