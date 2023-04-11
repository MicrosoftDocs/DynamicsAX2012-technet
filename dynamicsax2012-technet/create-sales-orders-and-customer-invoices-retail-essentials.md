---
title: Create sales orders and customer invoices (Retail essentials)
TOCTitle: Create sales orders and customer invoices (Retail essentials)
ms:assetid: 59ee8135-b77b-4754-bfdd-a3a95d2cd7d9
ms:mtpsurl: https://technet.microsoft.com/library/Dn736883(v=AX.60)
ms:contentKeyID: 62200361
author: tonyafehr
ms.date: 12/17/2014
mtps_version: v=AX.60
f1_keywords:
- MsDynAx060.Forms.SalesCreateOrder
- MsDynAx060.Forms.SalesTableListPage
---

# Create sales orders and customer invoices (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to create a sales order for a customer in Retail essentials. This topic also describes how to create, post, and print a customer invoice for products in a sales order.

## Create sales orders

To create a sales order, complete the following steps:

1.  Click **Retail essentials** \> **Customers** \> **All sales orders**.

2.  On the **All sales orders** page, on the **Action Pane**, on the **Sales order** tab, click **Sales order**.

3.  In the **Create sales order** form, in the **Customer account** field, select a customer for the sales order.
    
    The information from the customer account is automatically added. You can modify this information for the sales order. The customer account is not updated for modifications that you make in the sales order.

4.  Complete the remaining fields in the form, and then click **OK**.

5.  In the **Sales order** form, on the **Sales order lines** FastTab, enter an item number, quantity, and remaining details for the item.

6.  To add products to the sales order, on the **Sales order lines** FastTab, click **Add line**. For more information about the fields in the form, see [Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\)).

## Create an invoice based on a sales order

To create an invoice for products in a sales order that have been delivered to a customer, complete the following steps:

1.  Click **Retail essentials** \> **Customers** \> **All sales orders**.

2.  On the **All sales orders** page, select a sales order.

3.  On the **Action Pane**, on the **Invoice** tab, click **Invoice**.

4.  In the **Posting invoice** form, on the **Parameters** FastTab, in the **Quantity** field, select **All**.

5.  Select the **Posting** check box.

6.  Make selections in the **Print options** field group as needed.

7.  Optional: Verify totals, tax, and quantities.
    
      - To view totals for a sales invoice, select an invoice, click **Totals**, view the information, and then close the form.
    
      - To view sales taxes for a customer invoice, select an invoice, click **Sales tax**, view the information, and then close the form.
    
      - To view or change quantities for a line item, click the **Lines** tab and select a line. The **Update** field contains the quantity for the line item that has not been invoiced yet.

8.  Click **OK**. The customer invoice is posted and printed.

## See also

[Key tasks: Customer invoices](key-tasks-customer-invoices.md)

  


