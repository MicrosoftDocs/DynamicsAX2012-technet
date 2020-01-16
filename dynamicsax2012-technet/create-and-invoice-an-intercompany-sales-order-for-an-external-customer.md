---
title: Create and invoice an intercompany sales order for an external customer
TOCTitle: Create and invoice an intercompany sales order for an external customer
ms:assetid: 1f3c6ffb-82fc-4617-b5c0-bb2dc93839ab
ms:mtpsurl: https://technet.microsoft.com/library/Aa496780(v=AX.60)
ms:contentKeyID: 43976705
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create and invoice an intercompany sales order for an external customer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use intercompany trade to record the sale of a product from one legal entity to another legal entity that is in the same organization.

When you create the original sales order, you can automatically create an intercompany purchase order for the intercompany vendor. This automatically creates an intercompany sales order in the intercompany vendor’s legal entity.

The following illustration shows the flow of the transactions when you create a sales order for an external customer, but the product must be ordered from a different legal entity in your organization before you can deliver the product to the customer. In this case, an intercompany purchase order is created for the vendor account that represents the other legal entity. In turn, an intercompany sales order is created in the other legal entity for the customer account that represents your legal entity. When an intercompany purchase order is invoiced, the invoice for the original sales order is automatically posted, if it is a direct delivery.

![Intercompany example: Sales for external use](images/Aa496780.IntercompanyExternalSalesProcess(AX.60).gif "Intercompany example: Sales for external use")

If you are using direct delivery, and you select **Packing slip** in the **Quantity** field in the **Posting invoice** form, the intercompany vendor invoice is based on the intercompany product receipt that was previously posted.

## Prerequisites

Before you begin, make sure that the following prerequisites are met to automatically post and print the intercompany invoices.

1.  Click **Sales and marketing** \> **Common** \> **Customers** \> **All customers**. On the **Action Pane**, on the **General** tab, click **Intercompany**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**. On the **Action Pane**, on the **General** tab, click **Intercompany**.

2.  In the **Intercompany** form for either the vendor or the customer, in the **Purchase order policies** area, in the **Intercompany purchase order (direct delivery)** field group, select the **Post invoice automatically** check box.

3.  In the **Purchase order policies** area, in the **Original sales order (direct delivery)** field group, select the **Post invoice automatically** check box. Select this check box if you want the invoice for the original sales order to be automatically printed when you post the intercompany vendor invoice.


> [!NOTE]
> <P>The print settings for the invoice are determined by the setup for the module, document, or transaction in the <STRONG>Print management setup</STRONG> form.</P>



## Create an original sales order for an external customer

Do these steps in legal entity A. This procedure corresponds to the box labeled 1 in the illustration.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  From the **All sales orders** list page, create the original sales order. The field values are copied from the customer account to the sales order.

3.  In the **Sales order** form, click **Header view** on the **Action Pane**.

4.  On the **Intercompany settings** FastTab, select the **Autocreate intercompany orders** check box.

5.  If you want the intercompany vendor to deliver the item directly to the external customer, select the **Direct delivery** check box.

6.  When you have finished entering the sales order, close the **Sales order** form.
    
    The intercompany purchase order is automatically created for all the items that have an assigned intercompany vendor, and then the intercompany sales order is created. An Infolog message tells you that an intercompany purchase order and intercompany sales order have been created. The message also contains links to those orders. If an item was not found, a red warning symbol is displayed in the Infolog. This symbol means that the order creation process was not completed.
    

    > [!NOTE]
    > <P>If you are creating several orders in different legal entities, and the items were not found in one of the legal entities, the order creation process stops, even for the legal entities that could fulfill their orders.</P>



## Invoice an intercompany sales order

When an intercompany sales order is invoiced, the corresponding intercompany purchase order is automatically invoiced. Then, if the original sales order is a direct delivery order, the original sales order is automatically invoiced.

Do these steps in legal entity B. This procedure corresponds to the box labeled 2 in the illustration.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  On the **All sales orders** list page, select the intercompany sales order.

3.  On the **Action Pane**, click the **Invoice** tab, and then click **Invoice**.

4.  Select the **Posting** check box.

5.  Select the sales order, and then click **OK**.
    
    The customer invoice for the intercompany sales order is automatically posted in legal entity B. The intercompany vendor invoice then is automatically created and posted in legal entity A. If the original sales order is set up as a direct delivery, the customer invoice is created for the original sales order in legal entity A.

## See also

[Set up vendors, customers, and items for intercompany trade](set-up-vendors-customers-and-items-for-intercompany-trade.md)

[Create and invoice an intercompany sales order for internal use](create-and-invoice-an-intercompany-sales-order-for-internal-use.md)

[Create and invoice an intercompany purchase order for internal use](create-and-invoice-an-intercompany-purchase-order-for-internal-use.md)

[Intercompany setup (form)](https://technet.microsoft.com/library/hh781085\(v=ax.60\))

  


