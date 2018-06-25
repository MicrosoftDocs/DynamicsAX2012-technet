---
title: (BRA) Create and post a return sales order
TOCTitle: (BRA) Create and post a return sales order
ms:assetid: fcbf3402-3f51-4add-9b59-e2d07eb39d22
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ937997(v=AX.60)
ms:contentKeyID: 50950786
ms.date: 11/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- create return sales orders
- post return sales orders
- return sales orders
- BR - 00031
---

# (BRA) Create and post a return sales order [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can return items that do not meet quality standards, do not meet customer order specifications, and items that are damaged in transit. You can create and post a return sales order to generate an incoming fiscal document for the returned items.

When you create a return sales order, a Return Materials Authorization (RMA) number is assigned to the return sales order in the **Sales order** form. The fiscal information, such as fiscal document type, Código Fiscal de Operações e Prestações (CFOP), service code, delivery CFOP, operation type, and the presence type of the fiscal operation for the return sales order is updated with the information in the original sales fiscal document. The tax groups for the return sales order are updated based on the tax matrix that is defined in the **Taxes matrix** form. For more information, see [(BRA) Set up a tax matrix](bra-set-up-a-tax-matrix.md).

You must select the **Generate incoming fiscal document** check box for the customer in the **Customers** form to generate and print an incoming fiscal document when you post a fiscal document for a sales return. You must set up a fiscal document type and assign it to a customer before you create and post a return sales order. For more information, see [(BRA) Set up fiscal document types](bra-set-up-fiscal-document-types.md) and [(BRA) Assign fiscal document types for customers or vendors](bra-assign-fiscal-document-types-for-customers-or-vendors.md).

1.  Click **Sales and marketing** \> **Common** \> **Return orders** \> **All return orders**.

2.  Create a return order. For more information, see [Return orders (form)](https://technet.microsoft.com/en-us/library/hh803010\(v=ax.60\)).

3.  Click **Inventory management** \> **Periodic** \> **Arrival overview**.

4.  Create and post an item arrival journal. For more information, see [Post arrival journal for returned products](post-arrival-journal-for-returned-products.md) and [Register the receipt of returned items](register-the-receipt-of-returned-items.md).

5.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

6.  Select a sales order that has a **Returned order** type and a **Confirmed** approval status, and then on the **Action Pane**, click **Edit** to open the order.

7.  Click the **Fiscal information** FastTab, and then in the **Presence type** field, modify the presence type of the fiscal operation, if required.
    

    > [!NOTE]
    > <P>This control is available only if cumulative update 8 for AX2012 R3 is installed.</P>



8.  Click the **Invoice** tab, and then click **Invoice** to open the **Posting invoice** form.

9.  Select the **Posting** and **Print invoice** check boxes to post and print the incoming fiscal document for the return sales order.

10. Click **OK** to create an incoming fiscal document for the return sales order.

The on-hand quantity of the returned item is updated in the **On-hand** form.

## See also

[(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md)

[(BRA) Customers (modified form)](https://technet.microsoft.com/en-us/library/jj933537\(v=ax.60\))

[(BRA) Return order (form)](https://technet.microsoft.com/en-us/library/jj911254\(v=ax.60\))

[Arrival overview (form)](https://technet.microsoft.com/en-us/library/hh227654\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

